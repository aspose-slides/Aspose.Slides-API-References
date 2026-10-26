---
title: Font()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された既存フォントと指定されたフォントスタイルを表す Font クラスの新しいインスタンスを作成します。
type: docs
weight: 1
url: /ja/system.drawing/font/font/
---
## Font::Font(const SharedPtr\<Font\>\&, FontStyle) コンストラクタ


指定された既存フォントと指定されたフォントスタイルを表す [Font](../) クラスの新しいインスタンスを作成します。

```cpp
System::Drawing::Font::Font(const SharedPtr<Font> &prototype, FontStyle new_style)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| prototype | const [SharedPtr](../../../system/sharedptr/)\<[Font](../)\>\& | The existing font to create the new one from |
| new_style | [FontStyle](../../fontstyle/) | A font style to apply to the new font |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, FontStyle, GraphicsUnit, uint8_t, bool) コンストラクタ


[Font](../) クラスの新しいインスタンスを作成します。

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | The font family of the new font |
| em_size | **float** | The em size of the new font in the units specified by **unit** parameter |
| style | [FontStyle](../../fontstyle/) | The style of the new font |
| unit | [GraphicsUnit](../../graphicsunit/) | The measurement units of the new font |
| gdi_charset | **uint8_t** | A GDI charset to be used for the new font |
| gdi_vertical_font | **bool** | True if the new font is derived from a GDI vertical font |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, GraphicsUnit) コンストラクタ


[Font](../) クラスの新しいインスタンスを作成します。

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | The font family of the new font |
| em_size | **float** | The em size of the new font in the units specified by **unit** parameter |
| unit | [GraphicsUnit](../../graphicsunit/) | The measurement units of the new font |

## Font::Font(const String\&, float, FontStyle, GraphicsUnit, uint8_t, bool) コンストラクタ


[Font](../) クラスの新しいインスタンスを作成します。

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | The name of the new font's font family |
| em_size | **float** | The em size of the new font in the units specified by **unit** parameter |
| style | [FontStyle](../../fontstyle/) | The style of the new font |
| unit | [GraphicsUnit](../../graphicsunit/) | The measurement units of the new font |
| gdi_charset | **uint8_t** | A GDI charset to be used for the new font |
| gdi_vertical_font | **bool** | True if the new font is derived from a GDI vertical font |

## Font::Font(const String\&, float, GraphicsUnit) コンストラクタ


[Font](../) クラスの新しいインスタンスを作成します。

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | The name of the new font's font family |
| em_size | **float** | The em size of the new font in the units specified by **unit** parameter |
| unit | [GraphicsUnit](../../graphicsunit/) | The measurement units of the new font |

## 参照

* Enum [FontStyle](../../fontstyle/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [Font](../)
* クラス [FontFamily](../../fontfamily/)
* クラス [String](../../../system/string/)
* 名前空間 [System::Drawing](../../)
* Library [Aspose.Slides](../../../)