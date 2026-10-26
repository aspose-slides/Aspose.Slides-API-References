---
title: SetSuperscript()
second_title: Aspose.Slides C++ API 參考
description: 建立上標
type: docs
weight: 92
url: /zh-hant/aspose.slides.mathtext/imathelement/setsuperscript/
---
## IMathElement::SetSuperscript(System::SharedPtr\<IMathElement\>) 方法

建立上標

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::SharedPtr<IMathElement> superscript)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 上標（右側的上標） |

### 返回值

新數學元素類型 [IMathSuperscriptElement](../../imathsuperscriptelement/)
## 備註



範例： 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## IMathElement::SetSuperscript(System::String) 方法

建立上標

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::String superscript)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | 上標（右側的上標） |

### 返回值

新數學元素類型 [IMathSuperscriptElement](../../imathsuperscriptelement/)
## 備註



範例： 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathSuperscriptElement](../../imathsuperscriptelement/)
* 類別 [IMathElement](../)
* 類別 [String](../../../system/string/)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)