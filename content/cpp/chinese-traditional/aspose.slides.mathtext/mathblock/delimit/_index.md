---
title: Delimit()
second_title: Aspose.Slides for C++ API 參考
description: 使用分隔字元將子元素分隔（不含方括號）
type: docs
weight: 209
url: /zh-hant/aspose.slides.mathtext/mathblock/delimit/
---
## MathBlock::Delimit(char16_t) 方法

使用分隔字元將子元素分隔（不含方括號）

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Delimit(char16_t separatorCharacter) override
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| separatorCharacter | char16_t | 分隔字元 |

### 回傳值

The math element of type [IMathDelimiter](../../imathdelimiter/)
## 備註



範例： 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## 相關參考

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathDelimiter](../../imathdelimiter/)
* 類別 [MathBlock](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)