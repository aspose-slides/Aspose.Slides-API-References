---
title: X509Certificate2()
second_title: Riferimento API Aspose.Slides per C++
description: Costruisce un X509Certificate2 vuoto.
type: docs
weight: 1
url: /it/system.security.cryptography.x509certificates/x509certificate2/x509certificate2/
---
## X509Certificate2::X509Certificate2() costruttore


Costruisce vuoto [X509Certificate2](../).

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2()
```

## X509Certificate2::X509Certificate2(const String\&) costruttore


Costruttore.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | File da cui caricare il certificato. |

## X509Certificate2::X509Certificate2(const SharedPtr\<X509Certificate\>\&) costruttore


Costruttore.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const SharedPtr<X509Certificate> &cert)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cert | const [SharedPtr](../../../system/sharedptr/)\<[X509Certificate](../../x509certificate/)\>\& | Un oggetto [X509Certificate](../../x509certificate/). |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&) costruttore


Costruttore.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequenza di byte che rappresenta il certificato codificato. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&) costruttore


Costruttore.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequenza di byte che rappresenta il certificato codificato. |
| password | const [String](../../../system/string/)\& | Password del certificato. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&) costruttore


Costruttore.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequenza di byte che rappresenta il certificato codificato. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Password del certificato. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) costruttore


Costruttore.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password, X509KeyStorageFlags key_storage_flags)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequenza di byte che rappresenta il certificato codificato. |
| password | const [String](../../../system/string/)\& | Password del certificato. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flag che indicano come memorizzare la chiave. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) costruttore


Costruttore.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequenza di byte che rappresenta il certificato codificato. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Password del certificato. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flag che indicano come memorizzare la chiave. |

## X509Certificate2::X509Certificate2(const String\&, const String\&) costruttore


Costruttore.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | File da cui caricare il certificato. |
| password | const [String](../../../system/string/)\& | Password del certificato. |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&) costruttore


Costruttore.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | File da cui caricare il certificato. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Password del certificato. |

## X509Certificate2::X509Certificate2(const String\&, const String\&, X509KeyStorageFlags) costruttore


Costruttore.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | File da cui caricare il certificato. |
| password | const [String](../../../system/string/)\& | Password del certificato. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flag che indicano come memorizzare la chiave. |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) costruttore


Costruttore.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | File da cui caricare il certificato. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Password del certificato. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flag che indicano come memorizzare la chiave. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) costruttore


Costruttore.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const ByteArrayPtr &private_key, X509KeyStorageFlags key_storage_flags)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequenza di byte che rappresenta il certificato codificato (parte pubblica). |
| private_key | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequenza di byte che rappresenta la chiave privata. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flag che indicano come memorizzare la chiave. |

## Vedi anche

* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Classe [X509Certificate2](../)
* Classe [String](../../../system/string/)
* Classe [X509Certificate](../../x509certificate/)
* Spazio dei nomi [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)