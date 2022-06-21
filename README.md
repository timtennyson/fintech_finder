# fintech_finder
This is a streamlit application that uses ethereum transactions to hire and pay employees.

## Technologies

Install the following python libraries:

[Pandas](https://pandas.pydata.org/)

[DataClasses](https://docs.python.org/3/library/dataclasses.html)

[Typing](https://docs.python.org/3/library/typing.html)

[DateTime](https://docs.python.org/3/library/datetime.html)

[Streamlit](https://docs.streamlit.io/)

[Hashlib](https://docs.python.org/3/library/hashlib.html)

[web3](https://web3js.readthedocs.io/en/v1.7.3/)

[ganache](https://trufflesuite.com/ganache/)

---

## Installation Guide

In order to run the application, you'll need to have Ganache installed and running. Copy the mnemonic seed phrase from Ganache and paste it into a .env file under the variable MNEMONIC= '<SEED PHRASE>'. Be sure to have the libraries above installed as well.



## Usage

Use terminal to open the program. Do this by entering "streamlit run fintech_finder.py" from the parent directory. Select the person you want to hire, input the number of hours, and send the transaction. After sending the transaction hash should appear on the lower left. See screenshots for reference.

!['Streamlit Screen Shot'](https://github.com/timtennyson/pychain_ledger/blob/main/streamlit_txn.jpg)
!['Ganache Screen Shot'](https://github.com/timtennyson/pychain_ledger/blob/main/txn_details.jpg)

## Contributors
Tim Tennyson


## License
Open Source
