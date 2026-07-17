---
title: Delimit()
second_title: Aspose.Slides C++ API 参考
description: 使用分隔符字符（不含方括号）对子元素进行分隔
type: docs
weight: 209
url: /zh/aspose.slides.mathtext/mathblock/delimit/
---
## MathBlock::Delimit(char16_t) 方法

使用分隔符字符（不含方括号）来分隔子元素

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Delimit(char16_t separatorCharacter) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| separatorCharacter | char16_t | 分隔符字符 |

### 返回值

类型为[IMathDelimiter](../../imathdelimiter/)的数学元素

## 备注



示例：
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathDelimiter](../../imathdelimiter/)
* 类 [MathBlock](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)