---
title: RemoveAt()
second_title: Aspose.Slides for C++ API 參考
description: 移除集合中指定索引處的元素。
type: docs
weight: 170
url: /zh-hant/aspose.slides.mathtext/mathblock/removeat/
---
## MathBlock::RemoveAt(int32_t) 方法

移除集合中指定索引處的元素。

```cpp
void Aspose::Slides::MathText::MathBlock::RemoveAt(int32_t index) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 要移除之元素的零基索引。 |
## 備註



範例： 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
mathBlock->RemoveAt(2);
```

## 另請參閱

* 類別 [MathBlock](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 程式庫 [Aspose.Slides](../../../)