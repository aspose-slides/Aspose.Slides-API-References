---
title: SetLowerLimit()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得下限
type: docs
weight: 157
url: /zh-hant/aspose.slides.mathtext/imathelement/setlowerlimit/
---
## IMathElement::SetLowerLimit(System::SharedPtr\<IMathElement\>) 方法


取得下限

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetLowerLimit(System::SharedPtr<IMathElement> limit)=0
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | limit |

### 返回值

[IMathLimit](../../imathlimit/) 類型的新實例
## 備註



範例：
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitValue = System::MakeObject<MathematicalText>(u"\U0001d45b→∞");
auto limitElement = baseElement->SetLowerLimit(limitValue);
```

## IMathElement::SetLowerLimit(System::String) 方法


取得下限

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetLowerLimit(System::String limit)=0
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | limit |

### 返回值

[IMathLimit](../../imathlimit/) 類型的新實例
## 備註



範例：
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitElement = baseElement->SetLowerLimit(u"\U0001d45b→∞");
```

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathLimit](../../imathlimit/)
* 類別 [IMathElement](../)
* 類別 [String](../../../system/string/)
* 命名空間 [Aspose::Slides::MathText](../../)
* 程式庫 [Aspose.Slides](../../../)