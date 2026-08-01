---
title: ReadValueChunk()
second_title: Aspose.Slides voor C++ API-referentie
description: Leest grote tekststromen die in een XML-document zijn ingebed.
type: docs
weight: 807
url: /nl/system.xml/xmlreader/readvaluechunk/
---
## XmlReader::ReadValueChunk(ArrayPtr\<char16_t\>, int32_t, int32_t) method

Leest grote tekststromen die in een XML-document zijn ingebed.

```cpp
virtual int32_t System::Xml::XmlReader::ReadValueChunk(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | De array van tekens die dient als buffer waarin de tekstinhoud wordt geschreven. Deze waarde mag niet **nullptr** zijn. |
| index | **int32_t** | De offset binnen de buffer waar de [XmlReader](../) kan beginnen met het kopiëren van de resultaten. |
| count | **int32_t** | Het maximale aantal tekens dat naar de buffer moet worden gekopieerd. Het werkelijke aantal gekopieerde tekens wordt geretourneerd door deze methode. |

### Retourwaarde

Het aantal tekens dat in de buffer is gelezen. De waarde nul wordt geretourneerd wanneer er geen tekstinhoud meer is.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [XmlReader](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)