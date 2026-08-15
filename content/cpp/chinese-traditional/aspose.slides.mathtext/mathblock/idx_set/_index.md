---
title: idx_set()
second_title: Aspose.Slides for C++ API 參考文件
description: 在指定索引處設置 IMathElement。
type: docs
weight: 40
url: /zh-hant/aspose.slides.mathtext/mathblock/idx_set/
---
## MathBlock::idx_set(int32_t, System::SharedPtr\<IMathElement\>) 方法

在指定的索引處設置 [IMathElement](../../imathelement/)。

```cpp
void Aspose::Slides::MathText::MathBlock::idx_set(int32_t index, System::SharedPtr<IMathElement> value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 項目的零基索引 |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 數學元素。 |
## 備註



範例： 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = mathBlock->idx_get(0);
```

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [MathBlock](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 程式庫 [Aspose.Slides](../../../)