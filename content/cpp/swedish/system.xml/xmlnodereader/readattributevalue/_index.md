---
title: ReadAttributeValue()
second_title: Aspose.Slides för C++ API-referens
description: Analyserar attributvärdet till en eller flera Text, EntityReference eller EndEntity noder.
type: docs
weight: 430
url: /sv/system.xml/xmlnodereader/readattributevalue/
---
## XmlNodeReader::ReadAttributeValue() metod

Analyserar attributvärdet till en eller flera **[Text](../../../system.text/)**, **EntityReference**, eller **EndEntity** noder.

```cpp
bool System::Xml::XmlNodeReader::ReadAttributeValue() override
```

### Returvärde

**true** om det finns noder att returnera. **false** om läsaren inte är placerad på ett attributnod när det första anropet görs eller om alla attributvärden har lästs. Ett tomt attribut, till exempel **misc=\"\"**, returnerar **true** med en enda nod med ett värde av [String::Empty](../../../system/string/empty/).

## Se även

* Klass [XmlNodeReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)