
# Aptos-enable-nft-receiving

This project allows you to enable NFT receiving for Aptos blockchain wallets.

## 1. Installation:

To set up the project, follow these steps:

1.  Open the project folder using **Command Prompt (cmd) or VS Code**.
2.  Install the required dependencies by running the following command:
    ```
    pip install -r requirements.txt
    ```

## 2. Configuration:

Before running the script, you need to configure the following settings:

1.  **Private Keys**:
    
    -   Add your private keys to the `private_keys.txt` file.
    -   Each private key should be on a new line.
2.  **Settings**:
    
    -   Open the `settings.py` file and configure the required parameters, such as API endpoints, wallet addresses, and other relevant settings.

## 3. Running the Script:

To start the process, execute the following command:
```
python main.py 
```
The script will automatically enable NFT receiving for the wallets specified in the `private_keys.txt` file. Ensure that all configurations are correctly set before running the script.
