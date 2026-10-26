---
title: ReadValueChunk()
second_title: Aspose.Slides för C++ API-referens
description: Läser stora textströmmar som är inbäddade i ett XML-dokument.
type: docs
weight: 807
url: /sv/system.xml/xmlreader/readvaluechunk/
---
## XmlReader::ReadValueChunk(ArrayPtr\<char16_t\>, int32_t, int32_t) metod


Läser stora textströmmar som är inbäddade i ett XML-dokument.

```cpp
virtual int32_t System::Xml::XmlReader::ReadValueChunk(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | Den array av tecken som fungerar som bufferten till vilken textinnehållet skrivs. Detta värde kan inte vara **nullptr**. |
| index | **int32_t** | Offseten i bufferten där [XmlReader](../) kan börja kopiera resultaten. |
| count | **int32_t** | Det maximala antalet tecken som ska kopieras till bufferten. Det faktiska antalet kopierade tecken returneras från den här metoden. |

### Returvärde

Antalet tecken som lästs in i bufferten. Värdet noll returneras när det inte finns mer textinnehåll.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [XmlReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)