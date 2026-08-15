---
title: get_Character()
second_title: Aspose.Slides for C++ API 參考文件
description: "分組字元 預設值: U+23DF (底部大括號)"
type: docs
weight: 14
url: /zh-hant/aspose.slides.mathtext/mathgroupingcharacter/get_character/
---
## MathGroupingCharacter::get_Character() 方法


分組字元 預設值: U+23DF (底部大括號)

```cpp
char16_t Aspose::Slides::MathText::MathGroupingCharacter::get_Character() override
```

## 說明


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