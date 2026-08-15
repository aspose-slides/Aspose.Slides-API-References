---
title: get_Count()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得集合實際包含的子數學元素數量。唯讀 int32_t.
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/mathblock/get_count/
---
## MathBlock::get_Count() 方法


取得集合實際包含的子數學元素數量。唯讀 **int32_t**.

```cpp
int32_t Aspose::Slides::MathText::MathBlock::get_Count() override
```

## 備註


範例： 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
int32_t count = mathBlock->get_Count();
```

## 另請參閱

* 類別 [MathBlock](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)