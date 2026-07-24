---
title: WriteRaw()
second_title: Aspose.Slides für C++ API-Referenz
description: Wenn sie in einer abgeleiteten Klasse überschrieben wird, schreibt sie Roh-Markup manuell aus einem Zeichenpuffer.
type: docs
weight: 287
url: /de/system.xml/xmlwriter/writeraw/
---
## XmlWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) Methode

Wenn sie in einer abgeleiteten Klasse überschrieben wird, schreibt sie Roh-Markup manuell aus einem Zeichenpuffer.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | Zeichenarray, das den zu schreibenden Text enthält. |
| index | **int32_t** | Die Position im Puffer, die den Anfang des zu schreibenden Textes angibt. |
| count | **int32_t** | Die Anzahl der zu schreibenden Zeichen. |

## XmlWriter::WriteRaw(const String\&) Methode

Wenn sie in einer abgeleiteten Klasse überschrieben wird, schreibt sie Roh-Markup manuell aus einer Zeichenkette.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(const String &data)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | const [String](../../../system/string/)\& | [String](../../../system/string/), das den zu schreibenden Text enthält. |

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [XmlWriter](../)
* Klasse [String](../../../system/string/)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)