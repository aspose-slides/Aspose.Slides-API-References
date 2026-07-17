---
title: MathBlock()
second_title: Aspose.Slides for C++ API 参考
description: 初始化 MathBlock 类的一个新实例。
type: docs
weight: 66
url: /zh/aspose.slides.mathtext/mathblock/mathblock/
---
## MathBlock::MathBlock() 构造函数

初始化 [MathBlock](../) 类的一个新实例。

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock()
```

## 备注

示例：
```cpp
auto mathBlock = System::MakeObject<MathBlock>();
```

## MathBlock::MathBlock(System::SharedPtr\<IMathElement\>) 构造函数

创建一个新的数学块并将指定的元素放入其中

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<IMathElement> mathElement)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 要放入块中的数学元素 |
## 备注

示例：
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBlock::MathBlock(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<IMathElement\>\>\>) 构造函数

创建一个新的数学块并将指定的元素放入其中

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<IMathElement>>> mathElements)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\>\> | 要放入块中的数学元素 |
## 备注

示例：
```cpp
auto elems = System::MakeArray<System::SharedPtr<IMathElement>>({System::MakeObject<MathematicalText>(u"item1"), System::MakeObject<MathematicalText>(u"item2")});
auto mathBlock = System::MakeObject<MathBlock>(elems);
```

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [MathBlock](../)
* 类 [IMathElement](../../imathelement/)
* 类 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)