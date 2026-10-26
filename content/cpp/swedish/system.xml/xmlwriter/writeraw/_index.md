---
title: WriteRaw()
second_title: Aspose.Slides för C++ API-referens
description: När den åsidosätts i en härledd klass skriver den rå markup manuellt från en teckenbuffer.
type: docs
weight: 287
url: /sv/system.xml/xmlwriter/writeraw/
---
## XmlWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) metod

När den åsidosätts i en härledd klass skriver den rå markup manuellt från en teckenbuffer.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | Teckenarray som innehåller texten som ska skrivas. |
| index | **int32_t** | Positionen i bufferten som anger början på texten som ska skrivas. |
| count | **int32_t** | Antalet tecken som ska skrivas. |

## XmlWriter::WriteRaw(const String\&) metod

När den åsidosätts i en härledd klass skriver den rå markup manuellt från en sträng.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(const String &data)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | const [String](../../../system/string/)\& | [String](../../../system/string/) som innehåller texten som ska skrivas. |

## Se också

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [XmlWriter](../)
* Klass [String](../../../system/string/)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)