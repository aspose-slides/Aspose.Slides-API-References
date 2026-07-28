---
title: get_LocalName()
second_title: Aspose.Slides for C++ API-referencia
description: Visszaadja az aktuális csomópont helyi nevét.
type: docs
weight: 27
url: /hu/system.xml/xmlvalidatingreader/get_localname/
---
## XmlValidatingReader::get_LocalName() metódus

Visszaadja az aktuális csomópont helyi nevét.

```cpp
String System::Xml::XmlValidatingReader::get_LocalName() override
```

### Visszatérési érték

Az aktuális csomópont neve, a prefix eltávolítva. Például a **LocalName** **book** a **<bk:book>** elem esetén. Az olyan csomóponttípusoknál, amelyeknek nincs neve (például **[Text](../../../system.text/)**, **Comment**, és így tovább), ez a metódus [String::Empty](../../../system/string/empty/).

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlValidatingReader](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)