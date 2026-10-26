---
title: ReadElementContentAsBase64()
second_title: Aspose.Slides för C++ API-referens
description: Läser elementet och avkodar Base64-innehållet.
type: docs
weight: 768
url: /sv/system.xml/xmlreader/readelementcontentasbase64/
---
## XmlReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) metod

Läser elementet och avkodar **Base64**-innehållet.

```cpp
virtual int32_t System::Xml::XmlReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bufferten att kopiera den resulterande texten till. Detta värde kan inte vara **nullptr**. |
| index | **int32_t** | Offsetet i bufferten där kopieringen av resultatet ska påbörjas. |
| count | **int32_t** | Det maximala antalet byte att kopiera till bufferten. Det faktiska antalet kopierade byte returneras av den här metoden. |

### Returvärde

Antalet byte som skrivits till bufferten.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [XmlReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)