---
title: Encrypt()
second_title: Αναφορά API του Aspose.Slides για C++
description: Κρυπτογραφεί το μήνυμα. Δεν είναι υλοποιημένο.
type: docs
weight: 118
url: /el/system.security.cryptography/rsacryptoserviceprovider/encrypt/
---
## RSACryptoServiceProvider::Encrypt(const ByteArrayPtr\&, bool) μέθοδος


Κρυπτογραφεί το μήνυμα. Δεν είναι υλοποιημένο.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(const ByteArrayPtr &rgb, bool use_oaep)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) για κρυπτογράφηση. |
| use_oaep | **bool** | True για χρήση padding OAEP, false για χρήση padding PKCS#1 v1.5. |

### Επιστρεφόμενη τιμή

Κρυπτογραφημένος πίνακας δεδομένων.

## RSACryptoServiceProvider::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) μέθοδος


Κρυπτογραφεί τα δεδομένα εισόδου χρησιμοποιώντας την καθορισμένη λειτουργία padding.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) πίνακας για κρυπτογράφηση. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Λειτουργία padding. |

### Επιστρεφόμενη τιμή

Κρυπτογραφημένα δεδομένα σε μορφή πίνακα byte.

## Δείτε επίσης

* Τύπος [ByteArrayPtr](../../../system/bytearrayptr/)
* Τύπος [SharedPtr](../../../system/sharedptr/)
* Κλάση [RSACryptoServiceProvider](../)
* Κλάση [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Χώρος ονομάτων [System::Security::Cryptography](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)