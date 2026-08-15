---
title: idx_get()
second_title: Aspose.Slides C++ API 參考
description: 取得指定索引處的元素。唯讀 IMathElement.
type: docs
weight: 14
url: /zh-hant/aspose.slides.mathtext/imathelementcollection/idx_get/
---
## IMathElementCollection::idx_get(int32_t) 方法


取得指定索引處的元素。唯讀 [IMathElement](../../imathelement/)。

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathElementCollection::idx_get(int32_t index)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 要取得之項目的零基索引 |
## 備註



範例： 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = collection->idx_get(0);
```

## 參見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [IMathElementCollection](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)