# Your Task

Implement the drink maker protocol, the logic that translates orders from customers of the coffee machine into messages for the drink maker.

# Use Case

The drink maker should receive the correct instructions for my coffee / tea / chocolate order.

I want to be able to send instructions to the drink maker to add 1 or 2 sugars.

When my order contains sugar the drink maker should add a stick (touillette) with it.

# Drink Maker Protocol

`T:1:0` (Drink maker makes 1 tea with 1 sugar and a stick)

`H::` (Drink maker makes 1 chocolate with no sugar - and therefore no stick)

`C:2:0` (Drink maker makes 1 coffee with 2 sugars and a stick)

`M:message-content` (Drink maker forwards any message received onto the coffee machine interface for the customer to see)

You can find the complete kata [here](https://simcap.github.io/coffeemachine/).
