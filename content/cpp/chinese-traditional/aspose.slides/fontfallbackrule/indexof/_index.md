---
title: IndexOf()
second_title: Aspose.Slides for C++ API 參考文件
description: 傳回集合中指定規則的索引。
type: docs
weight: 157
url: /zh-hant/aspose.slides/fontfallbackrule/indexof/
---
## FontFallBackRule::IndexOf(System::String) 方法


傳回集合中指定規則的索引。

```cpp
int32_t Aspose::Slides::FontFallBackRule::IndexOf(System::String fontName) override
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | 要尋找的字型名稱。 |

### 傳回值

字型的索引，若清單中未找到字型則為 -1。

## 備註



```cpp
// 建立包含字型清單的規則。
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// 取得 Tahoma 的索引。
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```


## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [FontFallBackRule](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)