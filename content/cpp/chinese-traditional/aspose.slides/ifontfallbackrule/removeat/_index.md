---
title: RemoveAt()
second_title: Aspose.Slides for C++ API 參考文件
description: 移除列表中指定索引的 FallBack 字體。
type: docs
weight: 92
url: /zh-hant/aspose.slides/ifontfallbackrule/removeat/
---
## IFontFallBackRule::RemoveAt(int32_t) 方法

從列表中指定的索引位置移除 FallBack 字體。

```cpp
virtual void Aspose::Slides::IFontFallBackRule::RemoveAt(int32_t index)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 要移除的字體的零基索引。 |
## 備註

```cpp
// 建立一個包含字體清單的規則.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//從清單中移除 Tahoma
newRule->RemoveAt(2);
```

## 另見

* 類別 [IFontFallBackRule](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)