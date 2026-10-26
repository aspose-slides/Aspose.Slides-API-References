---
title: XPathNodeType
second_title: Aspose.Slides for C++ API-referencia
description: Meghatározza az XPath csomópont típusokat, amelyeket az XPathNavigator osztály visszaadhat.
type: docs
weight: 157
url: /hu/system.xml.xpath/xpathnodetype/
---
## XPathNodeType enum


Meghatározza a [XPath](../) csomópont típusokat, amelyeket a [XPathNavigator](../xpathnavigator/) osztály visszaadhat.

```cpp
enum class XPathNodeType
```

### Values

| Név | Érték | Leírás |
| --- | --- | --- |
| Root | 0 | Az XML dokumentum vagy csomópontfa gyökércsomópontja. |
| Element | 1 | Egy elem, például **<element>**. |
| Attribute | 2 | Egy attribútum, például **id='123'**. |
| Namespace | 3 | Egy névtér, például **xmlns=\"namespace\"**. |
| Text | 4 | Egy csomópont szöveges tartalma. Ez megfelel a Document [Object](../../system/object/) Model (DOM) [Text](../../system.text/) és a CDATA csomópont típusoknak. Legalább egy karaktert tartalmaz. |
| SignificantWhitespace | 5 | Egy csomópont, amelyben szóköz karakterek vannak, és a **xml:space** értéke **preserve**. |
| Whitespace | 6 | Egy csomópont, amely csak szóköz karaktereket tartalmaz, és nincs jelentős szóköz. A szóköz karakterek a **'\x20'**, **'\x0d'**, **'\x0a'**, **'\x09'**. |
| ProcessingInstruction | 7 | Egy feldolgozási utasítás, például **<?pi test?>**. Ez nem tartalmazza az XML deklarációkat, amelyek nem láthatók a [XPathNavigator](../xpathnavigator/) osztály számára. |
| Comment | 8 | Egy megjegyzés, például ****. |
| All | 9 | Az XPathNodeType csomópont típusok bármelyike. |

## See Also

* Névterület [System::Xml::XPath](../)
* Könyvtár [Aspose.Slides](../../)