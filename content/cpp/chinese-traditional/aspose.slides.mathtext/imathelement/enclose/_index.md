---
title: Enclose()
second_title: Aspose.Slides for C++ API 參考
description: 將數學元素括於括號中
type: docs
weight: 40
url: /zh-hant/aspose.slides.mathtext/imathelement/enclose/
---
## IMathElement::Enclose() 方法

將數學元素括於括號中

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose()=0
```

### 返回值

包含括號的 [IMathDelimiter](../../imathdelimiter/) 類型的數學元素
## 備註



範例：
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## IMathElement::Enclose(char16_t, char16_t) 方法

將此元素以指定字符（如括號或其他字符）作為框架包圍

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose(char16_t beginningCharacter, char16_t endingCharacter)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| beginningCharacter | char16_t | 起始字符（通常為左括號） |
| endingCharacter | char16_t | 結束字符（通常為右括號） |

### 返回值

包含指定字符作為框架的 [IMathDelimiter](../../imathdelimiter/) 類型的數學元素
## 備註



範例：
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathDelimiter](../../imathdelimiter/)
* 類別 [IMathElement](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)