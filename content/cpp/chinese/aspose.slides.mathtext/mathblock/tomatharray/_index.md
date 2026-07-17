---
title: ToMathArray()
second_title: Aspose.Slides for C++ API 参考
description: 将子元素放入垂直数组
type: docs
weight: 235
url: /zh/aspose.slides.mathtext/mathblock/tomatharray/
---
## MathBlock::ToMathArray() 方法

将子元素放入垂直数组

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathBlock::ToMathArray() override
```

### 返回值

类型 [IMathArray](../../imatharray/) 的新实例

## 备注


示例：
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IMathArray](../../imatharray/)
* 类 [MathBlock](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)