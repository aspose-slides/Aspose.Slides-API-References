---
title: Enclose()
second_title: Aspose.Slides for C++ API 參考
description: 將數學元素括於括號中
type: docs
weight: 27
url: /zh-hant/aspose.slides.mathtext/mathelementbase/enclose/
---
## MathElementBase::Enclose() 方法


將數學元素括於括號中

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose() override
```


### 返回值

類型為 [IMathDelimiter](../../imathdelimiter/) 的數學元素，包含括號
## 備註



範例： 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## MathElementBase::Enclose(char16_t, char16_t) 方法


將數學元素以指定字元（例如括號或其他字元）作為框架括起

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| beginningCharacter | char16_t | 起始字元（通常為左括號） |
| endingCharacter | char16_t | 結束字元（通常為右括號） |

### 返回值

類型為 [IMathDelimiter](../../imathdelimiter/) 的數學元素，包含指定字元作為框架
## 備註



範例： 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathDelimiter](../../imathdelimiter/)
* 類別 [MathElementBase](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)