# homework_DeepLearning

Nick Nordby HW submission for the Deep Learing segement.

1) Which model has a lower loss?

> The "Closing" model had the lower loss of 0.032 vs the 0.070 recognized in my FNG model.

2) Which model tracks the actual values better over time?

> Based on the hvplot charts produced, it is clear to me that the "Closing" model tracked the actual values better over time. I believe this is also correlated to the lower loss mentioned in the answer to question #1. 

3) Which window size works best for the model?

> The fewer number of windows I used (I tested using 1 window and 5 windows), the higher the "loss" would be. To note, I would match the "window" and "number of units" numbers, per guidance of the "gold_price_predict" activity we did in class. Given the higher loss with fewer windows, I stuck with the original 10. 
