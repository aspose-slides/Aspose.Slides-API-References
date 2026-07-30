---
title: GetAttribute()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vrací hodnotu atributu se zadaným lokálním názvem a URI jmenného prostoru.
type: docs
weight: 482
url: /cs/system.xml.xpath/xpathnavigator/getattribute/
---
## XPathNavigator::GetAttribute(String, String) metoda

Vrací hodnotu atributu se zadaným lokálním názvem a URI jmenného prostoru.

```cpp
virtual String System::Xml::XPath::XPathNavigator::GetAttribute(String localName, String namespaceURI)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Lokální název atributu. **localName** rozlišuje velká a malá písmena. |
| namespaceURI | [String](../../../system/string/) | URI jmenného prostoru atributu. |

### Návratová hodnota

Objekt [String](../../../system/string/) obsahující hodnotu zadaného atributu; [String::Empty](../../../system/string/empty/) pokud není nalezen odpovídající atribut, nebo pokud [XPathNavigator](../) není umístěn na uzlu elementu.

## Viz také

* Třída [String](../../../system/string/)
* Třída [XPathNavigator](../)
* Jmenný prostor [System::Xml::XPath](../../)
* Knihovna [Aspose.Slides](../../../)