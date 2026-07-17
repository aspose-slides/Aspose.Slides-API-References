---
title: RemoveAt()
second_title: Aspose.Slides C++ API 参考
description: 删除集合中指定索引处的元素。
type: docs
weight: 170
url: /zh/aspose.slides.mathtext/mathblock/removeat/
---
## MathBlock::RemoveAt(int32_t) 方法


从集合中删除指定索引处的元素。

```cpp
void Aspose::Slides::MathText::MathBlock::RemoveAt(int32_t index) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 要删除的元素的零基索引。 |
## 备注



示例：
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
mathBlock->RemoveAt(2);
```

## 另见

* 类 [MathBlock](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)