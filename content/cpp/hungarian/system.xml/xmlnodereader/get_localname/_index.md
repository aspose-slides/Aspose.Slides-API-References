---
title: get_LocalName()
second_title: Aspose.Slides C++ API-referencia
description: Visszaadja az aktuális csomópont helyi nevét.
type: docs
weight: 27
url: /hu/system.xml/xmlnodereader/get_localname/
---
## XmlNodeReader::get_LocalName() metódus


Visszaadja az aktuális csomópont helyi nevét.

```cpp
String System::Xml::XmlNodeReader::get_LocalName() override
```


### Visszatérési érték

Az aktuális csomópont neve, a prefix eltávolítva. Például a **LocalName** **book** a **<bk:book>** elem esetén. Olyan csomóponttípusoknál, amelyeknek nincs neve (például **[Text](../../../system.text/)**, **Comment**, stb.), ez a metódus [String::Empty](../../../system/string/empty/).

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlNodeReader](../)
* Névterület [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)