---
title: Delimit()
second_title: Aspose.Slides C++ API 参考
description: 使用分隔符字符对所有子元素进行定界（不包括括号）
type: docs
weight: 1
url: /zh/aspose.slides.mathtext/imathblock/delimit/
---
## IMathBlock::Delimit(char16_t) 方法


使用分隔符字符对所有子元素进行定界（不包括括号）

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Delimit(char16_t separatorCharacter)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| separatorCharacter | char16_t | 用作分隔符的字符 |

### 返回值

[IMathDelimiter](../../imathdelimiter/) 元素的实例
## 备注



示例： 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathDelimiter](../../imathdelimiter/)
* 类 [IMathBlock](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)