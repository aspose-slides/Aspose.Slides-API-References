---
title: MasterSlideCollection
second_title: Aspose.Slides for .NET API 参考
description: 表示母版幻灯片的集合
type: docs
weight: 7330
url: /zh/net/aspose.slides/masterslidecollection/
---
## MasterSlideCollection class

表示母版幻灯片的集合。

```csharp
public sealed class MasterSlideCollection : DomObject<Presentation>, IMasterSlideCollection
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Count](../../aspose.slides/masterslidecollection/count) { get; } | 获取集合中实际包含的元素数量。 只读Int32。 |
| [IsSynchronized](../../aspose.slides/masterslidecollection/issynchronized) { get; } | 返回一个值，指示对集合的访问是否同步（线程安全）。 只读Boolean。 |
| [Item](../../aspose.slides/masterslidecollection/item) { get; } | 获取指定索引处的元素。 只读[`MasterSlide`](../masterslide)。 |
| [SyncRoot](../../aspose.slides/masterslidecollection/syncroot) { get; } | 返回同步根。 只读Object。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddClone](../../aspose.slides/masterslidecollection/addclone)(IMasterSlide) | 将指定母版幻灯片的副本添加到集合的末尾。 链接的布局幻灯片也将被复制。 |
| [CopyTo](../../aspose.slides/masterslidecollection/copyto)(Array, int) | 将集合中的所有元素复制到指定的数组。 |
| [GetEnumerator](../../aspose.slides/masterslidecollection/getenumerator)() | 返回一个遍历集合的枚举器。 |
| [InsertClone](../../aspose.slides/masterslidecollection/insertclone)(int, IMasterSlide) | 将指定母版幻灯片的副本插入到集合的指定位置。 链接的布局幻灯片也将被复制。 |
| [Remove](../../aspose.slides/masterslidecollection/remove)(IMasterSlide) | 从集合中删除特定对象的第一个匹配项。 |
| [RemoveAt](../../aspose.slides/masterslidecollection/removeat)(int) | 移除集合指定索引处的元素。 |
| [RemoveUnused](../../aspose.slides/masterslidecollection/removeunused)(bool) | 删除未使用的母版幻灯片。 |

### 也可以看看

* class [DomObject&lt;TParent&gt;](../domobject-1)
* class [Presentation](../presentation)
* interface [IMasterSlideCollection](../imasterslidecollection)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->