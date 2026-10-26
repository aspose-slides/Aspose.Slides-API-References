---
title: XPathNodeType
second_title: Aspose.Slides voor C++ API Referentie
description: Definieert de XPath-knooppunt types die kunnen worden geretourneerd vanuit de XPathNavigator-klasse.
type: docs
weight: 157
url: /nl/system.xml.xpath/xpathnodetype/
---
## XPathNodeType enum

Definieert de [XPath](../) knooptypen die kunnen worden geretourneerd vanuit de [XPathNavigator](../xpathnavigator/) klasse.

```cpp
enum class XPathNodeType
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Root | 0 | De rootknoop van het XML-document of knooptboom. |
| Element | 1 | Een element, bijvoorbeeld **<element>**. |
| Attribute | 2 | Een attribuut, bijvoorbeeld **id='123'**. |
| Namespace | 3 | Een naamruimte, bijvoorbeeld **xmlns=\"namespace\"**. |
| Text | 4 | De tekstinhoud van een knoop. Equivalent aan het Document [Object](../../system/object/) Model (DOM) [Text](../../system.text/) en CDATA knooptypen. Bevat minstens één teken. |
| SignificantWhitespace | 5 | Een knoop met witruimte-tekens en **xml:space** ingesteld op **preserve**. |
| Whitespace | 6 | Een knoop met alleen witruimte-tekens en geen significante witruimte. Witruimte-tekens zijn **'\x20'**, **'\x0d'**, **'\x0a'**, **'\x09'**. |
| ProcessingInstruction | 7 | Een verwerkingsinstructie, bijvoorbeeld **<?pi test?>**. Dit omvat geen XML-declaraties, die niet zichtbaar zijn voor de [XPathNavigator](../xpathnavigator/) klasse. |
| Comment | 8 | Een opmerking, bijvoorbeeld ****. |
| All | 9 | Elk van de XPathNodeType knooptypen. |

## Zie ook

* Namespace [System::Xml::XPath](../)
* Library [Aspose.Slides](../../)