---
title: get_Arguments()
second_title: Aspose.Slides for C++ API 參考文件
description: 陣列項目的集合
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/imatharray/get_arguments/
---
## IMathArray::get_Arguments() 方法


陣列項目的集合

```cpp
virtual System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::IMathArray::get_Arguments()=0
```

## 備註


範例：
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->get_Arguments()->Add(System::MakeObject<MathematicalText>(u"item2"));
```

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathElementCollection](../../imathelementcollection/)
* 類別 [IMathArray](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)