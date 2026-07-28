---
title: PixelFormat
second_title: Aspose.Slides C++ API referenciája
description: Megadja egy pixel színadat-formátumát.
type: docs
weight: 326
url: /hu/system.drawing.imaging/pixelformat/
---
## PixelFormat enum


Megadja egy pixel színadat-formátumát.

```cpp
enum class PixelFormat
```

### Értékek

| Név | Érték | Leírás |
| --- | --- | --- |
| Indexed | 65536 | Azt adja meg, hogy a pixel adat tartalmaz színindexált értékeket, ami azt jelenti, hogy ezek a rendszer szín táblázatának színeire mutató indexek. |
| Gdi | 131072 | Azt adja meg, hogy a pixel adat GDI színeket tartalmaz. |
| Alpha | 262144 | Azt adja meg, hogy a pixel adat alfa értékeket tartalmaz, amelyek nincsenek előre szorzva. |
| PAlpha | 524288 | Azt adja meg, hogy a pixel adat előre szorzott alfa értékeket tartalmaz. |
| Extended | 1048576 | Fenntartott. |
| Canonical | 2097152 | Azt adja meg, hogy a pixel formátum 32 bit pixelként, 24 bites színmélységgel és 8 bites alfa csatornával rendelkezik. |
| Undefined | 0 | Azt adja meg, hogy a pixel formátum nincs definiálva. |
| DontCare | 0 | A pixel formátum nincs megadva. |
| Format1bppIndexed | n/a | Azt adja meg, hogy a pixel formátum 1 bites pixelenként indexelt szín. |
| Format4bppIndexed | n/a | Azt adja meg, hogy a pixel formátum 4 bites pixelenként indexelt szín. |
| Format8bppIndexed | n/a | Azt adja meg, hogy a pixel formátum 8 bites pixelenként indexelt szín. |
| Format16bppGrayScale | n/a | Azt adja meg, hogy a pixel formátum 16 bit pixelként. A színinformáció 65536 szürkeárnyalatot határoz meg. |
| Format16bppRgb555 | n/a | Azt adja meg, hogy a pixel formátum 16 bit pixelként, 5 bittel minden vörös, zöld és kék komponenshez, a maradék bit nincs használva. |
| Format16bppRgb565 | n/a | Azt adja meg, hogy a pixel formátum 16 bit pixelként, 5 bittel a vörös, 6 bittel a zöld és 5 bittel a kék komponenshez. |
| Format16bppArgb1555 | n/a | Azt adja meg, hogy a pixel formátum 16 bit pixelként, 5 bittel minden vörös, zöld és kék komponenshez, valamint 1 bittel az alfa számára. |
| Format24bppRgb | n/a | Azt adja meg, hogy a pixel formátum 24 bit pixelként, 8 bittel minden vörös, zöld és kék komponenshez. |
| Format32bppRgb | n/a | Azt adja meg, hogy a pixel formátum 32 bit pixelként, 8 bittel minden vörös, zöld és kék komponenshez, a maradék 8 bit nincs használva. |
| Format32bppArgb | n/a | Azt adja meg, hogy a pixel formátum 32 bit pixelként, 8 bittel minden vörös, zöld és kék komponenshez, valamint 8 bittel az alfa számára. |
| Format32bppPArgb | n/a | Azt adja meg, hogy a pixel formátum 32 bit pixelként, 8 bittel minden vörös, zöld és kék komponenshez, valamint 8 bittel az alfa számára. A vörös, zöld és kék komponensek előre szorzottak az alfa komponens értékének megfelelően. |
| Format48bppRgb | n/a | Azt adja meg, hogy a pixel formátum 48 bit pixelként, 16 bittel minden vörös, zöld és kék komponenshez. |
| Format64bppArgb | n/a | Azt adja meg, hogy a pixel formátum 64 bit pixelként, 16 bittel minden vörös, zöld és kék komponenshez, valamint 16 bittel az alfa számára. |
| Format64bppPArgb | n/a | Azt adja meg, hogy a pixel formátum 64 bit pixelként, 16 bittel minden vörös, zöld és kék komponenshez, valamint 16 bittel az alfa számára. A vörös, zöld és kék komponensek előre szorzottak az alfa komponens értékének megfelelően. |
| Format32bppCMYK | n/a | Azt adja meg, hogy a pixel formátum 32 bit pixelként, 8 bittel minden cián, magenta, sárga és fekete (key) komponenshez. |
| Max | 16 | Az enum maximális értéke. |

## Lásd még

* Névterület [System::Drawing::Imaging](../)
* Könyvtár [Aspose.Slides](../../)