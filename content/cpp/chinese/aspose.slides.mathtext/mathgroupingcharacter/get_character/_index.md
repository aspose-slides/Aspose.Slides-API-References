---
title: get_Character()
second_title: Aspose.Slides for C++ API 参考
description: "分组字符 默认值: U+23DF（底部花括号）"
type: docs
weight: 14
url: /zh/aspose.slides.mathtext/mathgroupingcharacter/get_character/
---
## MathGroupingCharacter::get_Character() 方法


分组字符 默认值: U+23DF (底部花括号)

```cpp
char16_t Aspose::Slides::MathText::MathGroupingCharacter::get_Character() override
```

## 备注


示例: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Character(u'\u23DD');
// 底部括号
```

## 另请参阅

* 类 [MathGroupingCharacter](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)