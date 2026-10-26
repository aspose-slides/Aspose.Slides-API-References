---
title: Remove()
second_title: Aspose.Slides for C++ API 參考文件
description: 從列表中移除第一次出現的特定 FallBack 字體。
type: docs
weight: 118
url: /zh-hant/aspose.slides/fontfallbackrule/remove/
---
## FontFallBackRule::Remove(System::String) 方法


從列表中移除首次出現的特定 FallBack 字體。

```cpp
void Aspose::Slides::FontFallBackRule::Remove(System::String fontName) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | 要從列表中移除的字體名稱。 |
## 備註



```cpp
// 建立一個包含字體清單的規則。
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// 從列表中移除 Tahoma。
newRule->Remove(u"Tahoma");
```


## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [FontFallBackRule](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)