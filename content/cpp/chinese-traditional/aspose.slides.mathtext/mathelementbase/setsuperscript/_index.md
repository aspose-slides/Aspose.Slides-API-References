---
title: SetSuperscript()
second_title: Aspose.Slides for C++ API 參考
description: 建立上標
type: docs
weight: 79
url: /zh-hant/aspose.slides.mathtext/mathelementbase/setsuperscript/
---
## MathElementBase::SetSuperscript(System::SharedPtr\<IMathElement\>) 方法


建立上標

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::SharedPtr<IMathElement> superscript) override
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 上標（右側的上標） |

### 回傳值

New math element of type [IMathSuperscriptElement](../../imathsuperscriptelement/)
## 備註



範例： 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## MathElementBase::SetSuperscript(System::String) 方法


建立上標

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::String superscript) override
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | 上標（右側的上標） |

### 回傳值

New math element of type [IMathSuperscriptElement](../../imathsuperscriptelement/)
## 備註



範例： 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathSuperscriptElement](../../imathsuperscriptelement/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [MathElementBase](../)
* 類別 [String](../../../system/string/)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)