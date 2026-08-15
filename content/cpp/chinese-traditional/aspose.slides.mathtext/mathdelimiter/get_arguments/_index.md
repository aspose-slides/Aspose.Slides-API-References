---
title: get_Arguments()
second_title: Aspose.Slides C++ API 參考
description: 一個或多個以分隔字元分隔的數學元素
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/mathdelimiter/get_arguments/
---
## MathDelimiter::get_Arguments() 方法


一個或多個以分隔字元分隔的數學元素

```cpp
System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::MathDelimiter::get_Arguments() override
```

## 備註


範例：
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
auto arguments = delimiter->get_Arguments();
```

## 另見

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathElementCollection](../../imathelementcollection/)
* 類別 [MathDelimiter](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)