---
title: set_RowSpacing()
second_title: Aspose.Slides for C++ API 参考
description: "数组行之间的间距 仅在 RowSpacingRule 设置为 3 时使用 当设置为 Exactly 时，计量单位为点；当设置为 Multiple 时，计量单位为半行。 默认: 0"
type: docs
weight: 131
url: /zh/aspose.slides.mathtext/matharray/set_rowspacing/
---
## MathArray::set_RowSpacing(uint32_t) 方法


数组行之间的间距 仅在 RowSpacingRule 设置为 3 时使用 当设置为 Exactly 时，测量单位为点；当设置为 Multiple 时，测量单位为半行。 默认: 0

```cpp
void Aspose::Slides::MathText::MathArray::set_RowSpacing(uint32_t value) override
```

## 备注


示例: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## 另见

* 类 [MathArray](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)