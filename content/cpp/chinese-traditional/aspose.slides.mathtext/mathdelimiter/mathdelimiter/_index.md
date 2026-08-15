---
title: MathDelimiter()
second_title: Aspose.Slides C++ API 參考
description: 使用指定的元素作為單一基礎參數來初始化 MathDelimiter
type: docs
weight: 144
url: /zh-hant/aspose.slides.mathtext/mathdelimiter/mathdelimiter/
---
## MathDelimiter::MathDelimiter(System::SharedPtr\<IMathElement\>) 建構子

使用指定的元素作為單一基礎參數來初始化 [MathDelimiter](../)

```cpp
Aspose::Slides::MathText::MathDelimiter::MathDelimiter(System::SharedPtr<IMathElement> element)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 套用分隔符的基礎元素。可以為 null。 |

## 備註

範例：
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = System::MakeObject<MathDelimiter>(element);
```

## 參見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [MathDelimiter](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)