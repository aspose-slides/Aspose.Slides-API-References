---
title: CreateMathAccent()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立一個套用至指定數學元素的數學重音，使用預設的重音字元值
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/mathaccentfactory/createmathaccent/
---
## MathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>) 方法

建立一個套用至指定的數學元素的數學重音，使用預設的重音字元值

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element) override
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 要套用重音的數學元素 |

### 傳回值

新的數學重音

## MathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>, char16_t) 方法

建立一個套用至指定數學元素的數學重音

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter) override
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 要套用重音的數學元素 |
| accentCharacter | char16_t | 重音字元 |

### 傳回值

新的數學重音

## 參見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathAccent](../../imathaccent/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [MathAccentFactory](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)