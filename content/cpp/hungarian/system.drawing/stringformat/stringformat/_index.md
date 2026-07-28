---
title: StringFormat()
second_title: Aspose.Slides for C++ API Referencia
description: Új példányt hoz létre a StringFormat osztályból.
type: docs
weight: 1
url: /hu/system.drawing/stringformat/stringformat/
---
## StringFormat::StringFormat() konstruktor

Új példányt hoz létre a [StringFormat](../) osztályból.

```cpp
System::Drawing::StringFormat::StringFormat()
```

## StringFormat::StringFormat(StringFormatFlags, int32_t) konstruktor

Új példányt hoz létre a [StringFormat](../) osztályból a megadott formátumjelzőkkel és nyelvvel.

```cpp
System::Drawing::StringFormat::StringFormat(StringFormatFlags options, int32_t language=0)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [StringFormatFlags](../../stringformatflags/) | Bitenkénti kombinációja a StringFormatFlags enum értékének, amely meghatározza a létrehozandó objektum által képviselt karakterlánc formátumát |
| language | **int32_t** | A szöveg nyelve |

## StringFormat::StringFormat(const SharedPtr\<StringFormat\>\&) konstruktor

Másoló konstruktor.

```cpp
System::Drawing::StringFormat::StringFormat(const SharedPtr<StringFormat> &format)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| format | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../)\>\& | A [StringFormat](../) objektum, amelyből másolni kell |

## Lásd még

* Enumeráció [StringFormatFlags](../../stringformatflags/)
* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [StringFormat](../)
* Névtér [System::Drawing](../../)
* Könyvtár [Aspose.Slides](../../../)