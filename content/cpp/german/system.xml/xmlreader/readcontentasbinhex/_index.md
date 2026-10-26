---
title: ReadContentAsBinHex()
second_title: Aspose.Slides für C++ API Referenz
description: Liest den Inhalt und gibt die BinHex dekodierten Binärbytes zurück.
type: docs
weight: 781
url: /de/system.xml/xmlreader/readcontentasbinhex/
---
## XmlReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) Methode

Liest den Inhalt und gibt die **BinHex** dekodierten Binärbytes zurück.

```cpp
virtual int32_t System::Xml::XmlReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Der Puffer, in den der resultierende Text kopiert werden soll. Dieser Wert darf nicht **nullptr** sein. |
| index | **int32_t** | Der Offset im Puffer, ab dem das Ergebnis kopiert werden soll. |
| count | **int32_t** | Die maximale Anzahl von Bytes, die in den Puffer kopiert werden sollen. Die tatsächliche Anzahl der kopierten Bytes wird von dieser Methode zurückgegeben. |

### Return Value

Die Anzahl der in den Puffer geschriebenen Bytes.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [XmlReader](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)