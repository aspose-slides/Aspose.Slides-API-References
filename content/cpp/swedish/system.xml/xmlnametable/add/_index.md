---
title: Add()
second_title: Aspose.Slides för C++ API-referens
description: När den åsidosätts i en avledd klass atomiserar den angivna strängen och lägger till den i XmlNameTable.
type: docs
weight: 14
url: /sv/system.xml/xmlnametable/add/
---
## XmlNameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) metod


När den åsidosätts i en avledd klass atomiserar den angivna strängen och lägger till den i [XmlNameTable](../).

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Teckenarrayen som innehåller namnet att lägga till. |
| offset | **int32_t** | Nollbaserat index i arrayen som anger det första tecknet i namnet. |
| length | **int32_t** | Antalet tecken i namnet. |

### Returvärde

Den nya atomiserade strängen eller den befintliga om den redan finns. Om längden är noll returneras [String::Empty](../../../system/string/empty/).

## XmlNameTable::Add(const String\&) metod


När den åsidosätts i en avledd klass atomiserar den angivna strängen och lägger till den i [XmlNameTable](../).

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const String &array)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | Namnet att lägga till. |

### Returvärde

Den nya atomiserade strängen eller den befintliga om den redan finns.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [String](../../../system/string/)
* Klass [XmlNameTable](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)