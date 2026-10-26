---
title: XPathNodeType
second_title: Aspose.Slides pro C++ API Reference
description: Definuje typy uzlů XPath, které mohou být vráceny ze třídy XPathNavigator.
type: docs
weight: 157
url: /cs/system.xml.xpath/xpathnodetype/
---
## XPathNodeType enum

Definuje typy uzlů [XPath](../), které mohou být vráceny ze třídy [XPathNavigator](../xpathnavigator/).

```cpp
enum class XPathNodeType
```

### Values

| Název | Hodnota | Popis |
| --- | --- | --- |
| Root | 0 | Kořenový uzel XML dokumentu nebo stromu uzlů. |
| Element | 1 | Element, např. **<element>**. |
| Attribute | 2 | Atribut, např. **id='123'**. |
| Namespace | 3 | Jmenný prostor, např. **xmlns=\"namespace\"**. |
| Text | 4 | Textový obsah uzlu. Ekvivalentní k typům uzlů Document [Object](../../system/object/) Model (DOM) [Text](../../system.text/) a CDATA. Obsahuje alespoň jeden znak. |
| SignificantWhitespace | 5 | Uzlu s bílé mezery a nastaveným **xml:space** na **preserve**. |
| Whitespace | 6 | Uzlu, který obsahuje pouze znaky bílých mezer a žádné významné mezery. Znaky bílých mezer jsou **'\x20'**, **'\x0d'**, **'\x0a'**, **'\x09'**. |
| ProcessingInstruction | 7 | Instrukce zpracování, např. **<?pi test?>**. To nezahrnuje XML deklarace, které nejsou viditelné pro třídu [XPathNavigator](../xpathnavigator/). |
| Comment | 8 | Komentář, např. ****. |
| All | 9 | Jakýkoli z typů uzlů XPathNodeType. |

## See Also

* Jmenný prostor [System::Xml::XPath](../)
* Knihovna [Aspose.Slides](../../)