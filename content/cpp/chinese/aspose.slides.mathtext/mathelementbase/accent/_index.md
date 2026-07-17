---
title: Accent()
second_title: Aspose.Slides C++ API 参考
description: 设置重音标记（此元素顶部的字符）
type: docs
weight: 196
url: /zh/aspose.slides.mathtext/mathelementbase/accent/
---
## MathElementBase::Accent(char16_t) 方法

设置一个重音标记（此元素顶部的字符）

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathElementBase::Accent(char16_t accentCharacter) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| accentCharacter | char16_t | 重音字符。值应在 (U+0300\\u2013U+036F) 或 (U+20D0\\u2013U+20EF) 范围内。 |

### 返回值

类型为 [IMathAccent](../../imathaccent/) 的新实例

## 备注



示例：
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathAccent](../../imathaccent/)
* 类 [MathElementBase](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)