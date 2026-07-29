---
title: ReadContentAsBinHex()
second_title: Aspose.Slides för C++ API-referens
description: Läser innehållet och returnerar de BinHex-avkodade binära bytena.
type: docs
weight: 599
url: /sv/system.xml/xmlvalidatingreader/readcontentasbinhex/
---
## XmlValidatingReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) method

Läser innehållet och returnerar de BinHex-avkodade binära byten.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bufferten som texten ska kopieras till. Detta värde kan inte vara **nullptr**. |
| index | **int32_t** | Förskjutningen i bufferten där resultatet ska börja kopieras. |
| count | **int32_t** | Det maximala antalet byte att kopiera till bufferten. Det faktiska antalet kopierade byte returneras från denna metod. |

### Returvärde

Antalet byte som skrivits till bufferten.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [XmlValidatingReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)