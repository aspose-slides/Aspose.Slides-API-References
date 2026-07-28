---
title: ReadAttributeValue()
second_title: Aspose.Slides for C++ API Referenciája
description: Feldolgozza az attribútum értékét egy vagy több Text, EntityReference vagy EndEntity csomópontba.
type: docs
weight: 560
url: /hu/system.xml/xmltextreader/readattributevalue/
---
## XmlTextReader::ReadAttributeValue() metódus


Feldolgozza az attribútum értékét egy vagy több **[Text](../../../system.text/)**, **EntityReference** vagy **EndEntity** csomópontba.

```cpp
bool System::Xml::XmlTextReader::ReadAttributeValue() override
```


### Visszatérési érték

**true** ha vannak visszaadható csomópontok. **false** ha az olvasó nincs attribútum csomóponton pozicionálva a kezdeti híváskor, vagy ha az összes attribútum értéket már olvasta. Egy üres attribútum, például **misc=\"\"**, **true**-t ad vissza egyetlen csomóponttal, amelynek értéke [String::Empty](../../../system/string/empty/).

## Lásd még

* Osztály [XmlTextReader](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)