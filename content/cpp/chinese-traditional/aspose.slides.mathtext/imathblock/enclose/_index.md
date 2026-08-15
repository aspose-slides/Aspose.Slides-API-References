---
title: Enclose()
second_title: Aspose.Slides for C++ API 參考
description: 將此區塊的子元素以指定的字元（例如括號或其他）封裝起來，並使用分隔字元作為分界
type: docs
weight: 14
url: /zh-hant/aspose.slides.mathtext/imathblock/enclose/
---
## IMathBlock::Enclose(char16_t, char16_t, char16_t) 方法

將此區塊的子元素用指定的字元（例如括號或其他）封裝起來，並以分隔字元作為分界

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| beginningCharacter | char16_t | 起始字元（通常為左括號） |
| endingCharacter | char16_t | 結束字元（通常為右括號） |
| separatorCharacter | char16_t | 分隔字元 |

### 回傳值

類型為 [IMathDelimiter](../../imathdelimiter/) 的數學元素，包含指定的字元作為框架與分隔符

## 備註



範例： 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathDelimiter](../../imathdelimiter/)
* 類別 [IMathBlock](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)