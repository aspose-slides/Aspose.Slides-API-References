---
title: get_LocalName()
second_title: Aspose.Slides för C++ API-referens
description: När den överskuggas i en härledd klass hämtar den det lokala namnet på den aktuella noden.
type: docs
weight: 40
url: /sv/system.xml/xmlreader/get_localname/
---
## XmlReader::get_LocalName() metod

När den överskuggas i en härledd klass hämtar den det lokala namnet på den aktuella noden.

```cpp
virtual String System::Xml::XmlReader::get_LocalName()=0
```

### Returvärde

Namnet på den aktuella noden utan prefixet. Till exempel är **LocalName** **book** för elementet **<bk:book>**. För nodtyper som inte har ett namn (som **[Text](../../../system.text/)**, **Comment**, och så vidare) returnerar den här metoden [String::Empty](../../../system/string/empty/).

## Se även

* Klass [String](../../../system/string/)
* Klass [XmlReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)