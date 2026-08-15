---
title: MathBox()
second_title: Aspose.Slides for C++ API 參考
description: 使用指定的元素作為參數來初始化 MathBox
type: docs
weight: 144
url: /zh-hant/aspose.slides.mathtext/mathbox/mathbox/
---
## MathBox::MathBox(System::SharedPtr\<IMathElement\>) 建構子


使用指定的元素作為參數來初始化 [MathBox](../)

```cpp
Aspose::Slides::MathText::MathBox::MathBox(System::SharedPtr<IMathElement> element)
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 套用至盒子的基礎元素。可以為 null。 |
## 備註



範例： 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [MathBox](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)