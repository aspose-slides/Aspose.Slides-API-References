---
title: Enclose()
second_title: Aspose.Slides for C++ API 参考
description: 将数学元素用指定字符（如括号或其他字符）进行框定
type: docs
weight: 170
url: /zh/aspose.slides.mathtext/mathdelimiter/enclose/
---
## MathDelimiter::Enclose(char16_t, char16_t) 方法

将数学元素用指定字符（例如括号或其他字符）包裹起来

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathDelimiter::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| beginningCharacter | char16_t | 起始字符（通常为左括号） |
| endingCharacter | char16_t | 结束字符（通常为右括号） |

### 返回值

如果 *beginningCharacter* 和 *endingCharacter* 为 null，则仅为相应属性分配值，不会创建新对象（返回此实例）。否则，返回类型为 Delimiter 的新数学元素，其中包含指定字符作为框架，并在其中嵌套此 [MathDelimiter](../) 实例。

## 备注



示例：
```cpp
auto innerDelimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u",y"))->Enclose(u'{', u'}');
auto outerDelimiter = innerDelimiter->Enclose(u'[', u']');
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathDelimiter](../../imathdelimiter/)
* 类 [MathDelimiter](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)