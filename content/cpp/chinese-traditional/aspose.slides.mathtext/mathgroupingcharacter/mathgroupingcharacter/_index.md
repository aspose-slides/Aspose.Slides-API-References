---
title: MathGroupingCharacter()
second_title: Aspose.Slides for C++ API 參考文件
description: 使用預設的分組字元 U+23DF（底部大括號）初始化 MathGroupingCharacter 類別的新實例
type: docs
weight: 92
url: /zh-hant/aspose.slides.mathtext/mathgroupingcharacter/mathgroupingcharacter/
---
## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>) 建構函式


使用預設的分組字元 U+23DF（底部大括號）初始化 [MathGroupingCharacter](../) 類別的新執行個體

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 套用於此條的基礎元素 |
## 備註



範例: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
```

## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) 建構函式


初始化 [MathGroupingCharacter](../) 類別的新執行個體。

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 套用於此條的基礎元素 |
| character | char16_t | 分組字元 |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | 分組字元的位置 |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | 分組字元的垂直對齊方式 |
## 備註



範例: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"), u'_', MathTopBotPositions::Top, MathTopBotPositions::Bottom);
```

## 相關參考

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathGroupingCharacter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)