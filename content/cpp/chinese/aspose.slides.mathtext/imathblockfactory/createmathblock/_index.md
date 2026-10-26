---
title: CreateMathBlock()
second_title: Aspose.Slides C++ API 参考
description: 创建数学块
type: docs
weight: 1
url: /zh/aspose.slides.mathtext/imathblockfactory/createmathblock/
---
## IMathBlockFactory::CreateMathBlock() 方法


创建数学块

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock()=0
```


### 返回值

新的数学块

## IMathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElement\>) 方法


创建数学块并将元素放入其中

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElement> mathElement)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 数学元素 |

### 返回值

新的数学块

## IMathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElementCollection\>) 方法


创建数学块并将多个元素放入其中

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElementCollection> mathElements)=0
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
* 类 [IMathBlockFactory](../)
* 类 [IMathElement](../../imathelement/)
* 类 [IMathElementCollection](../../imathelementcollection/)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)