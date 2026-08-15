---
title: Overbar()
second_title: Aspose.Slides for C++ API 參考
description: 在此元素的頂部設置一條橫線
type: docs
weight: 209
url: /zh-hant/aspose.slides.mathtext/mathelementbase/overbar/
---
## MathElementBase::Overbar() 方法

在此元素的上方設置一條橫線

```cpp
System::SharedPtr<IMathBar> Aspose::Slides::MathText::MathElementBase::Overbar() override
```

### 返回值

新建的 [IMathBar](../../imathbar/) 類型實例
## 備註



範例：
```cpp
auto bar = System::MakeObject<MathematicalText>(u"x")->Overbar();
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathBar](../../imathbar/)
* 類別 [MathElementBase](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)