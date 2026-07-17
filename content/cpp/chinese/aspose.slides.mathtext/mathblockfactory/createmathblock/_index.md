---
title: CreateMathBlock()
second_title: Aspose.Slides for C++ API 参考
description: 创建数学块
type: docs
weight: 1
url: /zh/aspose.slides.mathtext/mathblockfactory/createmathblock/
---
## MathBlockFactory::CreateMathBlock() 方法

创建数学块

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock() override
```

### 返回值

新的数学块

## MathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElement\>) 方法

创建数学块并将元素放入其中

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElement> mathElement) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 数学元素 |

### 返回值

新的数学块

## MathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElementCollection\>) 方法

创建数学块并将元素放入其中

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElementCollection> mathElements) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElementCollection](../../imathelementcollection/)\> | 数学元素 |

### 返回值

新的数学块

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathBlock](../../imathblock/)
* 类 [MathBlockFactory](../)
* 类 [IMathElement](../../imathelement/)
* 类 [IMathElementCollection](../../imathelementcollection/)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)