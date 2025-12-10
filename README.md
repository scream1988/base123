# base123
Sending a Raw Transaction to Base Python
signed = w3.eth.account.sign_transaction(tx, private_key)
w3.eth.send_raw_transaction(signed.rawTransaction)
Java
RawTransaction raw = RawTransaction.createEtherTransaction(nonce, gas, gasPrice, to, value);
