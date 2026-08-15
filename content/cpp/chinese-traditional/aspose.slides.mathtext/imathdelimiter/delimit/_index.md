---
title: Delimit()
second_title: Aspose.Slides for C++ API 參考文件
description: 使用指定的分隔符字符來分隔參數
type: docs
weight: 144
url: /zh-hant/aspose.slides.mathtext/imathdelimiter/delimit/
---
## IMathDelimiter::Delimit(char16_t) 方法

使用指定的分隔符字符來分隔參數

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathDelimiter::Delimit(char16_t separatorCharacter)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| separatorCharacter | char16_t | 分隔符字符 |

### 返回值

套用分隔符字符後的此物件
## 備註



範例:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->Delimit(u'|');
```

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathDelimiter](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)