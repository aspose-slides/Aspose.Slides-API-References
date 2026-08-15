---
title: RemoveAt()
second_title: Aspose.Slides for C++ API 參考文件
description: 移除清單中指定索引的 FallBack 字體。
type: docs
weight: 131
url: /zh-hant/aspose.slides/fontfallbackrule/removeat/
---
## FontFallBackRule::RemoveAt(int32_t) 方法


移除清單中指定索引的 FallBack 字體。

```cpp
void Aspose::Slides::FontFallBackRule::RemoveAt(int32_t index) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 要移除的字體之零基索引。 |
## 備註



```cpp
// 建立一個包含字體清單的規則。
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// 從清單中移除 Tahoma。
newRule->RemoveAt(2);
```


## 另請參閱

* 類別 [FontFallBackRule](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)