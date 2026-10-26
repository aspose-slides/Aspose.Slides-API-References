---
title: Insert()
second_title: Aspose.Slides for C++ API 參考
description: 在指定索引處將數學元素插入集合。
type: docs
weight: 53
url: /zh-hant/aspose.slides.mathtext/imathelementcollection/insert/
---
## IMathElementCollection::Insert(int32_t, System::SharedPtr\<IMathElement\>) 方法

在指定索引處將數學元素插入集合。

```cpp
virtual void Aspose::Slides::MathText::IMathElementCollection::Insert(int32_t index, System::SharedPtr<IMathElement> item)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 零基索引，指示 [IMathElement](../../imathelement/) 應插入的位置。 |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 要插入的 [IMathElement](../../imathelement/)。 |
## 附註

範例：
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
```

## 相關參考

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [IMathElementCollection](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)