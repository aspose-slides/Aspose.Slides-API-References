---
title: set_Character()
second_title: Aspose.Slides for C++ API 參考文件
description: "字元分組 預設值：U+23DF (BOTTOM CURLY BRACKET)"
type: docs
weight: 27
url: /zh-hant/aspose.slides.mathtext/imathgroupingcharacter/set_character/
---
## IMathGroupingCharacter::set_Character(char16_t) 方法

字元分組 預設值：U+23DF（底部大括號）

```cpp
virtual void Aspose::Slides::MathText::IMathGroupingCharacter::set_Character(char16_t value)=0
```

## 備註

範例：
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Character(u'\u23DD');
// 底部括號
```

## 另請參閱

* 類別 [IMathGroupingCharacter](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)