---
title: SetSubSuperscriptOnTheLeft()
second_title: Aspose.Slides for C++ API 參考文件
description: 在左側建立下標與上標
type: docs
weight: 118
url: /zh-hant/aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft/
---
## IMathElement::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method

在左側建立下標與上標

```cpp
virtual System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 下標（左側的下標） |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 上標（左側的上標） |

### 傳回值

新數學元素，類型為 [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)

## 備註



範例： 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(subscript, superscript);
```

## IMathElement::SetSubSuperscriptOnTheLeft(System::String, System::String) method

在左側建立下標與上標

```cpp
virtual System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | 下標（左側的下標） |
| superscript | [System::String](../../../system/string/) | 上標（左側的上標） |

### 傳回值

新數學元素，類型為 [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)

## 備註



範例： 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(u"i", u"j");
```

## 另請參閱

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
* 類別 [IMathElement](../)
* 類別 [String](../../../system/string/)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)