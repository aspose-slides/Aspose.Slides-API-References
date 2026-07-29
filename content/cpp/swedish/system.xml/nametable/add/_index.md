---
title: Add()
second_title: Aspose.Slides för C++ API-referens
description: Atomiserar den angivna strängen och lägger till den i NameTable.
type: docs
weight: 14
url: /sv/system.xml/nametable/add/
---
## NameTable::Add(const String\&) metod

Atomiserar den angivna strängen och lägger till den i [NameTable](../).

```cpp
const String & System::Xml::NameTable::Add(const String &key) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| key | const [String](../../../system/string/)\& | Strängen att lägga till. |

### Returvärde

Den atomiserade strängen eller den befintliga strängen om den redan finns i [NameTable](../).

## NameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) metod

Atomiserar den angivna strängen och lägger till den i [NameTable](../).

```cpp
const String & System::Xml::NameTable::Add(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Teckenarrayen som innehåller strängen som ska läggas till. |
| start | **int32_t** | Det nollbaserade indexet i arrayen som anger det första tecknet i strängen. |
| len | **int32_t** | Antalet tecken i strängen. |

### Returvärde

Den atomiserade strängen eller den befintliga strängen om den redan finns i [NameTable](../). Om **len** är noll, returneras [String::Empty](../../../system/string/empty/).

## Se också

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [String](../../../system/string/)
* Klass [NameTable](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)