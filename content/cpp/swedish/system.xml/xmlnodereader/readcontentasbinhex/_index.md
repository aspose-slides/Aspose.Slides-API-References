---
title: ReadContentAsBinHex()
second_title: Aspose.Slides för C++ API-referens
description: Läser innehållet och returnerar de BinHex-avkodade binära bytena.
type: docs
weight: 456
url: /sv/system.xml/xmlnodereader/readcontentasbinhex/
---
## XmlNodeReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) metod


Läser innehållet och returnerar de BinHex-avkodade binära byten.

```cpp
int32_t System::Xml::XmlNodeReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Den buffer som resultattexten ska kopieras till. Detta värde kan inte vara **nullptr**. |
| index | **int32_t** | Förskjutningen i bufferten där kopieringen av resultatet ska börja. |
| count | **int32_t** | Det maximala antalet byte som ska kopieras till bufferten. Det faktiska antalet byte som kopierades returneras från denna metod. |

### Returvärde

Antalet byte som skrevs till bufferten.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [XmlNodeReader](../)
* Namnrymd [System::Xml](../../)
* Library [Aspose.Slides](../../../)