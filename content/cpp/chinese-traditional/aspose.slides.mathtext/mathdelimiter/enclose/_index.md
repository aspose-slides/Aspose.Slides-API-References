---
title: Enclose()
second_title: Aspose.Slides for C++ API 參考
description: 將數學元素包圍在指定的字符中，例如括號或其他作為框架的字符
type: docs
weight: 170
url: /zh-hant/aspose.slides.mathtext/mathdelimiter/enclose/
---
## MathDelimiter::Enclose(char16_t, char16_t) 方法


將數學元素包圍在指定的字符中，例如括號或其他作為框架的字符

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathDelimiter::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| beginningCharacter | char16_t | 起始字符（通常為左括號） |
| endingCharacter | char16_t | 結束字符（通常為右括號） |

### 返回值

如果 *beginningCharacter* 和 *endingCharacter* 為 null，僅為相應屬性指派值，且不會建立新物件（返回此實例）。否則，返回一個類型為 Delimiter 的新數學元素，該元素包含指定的字符作為框架，並在其中框住此 [MathDelimiter](../) 實例。  

## 備註



範例： 
```cpp
auto innerDelimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u",y"))->Enclose(u'{', u'}');
auto outerDelimiter = innerDelimiter->Enclose(u'[', u']');
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathDelimiter](../../imathdelimiter/)
* 類別 [MathDelimiter](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)