# RC5 Encryption/Decryption Interface

* [Backend Project](https://github.com/sergiu1301/CryptographyBackend)
* [Frontend Project](https://github.com/sergiu1301/CryptographyFrontend)

This is a user-friendly interface designed to demonstrate the **RC5 encryption and decryption algorithm**. It allows users to configure specific parameters and observe the results of the encryption or decryption process in real-time.

---

## Features
1. **Algorithm Selection**:
   - Currently supports **RC5**.
   - Placeholder for future support of AES, RSA, or other algorithms.

2. **Encryption/Decryption Modes**:
   - Choose between **Encrypt** or **Decrypt** operations.

3. **Configurable Parameters**:
   - `w (word size)`:
     - Selectable values: **16 bits**, **32 bits**, or **64 bits**.
     - Represents the word size in the RC5 algorithm.
   - `r (rounds)`:
     - Choose the number of rounds (from **0** to **255**) to control the complexity of the algorithm.

4. **Text Fields**:
   - **Plaintext**: Enter the text to be encrypted (for encryption mode).
   - **Ciphertext**: Enter the encrypted text to be decrypted (for decryption mode).
   - **Key**: Specify the encryption key (validated for bit-length compatibility).

5. **Validation**:
   - Ensures that:
     - The key length in bits is greater than or equal to the selected `w`.
     - Configurable options follow the RC5 specification (e.g., valid `w` values and `r` ranges).

6. **Results Display**:
   - Shows the **encrypted** or **decrypted** result in a neatly formatted section below the interface.

---

## How It Works
1. **Step 1**: Choose the algorithm (**RC5**).
2. **Step 2**: Select operation (`Encrypt` or `Decrypt`).
3. **Step 3**: Configure the parameters:
   - Select the **word size** (`w`).
   - Set the number of **rounds** (`r`).
4. **Step 4**: Provide the required input:
   - For encryption: Enter the plaintext and key.
   - For decryption: Enter the ciphertext and key.
5. **Step 5**: Click **Start**.
6. **Output**: The result will be displayed in the **Result** section at the bottom.

---

## Example Usage
- **Encryption**:
  - **w**: 32 bits
  - **r**: 12 rounds
  - **Plaintext**: `Example`
  - **Key**: `test`
  - **Result**: `BEFCCC676F171FC4`

  **Decryption**:
  - **w**: 32 bits
  - **r**: 12 rounds
  - **Plaintext**: `BEFCCC676F171FC4`
  - **Key**: `test`
  - **Result**: `Example`

---

## Notes
- The interface ensures compatibility with RC5 specifications:
  - Validates key length against the selected word size.
  - Restricts parameter choices to RC5-supported values.
- Future support for other algorithms is planned.

---

## Screenshot
![RC5 Encryption/Decryption Interface](https://github.com/user-attachments/assets/7e1a30c7-4106-464b-873c-4ab689d7f522)

![RC5 Encryption/Decryption Interface](https://github.com/user-attachments/assets/203b734f-eefd-490c-85da-8592b0f4504b)



