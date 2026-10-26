---
title: get_LocalName()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar det lokala namnet på den aktuella noden.
type: docs
weight: 27
url: /sv/system.xml/xmltextreader/get_localname/
---
## XmlTextReader::get_LocalName() metod


Returnerar det lokala namnet på den aktuella noden.

```cpp
String System::Xml::XmlTextReader::get_LocalName() override
```


### Returvärde

Namnet på den aktuella noden utan prefixet. Till exempel är **LocalName** **book** för elementet **<bk:book>**. För nodtyper som inte har ett namn (som **[Text](../../../system.text/)**, **Comment**, och så vidare) returnerar den här metoden [String::Empty](../../../system/string/empty/).

## Se också

* Klass [String](../../../system/string/)
* Klass [XmlTextReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)