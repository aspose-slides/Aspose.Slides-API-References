---
title: RemoveAt()
second_title: Aspose.Slides for C++ API 參考
description: 移除集合中指定索引處的元素。
type: docs
weight: 105
url: /zh-hant/aspose.slides.mathtext/imathelementcollection/removeat/
---
## IMathElementCollection::RemoveAt(int32_t) method

移除集合中指定索引位置的元素。

```cpp
virtual void Aspose::Slides::MathText::IMathElementCollection::RemoveAt(int32_t index)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 要移除之元素的零基索引。 |
## 備註

範例：
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
collection->RemoveAt(2);
```

## 參見

* 類別 [IMathElementCollection](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)