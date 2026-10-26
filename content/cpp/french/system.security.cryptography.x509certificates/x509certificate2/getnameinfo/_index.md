---
title: GetNameInfo()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient le nom du sujet ou de l'émetteur du certificat.
type: docs
weight: 248
url: /fr/system.security.cryptography.x509certificates/x509certificate2/getnameinfo/
---
## X509Certificate2::GetNameInfo(X509NameType, bool) const method

Obtient le nom du sujet ou de l'émetteur du certificat.

```cpp
String System::Security::Cryptography::X509Certificates::X509Certificate2::GetNameInfo(X509NameType name_type, bool for_issuer) const
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| name_type | [X509NameType](../../x509nametype/) | Options de formatage du nom. |
| for_issuer | **bool** | Si vrai, renvoie le nom de l'émetteur, sinon renvoie le nom du sujet. |

### Valeur de retour

Nom formaté de l'émetteur ou du sujet.

## Voir aussi

* Enum [X509NameType](../../x509nametype/)
* Class [String](../../../system/string/)
* Class [X509Certificate2](../)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)