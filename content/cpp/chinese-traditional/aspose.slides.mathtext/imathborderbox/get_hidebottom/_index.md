---
title: get_HideBottom()
second_title: Aspose.Slides for C++ API 參考
description: 隱藏底部邊緣（預設為 false） - 指定邊框盒底部邊緣的隱藏或顯示狀態。
type: docs
weight: 40
url: /zh-hant/aspose.slides.mathtext/imathborderbox/get_hidebottom/
---
## IMathBorderBox::get_HideBottom() 方法


隱藏底部邊緣（預設為 false） - 指定邊框盒底部邊緣的隱藏或顯示狀態。

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_HideBottom()=0
```

## 備註


範例：
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_HideBottom(true);
```

## 另見

* 類別 [IMathBorderBox](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)