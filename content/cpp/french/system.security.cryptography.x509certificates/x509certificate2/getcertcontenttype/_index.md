---
title: GetCertContentType()
second_title: Référence de l'API Aspose.Slides for C++
description: Obtient le type du certificat contenu dans le tableau d'octets spécifié.
type: docs
weight: 391
url: /fr/system.security.cryptography.x509certificates/x509certificate2/getcertcontenttype/
---
## X509Certificate2::GetCertContentType(const ByteArrayPtr\&) méthode

Obtient le type du certificat contenu dans le tableau d'octets spécifié.

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const ByteArrayPtr &raw_data)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Données du certificat. |

### Valeur de retour

Type de certificat X.509.

## X509Certificate2::GetCertContentType(const String\&) méthode

Obtient le type du certificat contenu dans le fichier spécifié.

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const String &filename)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Nom du fichier de certificat. |

### Valeur de retour

Type de certificat X.509.

## Voir aussi

* Enum [X509ContentType](../../x509contenttype/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Classe [X509Certificate2](../)
* Classe [String](../../../system/string/)
* Espace de noms [System::Security::Cryptography::X509Certificates](../../)
* Bibliothèque [Aspose.Slides](../../../)