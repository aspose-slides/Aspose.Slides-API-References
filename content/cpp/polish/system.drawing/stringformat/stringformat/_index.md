---
title: StringFormat()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Tworzy nową instancję klasy StringFormat.
type: docs
weight: 1
url: /pl/system.drawing/stringformat/stringformat/
---
## StringFormat::StringFormat() konstruktor

Tworzy nową instancję klasy [StringFormat](../).

```cpp
System::Drawing::StringFormat::StringFormat()
```

## StringFormat::StringFormat(StringFormatFlags, int32_t) konstruktor

Tworzy nową instancję klasy [StringFormat](../) z określonymi flagami formatu i językiem.

```cpp
System::Drawing::StringFormat::StringFormat(StringFormatFlags options, int32_t language=0)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [StringFormatFlags](../../stringformatflags/) | Bitowa kombinacja wartości wyliczenia StringFormatFlags określająca format łańcucha reprezentowanego przez tworzone obiekty |
| language | **int32_t** | Język tekstu |

## StringFormat::StringFormat(const SharedPtr\<StringFormat\>\&) konstruktor

Konstruktor kopiujący.

```cpp
System::Drawing::StringFormat::StringFormat(const SharedPtr<StringFormat> &format)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| format | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../)\>\& | Obiekt [StringFormat](../) do skopiowania |

## Zobacz także

* Enum [StringFormatFlags](../../stringformatflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [StringFormat](../)
* Przestrzeń nazw [System::Drawing](../../)
* Biblioteka [Aspose.Slides](../../../)