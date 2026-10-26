---
title: SetSubSuperscriptOnTheRight()
second_title: Aspose.Slides C++ API 參考
description: 在右側建立下標與上標
type: docs
weight: 92
url: /zh-hant/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright/
---
## MathElementBase::SetSubSuperscriptOnTheRight(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) 方法


在右側建立下標與上標

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 下標（右側的下指數） |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 上標（右側的上指數） |

### 返回值

新數學元素，類型為 [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## 備註



範例： 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(subscript, superscript);
```

## MathElementBase::SetSubSuperscriptOnTheRight(System::String, System::String) 方法


在右側建立下標與上標

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript) override
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | 下標（右側的下指數） |
| superscript | [System::String](../../../system/string/) | 上標（右側的上指數） |

### 返回值

新數學元素，類型為 [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## 備註



範例： 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(u"i", u"j");
```

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [MathElementBase](../)
* 類別 [String](../../../system/string/)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)