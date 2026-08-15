---
title: SetSubscript()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立下標
type: docs
weight: 66
url: /zh-hant/aspose.slides.mathtext/mathelementbase/setsubscript/
---
## MathElementBase::SetSubscript(System::SharedPtr\<IMathElement\>) 方法


建立下標

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::SharedPtr<IMathElement> subscript) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 下標（右側的下標） |

### 返回值

新數學元素，類型為 [IMathSubscriptElement](../../imathsubscriptelement/)
## 備註



範例： 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## MathElementBase::SetSubscript(System::String) 方法


建立下標

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::String subscript) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | 下標（右側的下標） |

### 返回值

新數學元素，類型為 [IMathSubscriptElement](../../imathsubscriptelement/)
## 備註



範例： 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto subscript = element->SetSubscript(u"i");
```

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathSubscriptElement](../../imathsubscriptelement/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [MathElementBase](../)
* 類別 [String](../../../system/string/)
* 名稱空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)