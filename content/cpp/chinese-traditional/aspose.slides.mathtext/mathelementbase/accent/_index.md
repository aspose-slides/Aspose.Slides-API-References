---
title: Accent()
second_title: Aspose.Slides for C++ API 參考文件
description: 設定此元素上方的重音符號（位於此元素上方的字元）
type: docs
weight: 196
url: /zh-hant/aspose.slides.mathtext/mathelementbase/accent/
---
## MathElementBase::Accent(char16_t) 方法

設定此元素上方的重音符號（位於此元素上方的字元）

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathElementBase::Accent(char16_t accentCharacter) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| accentCharacter | char16_t | 重音字元。值應位於 (U+0300\u2013U+036F) 或 (U+20D0\u2013U+20EF) 範圍內 |

## 回傳值

新實例的類型 [IMathAccent](../../imathaccent/)

## 備註



範例： 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
```

## 另請參考

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathAccent](../../imathaccent/)
* 類別 [MathElementBase](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)