---
title: ReadContentAsBase64()
second_title: Aspose.Slides für C++ API-Referenz
description: Liest den Inhalt und gibt die Base64-dekodierten Binärbytes zurück.
type: docs
weight: 573
url: /de/system.xml/xmlvalidatingreader/readcontentasbase64/
---
## XmlValidatingReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) Methode

Liest den Inhalt und gibt die Base64-dekodierten Binärbytes zurück.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Der Puffer, in den der resultierende Text kopiert wird. Dieser Wert darf nicht **nullptr** sein. |
| index | **int32_t** | Der Versatz im Puffer, ab dem das Kopieren des Ergebnisses beginnen soll. |
| count | **int32_t** | Die maximale Anzahl von Bytes, die in den Puffer kopiert werden sollen. Die tatsächlich kopierte Anzahl von Bytes wird von dieser Methode zurückgegeben. |

### Return Value

Die Anzahl der in den Puffer geschriebenen Bytes.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [XmlValidatingReader](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)