---
title: ToMathArray()
second_title: Aspose.Slides for C++ API 參考
description: 將資料放入垂直陣列
type: docs
weight: 170
url: /zh-hant/aspose.slides.mathtext/mathelementbase/tomatharray/
---
## MathElementBase::ToMathArray() 方法


將資料放入垂直陣列

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathElementBase::ToMathArray() override
```


### 返回值

[IMathArray](../../imatharray/) 類型的新實例
## 備註



範例： 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## 另見

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathArray](../../imatharray/)
* 類別 [MathElementBase](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 程式庫 [Aspose.Slides](../../../)