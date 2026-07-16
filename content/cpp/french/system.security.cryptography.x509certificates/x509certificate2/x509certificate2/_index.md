---
title: X509Certificate2()
second_title: Référence de l'API Aspose.Slides pour C++
description: Construit un X509Certificate2 vide.
type: docs
weight: 1
url: /fr/system.security.cryptography.x509certificates/x509certificate2/x509certificate2/
---
## X509Certificate2::X509Certificate2() constructeur


Construit un [X509Certificate2](../) vide.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2()
```

## X509Certificate2::X509Certificate2(const String\&) constructeur


Constructeur.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Fichier à partir duquel charger le certificat. |

## X509Certificate2::X509Certificate2(const SharedPtr\<X509Certificate\>\&) constructeur


Constructeur.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const SharedPtr<X509Certificate> &cert)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| cert | const [SharedPtr](../../../system/sharedptr/)\<[X509Certificate](../../x509certificate/)\>\& | Un objet [X509Certificate](../../x509certificate/). |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&) constructeur


Constructeur.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Séquence d'octets représentant le certificat encodé. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&) constructeur


Constructeur.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Séquence d'octets représentant le certificat encodé. |
| password | const [String](../../../system/string/)\& | Mot de passe du certificat. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&) constructeur


Constructeur.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Séquence d'octets représentant le certificat encodé. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Mot de passe du certificat. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) constructeur


Constructeur.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password, X509KeyStorageFlags key_storage_flags)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Séquence d'octets représentant le certificat encodé. |
| password | const [String](../../../system/string/)\& | Mot de passe du certificat. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Indicateurs indiquant comment stocker la clé. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) constructeur


Constructeur.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Séquence d'octets représentant le certificat encodé. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Mot de passe du certificat. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Indicateurs indiquant comment stocker la clé. |

## X509Certificate2::X509Certificate2(const String\&, const String\&) constructeur


Constructeur.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Fichier à partir duquel charger le certificat. |
| password | const [String](../../../system/string/)\& | Mot de passe du certificat. |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&) constructeur


Constructeur.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Fichier à partir duquel charger le certificat. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Mot de passe du certificat. |

## X509Certificate2::X509Certificate2(const String\&, const String\&, X509KeyStorageFlags) constructeur


Constructeur.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Fichier à partir duquel charger le certificat. |
| password | const [String](../../../system/string/)\& | Mot de passe du certificat. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Indicateurs indiquant comment stocker la clé. |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) constructeur


Constructeur.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Fichier à partir duquel charger le certificat. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Mot de passe du certificat. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Indicateurs indiquant comment stocker la clé. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) constructeur


Constructeur.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const ByteArrayPtr &private_key, X509KeyStorageFlags key_storage_flags)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Séquence d'octets représentant le certificat encodé (partie publique). |
| private_key | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Séquence d'octets représentant la clé privée. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Indicateurs indiquant comment stocker la clé. |

## Voir aussi

* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Class [X509Certificate2](../)
* Class [String](../../../system/string/)
* Class [X509Certificate](../../x509certificate/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)