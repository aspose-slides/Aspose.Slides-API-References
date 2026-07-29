---
title: WriteRaw()
second_title: Aspose.Slides för C++ API-referens
description: Skriver rå markup manuellt från en teckenbuffert.
type: docs
weight: 417
url: /sv/system.xml/xmltextwriter/writeraw/
---
## XmlTextWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) method

Skriver rå markup manuellt från en teckenbuffert.

```cpp
void System::Xml::XmlTextWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | Teckenarray som innehåller texten som ska skrivas. |
| index | **int32_t** | Positionen i bufferten som anger början på texten som ska skrivas. |
| count | **int32_t** | Antalet tecken som ska skrivas. |

## XmlTextWriter::WriteRaw(const String\&) method

Skriver rå markup manuellt från en sträng.

```cpp
void System::Xml::XmlTextWriter::WriteRaw(const String &data) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | const [String](../../../system/string/)\& | [String](../../../system/string/) som innehåller texten som ska skrivas. |

## Se också

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [XmlTextWriter](../)
* Klass [String](../../../system/string/)
* Namnutrymme [System::Xml](../../)
* Library [Aspose.Slides](../../../)