---
title: get_LocalName()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar det lokala namnet på den aktuella noden.
type: docs
weight: 27
url: /sv/system.xml/xmlnodereader/get_localname/
---
## XmlNodeReader::get_LocalName() metod


Returnerar det lokala namnet på den aktuella noden.

```cpp
String System::Xml::XmlNodeReader::get_LocalName() override
```


### Returvärde

Namnet på den aktuella noden med prefixet borttaget. Till exempel är **LocalName** **book** för elementet **<bk:book>**. För nodtyper som inte har ett namn (som **[Text](../../../system.text/)**, **Comment**, och så vidare) returnerar den här metoden [String::Empty](../../../system/string/empty/).

## Se även

* Klass [String](../../../system/string/)
* Klass [XmlNodeReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)