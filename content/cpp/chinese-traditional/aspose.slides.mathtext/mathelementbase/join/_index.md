---
title: Join()
second_title: Aspose.Slides for C++ API 參考
description: 將數學元素合併並形成數學區塊
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/mathelementbase/join/
---
## MathElementBase::Join(System::SharedPtr\<IMathElement\>) 方法


將數學元素合併並形成數學區塊

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::SharedPtr<IMathElement> mathElement) override
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 要合併的元素 |

### 返回值

包含此實例和指定參數的新 [IMathBlock](../../imathblock/)

## 備註



範例： 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathElementBase::Join(System::String) 方法


將數學文本合併並形成數學區塊

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::String mathText) override
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | 要合併的數學文本 |

### 返回值

包含此實例和指定參數的新 [IMathBlock](../../imathblock/)

## 備註



範例： 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## 參見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathBlock](../../imathblock/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [MathElementBase](../)
* 類別 [String](../../../system/string/)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)