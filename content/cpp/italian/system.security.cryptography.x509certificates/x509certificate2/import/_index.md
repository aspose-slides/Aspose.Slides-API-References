---
title: Import()
second_title: Riferimento API di Aspose.Slides per C++
description: Importa le informazioni dal file di certificato specificato.
type: docs
weight: 300
url: /it/system.security.cryptography.x509certificates/x509certificate2/import/
---
## X509Certificate2::Import(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) metodo


Importa le informazioni dal file di certificato specificato.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Il nome del file di certificato. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | La password necessaria per accedere ai dati del certificato. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const String\&, const String\&, X509KeyStorageFlags) metodo


Importa le informazioni dal file di certificato specificato.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Il nome del file di certificato. |
| password | const [String](../../../system/string/)\& | La password necessaria per accedere ai dati del certificato. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) metodo


Importa le informazioni dai dati del certificato specificato.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const ByteArrayPtr &data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | I dati del certificato X.509. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | La password necessaria per accedere ai dati del certificato. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) metodo


Importa le informazioni dai dati del certificato specificato.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const ByteArrayPtr &data, const String &password, X509KeyStorageFlags key_storage_flags) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Il nome del file di certificato. |
| password | const [String](../../../system/string/)\& | La password necessaria per accedere ai dati del certificato. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const String\&) metodo


Importa le informazioni dal file di certificato specificato.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const String &filename) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Il nome del file di certificato. |

## X509Certificate2::Import(const ByteArrayPtr\&) metodo


Importa le informazioni dai dati del certificato specificato.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const ByteArrayPtr &data) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Il nome del file di certificato. |

## Vedi anche

* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Classe [String](../../../system/string/)
* Classe [X509Certificate2](../)
* Spazio dei nomi [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)