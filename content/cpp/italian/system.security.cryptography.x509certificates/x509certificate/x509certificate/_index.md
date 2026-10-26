---
title: X509Certificate()
second_title: Riferimento API Aspose.Slides per C++
description:
type: docs
weight: 1
url: /it/system.security.cryptography.x509certificates/x509certificate/x509certificate/
---
## X509Certificate::X509Certificate(const X509Certificate\&) costruttore




```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const X509Certificate &)=delete
```

## X509Certificate::X509Certificate() costruttore


Costruttore.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate()
```

## X509Certificate::X509Certificate(const ByteArrayPtr\&) costruttore


Costruttore.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &data)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequenza di byte che rappresenta il certificato codificato. |

## X509Certificate::X509Certificate(const String\&) costruttore


Costruttore.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | File da cui caricare il certificato. |

## X509Certificate::X509Certificate(const SharedPtr\<X509Certificate\>\&) costruttore


Costruttore.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const SharedPtr<X509Certificate> &cert)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cert | const [SharedPtr](../../../system/sharedptr/)\<[X509Certificate](../)\>\& | Un certificato usato per inizializzare questo oggetto. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const String\&) costruttore


Costruttore.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const String &password)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequenza di byte che rappresenta il certificato codificato. |
| password | const [String](../../../system/string/)\& | Password utilizzata per accedere ai dati del certificato. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const SecureStringPtr\&) costruttore


Costruttore.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const SecureStringPtr &password)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequenza di byte che rappresenta il certificato codificato. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Password utilizzata per accedere ai dati del certificato. |

## X509Certificate::X509Certificate(const String\&, const String\&) costruttore


Costruttore.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const String &password)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | File da cui caricare il certificato. |
| password | const [String](../../../system/string/)\& | Password utilizzata per accedere ai dati del certificato. |

## X509Certificate::X509Certificate(const String\&, const SecureStringPtr\&) costruttore


Costruttore.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const SecureStringPtr &password)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | File da cui caricare il certificato. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Password utilizzata per accedere ai dati del certificato. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) costruttore


Costruttore.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const String &password, X509KeyStorageFlags key_storage_flags)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequenza di byte che rappresenta il certificato codificato. |
| password | const [String](../../../system/string/)\& | Password utilizzata per accedere ai dati del certificato. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flag che indicano come memorizzare la chiave. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) costruttore


Costruttore.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequenza di byte che rappresenta il certificato codificato. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Password utilizzata per accedere ai dati del certificato. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flag che indicano come memorizzare la chiave. |

## X509Certificate::X509Certificate(const String\&, const String\&, X509KeyStorageFlags) costruttore


Costruttore.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | File da cui caricare il certificato. |
| password | const [String](../../../system/string/)\& | Password utilizzata per accedere ai dati del certificato. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flag che indicano come memorizzare la chiave. |

## X509Certificate::X509Certificate(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) costruttore


Costruttore.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | File da cui caricare il certificato. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Password utilizzata per accedere ai dati del certificato. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flag che indicano come memorizzare la chiave. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) costruttore


Costruttore.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const ByteArrayPtr &private_key, X509KeyStorageFlags key_storage_flags)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequenza di byte che rappresenta il certificato codificato (parte pubblica). |
| private_key | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequenza di byte che rappresenta la chiave privata. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flag che indicano come memorizzare la chiave. |

## Vedi anche

* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Classe [X509Certificate](../)
* Classe [String](../../../system/string/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Libreria [Aspose.Slides](../../../)