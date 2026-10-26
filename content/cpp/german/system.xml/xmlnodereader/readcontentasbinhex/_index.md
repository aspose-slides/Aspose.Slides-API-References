---
title: ReadContentAsBinHex()
second_title: Aspose.Slides für C++ API-Referenz
description: Liest den Inhalt und gibt die BinHex-decodierten Binärbytes zurück.
type: docs
weight: 456
url: /de/system.xml/xmlnodereader/readcontentasbinhex/
---
## XmlNodeReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) Methode

Liest den Inhalt und gibt die BinHex-decodierten Binärbytes zurück.

```cpp
int32_t System::Xml::XmlNodeReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Der Puffer, in den der resultierende Text kopiert wird. Dieser Wert darf nicht **nullptr** sein. |
| index | **int32_t** | Der Versatz im Puffer, an dem das Kopieren des Ergebnisses beginnen soll. |
| count | **int32_t** | Die maximale Anzahl von Bytes, die in den Puffer kopiert werden sollen. Die tatsächlich kopierte Anzahl von Bytes wird von dieser Methode zurückgegeben. |

### Rückgabewert

Die Anzahl der Bytes, die in den Puffer geschrieben wurden.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [XmlNodeReader](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)