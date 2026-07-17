---
title: set_Character()
second_title: Aspose.Slides C++ API 参考
description: "分组字符 默认值: U+23DF (底部花括号)"
type: docs
weight: 27
url: /zh/aspose.slides.mathtext/mathgroupingcharacter/set_character/
---
## MathGroupingCharacter::set_Character(char16_t) 方法


分组字符 默认值: U+23DF (底部花括号)

```cpp
void Aspose::Slides::MathText::MathGroupingCharacter::set_Character(char16_t value) override
```

## 备注


示例: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Character(u'\u23DD');
// 底部括号
```

## 另见

* 类 [MathGroupingCharacter](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)