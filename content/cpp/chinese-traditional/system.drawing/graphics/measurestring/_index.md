---
title: MeasureString()
second_title: Aspose.Slides for C++ API 參考
description: 傳回在指定字型與指定格式下繪製的指定字串的尺寸。
type: docs
weight: 521
url: /zh-hant/system.drawing/graphics/measurestring/
---
## Graphics::MeasureString(String const&, System::SharedPtr\<Font\> const&, PointF const&, System::SharedPtr\<StringFormat\> const&) const 方法


傳回在指定字型與指定格式下繪製的指定字串的尺寸。

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, PointF const &origin=PointF(0, 0), System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | 欲計算尺寸的字串 |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | 用於繪製字串的字型 |
| origin | [PointF](../../pointf/) const\& | 指定字串左上角的位置 |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | 指定字串的格式 |

### 傳回值

一個 [SizeF](../../sizef/) 物件，代表字串的大小，單位為目前 Graphics 物件的 PageUnit 屬性所指定的測量單位。

## Graphics::MeasureString(String const&, System::SharedPtr\<Font\> const&, int, System::SharedPtr\<StringFormat\> const&) const 方法


傳回在指定字型與指定格式下繪製的指定字串的尺寸。

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, int width, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | 欲計算尺寸的字串 |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | 用於繪製字串的字型 |
| width | int | 字串的最大寬度 |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | 指定字串的格式 |

### 傳回值

一個 [SizeF](../../sizef/) 物件，代表字串的大小，單位為目前 Graphics 物件的 PageUnit 屬性所指定的測量單位。

## Graphics::MeasureString(String const&, System::SharedPtr\<Font\> const&, SizeF const&, System::SharedPtr\<StringFormat\> const&, int\&, int\&) const 方法


未實作。

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat, int &charactersFitted, int &linesFilled) const
```


## Graphics::MeasureString(String const&, System::SharedPtr\<Font\> const&, SizeF const&, System::SharedPtr\<StringFormat\> const&) const 方法


傳回在指定字型與指定格式下繪製的指定字串的尺寸。

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | 欲計算尺寸的字串 |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | 用於繪製字串的字型 |
| layoutArea | [SizeF](../../sizef/) const\& | 字串的最大佈局區域 |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | 指定字串的格式 |

### 傳回值

一個 [SizeF](../../sizef/) 物件，代表字串的大小，單位為目前 Graphics 物件的 PageUnit 屬性所指定的測量單位。

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [SizeF](../../sizef/)
* 類別 [String](../../../system/string/)
* 類別 [Font](../../font/)
* 類別 [PointF](../../pointf/)
* 類別 [StringFormat](../../stringformat/)
* 類別 [Graphics](../)
* 命名空間 [System::Drawing](../../)
* 程式庫 [Aspose.Slides](../../../)