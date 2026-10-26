---
title: FontFamily()
second_title: Aspose.Slides for C++ API 参考
description: 构造一个新的 FontFamily 类实例，该实例表示具有指定名称的字体系列。
type: docs
weight: 1
url: /zh/system.drawing/fontfamily/fontfamily/
---
## FontFamily::FontFamily(const String\&) 构造函数

构造一个新的 [FontFamily](../) 类实例，该实例表示具有指定名称的字体系列。

```cpp
System::Drawing::FontFamily::FontFamily(const String &name)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | 字体系列名称 |

## FontFamily::FontFamily(const String\&, const SharedPtr\<Text::FontCollection\>\&) 构造函数

构造一个新的 [FontFamily](../) 实例，在指定的 FontCollection 中使用指定的名称。

```cpp
System::Drawing::FontFamily::FontFamily(const String &name, const SharedPtr<Text::FontCollection> &font_collection)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | 字体系列名称 |
| font_collection | const [SharedPtr](../../../system/sharedptr/)\<[Text::FontCollection](../../../system.drawing.text/fontcollection/)\>\& | 包含此实例的 FontCollection。 |

## FontFamily::FontFamily(Text::GenericFontFamilies) 构造函数

构造一个新的 [FontFamily](../) 实例，来源于指定的通用字体系列。

```cpp
System::Drawing::FontFamily::FontFamily(Text::GenericFontFamilies generic_family)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| generic_family | [Text::GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/) | 用于构造 [FontFamily](../) 的 GenericFontFamilies 值。 |

## 另请参阅

* 枚举 [GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [FontFamily](../)
* 类 [FontCollection](../../../system.drawing.text/fontcollection/)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)