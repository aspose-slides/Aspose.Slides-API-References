---
title: ToString()
second_title: Référence API Aspose.Slides pour C++
description: Renvoie la valeur de chaîne du XmlQualifiedName.
type: docs
weight: 79
url: /fr/system.xml/xmlqualifiedname/tostring/
---
## XmlQualifiedName::ToString() const méthode

Renvoie la valeur de chaîne du [XmlQualifiedName](../).

```cpp
String System::Xml::XmlQualifiedName::ToString() const override
```

### Valeur de retour

La valeur de chaîne du [XmlQualifiedName](../) au format **namespace:localname**. Si l'objet n'a pas d'espace de noms défini, cette méthode renvoie uniquement le nom local.

## XmlQualifiedName::ToString(const String\&, const String\&) méthode

Renvoie la valeur de chaîne du [XmlQualifiedName](../).

```cpp
static String System::Xml::XmlQualifiedName::ToString(const String &name, const String &ns)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Le nom de l'objet. |
| ns | const [String](../../../system/string/)\& | L'espace de noms de l'objet. |

### Valeur de retour

La valeur de chaîne du [XmlQualifiedName](../) au format **namespace:localname**. Si l'objet n'a pas d'espace de noms défini, cette méthode renvoie uniquement le nom local.

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlQualifiedName](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)