---
title: Remove()
second_title: Aspose.Slides for C++ API 參考
description: 從集合中移除特定物件的第一個出現。
type: docs
weight: 131
url: /zh-hant/aspose.slides.mathtext/mathblock/remove/
---
## MathBlock::Remove(System::SharedPtr\<IMathElement\>) 方法

從集合中移除第一次出現的特定物件。

```cpp
bool Aspose::Slides::MathText::MathBlock::Remove(System::SharedPtr<IMathElement> item) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 要從集合中移除的物件。 |

### 返回值

如果成功從集合中移除 *item*，則返回 true；否則返回 false。如果在原始集合中找不到 *item*，此方法也會返回 false。

## 備註



範例： 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
mathBlock->Remove(plusElement);
```

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [MathBlock](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 程式庫 [Aspose.Slides](../../../)