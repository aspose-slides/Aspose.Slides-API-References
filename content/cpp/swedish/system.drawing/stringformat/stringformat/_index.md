---
title: StringFormat()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny instans av StringFormat-klass.
type: docs
weight: 1
url: /sv/system.drawing/stringformat/stringformat/
---
## StringFormat::StringFormat() konstruktor


Skapar en ny instans av [StringFormat](../) klass.

```cpp
System::Drawing::StringFormat::StringFormat()
```

## StringFormat::StringFormat(StringFormatFlags, int32_t) konstruktor


Skapar en ny instans av [StringFormat](../) klass med de angivna formatflaggorna och språket.

```cpp
System::Drawing::StringFormat::StringFormat(StringFormatFlags options, int32_t language=0)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [StringFormatFlags](../../stringformatflags/) | En bitvis kombination av StringFormatFlags enumvärde som specificerar strängformatet som ska representeras av det objekt som skapas |
| language | **int32_t** | Ett språk för texten |

## StringFormat::StringFormat(const SharedPtr\<StringFormat\>\&) konstruktor


Kopieringskonstruktor.

```cpp
System::Drawing::StringFormat::StringFormat(const SharedPtr<StringFormat> &format)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| format | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../)\>\& | Ett [StringFormat](../)-objekt att kopiera från |

## Se även

* Enum [StringFormatFlags](../../stringformatflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [StringFormat](../)
* Namnutrymme [System::Drawing](../../)
* Bibliotek [Aspose.Slides](../../../)