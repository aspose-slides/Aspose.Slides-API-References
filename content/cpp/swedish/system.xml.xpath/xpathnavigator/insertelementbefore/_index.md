---
title: InsertElementBefore()
second_title: Aspose.Slides för C++ API-referens
description: Skapar ett nytt syskon-element före den aktuella noden med det angivna namnutrymmesprefixet, lokala namnet och den angivna namnutrymmes-URI:n, med det angivna värdet.
type: docs
weight: 1015
url: /sv/system.xml.xpath/xpathnavigator/insertelementbefore/
---
## XPathNavigator::InsertElementBefore(String, String, String, String) metod


Skapar ett nytt syskon-element före den aktuella noden med det angivna namnutrymmesprefixet, lokala namnet och namnutrymmes-URI, med det angivna värdet.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertElementBefore(String prefix, String localName, String namespaceURI, String value)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Namnutrymmesprefixet för det nya barnelementet (om någon). |
| localName | [String](../../../system/string/) | Det lokala namnet för det nya barnelementet (om någon). |
| namespaceURI | [String](../../../system/string/) | Namnutrymmes-URI för det nya barnelementet (om någon). [String::Empty](../../../system/string/empty/) och **nullptr** är ekvivalenta. |
| value | [String](../../../system/string/) | Värdet för det nya barnelementet. Om [String::Empty](../../../system/string/empty/) eller **nullptr** skickas, skapas ett tomt element. |

## Se även

* Klass [String](../../../system/string/)
* Klass [XPathNavigator](../)
* Namnrymd [System::Xml::XPath](../../)
* Bibliotek [Aspose.Slides](../../../)