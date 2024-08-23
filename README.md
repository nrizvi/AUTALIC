# AUTACT: AUTism Anti-Ableist Classification in Text
## Encrypted Dataset

The dataset in this repository is encrypted for security reasons. 
<strong>BOTH the .gpg and .enc files contain the SAME data so you only need to download/decrypt one of them.</strong>

To decrypt the dataset, use the following command:

### MAC OS and Linux
1) .gpg file:
``gpg -d AUTACT_all_labels.csv.gpg > AUTACT_all_labels.csv``
2) .enc file: ``openssl enc -aes-256-cbc -d -in AUTACT_all_labels.enc -out AUTACT_all_labels.csv``

### Windows 
#### Command Prompt/PowerShell
1) .gpg file: ``gpg -d AUTACT_all_labels.csv.gpg -o AUTACT_all_labels.csv``
2) .enc file: ``openssl enc -aes-256-cbc -d -in AUTACT_all_labels.enc -out AUTACT_all_labels.csv``
#### Git Bash
1) .gpg file: ``gpg -d AUTACT_all_labels.csv.gpg > AUTACT_all_labels.csv``
2) .enc file using OpenSSL in Git Bash: ``openssl enc -aes-256-cbc -d -in AUTACT_all_labels.enc -out AUTACT_all_labels.csv``
