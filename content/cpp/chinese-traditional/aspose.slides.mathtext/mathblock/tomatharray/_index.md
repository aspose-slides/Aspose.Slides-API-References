---
title: ToMathArray()
second_title: Aspose.Slides for C++ API 參考
description: 將子元素放入垂直陣列
type: docs
weight: 235
url: /zh-hant/aspose.slides.mathtext/mathblock/tomatharray/
---
## MathBlock::ToMathArray() 方法


將子元素放入垂直陣列

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathBlock::ToMathArray() override
```


### 返回值

新實例的類型 [IMathArray](../../imatharray/)
## 備註



範例: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathArray](../../imatharray/)
* 類別 [MathBlock](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 程式庫 [Aspose.Slides](../../../)