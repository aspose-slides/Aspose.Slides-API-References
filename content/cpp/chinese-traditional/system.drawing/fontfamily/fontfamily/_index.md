---
title: FontFamily()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立一個新的 FontFamily 類別實例，表示具有指定名稱的字型系列。
type: docs
weight: 1
url: /zh-hant/system.drawing/fontfamily/fontfamily/
---
## FontFamily::FontFamily(const String\&) 建構函式

建立一個新的 [FontFamily](../) 類別實例，表示具有指定名稱的字型系列。

```cpp
System::Drawing::FontFamily::FontFamily(const String &name)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | 字型系列的名稱 |

## FontFamily::FontFamily(const String\&, const SharedPtr\<Text::FontCollection\>\&) 建構函式

建立一個新的 [FontFamily](../) 實例於指定的 FontCollection 中，並使用指定的名稱。

```cpp
System::Drawing::FontFamily::FontFamily(const String &name, const SharedPtr<Text::FontCollection> &font_collection)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | 字型系列的名稱 |
| font_collection | const [SharedPtr](../../../system/sharedptr/)\<[Text::FontCollection](../../../system.drawing.text/fontcollection/)\>\& | 包含此實例的 FontCollection |

## FontFamily::FontFamily(Text::GenericFontFamilies) 建構函式

從指定的通用字型系列建立一個新的 [FontFamily](../) 實例。

```cpp
System::Drawing::FontFamily::FontFamily(Text::GenericFontFamilies generic_family)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| generic_family | [Text::GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/) | 用於構造 [FontFamily](../) 的 GenericFontFamilies 值 |

## 參見

* Enum [GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [FontFamily](../)
* Class [FontCollection](../../../system.drawing.text/fontcollection/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)