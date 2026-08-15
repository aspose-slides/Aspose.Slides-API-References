---
title: get_Character()
second_title: Aspose.Slides C++ API 參考文件
description: "分組字元 預設值： U+23DF (底部大括弧)"
type: docs
weight: 14
url: /zh-hant/aspose.slides.mathtext/imathgroupingcharacter/get_character/
---
## IMathGroupingCharacter::get_Character() 方法


分組字元 預設值： U+23DF (底部大括弧)

```cpp
virtual char16_t Aspose::Slides::MathText::IMathGroupingCharacter::get_Character()=0
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