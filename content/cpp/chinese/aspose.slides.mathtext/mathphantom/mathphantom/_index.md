---
title: MathPhantom()
second_title: Aspose.Slides C++ API 参考
description: 使用指定的基本数学元素初始化 MathPhantom 类的新实例。
type: docs
weight: 144
url: /zh/aspose.slides.mathtext/mathphantom/mathphantom/
---
## MathPhantom::MathPhantom(System::SharedPtr\<IMathElement\>) 构造函数


使用指定的基本数学元素初始化 [MathPhantom](../) 类的新实例。

```cpp
Aspose::Slides::MathText::MathPhantom::MathPhantom(System::SharedPtr<IMathElement> element)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 基础 [IMathElement](../../imathelement/)，其可见性和布局将由 phantom 控制。该元素定义可能被隐藏或显示的内容，同时仍影响周围数学的几何对齐。 |
## 备注



phantom 元素用于保留或抑制其基础表达式的视觉空间，而不一定显示它。它对应 OMML 元素 **<m:phant>**。 

示例： 
```cpp
System::SharedPtr<IMathElement> fraction = System::MakeObject<MathFraction>(
    System::MakeObject<MathematicalText>(u"1"),
    System::MakeObject<MathematicalText>(u"2"));
```

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IMathElement](../../imathelement/)
* 类 [MathPhantom](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)