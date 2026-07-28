---
title: ColorTransformOperation
second_title: Aspose.Slides C++ API referenciája
description: Meghatározza a színátalakítási műveletet.
type: docs
weight: 5747
url: /hu/aspose.slides/colortransformoperation/
---
## ColorTransformOperation enum

Meghatározza a színátalakítási műveletet.

```cpp
enum class ColorTransformOperation
```

### Értékek

| Név | Érték | Leírás |
| --- | --- | --- |
| Tint | 0 | A színt tónusozza. A paraméter értéke 0 (eredeti szín) és 1 (fehér) között van. |
| Shade | 1 | A színt árnyalja. A paraméter értéke 0 (eredeti szín) és 1 (fekete) között van. |
| Complement | 2 | A színt egy RGB komplementer színre változtatja. m = Max(r, g, b); r = m - r; g = m - g; b = m - b; |
| Inverse | 3 | A színt invertált színre változtatja. r = 1 - r; g = 1 - g; b = 1 - b; |
| Grayscale | 4 | A színt egy szürke színre változtatja azonos fényességgel. A paramétert figyelmen kívül hagyja. |
| SetAlpha | 5 | Meghatározza a szín alfa komponensét. A paraméter értéke 0 (átlátszó) és 1 (átlátszatlan) között van. |
| AddAlpha | 6 | Hozzáadja a paraméter értékét a szín alfa komponenséhez. A paraméter értéke -1 és 1 között van. |
| MultiplyAlpha | 7 | Szorzásra kerül az alfa komponens a paraméter értékével. |
| SetHue | 8 | A szín hue komponensét a paraméter értékére állítja. A paraméter 0 és 360 között van. |
| AddHue | 9 | Hozzáadja a paraméter értékét a szín hue komponenséhez. A paraméter -360 és 360 között van. |
| MultiplyHue | 10 | Szorzásra kerül a hue komponens a paraméter értékével. |
| SetSaturation | 11 | A szaturáció komponensét a paraméter értékére állítja. A paraméter 0 és 1 között van. |
| AddSaturation | 12 | Hozzáadja a paraméter értékét a szaturáció komponenshez. A paraméter -1 és 1 között van. |
| MultiplySaturation | 13 | Szorzásra kerül a szaturáció komponens a paraméter értékével. |
| SetLuminance | 14 | A luminancia komponensét a paraméter értékére állítja. A paraméter 0 és 1 között van. |
| AddLuminance | 15 | Hozzáadja a paraméter értékét a luminancia komponenshez. A paraméter -1 és 1 között van. |
| MultiplyLuminance | 16 | Szorzásra kerül a luminancia komponens a paraméter értékével. |
| SetRed | 17 | A piros komponensét a paraméter értékére állítja. A paraméter 0 és 1 között van. |
| AddRed | 18 | Hozzáadja a paraméter értékét a piros komponenshez. A paraméter -1 és 1 között van. |
| MultiplyRed | 19 | Szorzásra kerül a piros komponens a paraméterrel. |
| SetGreen | 20 | A zöld komponensét a paraméter értékére állítja. A paraméter 0 és 1 között van. |
| AddGreen | 21 | Hozzáadja a paramétert a zöld komponenshez. A paraméter -1 és 1 között van. |
| MultiplyGreen | 22 | Szorzásra kerül a zöld komponens a paraméter értékével. |
| SetBlue | 23 | A kék komponensét a paraméter értékére állítja. A paraméter 0 és 360 között van. |
| AddBlue | 24 | Hozzáadja a paraméter értékét a kék komponenshez. A paraméter -1 és 1 között van. |
| MultiplyBlue | 25 | Szorzásra kerül a kék komponens a paraméter értékével. |
| Gamma | 26 | Gamma korrekció. A paramétert figyelmen kívül hagyja. |
| InverseGamma | 27 | Invertált gamma korrekció. A paramétert figyelmen kívül hagyja. |

## Lásd még

* Névtér [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)