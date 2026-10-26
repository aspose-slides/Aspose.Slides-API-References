---
title: ReadContentAsBase64()
second_title: Aspose.Slides för C++ API-referens
description: Läser innehållet och returnerar de Base64-dekodade binära byten.
type: docs
weight: 573
url: /sv/system.xml/xmlvalidatingreader/readcontentasbase64/
---
## XmlValidatingReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) metod

Läser innehållet och returnerar de Base64-dekodade binära byten.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bufferten som texten ska kopieras till. Detta värde får inte vara **nullptr**. |
| index | **int32_t** | Offseten i bufferten där kopieringen av resultatet ska börja. |
| count | **int32_t** | Det maximala antalet byte som ska kopieras till bufferten. Det faktiska antalet kopierade byte returneras av den här metoden. |

### Returvärde

Antalet byte som skrevs till bufferten.

## Se också

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [XmlValidatingReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)