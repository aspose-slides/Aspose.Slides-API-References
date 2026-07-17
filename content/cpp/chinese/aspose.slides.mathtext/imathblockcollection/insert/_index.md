---
title: Insert()
second_title: Aspose.Slides for C++ API 参考
description: 将在集合的指定索引处插入 IMathBlock。
type: docs
weight: 27
url: /zh/aspose.slides.mathtext/imathblockcollection/insert/
---
## IMathBlockCollection::Insert(int32_t, System::SharedPtr\<IMathBlock\>) 方法


在指定索引处将 [IMathBlock](../../imathblock/) 插入集合。

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Insert(int32_t index, System::SharedPtr<IMathBlock> item)=0
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 应插入项目的零基索引。 |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | 要插入的 [IMathBlock](../../imathblock/)。 |
## 备注



示例： 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Insert(0, block);
```

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IMathBlock](../../imathblock/)
* 类 [IMathBlockCollection](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)