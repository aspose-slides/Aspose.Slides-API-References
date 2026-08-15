---
title: idx_get()
second_title: Aspose.Slides for C++ API 參考文件
description: 在指定的索引處取得 IMathElement。
type: docs
weight: 27
url: /zh-hant/aspose.slides.mathtext/mathblock/idx_get/
---
## MathBlock::idx_get(int32_t) 方法


在指定的索引處取得 [IMathElement](../../imathelement/)。

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBlock::idx_get(int32_t index) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 項目的零基索引 |

### 傳回值

數學元素。

## 備註



範例： 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = mathBlock->idx_get(0);
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [MathBlock](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)