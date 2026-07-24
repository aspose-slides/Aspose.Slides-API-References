---
title: XmlNodeType
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den Typ des Knotens an.
type: docs
weight: 833
url: /de/system.xml/xmlnodetype/
---
## XmlNodeType enum


Gibt den Typ des Knotens an.

```cpp
enum class XmlNodeType
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | 0 | Dies wird von [XmlReader](../xmlreader/) zurückgegeben, wenn keine **Read**-Methode aufgerufen wurde. |
| Element | 1 | Ein Element (zum Beispiel **<item>**). |
| Attribute | 2 | Ein Attribut (zum Beispiel **id='123'**). |
| Text | 3 | Der Textinhalt eines Knotens. Ein [XmlNodeType::Text](./)-Knoten kann keine untergeordneten Knoten haben. Er kann als Kindknoten der [XmlNodeType::Attribute](./)-, [XmlNodeType::DocumentFragment](./)-, [XmlNodeType::Element](./)- und [XmlNodeType::EntityReference](./)-Knoten auftreten. |
| CDATA | 4 | Ein CDATA-Abschnitt (zum Beispiel **my escaped text**). |
| EntityReference | 5 | Eine Referenz auf eine Entität (zum Beispiel **&num;**). |
| Entity | 6 | Eine Entitätsdeklaration (zum Beispiel **<!ENTITY...>**). |
| ProcessingInstruction | 7 | Eine Verarbeitungsanweisung (zum Beispiel **<?pi test?>**). |
| Comment | 8 | Ein Kommentar (zum Beispiel ****). |
| Document | 9 | Ein Dokumentobjekt, das als Wurzel des Dokumentbaums Zugriff auf das gesamte XML-Dokument bietet. |
| DocumentType | 10 | Die Dokumenttyp-Deklaration, angezeigt durch das folgende Tag (zum Beispiel **<!DOCTYPE...>**). |
| DocumentFragment | 11 | Ein Dokumentfragment. |
| Notation | 12 | Eine Notation in der Dokumenttyp-Deklaration (zum Beispiel **<!NOTATION...>**). |
| Whitespace | 13 | Weißraum zwischen Markup. |
| SignificantWhitespace | 14 | Weißraum zwischen Markup in einem gemischten Inhaltsmodell oder Weißraum innerhalb des **xml:space=\"preserve\"**-Geltungsbereichs. |
| EndElement | 15 | Ein End-Element-Tag (zum Beispiel ****). |
| EndEntity | 16 | Wird zurückgegeben, wenn [XmlReader](../xmlreader/) das Ende des Entitätenersetzens erreicht, als Ergebnis eines Aufrufs von [XmlReader::ResolveEntity](../xmlreader/resolveentity/). |
| XmlDeclaration | 17 | Die XML-Deklaration (zum Beispiel **<?xml version='1.0'?>**). Der [XmlNodeType::XmlDeclaration](./)-Knoten muss der erste Knoten im Dokument sein. Er darf keine Kinder haben. Er ist ein Kindknoten des [XmlNodeType::Document](./)-Knotens. Er kann Attribute besitzen, die Versions- und Codierungsinformationen bereitstellen. |

## Siehe auch

* Namensraum [System::Xml](../)
* Bibliothek [Aspose.Slides](../../)