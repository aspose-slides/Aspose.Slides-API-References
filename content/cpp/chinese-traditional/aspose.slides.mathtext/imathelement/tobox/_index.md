---
title: ToBox()
second_title: Aspose.Slides for C++ API 參考
description: 將此元素放入非可視的方框（邏輯分組）中，用於將方程式或其他數學文字的組件分組。方框物件可以（例如）作為帶或不帶對齊點的運算子模擬器，作為換行點，或以不允許換行的方式分組。
type: docs
weight: 274
url: /zh-hant/aspose.slides.mathtext/imathelement/tobox/
---
## IMathElement::ToBox() 方法


將此元素放置於非可視的方框（邏輯分組）中，用於將方程式或其他數學文字的組件分組。方框物件可以（例如）作為帶或不帶對齊點的運算子模擬器，作為換行點，或以不允許換行的方式分組。

```cpp
virtual System::SharedPtr<IMathBox> Aspose::Slides::MathText::IMathElement::ToBox()=0
```


### 返回值

包含此元素的邏輯方框
## 備註



範例： 
```cpp
auto box = System::MakeObject<MathematicalText>(u"x:=y")->ToBox();
```

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathBox](../../imathbox/)
* 類別 [IMathElement](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)