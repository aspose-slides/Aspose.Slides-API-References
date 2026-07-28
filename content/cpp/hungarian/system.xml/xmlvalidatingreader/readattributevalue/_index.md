---
title: ReadAttributeValue()
second_title: Aspose.Slides C++ API referenciája
description: Az attribútum értékét egy vagy több Text, EntityReference vagy EndEntity csomópontba dolgozza fel.
type: docs
weight: 508
url: /hu/system.xml/xmlvalidatingreader/readattributevalue/
---
## XmlValidatingReader::ReadAttributeValue() metódus


Feldolgozza az attribútum értékét egy vagy több **[Text](../../../system.text/)**, **EntityReference**, vagy **EndEntity** csomópontba.

```cpp
bool System::Xml::XmlValidatingReader::ReadAttributeValue() override
```


### Visszatérési érték

**true**, ha vannak visszaadandó csomópontok. **false**, ha az olvasó nincs egy attribútum csomóponton pozicionálva a kezdeti híváskor, vagy ha az összes attribútumérték le lett olvasva. Egy üres attribútum, például **misc=\"\"**, **true**-t ad vissza egyetlen csomóponttal, amelynek értéke [String::Empty](../../../system/string/empty/).

## Lásd még

* Osztály [XmlValidatingReader](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)