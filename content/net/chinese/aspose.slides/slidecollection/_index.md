---
title: SlideCollection
second_title: Aspose.Sildes for .NET API 参考
description: 表示幻灯片的集合。
type: docs
weight: 9990
url: /zh/aspose.slides/slidecollection/
---
## SlideCollection 类

表示幻灯片的集合。

```csharp
public sealed class SlideCollection : DomObject<Presentation>, ISlideCollection
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Count](../../aspose.slides/slidecollection/count) { get; } | 获取集合中实际包含的元素数量。只读 Int32。 |
| [IsSynchronized](../../aspose.slides/slidecollection/issynchronized) { get; } | 返回一个值，指示对集合的访问是否已同步（线程安全）。只读 Boolean。 |
| [Item](../../aspose.slides/slidecollection/item) { get; } | 获取指定索引处的元素。只读 [`Slide`](../slide)。 |
| [SyncRoot](../../aspose.slides/slidecollection/syncroot) { get; } | 返回同步根。只读 Object。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone)(ISlide) | 向集合末尾添加指定幻灯片的副本。 |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | 向集合末尾添加指定幻灯片的副本。 |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_3)(ISlide, ISection) | 向指定章节的末尾添加指定幻灯片的副本。 |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | 向集合末尾添加指定源幻灯片的副本。将自动从指定的母版中选择适当的布局（适当的布局是与源幻灯片布局具有相同 Type 或 Name 的布局）。如果没有适当的布局，则会克隆源幻灯片的布局（如果 allowCloneMissingLayout 为 true），否则将抛出 PptxEditException（如果 allowCloneMissingLayout 为 false）。 |
| [AddEmptySlide](../../aspose.slides/slidecollection/addemptyslide)(ILayoutSlide) | 向集合末尾添加一个新的空幻灯片。 |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml)(Stream) | 从 HTML 文本创建幻灯片并将其添加到集合末尾。 |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_4)(string) | 从 HTML 文本创建幻灯片并将其添加到集合末尾。 |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_2)(TextReader) | 从 HTML 文本创建幻灯片并将其添加到集合末尾。 |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | 从 HTML 文本创建幻灯片并将其添加到集合末尾。 |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | 从 HTML 文本创建幻灯片并将其添加到集合末尾。 |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | 从 HTML 文本创建幻灯片并将其添加到集合末尾。 |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf)(Stream) | 从 PDF 文档创建幻灯片并将其添加到集合末尾。 |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_2)(string) | 从 PDF 文档创建幻灯片并将其添加到集合末尾。 |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | 从 PDF 文档创建幻灯片并将其添加到集合末尾。 |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | 在考虑 PDF 导入选项的情况下，从 PDF 文档创建幻灯片并将其添加到集合末尾。 |
| [CopyTo](../../aspose.slides/slidecollection/copyto)(Array, int) | 将集合中的所有元素复制到指定的数组。 |
| [GetEnumerator](../../aspose.slides/slidecollection/getenumerator)() | 返回一个遍历集合的枚举器。 |
| [IndexOf](../../aspose.slides/slidecollection/indexof)(ISlide) | 返回指定幻灯片在集合中的索引。 |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone)(int, ISlide) | 在集合的指定位置插入指定幻灯片的副本。 |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | 在集合的指定位置插入指定幻灯片的副本。 |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | 在集合的指定位置插入指定源幻灯片的副本。将自动从指定的母版中选择适当的布局（适当的布局是与源幻灯片布局具有相同 Type 或 Name 的布局）。如果没有适当的布局，则会克隆源幻灯片的布局（如果 allowCloneMissingLayout 为 true），否则将抛出 PptxEditException（如果 allowCloneMissingLayout 为 false）。 |
| [InsertEmptySlide](../../aspose.slides/slidecollection/insertemptyslide)(int, ILayoutSlide) | 在集合的指定位置插入指定幻灯片的副本。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml)(int, Stream) | 从 HTML 文本创建幻灯片并将其插入到集合的指定位置。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_6)(int, string) | 从 HTML 文本创建幻灯片并将其插入到集合的指定位置。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | 从 HTML 文本创建幻灯片并将其插入到集合的指定位置。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | 从 HTML 文本创建幻灯片并将其插入到集合的指定位置。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | 从 HTML 文本创建幻灯片并将其插入到集合的指定位置。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | 从 HTML 文本创建幻灯片并将其插入到集合的指定位置。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | 从 HTML 文本创建幻灯片并将其插入到集合的指定位置。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | 从 HTML 文本创建幻灯片并将其插入到集合的指定位置。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | 从 HTML 文本创建幻灯片并将其插入到集合的指定位置。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | 从 HTML 文本创建幻灯片并将其插入到集合的指定位置。 |
| [Remove](../../aspose.slides/slidecollection/remove)(ISlide) | 从集合中移除指定对象的第一次出现。 |
| [RemoveAt](../../aspose.slides/slidecollection/removeat)(int) | 移除集合中指定索引处的元素。 |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder)(int, ISlide) | 将幻灯片从集合中移动到指定位置。 |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder_1)(int, params ISlide[]) | 将幻灯片从集合中移动到指定位置。幻灯片将从索引开始按照它们在列表中出现的顺序放置。 |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray)() | 创建并返回包含所有幻灯片的数组。 |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray_1)(int, int) | 创建并返回包含指定范围内所有幻灯片的数组。第一个要添加的幻灯片的索引。要添加的幻灯片数量。 |

### 另请参见

* 类 [DomObject&lt;TParent&gt;](../domobject-1)
* 类 [Presentation](../presentation)
* 接口 [ISlideCollection](../islidecollection)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->