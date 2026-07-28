---
title: MoveToAttribute()
second_title: Aspose.Slides C++ API referenciája
description: Áthelyezi az XPathNavigatort az attribútumra, amelynek a helyi neve és a névtér URI-ja megegyezik.
type: docs
weight: 495
url: /hu/system.xml.xpath/xpathnavigator/movetoattribute/
---
## XPathNavigator::MoveToAttribute(String, String) metódus


Áthelyezi a [XPathNavigator](../) az attribútumra, amelynek egyezik a helyi neve és a névtér URI-ja.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToAttribute(String localName, String namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Az attribútum helyi neve. |
| namespaceURI | [String](../../../system/string/) | Az attribútum névtér URI-ja; **nullptr** egy üres névtér esetén. |

### Return Value

**true** ha a [XPathNavigator](../) sikeresen áthelyeződik az attribútumra; egyébként **false**. Ha **false**, a [XPathNavigator](../) pozíciója változatlan marad.

## See Also

* Osztály [String](../../../system/string/)
* Osztály [XPathNavigator](../)
* Névterület [System::Xml::XPath](../../)
* Könyvtár [Aspose.Slides](../../../)