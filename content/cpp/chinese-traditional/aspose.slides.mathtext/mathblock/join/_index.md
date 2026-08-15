---
title: Join()
second_title: Aspose.Slides for C++ API 參考
description: 將數學元素與此數學區塊結合
type: docs
weight: 183
url: /zh-hant/aspose.slides.mathtext/mathblock/join/
---
## MathBlock::Join(System::SharedPtr\<IMathElement\>) 方法

Joins a mathematical element with this mathematical block

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::SharedPtr<IMathElement> mathElement) override
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 要加入的元素 |

### Return Value

當前的 [IMathBlock](../../imathblock/) 實例
## 備註



範例： 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathBlock::Join(System::String) 方法

Joins a mathematical text with this mathematical block

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::String mathText) override
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | 要加入的數學文字 |

### Return Value

包含此實例和指定參數的新 [IMathBlock](../../imathblock/)
## 備註



範例： 
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBlock](../../imathblock/)
* Class [IMathElement](../../imathelement/)
* Class [MathBlock](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)