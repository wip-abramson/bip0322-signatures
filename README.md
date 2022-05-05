# BIP-0322 Signatures for Verifiable Credentials

[BIP-0322: Generic Signed Message Format](https://github.com/bitcoin/bips/blob/master/bip-0322.mediawiki)

There are two jupyter notebooks in this folder. They attempt to demonstrate how you would use BIP-0322 signatures to sign and verify a VC. There is a notebook for each.

However, initially all these notebooks are trying to do is implement BIP-0322 signatures using the [buidl-python](https://github.com/buidl-bitcoin/buidl-python/) library developed by Jimmy Song. 

## Current Issues

I am currently unable to either verify or produce the signature provided in the BIP-0322 test vectors. However, using the current implementation in the signing notebook I am able to produce a signature, that can be verified in the verification notebook.

The most likely issue here is I have replicated the same error across both notebooks, however currently I have been unable to spot this.

## Note: These instructions are for a linux machine

## Pre-requisites

* Python v3.8
* Pip


## Running the Notebooks

1. Create a virtual environment
```
python -m venv venv
```

2. Activate the virtual environment
```
source venv/bin/activate
```

3. Install python packages
```
pip install -r requirements.txt
```

4. Launch the jupyter server
```
jupyter notebook
```

5. Run through the notebooks

shift + enter runs a cell