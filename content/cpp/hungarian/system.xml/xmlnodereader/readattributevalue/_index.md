---
title: ReadAttributeValue()
second_title: Aspose.Slides C++ API hivatkozás
description: Feldolgozza az attribútumértéket egy vagy több Text, EntityReference vagy EndEntity csomópontba.
type: docs
weight: 430
url: /hu/system.xml/xmlnodereader/readattributevalue/
---
## XmlNodeReader::ReadAttributeValue() metódus

Feldolgozza az attribútumértéket egy vagy több **[Text](../../../system.text/)**, **EntityReference** vagy **EndEntity** csomóponttá.

```cpp
bool System::Xml::XmlNodeReader::ReadAttributeValue() override
```

### Visszatérési érték

**true** ha vannak visszaadható csomópontok. **false** ha az olvasó nem egy attribútum csomóponton van pozicionálva a kezdeti híváskor, vagy ha az összes attribútumérték már be lett olvasva. Egy üres attribútum, például **misc=\"\"**, **true**-t ad vissza egyetlen csomóponttal, amelynek értéke [String::Empty](../../../system/string/empty/).

## Lásd még

* Osztály [XmlNodeReader](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)