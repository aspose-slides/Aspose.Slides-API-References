---
title: Enclose()
second_title: Aspose.Slides for C++ API 參考
description: 將此區塊的子元素以指定的字元（例如括號或其他字元）作為框架包圍
type: docs
weight: 222
url: /zh-hant/aspose.slides.mathtext/mathblock/enclose/
---
## MathBlock::Enclose(char16_t, char16_t) 方法

將此區塊的子元素用指定的字元（例如括號或其他字元）包圍

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| beginningCharacter | char16_t | 開始字元（通常為左括號） |
| endingCharacter | char16_t | 結束字元（通常為右括號） |

### 回傳值

型別為 [IMathDelimiter](../../imathdelimiter/) 的數學元素，包含指定的字元作為框架

## 附註



範例： 
```cpp
auto block = System::MakeObject<MathematicalText>(u"x")->Join(u"+y");
auto delimiter = System::ExplicitCast<IMathElement>(block)->Enclose(u'[', u']');
```

## MathBlock::Enclose(char16_t, char16_t, char16_t) 方法

將此區塊的子元素用指定的字元（例如括號或其他字元）包圍，並以分隔字元作為分界

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| beginningCharacter | char16_t | 開始字元（通常為左括號） |
| endingCharacter | char16_t | 結束字元（通常為右括號） |
| separatorCharacter | char16_t | 分隔字元 |

### 回傳值

型別為 [IMathDelimiter](../../imathdelimiter/) 的數學元素，包含指定的字元作為框架與分隔符號

## 附註



範例： 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## 參見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathDelimiter](../../imathdelimiter/)
* 類別 [MathBlock](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)