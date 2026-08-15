---
title: ToBox()
second_title: Aspose.Slides for C++ API 參考
description: 將此元素放置於非可視方框（邏輯分組）中，用於對方程式或其他數學文字的組件進行分組。方框物件可以（例如）作為帶或不帶對齊點的運算子模擬器，作為換行點，或被分組以防止其中換行。
type: docs
weight: 261
url: /zh-hant/aspose.slides.mathtext/mathelementbase/tobox/
---
## MathElementBase::ToBox() 方法


將此元素放置於非可視方框（邏輯分組）中，用於對方程式或其他數學文字的組件進行分組。方框物件可以（例如）作為帶或不帶對齊點的運算子模擬器，作為換行點，或被分組以避免在其中換行。

```cpp
System::SharedPtr<IMathBox> Aspose::Slides::MathText::MathElementBase::ToBox() override
```


### 返回值

邏輯方框，內含此元素
## 備註



範例： 
```cpp
auto box = System::MakeObject<MathematicalText>(u"x:=y")->ToBox();
```

## 另見

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathBox](../../imathbox/)
* 類別 [MathElementBase](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)