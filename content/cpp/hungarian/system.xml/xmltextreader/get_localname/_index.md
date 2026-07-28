---
title: get_LocalName()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja az aktuális csomópont helyi nevét.
type: docs
weight: 27
url: /hu/system.xml/xmltextreader/get_localname/
---
## XmlTextReader::get_LocalName() metódus


Visszaadja az aktuális csomópont helyi nevét.

```cpp
String System::Xml::XmlTextReader::get_LocalName() override
```


### Visszatérési érték

A prefix eltávolításával kapott aktuális csomópont neve. Például a **LocalName** **book** a **<bk:book>** elem esetén. Olyan csomóponttípusoknál, amelyeknek nincs neve (például **[Text](../../../system.text/)**, **Comment**, stb.), ez a metódus visszaadja [String::Empty](../../../system/string/empty/).

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlTextReader](../)
* Névterület [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)