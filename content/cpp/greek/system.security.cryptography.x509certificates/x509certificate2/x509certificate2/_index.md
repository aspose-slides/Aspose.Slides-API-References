---
title: X509Certificate2()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί κενό X509Certificate2.
type: docs
weight: 1
url: /el/system.security.cryptography.x509certificates/x509certificate2/x509certificate2/
---
## X509Certificate2::X509Certificate2() κατασκευαστής

Δημιουργεί κενό [X509Certificate2](../).

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2()
```

## X509Certificate2::X509Certificate2(const String\&) κατασκευαστής

Κατασκευαστής.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Αρχείο από το οποίο φορτώνεται το πιστοποιητικό. |

## X509Certificate2::X509Certificate2(const SharedPtr\<X509Certificate\>\&) κατασκευαστής

Κατασκευαστής.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const SharedPtr<X509Certificate> &cert)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cert | const [SharedPtr](../../../system/sharedptr/)\<[X509Certificate](../../x509certificate/)\>\& | Ένα αντικείμενο [X509Certificate](../../x509certificate/). |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&) κατασκευαστής

Κατασκευαστής.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Ακολουθία byte που αντιπροσωπεύει το κωδικοποιημένο πιστοποιητικό. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&) κατασκευαστής

Κατασκευαστής.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Ακολουθία byte που αντιπροσωπεύει το κωδικοποιημένο πιστοποιητικό. |
| password | const [String](../../../system/string/)\& | Κωδικός πρόσβασης πιστοποιητικού. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&) κατασκευαστής

Κατασκευαστής.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Ακολουθία byte που αντιπροσωπεύει το κωδικοποιημένο πιστοποιητικό. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Κωδικός πρόσβασης πιστοποιητικού. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) κατασκευαστής

Κατασκευαστής.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password, X509KeyStorageFlags key_storage_flags)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Ακολουθία byte που αντιπροσωπεύει το κωδικοποιημένο πιστοποιητικό. |
| password | const [String](../../../system/string/)\& | Κωδικός πρόσβασης πιστοποιητικού. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Σημαίες που υποδεικνύουν πώς να αποθηκευτεί το κλειδί. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) κατασκευαστής

Κατασκευαστής.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Ακολουθία byte που αντιπροσωπεύει το κωδικοποιημένο πιστοποιητικό. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Κωδικός πρόσβασης πιστοποιητικού. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Σημαίες που υποδεικνύουν πώς να αποθηκευτεί το κλειδί. |

## X509Certificate2::X509Certificate2(const String\&, const String\&) κατασκευαστής

Κατασκευαστής.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Αρχείο από το οποίο φορτώνεται το πιστοποιητικό. |
| password | const [String](../../../system/string/)\& | Κωδικός πρόσβασης πιστοποιητικού. |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&) κατασκευαστής

Κατασκευαστής.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Αρχείο από το οποίο φορτώνεται το πιστοποιητικό. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Κωδικός πρόσβασης πιστοποιητικού. |

## X509Certificate2::X509Certificate2(const String\&, const String\&, X509KeyStorageFlags) κατασκευαστής

Κατασκευαστής.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Αρχείο από το οποίο φορτώνεται το πιστοποιητικό. |
| password | const [String](../../../system/string/)\& | Κωδικός πρόσβασης πιστοποιητικού. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Σημαίες που υποδεικνύουν πώς να αποθηκευτεί το κλειδί. |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) κατασκευαστής

Κατασκευαστής.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Αρχείο από το οποίο φορτώνεται το πιστοποιητικό. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Κωδικός πρόσβασης πιστοποιητικού. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Σημαίες που υποδεικνύουν πώς να αποθηκευτεί το κλειδί. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) κατασκευαστής

Κατασκευαστής.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const ByteArrayPtr &private_key, X509KeyStorageFlags key_storage_flags)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Ακολουθία byte που αντιπροσωπεύει το κωδικοποιημένο πιστοποιητικό (δημόσιο μέρος). |
| private_key | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Ακολουθία byte που αντιπροσωπεύει το ιδιωτικό κλειδί. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Σημαίες που υποδεικνύουν πώς να αποθηκευτεί το κλειδί. |

## Δείτε επίσης

* Απαριθμητικό [X509KeyStorageFlags](../../x509keystorageflags/)
* Τύπος ορισμού [SharedPtr](../../../system/sharedptr/)
* Τύπος ορισμού [ByteArrayPtr](../../../system/bytearrayptr/)
* Τύπος ορισμού [SecureStringPtr](../../../system.security/securestringptr/)
* Κλάση [X509Certificate2](../)
* Κλάση [String](../../../system/string/)
* Κλάση [X509Certificate](../../x509certificate/)
* Χώρος ονομάτων [System::Security::Cryptography::X509Certificates](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)