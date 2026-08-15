---
title: Divide()
second_title: Aspose.Slides for C++ API 參考
description: 使用此分子和指定的分母建立分數
type: docs
weight: 27
url: /zh-hant/aspose.slides.mathtext/imathelement/divide/
---
## IMathElement::Divide(System::SharedPtr\<IMathElement\>) 方法


使用此分子和指定的分母建立分數

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator)=0
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 分母 |

### 返回值

新的分數
## 備註



範例： 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## IMathElement::Divide(System::String) 方法


使用此分子和指定的分母建立分數

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator)=0
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | 分母 |

### 返回值

新的分數
## 備註



範例： 
```cpp
System::SharedPtr<IMathElement> numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## IMathElement::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) 方法


使用此分子和指定的分母建立指定類型的分數

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType)=0
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 分母 |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | 分數類型：Bar, NoBar, Skewed, Linear |

### 返回值

新的分數
## 備註



範例： 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator, MathFractionTypes::Linear);
```

## IMathElement::Divide(System::String, MathFractionTypes) 方法


使用此分子和指定的分母建立指定類型的分數

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator, MathFractionTypes fractionType)=0
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | 分母 |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | 分數類型：Bar, NoBar, Skewed, Linear |

### 返回值

新的分數
## 備註



範例： 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y", MathFractionTypes::Linear);
```

## 另請參閱

* 枚舉 [MathFractionTypes](../../mathfractiontypes/)
* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathFraction](../../imathfraction/)
* 類別 [IMathElement](../)
* 類別 [String](../../../system/string/)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)