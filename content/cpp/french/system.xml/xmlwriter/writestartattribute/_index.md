---
title: WriteStartAttribute()
second_title: Référence API Aspose.Slides pour C++
description: Écrit le début d’un attribut avec le nom local spécifié et l’URI de l’espace de noms.
type: docs
weight: 144
url: /fr/system.xml/xmlwriter/writestartattribute/
---
## XmlWriter::WriteStartAttribute(const String\&, const String\&) méthode

Écrit le début d'un attribut avec le nom local et l'URI d'espace de noms spécifiés.

```cpp
void System::Xml::XmlWriter::WriteStartAttribute(const String &localName, const String &ns)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Le nom local de l'attribut. |
| ns | const [String](../../../system/string/)\& | L'URI d'espace de noms de l'attribut. |

## XmlWriter::WriteStartAttribute(const String\&, const String\&, const String\&) méthode

Lorsqu'elle est remplacée dans une classe dérivée, écrit le début d'un attribut avec le préfixe, le nom local et l'URI d'espace de noms spécifiés.

```cpp
virtual void System::Xml::XmlWriter::WriteStartAttribute(const String &prefix, const String &localName, const String &ns)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Le préfixe d'espace de noms de l'attribut. |
| localName | const [String](../../../system/string/)\& | Le nom local de l'attribut. |
| ns | const [String](../../../system/string/)\& | L'URI d'espace de noms pour l'attribut. |

## XmlWriter::WriteStartAttribute(const String\&) méthode

Écrit le début d'un attribut avec le nom local spécifié.

```cpp
void System::Xml::XmlWriter::WriteStartAttribute(const String &localName)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Le nom local de l'attribut. |

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlWriter](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)