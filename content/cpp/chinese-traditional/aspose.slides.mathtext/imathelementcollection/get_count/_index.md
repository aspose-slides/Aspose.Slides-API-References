---
title: get_Count()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得集合實際包含的元素數量。唯讀 int32_t.
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/imathelementcollection/get_count/
---
## IMathElementCollection::get_Count() 方法

取得集合實際包含的元素數量。唯讀 **int32_t**.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathElementCollection::get_Count()=0
```
## 備註

範例：
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
int32_t count = collection->get_Count();
```
## 另請參閱

* 類別 [IMathElementCollection](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)