---
title: SignData()
second_title: Aspose.Slides για C++ API Αναφορά
description: Υπολογίζει την υπογραφή της καθορισμένης τιμής εισόδου.
type: docs
weight: 183
url: /el/system.security.cryptography/rsacryptoserviceprovider/signdata/
---
## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const SharedPtr\<Object\>\&) μέθοδος

Υπολογίζει την υπογραφή της καθορισμένης τιμής εισόδου.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) για ανάγνωση δεδομένων εισόδου από. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Αλγόριθμος κατακερματισμού προς χρήση. |

### Τιμή Επιστροφής

[RSA](../../rsa/) υπογραφή για τα καθορισμένα δεδομένα.

## RSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Object\>\&) μέθοδος

Υπολογίζει την υπογραφή της καθορισμένης τιμής εισόδου.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream, const SharedPtr<Object> &halg)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Ροή για ανάγνωση των δεδομένων που υπογραφονται από. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Αλγόριθμος κατακερματισμού προς χρήση. |

### Τιμή Επιστροφής

[RSA](../../rsa/) υπογραφή για τα καθορισμένα δεδομένα.

## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const SharedPtr\<Object\>\&) μέθοδος

Υπολογίζει την υπογραφή της καθορισμένης τιμής εισόδου.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count, const SharedPtr<Object> &halg)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) για ανάγνωση δεδομένων εισόδου από. |
| offset | **int32_t** | Δείκτης έναρξης τμήματος του buffer εισόδου. |
| count | **int32_t** | Μέγεθος τμήματος του buffer εισόδου. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Αλγόριθμος κατακερματισμού προς χρήση. |

### Τιμή Επιστροφής

[RSA](../../rsa/) υπογραφή για τα καθορισμένα δεδομένα.

## Δείτε επίσης

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Object](../../../system/object/)
* Κλάση [RSACryptoServiceProvider](../)
* Κλάση [Stream](../../../system.io/stream/)
* Χώρος ονομάτων [System::Security::Cryptography](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)