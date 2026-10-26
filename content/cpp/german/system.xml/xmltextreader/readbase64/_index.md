---
title: ReadBase64()
second_title: Aspose.Slides für C++ API Referenz
description: Dekodiert Base64 und gibt die dekodierten binären Bytes zurück.
type: docs
weight: 768
url: /de/system.xml/xmltextreader/readbase64/
---
## XmlTextReader::ReadBase64(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) Methode

Dekodiert Base64 und gibt die dekodierten binären Bytes zurück.

```cpp
int32_t System::Xml::XmlTextReader::ReadBase64(const ArrayPtr<uint8_t> &array, int32_t offset, int32_t len)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Das Array von Zeichen, das als Puffer dient, in den die Textinhalte geschrieben werden. |
| offset | **int32_t** | Der nullbasierte Index im Array, der angibt, wo die Methode mit dem Schreiben in den Puffer beginnen kann. |
| len | **int32_t** | Die Anzahl der Bytes, die in den Puffer geschrieben werden sollen. |

### Rückgabewert

Die Anzahl der in den Puffer geschriebenen Bytes.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [XmlTextReader](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)