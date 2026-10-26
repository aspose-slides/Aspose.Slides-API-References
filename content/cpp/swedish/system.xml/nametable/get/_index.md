---
title: Get()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar den atomiserade strängen med det angivna värdet.
type: docs
weight: 27
url: /sv/system.xml/nametable/get/
---
## NameTable::Get(const String\&) metod


Returnerar den atomiserade strängen med det angivna värdet.

```cpp
const String & System::Xml::NameTable::Get(const String &value) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Namnet att hitta. |

### Returvärde

Den atomiserade strängobjektet eller **nullptr** om strängen ännu inte har atomiserats.

## NameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) metod


Returnerar den atomiserade strängen som innehåller samma tecken som det angivna teckensegmentet i den givna arrayen.

```cpp
const String & System::Xml::NameTable::Get(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Teckenarrayen som innehåller namnet att hitta. |
| start | **int32_t** | Det nollbaserade indexet i arrayen som anger det första tecknet i namnet. |
| len | **int32_t** | Antalet tecken i namnet. |

### Returvärde

Den atomiserade strängen eller **nullptr** om strängen ännu inte har atomiserats. Om **len** är noll, returneras [String::Empty](../../../system/string/empty/).

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [String](../../../system/string/)
* Klass [NameTable](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)