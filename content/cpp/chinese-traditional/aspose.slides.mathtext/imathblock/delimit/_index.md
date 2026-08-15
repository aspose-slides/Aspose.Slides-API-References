---
title: Delimit()
second_title: Aspose.Slides for C++ API 參考文件
description: 使用分隔字元將所有子元素分隔（不含括號）
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/imathblock/delimit/
---
## IMathBlock::Delimit(char16_t) 方法

將所有子元素以分隔字元分隔（不含括號）

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Delimit(char16_t separatorCharacter)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| separatorCharacter | char16_t | 用作分隔符的字元 |

### 傳回值

[IMathDelimiter](../../imathdelimiter/) 元素的實例

## 備註



範例:
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathDelimiter](../../imathdelimiter/)
* 類別 [IMathBlock](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)