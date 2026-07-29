---
title: Font()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny instans av Font-klassen som representerar det angivna befintliga teckensnittet med den angivna teckensnittsstilen.
type: docs
weight: 1
url: /sv/system.drawing/font/font/
---
## Font::Font(const SharedPtr\<Font\>\&, FontStyle) konstruktor

Skapar en ny instans av [Font](../) klass som representerar det angivna befintliga teckensnittet med den angivna teckensnittsstilen.

```cpp
System::Drawing::Font::Font(const SharedPtr<Font> &prototype, FontStyle new_style)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prototype | const [SharedPtr](../../../system/sharedptr/)\<[Font](../)\>\& | Det befintliga teckensnittet att skapa det nya från |
| new_style | [FontStyle](../../fontstyle/) | En teckensnittsstil att tillämpa på det nya teckensnittet |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, FontStyle, GraphicsUnit, uint8_t, bool) konstruktor

Skapar en ny instans av [Font](../) klass.

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | Teckensnittsfamiljen för det nya teckensnittet |
| em_size | **float** | Em-storleken på det nya teckensnittet i de enheter som anges av **unit**-parametern |
| style | [FontStyle](../../fontstyle/) | Stilen för det nya teckensnittet |
| unit | [GraphicsUnit](../../graphicsunit/) | Måttenheterna för det nya teckensnittet |
| gdi_charset | **uint8_t** | Ett GDI-teckenuppsättning som ska användas för det nya teckensnittet |
| gdi_vertical_font | **bool** | True om det nya teckensnittet härstammar från ett vertikalt GDI-teckensnitt |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, GraphicsUnit) konstruktor

Skapar en ny instans av [Font](../) klass.

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | Teckensnittsfamiljen för det nya teckensnittet |
| em_size | **float** | Em-storleken på det nya teckensnittet i de enheter som anges av **unit**-parametern |
| unit | [GraphicsUnit](../../graphicsunit/) | Måttenheterna för det nya teckensnittet |

## Font::Font(const String\&, float, FontStyle, GraphicsUnit, uint8_t, bool) konstruktor

Skapar en ny instans av [Font](../) klass.

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | Namnet på det nya teckensnittets teckensnittsfamilj |
| em_size | **float** | Em-storleken på det nya teckensnittet i de enheter som anges av **unit**-parametern |
| style | [FontStyle](../../fontstyle/) | Stilen för det nya teckensnittet |
| unit | [GraphicsUnit](../../graphicsunit/) | Måttenheterna för det nya teckensnittet |
| gdi_charset | **uint8_t** | Ett GDI-teckenuppsättning som ska användas för det nya teckensnittet |
| gdi_vertical_font | **bool** | True om det nya teckensnittet härstammar från ett vertikalt GDI-teckensnitt |

## Font::Font(const String\&, float, GraphicsUnit) konstruktor

Skapar en ny instans av [Font](../) klass.

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | Namnet på det nya teckensnittets teckensnittsfamilj |
| em_size | **float** | Em-storleken på det nya teckensnittet i de enheter som anges av **unit**-parametern |
| unit | [GraphicsUnit](../../graphicsunit/) | Måttenheterna för det nya teckensnittet |

## Se även

* Enum [FontStyle](../../fontstyle/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Font](../)
* Klass [FontFamily](../../fontfamily/)
* Klass [String](../../../system/string/)
* Namnrymd [System::Drawing](../../)
* Library [Aspose.Slides](../../../)