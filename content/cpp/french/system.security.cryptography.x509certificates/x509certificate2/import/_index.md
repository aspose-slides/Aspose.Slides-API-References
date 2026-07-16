---
title: Import()
second_title: Référence de l'API Aspose.Slides pour C++
description: Importe les informations du fichier de certificat spécifié.
type: docs
weight: 300
url: /fr/system.security.cryptography.x509certificates/x509certificate2/import/
---
## X509Certificate2::Import(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) méthode


Importe les informations du fichier de certificat spécifié.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Le nom du fichier de certificat. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Le mot de passe requis pour accéder aux données du certificat. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const String\&, const String\&, X509KeyStorageFlags) méthode


Importe les informations du fichier de certificat spécifié.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Le nom du fichier de certificat. |
| password | const [String](../../../system/string/)\& | Le mot de passe requis pour accéder aux données du certificat. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) méthode


Importe les informations des données de certificat spécifiées.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const ByteArrayPtr &data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Les données du certificat X.509. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Le mot de passe requis pour accéder aux données du certificat. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) méthode


Importe les informations des données de certificat spécifiées.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const ByteArrayPtr &data, const String &password, X509KeyStorageFlags key_storage_flags) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Le nom du fichier de certificat. |
| password | const [String](../../../system/string/)\& | Le mot de passe requis pour accéder aux données du certificat. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const String\&) méthode


Importe les informations du fichier de certificat spécifié.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const String &filename) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Le nom du fichier de certificat. |

## X509Certificate2::Import(const ByteArrayPtr\&) méthode


Importe les informations des données de certificat spécifiées.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const ByteArrayPtr &data) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Le nom du fichier de certificat. |

## Voir aussi

* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Classe [String](../../../system/string/)
* Classe [X509Certificate2](../)
* Espace de noms [System::Security::Cryptography::X509Certificates](../../)
* Bibliothèque [Aspose.Slides](../../../)