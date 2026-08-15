---
title: Accent()
second_title: Aspose.Slides for C++ API 參考
description: 設定此元素上方的重音標記（字元）
type: docs
weight: 209
url: /zh-hant/aspose.slides.mathtext/imathelement/accent/
---
## IMathElement::Accent(char16_t) 方法

設定此元素上方的重音標記（字元）

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathElement::Accent(char16_t accentCharacter)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| accentCharacter | char16_t | 重音字元。其值應在 (U+0300\u2013U+036F) 或 (U+20D0\u2013U+20EF) 範圍內 |

### 回傳值

New instance of type [IMathAccent](../../imathaccent/)
## 備註

範例：
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
```

## 相關參考

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathAccent](../../imathaccent/)
* 類別 [IMathElement](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)