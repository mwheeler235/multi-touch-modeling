Marketers typically have control over Customer touchpoints (Type of channel and campaign). Let's cast attribution modeling as a binary time series classification problem where we want to predict from the sequence of touchpoints contributing to a customer's conversion. We can use a Recurrent Neural Networks (RNN), specifically a Long Short-Term Memory (LSTM) network. These models can capture patterns, including:

* Influence of marketing channel combinations
* Order of touchpoints
* Timing of touchpoints
* Leverages Historical Data

The first step is to train an LSTM model on customer journey data. For each customer, we need:

* The sequence of touchpoints
* Status of conversion 
* Customer Features like Age and Income
