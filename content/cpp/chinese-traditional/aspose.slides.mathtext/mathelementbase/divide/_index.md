---
title: Divide()
second_title: Aspose.Slides for C++ API 參考文件
description: 使用此分子和指定的分母建立分數
type: docs
weight: 14
url: /zh-hant/aspose.slides.mathtext/mathelementbase/divide/
---
## MathElementBase::Divide(System::SharedPtr\<IMathElement\>) 方法


建立一個分子為此且分母為指定值的分數

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 分母 |

### 傳回值

新的分數
## 備註



範例： 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## MathElementBase::Divide(System::String) 方法


建立一個分子為此且分母為指定值的分數

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | 分母 |

### 傳回值

新的分數
## 備註



範例： 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## MathElementBase::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) 方法


建立一個指定類型的分數，分子為此且分母為指定值

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 分母 |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | 分數類型：Bar, NoBar, Skewed, Linear |

### 傳回值

新的分數
## 備註



範例： 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator, MathFractionTypes::Linear);
```

## MathElementBase::Divide(System::String, MathFractionTypes) 方法


建立一個指定類型的分數，分子為此且分母為指定值

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator, MathFractionTypes fractionType) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | 分母 |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | 分數類型：Bar, NoBar, Skewed, Linear |

### 傳回值

新的分數
## 備註



範例： 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y", MathFractionTypes::Linear);
```

## 另請參閱

* Enum [MathFractionTypes](../../mathfractiontypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFraction](../../imathfraction/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)