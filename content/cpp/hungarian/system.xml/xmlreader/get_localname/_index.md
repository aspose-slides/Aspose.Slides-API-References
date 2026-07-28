---
title: get_LocalName()
second_title: Aspose.Slides C++ API Referencia
description: Ha egy leszármaztatott osztályban felül van írva, visszaadja az aktuális csomópont helyi nevét.
type: docs
weight: 40
url: /hu/system.xml/xmlreader/get_localname/
---
## XmlReader::get_LocalName() metódus


Ha egy leszármaztatott osztályban felül van írva, visszaadja az aktuális csomópont helyi nevét.

```cpp
virtual String System::Xml::XmlReader::get_LocalName()=0
```


### Visszatérési érték

Az aktuális csomópont neve a prefix eltávolítása után. Például a **LocalName** **book** lesz a **<bk:book>** elemhez. Az olyan csomóponttípusoknál, amelyeknek nincs neve (például **[Text](../../../system.text/)**, **Comment**, és így tovább), ez a metódus [String::Empty](../../../system/string/empty/) értéket ad vissza.

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlReader](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)