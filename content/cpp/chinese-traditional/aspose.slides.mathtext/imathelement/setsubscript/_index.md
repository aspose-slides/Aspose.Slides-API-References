---
title: SetSubscript()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立下標
type: docs
weight: 79
url: /zh-hant/aspose.slides.mathtext/imathelement/setsubscript/
---
## IMathElement::SetSubscript(System::SharedPtr\<IMathElement\>) 方法

建立下標

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::SharedPtr<IMathElement> subscript)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 下標（右側的下標） |

### 返回值

新的數學元素類型 [IMathSubscriptElement](../../imathsubscriptelement/)
## 備註



範例： 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## IMathElement::SetSubscript(System::String) 方法

建立下標

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::String subscript)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | 下標（右側的下標） |

### 返回值

新的數學元素類型 [IMathSubscriptElement](../../imathsubscriptelement/)
## 備註



範例： 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto subscript = element->SetSubscript(u"i");
```

## 另請參閱

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathSubscriptElement](../../imathsubscriptelement/)
* 類別 [IMathElement](../)
* 類別 [String](../../../system/string/)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)