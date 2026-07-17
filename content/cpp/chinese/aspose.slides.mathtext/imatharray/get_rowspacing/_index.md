---
title: get_RowSpacing()
second_title: Aspose.Slides C++ API 参考
description: "数组行之间的间距，仅在 RowSpacingRule 设置为 3 时使用。恰好在这种情况下，度量单位为 points，或在 Multiple 情况下，度量单位为 half-lines。默认值：0"
type: docs
weight: 118
url: /zh/aspose.slides.mathtext/imatharray/get_rowspacing/
---
## IMathArray::get_RowSpacing() 方法

数组行之间的间距 仅当 RowSpacingRule 设置为 3 时使用 恰好在这种情况下，度量单位为 points，或在 Multiple 情况下，度量单位为 half-lines。默认：0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathArray::get_RowSpacing()=0
```

## 备注

示例：
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## 另请参阅

* 类 [IMathArray](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)