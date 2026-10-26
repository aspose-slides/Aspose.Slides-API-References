---
title: WriteRaw()
second_title: Aspose.Slides für C++ API-Referenz
description: Schreibt das rohe Markup manuell aus einem Zeichenpuffer.
type: docs
weight: 417
url: /de/system.xml/xmltextwriter/writeraw/
---
## XmlTextWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) method

Schreibt das rohe Markup manuell aus einem Zeichenpuffer.

```cpp
void System::Xml::XmlTextWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | Zeichen-Array, das den zu schreibenden Text enthält. |
| index | **int32_t** | Die Position im Puffer, die den Beginn des zu schreibenden Textes angibt. |
| count | **int32_t** | Die Anzahl der zu schreibenden Zeichen. |

## XmlTextWriter::WriteRaw(const String\&) method

Schreibt das rohe Markup manuell aus einer Zeichenkette.

```cpp
void System::Xml::XmlTextWriter::WriteRaw(const String &data) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | const [String](../../../system/string/)\& | [String](../../../system/string/) die den zu schreibenden Text enthält. |

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlTextWriter](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)