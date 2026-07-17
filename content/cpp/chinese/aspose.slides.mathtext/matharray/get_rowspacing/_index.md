---
title: get_RowSpacing()
second_title: Aspose.Slides for C++ API 参考
description: "数组行之间的间距，仅在 RowSpacingRule 设置为 3 时使用。此时度量单位为点；或在 Multiple 时，度量单位为半行。默认值：0"
type: docs
weight: 118
url: /zh/aspose.slides.mathtext/matharray/get_rowspacing/
---
## MathArray::get_RowSpacing() 方法

数组行之间的间距，仅在 RowSpacingRule 设置为 3 时使用。此时度量单位为点；或在 Multiple 时，度量单位为半行。默认值：0

```cpp
uint32_t Aspose::Slides::MathText::MathArray::get_RowSpacing() override
```

## 备注


示例：
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## 另请参阅

* 类 [MathArray](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)