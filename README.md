#  A Hybrid Aggregation Approach for Federated Learning to Improve Energy Consumption in Smart Buildings
For this purpose, the study proposed the implementation of the federated learning framework, which is a hybrid model FedPSO-MLP consisting of an MLP combined with PSO that can demonstrate optimization of the MLP network architecture and improvement in the network communication performance by modifying the clarity and form of client’s data during transmission in servers.
In addition, the experiments undertaken demonstrated that the proposed FedPSO-MLP outperformed the most popular Federated Averaging algorithm FedAvg, by resulting in a
reduction of error by approximately 75%. The outperformance and higher flexibility of the FedPSO-MLP over FedAvg were comprehended based on the several model criteria discussed (RMSE, MAE, and MSE). Furthermore, the hybrid algorithm significantly reduced the communication cost and data used in the network communication as well as improved the global model accuracy by an average of 96% <br><br>

<img src='./doc/imgs/fedlmP.png' title='Schematic diagram of the proposed FedLM-PSO
model' >
<center>Schematic diagram of the proposed FedLM-PSO model</center>

# Requirements
Install all the packages from requirments.txt
<ul>
<li>NumPy
<li>Pandas
<li>scikit-learn
<li>MLPRegressor
</ul>
You will also need to have software installed to run and execute a Pycharm IDE.

# Data

These data were collected and disseminated according to this publication: https://www.nature.com/articles/s41597-020-00582-3

# Running the experiments
The baseline experiment trains the model in the conventional way.

To run the baseline experiment on FedPSO-MLP using CPU:<br>
<pre><b> &nbsp; python ./FedPSO_MLP.py </b> </pre>

# Citation
If you find our work useful in your research, please cite:
Aline Abboud, Mohamed-el-Amine Brahmia, Rocks Mazraani, Abdelhafid Abouaissa and Ahmad Shahin, <b>"A Hybrid Aggregation Approach for Federated Learning to Improve Energy Consumption in Smart Buildings"</b>, 2022.
