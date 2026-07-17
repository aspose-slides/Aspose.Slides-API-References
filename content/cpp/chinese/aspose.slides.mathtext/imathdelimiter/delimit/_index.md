---
title: Delimit()
second_title: 适用于 C++ 的 Aspose.Slides API 参考
description: 使用指定的分隔符字符分隔参数
type: docs
weight: 144
url: /zh/aspose.slides.mathtext/imathdelimiter/delimit/
---
## IMathDelimiter::Delimit(char16_t) 方法

使用指定的分隔符字符分隔参数

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathDelimiter::Delimit(char16_t separatorCharacter)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| separatorCharacter | char16_t | 分隔符字符 |

### 返回值

在应用分隔符字符后返回此对象
## 备注



示例：
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->Delimit(u'|');
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathDelimiter](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)