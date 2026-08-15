---
title: set_HideTop()
second_title: Aspose.Slides C++ API 參考
description: 隱藏上邊緣 (預設為 false) - 指定 border box 上邊緣的隱藏或顯示狀態。
type: docs
weight: 27
url: /zh-hant/aspose.slides.mathtext/imathborderbox/set_hidetop/
---
## IMathBorderBox::set_HideTop(bool) 方法


隱藏上邊緣（default is false） - 指定 border box 上邊緣的隱藏或顯示狀態。

```cpp
virtual void Aspose::Slides::MathText::IMathBorderBox::set_HideTop(bool value)=0
```

## 備註


範例: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_HideTop(true);
```

## 另請參閱

* 類別 [IMathBorderBox](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)