---
title: Font()
second_title: Aspose.Slides for C++ API 參考文件
description: 建構一個新的 Font 類別實例，該實例代表具有指定字體樣式的指定現有字體。
type: docs
weight: 1
url: /zh-hant/system.drawing/font/font/
---
## Font::Font(const SharedPtr\<Font\>\&, FontStyle) 建構子

建構一個新的 [Font](../) 類別實例，該實例代表指定的現有字體，並套用指定的字體樣式。

```cpp
System::Drawing::Font::Font(const SharedPtr<Font> &prototype, FontStyle new_style)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| prototype | const [SharedPtr](../../../system/sharedptr/)\<[Font](../)\>\& | The existing font to create the new one from |
| new_style | [FontStyle](../../fontstyle/) | A font style to apply to the new font |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, FontStyle, GraphicsUnit, uint8_t, bool) 建構子

建構一個新的 [Font](../) 類別實例。

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | The font family of the new font |
| em_size | **float** | The em size of the new font in the units specified by **unit** parameter |
| style | [FontStyle](../../fontstyle/) | The style of the new font |
| unit | [GraphicsUnit](../../graphicsunit/) | The measurement units of the new font |
| gdi_charset | **uint8_t** | A GDI charset to be used for the new font |
| gdi_vertical_font | **bool** | True if the new font is derived from a GDI vertical font |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, GraphicsUnit) 建構子

建構一個新的 [Font](../) 類別實例。

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | The font family of the new font |
| em_size | **float** | The em size of the new font in the units specified by **unit** parameter |
| unit | [GraphicsUnit](../../graphicsunit/) | The measurement units of the new font |

## Font::Font(const String\&, float, FontStyle, GraphicsUnit, uint8_t, bool) 建構子

建構一個新的 [Font](../) 類別實例。

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | The name of the new font's font family |
| em_size | **float** | The em size of the new font in the units specified by **unit** parameter |
| style | [FontStyle](../../fontstyle/) | The style of the new font |
| unit | [GraphicsUnit](../../graphicsunit/) | The measurement units of the new font |
| gdi_charset | **uint8_t** | A GDI charset to be used for the new font |
| gdi_vertical_font | **bool** | True if the new font is derived from a GDI vertical font |

## Font::Font(const String\&, float, GraphicsUnit) 建構子

建構一個新的 [Font](../) 類別實例。

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | The name of the new font's font family |
| em_size | **float** | The em size of the new font in the units specified by **unit** parameter |
| unit | [GraphicsUnit](../../graphicsunit/) | The measurement units of the new font |

## 另請參閱

* Enum [FontStyle](../../fontstyle/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../)
* Class [FontFamily](../../fontfamily/)
* Class [String](../../../system/string/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)