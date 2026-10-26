---
title: Remove()
second_title: Aspose.Slides for C++ API 參考
description: 從列表中移除第一個出現的特定 FallBack 字型。
type: docs
weight: 79
url: /zh-hant/aspose.slides/ifontfallbackrule/remove/
---
## IFontFallBackRule::Remove(System::String) 方法


從列表中移除第一個出現的特定 FallBack 字型。

```cpp
virtual void Aspose::Slides::IFontFallBackRule::Remove(System::String fontName)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | 要從列表中移除的字型名稱。 |
## 備註



```cpp
// 建立一個包含字型清單的規則。
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// 從清單中移除 Tahoma
newRule->Remove(u"Tahoma");
```


## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [IFontFallBackRule](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)