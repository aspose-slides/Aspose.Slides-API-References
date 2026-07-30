---
title: XmlNodeType
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica il tipo di nodo.
type: docs
weight: 833
url: /it/system.xml/xmlnodetype/
---
## XmlNodeType enum

Specifica il tipo di nodo.

```cpp
enum class XmlNodeType
```

### Valori

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | Questo è restituito da [XmlReader](../xmlreader/) se non è stato chiamato un metodo **Read**. |
| Element | 1 | Un elemento (ad esempio, **<item>**). |
| Attribute | 2 | Un attributo (ad esempio, **id='123'**). |
| Text | 3 | Il contenuto testuale di un nodo. Un nodo [XmlNodeType::Text](./) non può avere alcun nodo figlio. Può apparire come nodo figlio dei nodi [XmlNodeType::Attribute](./), [XmlNodeType::DocumentFragment](./), [XmlNodeType::Element](./) e [XmlNodeType::EntityReference](./). |
| CDATA | 4 | Una sezione CDATA (ad esempio, **my escaped text**). |
| EntityReference | 5 | Un riferimento a un'entità (ad esempio, **&num;**). |
| Entity | 6 | Una dichiarazione di entità (ad esempio, **<!ENTITY...>**). |
| ProcessingInstruction | 7 | Un'istruzione di elaborazione (ad esempio, **<?pi test?>**). |
| Comment | 8 | Un commento (ad esempio, ****). |
| Document | 9 | Un oggetto documento che, come radice dell'albero del documento, fornisce l'accesso all'intero documento XML. |
| DocumentType | 10 | La dichiarazione del tipo di documento, indicata dal seguente tag (ad esempio, **<!DOCTYPE...>**). |
| DocumentFragment | 11 | Un frammento di documento. |
| Notation | 12 | Una notazione nella dichiarazione del tipo di documento (ad esempio, **<!NOTATION...>**). |
| Whitespace | 13 | Spazio bianco tra i markup. |
| SignificantWhitespace | 14 | Spazio bianco tra i markup in un modello di contenuto misto o spazio bianco all'interno dell'ambito **xml:space=\"preserve\"**. |
| EndElement | 15 | Un tag di chiusura elemento (ad esempio, ****). |
| EndEntity | 16 | Restituito quando [XmlReader](../xmlreader/) arriva alla fine della sostituzione dell'entità a seguito di una chiamata a [XmlReader::ResolveEntity](../xmlreader/resolveentity/). |
| XmlDeclaration | 17 | La dichiarazione XML (ad esempio, **<?xml version='1.0'?>**). Il nodo [XmlNodeType::XmlDeclaration](./) deve essere il primo nodo nel documento. Non può avere figli. È un figlio del nodo [XmlNodeType::Document](./). Può avere attributi che forniscono informazioni sulla versione e sulla codifica. |

## Vedi anche

* Namespace [System::Xml](../)
* Library [Aspose.Slides](../../)