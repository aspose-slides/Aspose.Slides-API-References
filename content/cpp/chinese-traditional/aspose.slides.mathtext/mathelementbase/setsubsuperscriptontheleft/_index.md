---
title: SetSubSuperscriptOnTheLeft()
second_title: Aspose.Slides for C++ API 參考
description: 在左側建立下標和上標
type: docs
weight: 105
url: /zh-hant/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft/
---
## MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method

在左側建立下標和上標

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 下標（左側下標） |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 上標（左側上標） |

### 返回值

新數學元素類型 [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## 備註



範例： 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(subscript, superscript);
```

## MathElementBase::SetSubSuperscriptOnTheLeft(System::String, System::String) method

在左側建立下標和上標

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | 下標（左側下標） |
| superscript | [System::String](../../../system/string/) | 上標（左側上標） |

### 返回值

新數學元素類型 [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## 備註



範例： 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(u"i", u"j");
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [MathElementBase](../)
* 類別 [String](../../../system/string/)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)