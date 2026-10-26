---
title: ReadAttributeValue()
second_title: Aspose.Slides för C++ API-referens
description: När den åsidosätts i en avledd klass parsar den attributvärdet till en eller flera Text, EntityReference eller EndEntity noder.
type: docs
weight: 677
url: /sv/system.xml/xmlreader/readattributevalue/
---
## XmlReader::ReadAttributeValue() metod


När den åsidosätts i en avledd klass, parsar attributvärdet till en eller flera **[Text](../../../system.text/)**, **EntityReference**, eller **EndEntity** noder.

```cpp
virtual bool System::Xml::XmlReader::ReadAttributeValue()=0
```


### Returvärde

**true** om det finns noder att returnera. **false** om läsaren inte är placerad på en attributnod när det första anropet görs eller om alla attributvärden har lästs. Ett tomt attribut, till exempel **misc=\"\"**, returnerar **true** med en enda nod med ett värde på [String::Empty](../../../system/string/empty/).

## Se även

* Klass [XmlReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)