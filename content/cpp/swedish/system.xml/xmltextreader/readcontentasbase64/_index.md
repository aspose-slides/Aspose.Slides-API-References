---
title: ReadContentAsBase64()
second_title: Aspose.Slides för C++ API-referens
description: Läser innehållet och returnerar de Base64-avkodade binära byten.
type: docs
weight: 638
url: /sv/system.xml/xmltextreader/readcontentasbase64/
---
## XmlTextReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) metod


Läser innehållet och returnerar de **Base64** avkodade binära byten.

```cpp
int32_t System::Xml::XmlTextReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bufferten som den resulterande texten ska kopieras till. Detta värde kan inte vara **nullptr**. |
| index | **int32_t** | Offseten i bufferten där kopieringen av resultatet ska börja. |
| count | **int32_t** | Det maximala antalet byte som får kopieras till bufferten. Det faktiska antalet kopierade byte returneras av denna metod. |

### Returvärde

Antalet byte som skrivits till bufferten.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [XmlTextReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)