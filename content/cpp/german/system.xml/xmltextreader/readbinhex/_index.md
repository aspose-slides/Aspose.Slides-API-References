---
title: ReadBinHex()
second_title: Aspose.Slides für C++ API-Referenz
description: Dekodiert BinHex und gibt die dekodierten Binärbytes zurück.
type: docs
weight: 781
url: /de/system.xml/xmltextreader/readbinhex/
---
## XmlTextReader::ReadBinHex(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Dekodiert **BinHex** und gibt die dekodierten Binärbytes zurück.

```cpp
int32_t System::Xml::XmlTextReader::ReadBinHex(const ArrayPtr<uint8_t> &array, int32_t offset, int32_t len)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Das Byte-Array, das als Puffer dient, in den die dekodierten Binärbytes geschrieben werden. |
| offset | **int32_t** | Der nullbasierte Index im Array, der angibt, wo die Methode mit dem Schreiben in den Puffer beginnen kann. |
| len | **int32_t** | Die Anzahl der Bytes, die in den Puffer geschrieben werden sollen. |

### Return Value

Die Anzahl der in Ihren Puffer geschriebenen Bytes.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)