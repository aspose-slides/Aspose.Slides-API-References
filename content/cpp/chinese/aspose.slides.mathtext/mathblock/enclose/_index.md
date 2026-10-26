---
title: Enclose()
second_title: Aspose.Slides C++ API 参考
description: 将此块的子元素用指定字符（如括号或其他字符）进行框定
type: docs
weight: 222
url: /zh/aspose.slides.mathtext/mathblock/enclose/
---
## MathBlock::Enclose(char16_t, char16_t) 方法


将此块的子元素用指定字符（如括号或其他字符）包裹

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| beginningCharacter | char16_t | 开始字符（通常是左括号） |
| endingCharacter | char16_t | 结束字符（通常是右括号） |

### 返回值

类型为 [IMathDelimiter](../../imathdelimiter/) 的数学元素，包含指定字符作为框架
## 备注



示例： 
```cpp
auto block = System::MakeObject<MathematicalText>(u"x")->Join(u"+y");
auto delimiter = System::ExplicitCast<IMathElement>(block)->Enclose(u'[', u']');
```

## MathBlock::Enclose(char16_t, char16_t, char16_t) 方法


将此块的子元素用指定字符（如括号或其他字符）包裹，并使用分隔符字符分隔

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter) override
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| beginningCharacter | char16_t | 开始字符（通常是左括号） |
| endingCharacter | char16_t | 结束字符（通常是右括号） |
| separatorCharacter | char16_t | 分隔符字符 |

### 返回值

类型为 [IMathDelimiter](../../imathdelimiter/) 的数学元素，包含指定字符作为框架并带有分隔符
## 备注



示例： 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathDelimiter](../../imathdelimiter/)
* 类 [MathBlock](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)