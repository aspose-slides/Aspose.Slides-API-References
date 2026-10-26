---
title: X509Certificate()
second_title: Aspose.Slides για C++ Αναφορά API
description: 
type: docs
weight: 1
url: /el/system.security.cryptography.x509certificates/x509certificate/x509certificate/
---
## X509Certificate::X509Certificate(const X509Certificate\&) κατασκευαστής




```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const X509Certificate &)=delete
```

## X509Certificate::X509Certificate() κατασκευαστής


Κατασκευαστής.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate()
```

## X509Certificate::X509Certificate(const ByteArrayPtr\&) κατασκευαστής


Κατασκευαστής.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &data)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Ακολουθία byte που αντιπροσωπεύει το κωδικοποιημένο πιστοποιητικό. |

## X509Certificate::X509Certificate(const String\&) κατασκευαστής


Κατασκευαστής.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Αρχείο από το οποίο φορτώνεται το πιστοποιητικό. |

## X509Certificate::X509Certificate(const SharedPtr\<X509Certificate\>\&) κατασκευαστής


Κατασκευαστής.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const SharedPtr<X509Certificate> &cert)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cert | const [SharedPtr](../../../system/sharedptr/)\<[X509Certificate](../)\>\& | Ένα πιστοποιητικό που χρησιμοποιείται για την αρχικοποίηση αυτού του αντικειμένου. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const String\&) κατασκευαστής


Κατασκευαστής.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const String &password)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Ακολουθία byte που αντιπροσωπεύει το κωδικοποιημένο πιστοποιητικό. |
| password | const [String](../../../system/string/)\& | Κωδικός πρόσβασης που χρησιμοποιείται για την πρόσβαση στα δεδομένα του πιστοποιητικού. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const SecureStringPtr\&) κατασκευαστής


Κατασκευαστής.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const SecureStringPtr &password)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Ακολουθία byte που αντιπροσωπεύει το κωδικοποιημένο πιστοποιητικό. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Κωδικός πρόσβασης που χρησιμοποιείται για την πρόσβαση στα δεδομένα του πιστοποιητικού. |

## X509Certificate::X509Certificate(const String\&, const String\&) κατασκευαστής


Κατασκευαστής.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const String &password)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Αρχείο από το οποίο φορτώνεται το πιστοποιητικό. |
| password | const [String](../../../system/string/)\& | Κωδικός πρόσβασης που χρησιμοποιείται για την πρόσβαση στα δεδομένα του πιστοποιητικού. |

## X509Certificate::X509Certificate(const String\&, const SecureStringPtr\&) κατασκευαστής


Κατασκευαστής.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const SecureStringPtr &password)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Αρχείο από το οποίο φορτώνεται το πιστοποιητικό. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Κωδικός πρόσβασης που χρησιμοποιείται για την πρόσβαση στα δεδομένα του πιστοποιητικού. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) κατασκευαστής


Κατασκευαστής.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const String &password, X509KeyStorageFlags key_storage_flags)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Ακολουθία byte που αντιπροσωπεύει το κωδικοποιημένο πιστοποιητικό. |
| password | const [String](../../../system/string/)\& | Κωδικός πρόσβασης που χρησιμοποιείται για την πρόσβαση στα δεδομένα του πιστοποιητικού. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Σημαίες που υποδεικνύουν πώς αποθηκεύεται το κλειδί. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) κατασκευαστής


Κατασκευαστής.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Ακολουθία byte που αντιπροσωπεύει το κωδικοποιημένο πιστοποιητικό. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Κωδικός πρόσβασης που χρησιμοποιείται για την πρόσβαση στα δεδομένα του πιστοποιητικού. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Σημαίες που υποδεικνύουν πώς αποθηκεύται το κλειδί. |

## X509Certificate::X509Certificate(const String\&, const String\&, X509KeyStorageFlags) κατασκευαστής


Κατασκευαστής.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Αρχείο από το οποίο φορτώνεται το πιστοποιητικό. |
| password | const [String](../../../system/string/)\& | Κωδικός πρόσβασης που χρησιμοποιείται για την πρόσβαση στα δεδομένα του πιστοποιητικού. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Σημαίες που υποδεικνύουν πώς αποθηκεύεται το κλειδί. |

## X509Certificate::X509Certificate(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) κατασκευαστής


Κατασκευαστής.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Αρχείο από το οποίο φορτώνεται το πιστοποιητικό. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Κωδικός πρόσβασης που χρησιμοποιείται για την πρόσβαση στα δεδομένα του πιστοποιητικού. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Σημαίες που υποδεικνύουν πώς αποθηκεύεται το κλειδί. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) κατασκευαστής


Κατασκευαστής.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const ByteArrayPtr &private_key, X509KeyStorageFlags key_storage_flags)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Ακολουθία byte που αντιπροσωπεύει το κωδικοποιημένο πιστοποιητικό (δημόσιο μέρος). |
| private_key | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Ακολουθία byte που αντιπροσωπεύει το ιδιωτικό κλειδί. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Σημαίες που υποδεικνύουν πώς αποθηκεύεται το κλειδί. |

## Δείτε επίσης

* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Class [X509Certificate](../)
* Class [String](../../../system/string/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)