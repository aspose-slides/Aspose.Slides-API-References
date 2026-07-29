---
title: Get()
second_title: Aspose.Slides för C++ API-referens
description: När den ersätts i en avledd klass, får den den atomiserade strängen som innehåller samma tecken som det angivna teckensegmentet i den givna arrayen.
type: docs
weight: 1
url: /sv/system.xml/xmlnametable/get/
---
## XmlNameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) metod

När den ersätts i en avledd klass, får den den atomiserade strängen som innehåller samma tecken som det angivna teckensegmentet i den givna arrayen.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Teckenarrayen som innehåller namnet att söka efter. |
| offset | **int32_t** | Det nollbaserade indexet i arrayen som specificerar det första tecknet i namnet. |
| length | **int32_t** | Antalet tecken i namnet. |

### Returvärde

Den atomiserade strängen eller **nullptr** om strängen ännu inte har atomiserats. Om **length** är noll, returneras [String::Empty](../../../system/string/empty/).

## XmlNameTable::Get(const String\&) metod

När den ersätts i en avledd klass, får den den atomiserade strängen som har samma värde som den angivna strängen.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const String &array)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | Namnet att söka efter. |

### Returvärde

Den atomiserade strängen eller **nullptr** om strängen ännu inte har atomiserats.

## Se också

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [String](../../../system/string/)
* Klass [XmlNameTable](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)