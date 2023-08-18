---
title: SlideCollection
second_title: Aspose.Slides for .NET API 参考
description: 表示幻灯片的集合
type: docs
weight: 9190
url: /zh/aspose.slides/slidecollection/
---
## SlideCollection class

表示幻灯片的集合。

```csharp
public sealed class SlideCollection : DomObject<Presentation>, ISlideCollection
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Count](../../aspose.slides/slidecollection/count) { get; } | 获取集合中实际包含的元素数量。 只读Int32。 |
| [IsSynchronized](../../aspose.slides/slidecollection/issynchronized) { get; } | 返回一个值，指示对集合的访问是否同步（线程安全）。 只读Boolean。 |
| [Item](../../aspose.slides/slidecollection/item) { get; } | 获取指定索引处的元素。 只读[`Slide`](../slide)。 |
| [SyncRoot](../../aspose.slides/slidecollection/syncroot) { get; } | 返回同步根。 只读Object。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone)(ISlide) | 将指定幻灯片的副本添加到集合的末尾。 |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | 将指定幻灯片的副本添加到集合的末尾。 |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_3)(ISlide, ISection) | 将指定幻灯片的副本添加到指定部分的末尾。 |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | 将指定源幻灯片的副本添加到集合的末尾。 将自动从指定的 master 中选择适当的布局（适当的布局是与源幻灯片布局的 具有相同类型或名称的布局）。如果没有适当的布局，则源幻灯片的 布局将被克隆（如果 allowCloneMissingLayout 为真）或 PptxEditException 将被抛出（如果 allowCloneMissingLayout 是假的）。 |
| [AddEmptySlide](../../aspose.slides/slidecollection/addemptyslide)(ILayoutSlide) | 将新的空幻灯片添加到集合的末尾。 |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml)(Stream) | 从 HTML 文本创建幻灯片并将它们添加到集合的末尾。 |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_4)(string) | 从 HTML 文本创建幻灯片并将它们添加到集合的末尾。 |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_2)(TextReader) | 从 HTML 文本创建幻灯片并将它们添加到集合的末尾。 |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | 从 HTML 文本创建幻灯片并将它们添加到集合的末尾。 |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | 从 HTML 文本创建幻灯片并将它们添加到集合的末尾。 |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | 从 HTML 文本创建幻灯片并将它们添加到集合的末尾。 |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf)(Stream) | 从 PDF 文档创建幻灯片并将它们添加到集合的末尾。 |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_1)(string) | 从 PDF 文档创建幻灯片并将它们添加到集合的末尾。 |
| [CopyTo](../../aspose.slides/slidecollection/copyto)(Array, int) | 将集合中的所有元素复制到指定的数组。 |
| [GetEnumerator](../../aspose.slides/slidecollection/getenumerator)() | 返回一个遍历集合的枚举器。 |
| [IndexOf](../../aspose.slides/slidecollection/indexof)(ISlide) | 返回集合中指定幻灯片的索引。 |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone)(int, ISlide) | 将指定幻灯片的副本插入到集合的指定位置。 |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | 将指定幻灯片的副本插入到集合的指定位置。 |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | 将指定源幻灯片的副本插入到集合的指定位置。 将自动从指定的 master 中选择适当的布局（适当的布局是与源幻灯片布局的 具有相同类型或名称的布局）。如果没有适当的布局，则源幻灯片的 布局将被克隆（如果 allowCloneMissingLayout 为真）或 PptxEditException 将被抛出（如果 allowCloneMissingLayout 是假的）。 |
| [InsertEmptySlide](../../aspose.slides/slidecollection/insertemptyslide)(int, ILayoutSlide) | 将指定幻灯片的副本插入到集合的指定位置。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml)(int, Stream) | 从 HTML 文本创建幻灯片并将它们插入到指定位置的集合中。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_4)(int, string) | 从 HTML 文本创建幻灯片并将它们插入到指定位置的集合中。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_2)(int, TextReader) | 从 HTML 文本创建幻灯片并将它们插入到指定位置的集合中。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | 从 HTML 文本创建幻灯片并将它们插入到指定位置的集合中。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_5)(int, string, IExternalResourceResolver, string) | 从 HTML 文本创建幻灯片并将它们插入到指定位置的集合中。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_3)(int, TextReader, IExternalResourceResolver, string) | 从 HTML 文本创建幻灯片并将它们插入到指定位置的集合中。 |
| [Remove](../../aspose.slides/slidecollection/remove)(ISlide) | 从集合中删除特定对象的第一个匹配项。 |
| [RemoveAt](../../aspose.slides/slidecollection/removeat)(int) | 移除集合指定索引处的元素。 |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder)(int, ISlide) | 将幻灯片从集合移动到指定位置。 |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder_1)(int, params ISlide[]) | 将幻灯片从集合移动到指定位置。 幻灯片将从索引开始放置，以便它们出现在列表中。 |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray)() | 创建并返回一个包含所有幻灯片的数组。 |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray_1)(int, int) | 创建并返回一个数组，其中包含指定范围内的所有幻灯片。  要添加的第一张幻灯片的索引。 要添加的幻灯片数量。 |

### 也可以看看

* class [DomObject&lt;TParent&gt;](../domobject-1)
* class [Presentation](../presentation)
* interface [ISlideCollection](../islidecollection)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
