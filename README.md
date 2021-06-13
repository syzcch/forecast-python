# forecast-python

## create venv
python3 -m venv forecast
source bin/activate

## install fbprophet
pip3 install pystan~=2.14
pip3 install fbprophet
pip3 install plotly

## add venv into jupyter notebook kernel
pip3 install ipykernel
python3 -m ipykernel install --user --name=forecast

https://blog.csdn.net/lizzy05/article/details/116280565
https://www.cnblogs.com/darklights/p/10133551.html
https://blog.csdn.net/coolljp21/article/details/110088634
