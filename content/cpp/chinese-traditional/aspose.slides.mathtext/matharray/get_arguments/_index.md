---
title: get_Arguments()
second_title: Aspose.Slides for C++ API 參考文件
description: 陣列項目的集合
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/matharray/get_arguments/
---
## MathArray::get_Arguments() 方法


陣列項目的集合

```cpp
System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::MathArray::get_Arguments() override
```

## 備註


範例：
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->get_Arguments()->Add(System::MakeObject<MathematicalText>(u"item2"));
```

## 參見

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathElementCollection](../../imathelementcollection/)
* 類別 [MathArray](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 程式庫 [Aspose.Slides](../../../)