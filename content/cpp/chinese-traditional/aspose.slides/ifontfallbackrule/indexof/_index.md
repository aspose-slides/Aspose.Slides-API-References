---
title: IndexOf()
second_title: Aspose.Slides for C++ API 參考
description: 傳回集合中指定規則的索引。
type: docs
weight: 118
url: /zh-hant/aspose.slides/ifontfallbackrule/indexof/
---
## IFontFallBackRule::IndexOf(System::String) 方法

傳回集合中指定規則的索引。

```cpp
virtual int32_t Aspose::Slides::IFontFallBackRule::IndexOf(System::String fontName)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | 要查找的字型名稱。 |

## 返回值

字型的索引；若在列表中找不到字型則返回 -1。

## 備註

```cpp
// 建立一個包含字型清單的規則。
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//取得 Tahoma 的索引
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```

## 另見

* 類別 [String](../../../system/string/)
* 類別 [IFontFallBackRule](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)