---
title: CreateMathAccent()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立一個套用於指定數學元素的數學重音，使用預設的重音字元值
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/imathaccentfactory/createmathaccent/
---
## IMathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>) 方法

建立一個套用於指定數學元素的數學重音，使用預設的重音字元值

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 套用重音的數學元素 |
| --- | --- | --- |

### 回傳值

新的數學重音

## IMathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>, char16_t) 方法

建立一個套用於指定數學元素的數學重音

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 套用重音的數學元素 |
| accentCharacter | char16_t | 重音字元 |
| --- | --- | --- |

### 回傳值

新的數學重音

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathAccent](../../imathaccent/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [IMathAccentFactory](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 程式庫 [Aspose.Slides](../../../)