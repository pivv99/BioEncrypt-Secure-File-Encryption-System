# BioEncrypt – Secure File Encryption System with Biometric Authentication

## Overview
BioEncrypt is a desktop-based cybersecurity project developed to provide secure file encryption and decryption using multiple layers of authentication. The application combines cryptographic protection with biometric verification and OTP-based authentication to improve access control and data security.

## Features
- AES-based file encryption and decryption
- Secure password hashing using bcrypt
- Multi-Factor Authentication (MFA)
  - Password authentication
  - Biometric face recognition
  - One-Time Password (OTP) verification
- Real-time face enrollment and authentication using webcam
- Desktop GUI built with wxPython
- Secure file explorer for managing encrypted files
- Event logging for encryption and decryption actions
- Separate key and nonce handling for secure encryption management

## Technologies Used
- Python
- wxPython
- OpenCV
- face_recognition
- bcrypt
- AES (PyCryptodome)
- pickle
- os / shutil
- random / secrets

## Security Concepts Applied
- Cryptography
- Authentication Security
- Access Control
- Data Protection
- Secure File Handling
- Multi-Factor Authentication

## Project Workflow
1. User signs up with username and password
2. User enrolls face biometrics using webcam
3. User logs in using:
   - Password
   - Face recognition
   - OTP verification
4. User can encrypt files securely
5. User must re-authenticate to decrypt files
6. Encryption and decryption activities are logged

## Future Improvements
- File integrity verification
- RSA key protection
- Secure database integration
- Email-based OTP delivery
- Improved access logging and security monitoring

## Screenshots
![image alt](https://github.com/pivv99/BioEncrypt-Secure-File-Encryption-System/blob/main/Login:%20Sign%20up%20Page.png?raw=true)
![image alt](https://github.com/pivv99/BioEncrypt-Secure-File-Encryption-System/blob/main/Login%20Page.png?raw=true)
![image alt](https://github.com/pivv99/BioEncrypt-Secure-File-Encryption-System/blob/main/Sign%20up%20Successfully.png?raw=true)
![image alt](https://github.com/pivv99/BioEncrypt-Secure-File-Encryption-System/blob/main/User%20Name%20:%20Password.png?raw=true)
![image alt](https://github.com/pivv99/BioEncrypt-Secure-File-Encryption-System/blob/main/Login%20Successfully%20.png?raw=true)
![image alt](https://github.com/pivv99/BioEncrypt-Secure-File-Encryption-System/blob/main/File%20Explorer.png?raw=true)
![image alt](https://github.com/pivv99/BioEncrypt-Secure-File-Encryption-System/blob/main/choosing%20files.png?raw=true)
![image alt](https://github.com/pivv99/BioEncrypt-Secure-File-Encryption-System/blob/main/File%20Encrypted.png?raw=true)
![image alt](https://github.com/pivv99/BioEncrypt-Secure-File-Encryption-System/blob/main/File%20decrypted.png?raw=true)
![image alt](https://github.com/pivv99/BioEncrypt-Secure-File-Encryption-System/blob/main/Logging%20Out.png?raw=true)


## Author
Mohamed Emaad
