---
title: ReadContentAsBinHex()
second_title: Aspose.Slides für C++ API Referenz
description: Liest den Inhalt und gibt die BinHex-dekodierten Binärbytes zurück.
type: docs
weight: 664
url: /de/system.xml/xmltextreader/readcontentasbinhex/
---
## XmlTextReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) Methode

Liest den Inhalt und gibt die **BinHex** dekodierten Binärbytes zurück.

```cpp
int32_t System::Xml::XmlTextReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Der Puffer, in den der resultierende Text kopiert wird. Dieser Wert darf nicht **nullptr** sein. |
| index | **int32_t** | Der Versatz im Puffer, an dem das Kopieren des Ergebnisses beginnt. |
| count | **int32_t** | Die maximale Anzahl an Bytes, die in den Puffer kopiert werden sollen. Die tatsächliche Anzahl der kopierten Bytes wird von dieser Methode zurückgegeben. |

### Rückgabewert

Die Anzahl der in den Puffer geschriebenen Bytes.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [XmlTextReader](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)