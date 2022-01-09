# Stock Market Prediction using Sequence Model
![Portion-Watermarking](https://socialify.git.ci/suva007/sequence-model/image?description=1&font=Rokkitt&language=1&name=1&owner=1&pattern=Circuit%20Board&theme=Dark)
- <a href="https://github.com/suva007/sequence-model/blob/main/Stock_market_prediction_using_sequence_model-2.ipynb" title="Link to notebook" style="background-color:#FFFFFF;color:#000000;text-decoration:none">📚 Link to notebook </a>
## Requirements 
> If you are facing error while accessing YAHOO api , please do the following in your colab notebook : 

> !pip install --upgrade pandas-datareader

> !pip install --upgrade pandas

> and restart your run time , and it will solve that issue.

## Intro
> Schematically, a RNN layer uses a for loop to iterate over the timesteps of a sequence, while maintaining an internal state that encodes information about the timesteps it has seen so far.

> Here is a simple example of a Sequential model that processes sequences of float data, embeds each float data into a (60,1)-dimensional vector, then processes the sequence of vectors using LSTM/GRU layers.

## Input
- ![image](https://user-images.githubusercontent.com/38084433/148694701-58b13177-123a-4441-8e77-cdaa64d84871.png)

## Results
- RMSE = 87.77460158447597
- ![image](https://user-images.githubusercontent.com/38084433/148694579-25f456b3-f1b0-4178-9449-50345703e735.png)

- ![image](https://user-images.githubusercontent.com/38084433/148694597-4a916af3-55bf-4ef2-8401-1ae84aa25e39.png)

## References
- https://keras.io/api/layers/recurrent_layers/
- https://keras.io/examples/
- https://www.kaggle.com/faressayah/stock-market-analysis-prediction-using-lstm
- https://www.tensorflow.org/guide/keras/rnn
## :wink: Thanks
