---
title: ReadContentAsBase64()
second_title: Aspose.Slides för C++ API-referens
description: Läser innehållet och returnerar de Base64-avkodade binära bytena.
type: docs
weight: 443
url: /sv/system.xml/xmlnodereader/readcontentasbase64/
---
## XmlNodeReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) method


Läser innehållet och returnerar de Base64-avkodade binära byten.

```cpp
int32_t System::Xml::XmlNodeReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bufferten som texten ska kopieras till. Detta värde kan inte vara **nullptr**. |
| index | **int32_t** | Förskjutningen i bufferten där kopieringen av resultatet ska börja. |
| count | **int32_t** | Det maximala antalet byte som ska kopieras till bufferten. Det faktiska antalet kopierade byte returneras av den här metoden. |

### Returnvärde

Antalet byte som skrevs till bufferten.

## Se också

* Typdefinition [ArrayPtr](../../../system/arrayptr/)
* Klass [XmlNodeReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)