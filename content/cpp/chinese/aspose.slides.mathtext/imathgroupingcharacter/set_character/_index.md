---
title: set_Character()
second_title: Aspose.Slides for C++ API 参考
description: "分组字符 默认值: U+23DF (底部花括号)"
type: docs
weight: 27
url: /zh/aspose.slides.mathtext/imathgroupingcharacter/set_character/
---
## IMathGroupingCharacter::set_Character(char16_t) 方法


分组字符 默认值: U+23DF (底部花括号)

```cpp
virtual void Aspose::Slides::MathText::IMathGroupingCharacter::set_Character(char16_t value)=0
```

## 备注


示例： 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Character(u'\u23DD');
// 底部括号
```

## 另请参阅

* 类 [IMathGroupingCharacter](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)