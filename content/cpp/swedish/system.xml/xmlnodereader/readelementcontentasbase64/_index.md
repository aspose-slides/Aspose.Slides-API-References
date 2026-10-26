---
title: ReadElementContentAsBase64()
second_title: Aspose.Slides för C++ API-referens
description: Läser elementet och avkodar Base64-innehållet.
type: docs
weight: 469
url: /sv/system.xml/xmlnodereader/readelementcontentasbase64/
---
## XmlNodeReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) metod

Läser elementet och avkodar Base64-innehållet.

```cpp
int32_t System::Xml::XmlNodeReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Den buffert som resultattexten ska kopieras till. Detta värde får inte vara **nullptr**. |
| index | **int32_t** | Offseten i bufferten där kopieringen av resultatet ska börja. |
| count | **int32_t** | Det maximala antalet byte som ska kopieras till bufferten. Det faktiska antalet byte som kopierades returneras av denna metod. |

### Return Value

Antalet byte som skrevs till bufferten.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [XmlNodeReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)