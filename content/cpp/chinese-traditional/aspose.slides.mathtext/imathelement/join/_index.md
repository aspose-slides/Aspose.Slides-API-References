---
title: Join()
second_title: Aspose.Slides for C++ API 參考
description: 將數學元素合併並形成數學區塊
type: docs
weight: 14
url: /zh-hant/aspose.slides.mathtext/imathelement/join/
---
## IMathElement::Join(System::SharedPtr\<IMathElement\>) 方法


將數學元素合併並形成數學區塊

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::SharedPtr<IMathElement> mathElement)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 要合併的元素 |

### 返回值

包含此實例及指定參數的新 [IMathBlock](../../imathblock/)

## 備註



範例： 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## IMathElement::Join(System::String) 方法


將數學文字合併並形成數學區塊

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::String mathText)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | 要合併的數學文字 |

### 返回值

包含此實例及指定參數的新 [IMathBlock](../../imathblock/)

## 備註



範例： 
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathBlock](../../imathblock/)
* 類別 [IMathElement](../)
* 類別 [String](../../../system/string/)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)