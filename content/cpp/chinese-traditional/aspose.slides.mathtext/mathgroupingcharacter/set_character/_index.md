---
title: set_Character()
second_title: Aspose.Slides for C++ API 參考文件
description: "分組字元 預設值: U+23DF (底部大括號)"
type: docs
weight: 27
url: /zh-hant/aspose.slides.mathtext/mathgroupingcharacter/set_character/
---
## MathGroupingCharacter::set_Character(char16_t) 方法

分組字元 預設值：U+23DF（底部大括號）

```cpp
void Aspose::Slides::MathText::MathGroupingCharacter::set_Character(char16_t value) override
```
## 備註

範例:
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Character(u'\u23DD');
// 底部括號
```
## 另請參閱

* 類別 [MathGroupingCharacter](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)