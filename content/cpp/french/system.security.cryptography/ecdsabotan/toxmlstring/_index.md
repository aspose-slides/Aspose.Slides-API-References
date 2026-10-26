---
title: ToXmlString()
second_title: Référence de l'API Aspose.Slides pour C++
description: Exporte tous les paramètres au format XML. Non implémenté.
type: docs
weight: 157
url: /fr/system.security.cryptography/ecdsabotan/toxmlstring/
---
## ECDsaBotan::ToXmlString(bool) méthode

Exporte tous les paramètres au format XML. Non implémenté.

```cpp
String System::Security::Cryptography::ECDsaBotan::ToXmlString(bool include_private_parameters) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| include_private_parameters | **bool** | True pour exporter à la fois les paramètres privés et publics, false pour n'exporter que les paramètres publics. |

### Valeur de retour

Paramètres encodés en XML.

## ECDsaBotan::ToXmlString(ECKeyXmlFormat) méthode

Exporte tous les paramètres au format XML.

```cpp
String System::Security::Cryptography::ECDsaBotan::ToXmlString(ECKeyXmlFormat format)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| format | [ECKeyXmlFormat](../../eckeyxmlformat/) | Format de la chaîne XML résultante. |

### Valeur de retour

Paramètres encodés en XML.

## Voir aussi

* Enum [ECKeyXmlFormat](../../eckeyxmlformat/)
* Classe [String](../../../system/string/)
* Classe [ECDsaBotan](../)
* Espace de noms [System::Security::Cryptography](../../)
* Bibliothèque [Aspose.Slides](../../../)