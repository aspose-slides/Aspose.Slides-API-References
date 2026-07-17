---
title: Font()
second_title: Aspose.Slides for C++ API 参考
description: 构造一个新的 Font 类实例，该实例表示具有指定字体样式的指定现有字体。
type: docs
weight: 1
url: /zh/system.drawing/font/font/
---
## Font::Font(const SharedPtr\<Font\>\&, FontStyle) 构造函数

构造一个新的 [Font](../) 类实例，该实例表示具有指定字体样式的指定现有字体。

```cpp
System::Drawing::Font::Font(const SharedPtr<Font> &prototype, FontStyle new_style)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| prototype | const [SharedPtr](../../../system/sharedptr/)\<[Font](../)\>\& | The existing font to create the new one from |
| new_style | [FontStyle](../../fontstyle/) | A font style to apply to the new font |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, FontStyle, GraphicsUnit, uint8_t, bool) 构造函数

构造一个新的 [Font](../) 类实例。

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | The font family of the new font |
| em_size | **float** | The em size of the new font in the units specified by **unit** parameter |
| style | [FontStyle](../../fontstyle/) | The style of the new font |
| unit | [GraphicsUnit](../../graphicsunit/) | The measurement units of the new font |
| gdi_charset | **uint8_t** | A GDI charset to be used for the new font |
| gdi_vertical_font | **bool** | True if the new font is derived from a GDI vertical font |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, GraphicsUnit) 构造函数

构造一个新的 [Font](../) 类实例。

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | The font family of the new font |
| em_size | **float** | The em size of the new font in the units specified by **unit** parameter |
| unit | [GraphicsUnit](../../graphicsunit/) | The measurement units of the new font |

## Font::Font(const String\&, float, FontStyle, GraphicsUnit, uint8_t, bool) 构造函数

构造一个新的 [Font](../) 类实例。

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | The name of the new font's font family |
| em_size | **float** | The em size of the new font in the units specified by **unit** parameter |
| style | [FontStyle](../../fontstyle/) | The style of the new font |
| unit | [GraphicsUnit](../../graphicsunit/) | The measurement units of the new font |
| gdi_charset | **uint8_t** | A GDI charset to be used for the new font |
| gdi_vertical_font | **bool** | True if the new font is derived from a GDI vertical font |

## Font::Font(const String\&, float, GraphicsUnit) 构造函数

构造一个新的 [Font](../) 类实例。

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | The name of the new font's font family |
| em_size | **float** | The em size of the new font in the units specified by **unit** parameter |
| unit | [GraphicsUnit](../../graphicsunit/) | The measurement units of the new font |

## 另见

* 枚举 [FontStyle](../../fontstyle/)
* 枚举 [GraphicsUnit](../../graphicsunit/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Font](../)
* 类 [FontFamily](../../fontfamily/)
* 类 [String](../../../system/string/)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)