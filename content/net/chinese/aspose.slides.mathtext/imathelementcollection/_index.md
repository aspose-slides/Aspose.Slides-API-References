---
title: IMathElementCollection
second_title: Aspose.Sildes for .NET API Reference
description: 表示数学元素 MathElement 的集合。
type: docs
weight: 7990
url: /zh/aspose.slides.mathtext/imathelementcollection/
---

## IMathElementCollection 接口

表示数学元素（MathElement）的集合。

```csharp
public interface IMathElementCollection : IEnumerable<IMathElement>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AsIEnumerable](../../aspose.slides.mathtext/imathelementcollection/asienumerable) { get; } | 返回 IEnumerable 接口。只读 IEnumerable。 |
| [Count](../../aspose.slides.mathtext/imathelementcollection/count) { get; } | 获取集合中实际包含的元素数量。只读 Int32。 |
| [Item](../../aspose.slides.mathtext/imathelementcollection/item) { get; } | 获取指定索引处的元素。只读 [`IMathElement`](../imathelement)。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Add](../../aspose.slides.mathtext/imathelementcollection/add)(IMathElement) | 将数学元素添加到集合的末尾。 |
| [Clear](../../aspose.slides.mathtext/imathelementcollection/clear)() | 从集合中移除所有元素。 |
| [Contains](../../aspose.slides.mathtext/imathelementcollection/contains)(IMathElement) | 确定集合中是否包含特定值。 |
| [CopyTo](../../aspose.slides.mathtext/imathelementcollection/copyto)(IMathElement[], int) | 拷贝到指定数组。 |
| [IndexOf](../../aspose.slides.mathtext/imathelementcollection/indexof)(IMathElement) | 确定特定数学元素在集合中的索引。 |
| [Insert](../../aspose.slides.mathtext/imathelementcollection/insert)(int, IMathElement) | 在指定索引处将数学元素插入集合。 |
| [Remove](../../aspose.slides.mathtext/imathelementcollection/remove)(IMathElement) | 从集合中移除特定对象的第一次出现。 |
| [RemoveAt](../../aspose.slides.mathtext/imathelementcollection/removeat)(int) | 移除集合中指定索引处的元素。 |

### 示例

示例：

```csharp
[C#]
IMathElementCollection collection = new MathBlock();
```

### 另见

* 接口 [IMathElement](../imathelement)
* 命名空间 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->