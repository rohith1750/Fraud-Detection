# Fraud-Detection
Dataset Overview:

The dataset provided is generated by the PaySim simulator, simulating mobile money transactions based on real transaction logs from a multinational mobile financial service provider. It's specifically designed for research purposes, focusing on fraud detection methodologies in financial transactions.

Dataset Details:

step: Represents a unit of time (1 step = 1 hour in real time, totaling 744 steps for 30 days). type: Denotes the type of transaction (e.g., CASH-IN, CASH-OUT, DEBIT, PAYMENT, TRANSFER). amount: Transaction amount in local currency. nameOrig: Initiating customer for the transaction. oldbalanceOrg: Initial balance of the originating customer before the transaction. newbalanceOrig: Balance of the originating customer after the transaction. nameDest: Recipient of the transaction (excludes information for merchants starting with 'M'). oldbalanceDest: Initial balance of the recipient before the transaction (excludes merchants). newbalanceDest: Balance of the recipient after the transaction (excludes merchants). isFraud: Indicates if the transaction is fraudulent (1 for fraudulent, 0 for legitimate). isFlaggedFraud: Flags illegal attempts, such as transfers exceeding 200,000 in a single transaction. Significance of the Dataset:

This synthetic dataset is valuable for studying and developing fraud detection methods. It combines normal transaction behaviors with injected fraudulent activities, providing a controlled environment to evaluate anomaly detection techniques. Researchers can explore approaches like oversampling and undersampling to address the challenge of highly imbalanced data, where fraudulent transactions are a minuscule fraction of the total.

Conclusion:

Due to the scarcity of publicly available real-world financial data, this synthetic dataset plays a critical role in advancing fraud detection algorithms. It supports both academic research and practical applications in the financial sector, particularly in mobile money transactions, aiding in the development of more robust and effective fraud prevention systems.
