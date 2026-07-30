---
title: StringFormat()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vytvoří novou instanci třídy StringFormat.
type: docs
weight: 1
url: /cs/system.drawing/stringformat/stringformat/
---
## StringFormat::StringFormat() konstruktor

Vytvoří novou instanci třídy [StringFormat](../).

```cpp
System::Drawing::StringFormat::StringFormat()
```

## StringFormat::StringFormat(StringFormatFlags, int32_t) konstruktor

Vytvoří novou instanci třídy [StringFormat](../) se zadanými příznaky formátu a jazykem.

```cpp
System::Drawing::StringFormat::StringFormat(StringFormatFlags options, int32_t language=0)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [StringFormatFlags](../../stringformatflags/) | Bitová kombinace hodnoty výčtu StringFormatFlags, která určuje formát řetězce reprezentovaný vytvořeným objektem |
| language | **int32_t** | Jazyk textu |

## StringFormat::StringFormat(const SharedPtr\<StringFormat\>\&) konstruktor

Kopírovací konstruktor.

```cpp
System::Drawing::StringFormat::StringFormat(const SharedPtr<StringFormat> &format)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| format | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../)\>\& | Objekt [StringFormat](../), ze kterého se kopíruje |

## Viz také

* Výčet [StringFormatFlags](../../stringformatflags/)
* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [StringFormat](../)
* Jmenný prostor [System::Drawing](../../)
* Knihovna [Aspose.Slides](../../../)