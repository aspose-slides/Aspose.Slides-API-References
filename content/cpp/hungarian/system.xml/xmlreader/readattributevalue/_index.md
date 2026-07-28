---
title: ReadAttributeValue()
second_title: Aspose.Slides a C++ API hivatkozás
description: Ha egy származtatott osztályban felül van írva, akkor elemzi az attribútumértéket egy vagy több Text, EntityReference vagy EndEntity csomóponttá.
type: docs
weight: 677
url: /hu/system.xml/xmlreader/readattributevalue/
---
## XmlReader::ReadAttributeValue() metódus

Amikor egy származtatott osztályban felülírják, elemzi az attribútumértéket, és egy vagy több **[Text](../../../system.text/)**, **EntityReference**, vagy **EndEntity** csomóponttá alakítja.

```cpp
virtual bool System::Xml::XmlReader::ReadAttributeValue()=0
```

### Visszatérési érték

**true** ha vannak visszaadandó csomópontok. **false** ha a reader nincs egy attribútum csomóponton pozicionálva, amikor az első hívás megtörténik, vagy ha az összes attribútumérték be lett olvasva. Egy üres attribútum, például **misc=\"\"**, **true**-t ad vissza egyetlen csomóponttal, amelynek értéke [String::Empty](../../../system/string/empty/).

## Lásd még

* Osztály [XmlReader](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)