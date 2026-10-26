---
title: ReadContentAsBase64()
second_title: Aspose.Slides für C++ API-Referenz
description: Liest den Inhalt und gibt die Base64-dekodierten Binärbytes zurück.
type: docs
weight: 755
url: /de/system.xml/xmlreader/readcontentasbase64/
---
## XmlReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) Methode

Liest den Inhalt und gibt die Base64-dekodierten Binärbytes zurück.

```cpp
virtual int32_t System::Xml::XmlReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Der Puffer, in den der resultierende Text kopiert werden soll. Dieser Wert darf nicht **nullptr**. |
| index | **int32_t** | Der Offset im Puffer, an dem das Kopieren des Ergebnisses beginnen soll. |
| count | **int32_t** | Die maximale Anzahl an Bytes, die in den Puffer kopiert werden sollen. Die tatsächliche Anzahl kopierter Bytes wird von dieser Methode zurückgegeben. |

### Rückgabewert

Die Anzahl der in den Puffer geschriebenen Bytes.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [XmlReader](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)