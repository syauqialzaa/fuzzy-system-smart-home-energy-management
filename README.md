# Fuzzy System for Smart Home Energy Management

Implement a fuzzy logic system that manages home appliances' energy usage by balancing user preferences and energy cost efficiency. This system can prioritize certain appliances during peak usage times to save energy.

There is **input variables** (time_of_day, outdoor_temp, occupancy, solar_intensity) and **output variables** (hvac_power, lighting_power, appliance_power). Fuzzy systems use rules to determine how the values of input variables affect output variables. For example, if the time of day is nighttime (input) and occupancy is low (another input), the system may decide to lower the lighting power (output).

## Key Points About The Rules

1. **Combination**: Each rule uses a combination of multiple input variables to determine the output.
2. **AND Operator**: The '&' sign is used as the AND operator, which means all conditions must be met for the rule to apply.
3. **Multiple Outputs**: Each rule determines values for all three output variables (hvac_power, lighting_power, appliance_power).
4. **Flexibility**: The system is flexible and can handle various situations. For example, not all rules use all input variables.
5. **Overlap**: Some situations may fulfill more than one rule. In this case, the fuzzy system will combine the results of the applicable rules to produce the final output.
6. **Extensibility**: The system can be easily extended by adding more rules to handle special situations or to improve control precision.