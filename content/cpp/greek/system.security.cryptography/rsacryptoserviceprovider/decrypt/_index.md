---
title: Decrypt()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αποκρυπτογραφεί το μήνυμα. Δεν είναι υλοποιημένο.
type: docs
weight: 105
url: /el/system.security.cryptography/rsacryptoserviceprovider/decrypt/
---
## RSACryptoServiceProvider::Decrypt(const ByteArrayPtr\&, bool) μέθοδος

Αποκρυπτογραφεί το μήνυμα. Δεν είναι υλοποιημένο.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(const ByteArrayPtr &rgb, bool use_oaep)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) για αποκρυπτογράφηση. |
| use_oaep | **bool** | True για χρήση συμπλήρωσης OAEP, false για χρήση συμπλήρωσης PKCS#1 v1.5. |

### Τιμή επιστροφής

Αποκρυπτογραφημένος πίνακας δεδομένων.

## RSACryptoServiceProvider::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) μέθοδος

Αποκρυπτογραφεί τα εισερχόμενα δεδομένα χρησιμοποιώντας το καθορισμένο τρόπο συμπλήρωσης.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) πίνακας για αποκρυπτογράφηση. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Τρόπος συμπλήρωσης. |

### Τιμή επιστροφής

Αποκρυπτογραφημένα δεδομένα σε μορφή πίνακα bytes.

## Δείτε επίσης

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [RSACryptoServiceProvider](../)
* Κλάση [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Χώρος ονομάτων [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)