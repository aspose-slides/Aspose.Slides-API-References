---
title: WriteStartElement()
second_title: Référence de l'API Aspose.Slides pour C++
description: Lorsqu'elle est redéfinie dans une classe dérivée, écrit la balise de démarrage spécifiée et l'associe à l'espace de noms donné.
type: docs
weight: 92
url: /fr/system.xml/xmlwriter/writestartelement/
---
## XmlWriter::WriteStartElement(const String\&, const String\&) méthode


Lorsqu'elle est redéfinie dans une classe dérivée, écrit la balise de démarrage spécifiée et l'associe à l'espace de noms fourni.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName, const String &ns)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Le nom local de l'élément. |
| ns | const [String](../../../system/string/)\& | L'URI de l'espace de noms à associer à l'élément. Si cet espace de noms est déjà dans le champ d'application et possède un préfixe associé, l'écrivain écrit automatiquement ce préfixe également. |

## XmlWriter::WriteStartElement(const String\&, const String\&, const String\&) méthode


Lorsqu'elle est redéfinie dans une classe dérivée, écrit la balise de démarrage spécifiée et l'associe à l'espace de noms et au préfixe fournis.

```cpp
virtual void System::Xml::XmlWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Le préfixe de l'espace de noms de l'élément. |
| localName | const [String](../../../system/string/)\& | Le nom local de l'élément. |
| ns | const [String](../../../system/string/)\& | L'URI de l'espace de noms à associer à l'élément. |

## XmlWriter::WriteStartElement(const String\&) méthode


Lorsqu'elle est redéfinie dans une classe dérivée, écrit une balise de démarrage avec le nom local spécifié.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Le nom local de l'élément. |

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlWriter](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)