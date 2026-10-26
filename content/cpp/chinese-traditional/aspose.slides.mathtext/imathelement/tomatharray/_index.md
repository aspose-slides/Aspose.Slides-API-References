---
title: ToMathArray()
second_title: Aspose.Slides for C++ API 參考
description: 將垂直陣列放入
type: docs
weight: 183
url: /zh-hant/aspose.slides.mathtext/imathelement/tomatharray/
---
## IMathElement::ToMathArray() 方法


將垂直陣列放入

```cpp
virtual System::SharedPtr<IMathArray> Aspose::Slides::MathText::IMathElement::ToMathArray()=0
```


### 返回值

類型 [IMathArray](../../imatharray/) 的新實例
## 備註



範例： 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathArray](../../imatharray/)
* 類別 [IMathElement](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)