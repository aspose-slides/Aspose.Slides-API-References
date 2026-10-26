---
title: VerifyData()
second_title: Aspose.Slides για C++ Αναφορά API
description: Ελέγχει την υπογραφή των δεδομένων.
type: docs
weight: 209
url: /el/system.security.cryptography/rsacryptoserviceprovider/verifydata/
---
## RSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const SharedPtr\<Object\>\&, const ByteArrayPtr\&) method

Ελέγχει την υπογραφή των δεδομένων.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg, const ByteArrayPtr &signature)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) για έλεγχο της υπογραφής. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Αλγόριθμος κατακερματισμού προς χρήση. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Η υπογραφή όπως ελήφθη. |

### Τιμή Επιστροφής

Αληθής εάν η υπογραφή είναι έγκυρη, ψευδής διαφορετικά.

## Δείτε επίσης

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Object](../../../system/object/)
* Κλάση [RSACryptoServiceProvider](../)
* Χώρος ονομάτων [System::Security::Cryptography](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)