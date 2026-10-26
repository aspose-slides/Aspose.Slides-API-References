---
title: ISlideCollection
second_title: Aspose.Sildes for .NET API 参考
description: 表示一个幻灯片集合。
type: docs
weight: 7050
url: /zh/aspose.slides/islidecollection/
---
## ISlideCollection 接口

表示一个幻灯片集合。

```csharp
public interface ISlideCollection : IGenericCollection<ISlide>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Item](../../aspose.slides/islidecollection/item) { get; } | 获取指定索引处的元素。只读 [`ISlide`](../islide)。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone)(ISlide) | 将指定幻灯片的副本添加到集合的末尾。 |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | 将指定幻灯片的副本添加到集合的末尾。 |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_3)(ISlide, ISection) | 将指定幻灯片的副本添加到指定章节的末尾。 |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | 将指定源幻灯片的副本添加到集合的末尾。将自动从指定的母版中选择合适的版式（合适的版式是与源幻灯片的版式具有相同类型或名称的版式）。如果没有合适的版式，则会克隆源幻灯片的版式（如果 allowCloneMissingLayout 为 true）或抛出 PptxEditException（如果 allowCloneMissingLayout 为 false）。 |
| [AddEmptySlide](../../aspose.slides/islidecollection/addemptyslide)(ILayoutSlide) | 在集合末尾添加一个新的空白幻灯片。 |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml)(Stream) | 从 HTML 文本创建幻灯片并将它们添加到集合的末尾。 |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_4)(string) | 从 HTML 文本创建幻灯片并将它们添加到集合的末尾。 |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_2)(TextReader) | 从 HTML 文本创建幻灯片并将它们添加到集合的末尾。 |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | 从 HTML 文本创建幻灯片并将它们添加到集合的末尾。 |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | 从 HTML 文本创建幻灯片并将它们添加到集合的末尾。 |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | 从 HTML 文本创建幻灯片并将它们添加到集合的末尾。 |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf)(Stream) | 从 PDF 文档创建幻灯片并将它们添加到集合的末尾。 |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_2)(string) | 从 PDF 文档创建幻灯片并将它们添加到集合的末尾。 |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | 从 PDF 文档创建幻灯片并将它们添加到集合的末尾。 |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | 根据 PDF 导入选项，从 PDF 文档创建幻灯片并将它们添加到集合的末尾。 |
| [IndexOf](../../aspose.slides/islidecollection/indexof)(ISlide) | 返回指定幻灯片在集合中的索引。 |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone)(int, ISlide) | 在集合的指定位置插入指定幻灯片的副本。 |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | 在集合的指定位置插入指定幻灯片的副本。 |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | 在集合的指定位置插入指定源幻灯片的副本。将自动从指定的母版中选择合适的版式（合适的版式是与源幻灯片的版式具有相同类型或名称的版式）。如果没有合适的版式，则会克隆源幻灯片的版式（如果 allowCloneMissingLayout 为 true）或抛出 PptxEditException（如果 allowCloneMissingLayout 为 false）。 |
| [InsertEmptySlide](../../aspose.slides/islidecollection/insertemptyslide)(int, ILayoutSlide) | 在集合的指定位置插入指定幻灯片的副本。 |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml)(int, Stream) | 从 HTML 文本创建幻灯片并将其插入到集合的指定位置。 |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_6)(int, string) | 从 HTML 文本创建幻灯片并将其插入到集合的指定位置。 |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | 从 HTML 文本创建幻灯片并将其插入到集合的指定位置。 |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | 从 HTML 文本创建幻灯片并将其插入到集合的指定位置。 |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | 从 HTML 文本创建幻灯片并将其插入到集合的指定位置。 |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | 从 HTML 文本创建幻灯片并将其插入到集合的指定位置。 |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | 从 HTML 文本创建幻灯片并将其插入到集合的指定位置。 |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | 从 HTML 文本创建幻灯片并将其插入到集合的指定位置。 |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | 从 HTML 文本创建幻灯片并将其插入到集合的指定位置。 |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | 从 HTML 文本创建幻灯片并将其插入到集合的指定位置。 |
| [Remove](../../aspose.slides/islidecollection/remove)(ISlide) | 从集合中移除第一次出现的指定对象。 |
| [RemoveAt](../../aspose.slides/islidecollection/removeat)(int) | 移除集合中指定索引处的元素。 |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder)(int, ISlide) | 将幻灯片从集合中移动到指定位置。 |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder_1)(int, params ISlide[]) | 将幻灯片从集合中移动到指定位置。幻灯片将从该索引开始按它们在列表中出现的顺序放置。 |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray)() | 创建并返回包含所有幻灯片的数组。 |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray_1)(int, int) | 创建并返回包含指定范围内所有幻灯片的数组。 |

### 另请参阅

* 接口 [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* 接口 [ISlide](../islide)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->