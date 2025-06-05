---  
title: SlideCollection
second_title: Aspose.Sildes for .NET API Reference  
description: 表示幻灯片的集合。
type: docs
weight: 9660  
url: /zh/aspose.slides/slidecollection/
---  

## SlideCollection class  

表示幻灯片的集合。  

```csharp  
public sealed class SlideCollection : DomObject<Presentation>, ISlideCollection  
```  

## Properties  

| 名称 | 描述 |  
| --- | --- |  
| [Count](../../aspose.slides/slidecollection/count) { get; } | 获取集合中实际包含的元素数量。只读 Int32。 |  
| [IsSynchronized](../../aspose.slides/slidecollection/issynchronized) { get; } | 返回一个值，指示对集合的访问是否是同步的（线程安全的）。只读 Boolean。 |  
| [Item](../../aspose.slides/slidecollection/item) { get; } | 获取指定索引处的元素。只读 [`Slide`](../slide)。 |  
| [SyncRoot](../../aspose.slides/slidecollection/syncroot) { get; } | 返回同步根。只读 Object。 |  

## Methods  

| 名称 | 描述 |  
| --- | --- |  
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone)(ISlide) | 将指定幻灯片的副本添加到集合的末尾。 |  
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | 将指定幻灯片的副本添加到集合的末尾。 |  
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_3)(ISlide, ISection) | 将指定幻灯片的副本添加到指定部分的末尾。 |  
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | 将指定源幻灯片的副本添加到集合的末尾。将自动从指定的母版选择合适的布局（合适的布局是与源幻灯片的布局具有相同类型或名称的布局）。如果没有合适的布局，则将克隆源幻灯片的布局（如果allowCloneMissingLayout为true）或抛出PptxEditException（如果allowCloneMissingLayout为false）。 |  
| [AddEmptySlide](../../aspose.slides/slidecollection/addemptyslide)(ILayoutSlide) | 在集合的末尾添加一个新的空白幻灯片。 |  
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml)(Stream) | 从HTML文本中创建幻灯片并将其添加到集合的末尾。 |  
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_4)(string) | 从HTML文本中创建幻灯片并将其添加到集合的末尾。 |  
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_2)(TextReader) | 从HTML文本中创建幻灯片并将其添加到集合的末尾。 |  
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | 从HTML文本中创建幻灯片并将其添加到集合的末尾。 |  
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | 从HTML文本中创建幻灯片并将其添加到集合的末尾。 |  
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | 从HTML文本中创建幻灯片并将其添加到集合的末尾。 |  
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf)(Stream) | 从PDF文档中创建幻灯片并将其添加到集合的末尾。 |  
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_2)(string) | 从PDF文档中创建幻灯片并将其添加到集合的末尾。 |  
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | 从PDF文档中创建幻灯片并将其添加到集合的末尾。 |  
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | 从PDF文档中创建幻灯片并将其添加到集合的末尾，考虑到PDF导入选项。 |  
| [CopyTo](../../aspose.slides/slidecollection/copyto)(Array, int) | 将集合中的所有元素复制到指定数组。 |  
| [GetEnumerator](../../aspose.slides/slidecollection/getenumerator)() | 返回一个枚举器，该枚举器遍历集合。 |  
| [IndexOf](../../aspose.slides/slidecollection/indexof)(ISlide) | 返回指定幻灯片在集合中的索引。 |  
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone)(int, ISlide) | 将指定幻灯片的副本插入到集合的指定位置。 |  
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | 将指定幻灯片的副本插入到集合的指定位置。 |  
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | 将指定源幻灯片的副本插入到集合的指定位置。将自动从指定的母版选择合适的布局（合适的布局是与源幻灯片的布局具有相同类型或名称的布局）。如果没有合适的布局，则将克隆源幻灯片的布局（如果allowCloneMissingLayout为true）或抛出PptxEditException（如果allowCloneMissingLayout为false）。 |  
| [InsertEmptySlide](../../aspose.slides/slidecollection/insertemptyslide)(int, ILayoutSlide) | 将指定幻灯片的副本插入到集合的指定位置。 |  
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml)(int, Stream) | 从HTML文本中创建幻灯片并将其插入到集合的指定位置。 |  
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_6)(int, string) | 从HTML文本中创建幻灯片并将其插入到集合的指定位置。 |  
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | 从HTML文本中创建幻灯片并将其插入到集合的指定位置。 |  
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | 从HTML文本中创建幻灯片并将其插入到集合的指定位置。 |  
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | 从HTML文本中创建幻灯片并将其插入到集合的指定位置。 |  
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | 从HTML文本中创建幻灯片并将其插入到集合的指定位置。 |  
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | 从HTML文本中创建幻灯片并将其插入到集合的指定位置。 |  
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | 从HTML文本中创建幻灯片并将其插入到集合的指定位置。 |  
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | 从HTML文本中创建幻灯片并将其插入到集合的指定位置。 |  
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | 从HTML文本中创建幻灯片并将其插入到集合的指定位置。 |  
| [Remove](../../aspose.slides/slidecollection/remove)(ISlide) | 从集合中删除特定对象的第一次出现。 |  
| [RemoveAt](../../aspose.slides/slidecollection/removeat)(int) | 删除集合中指定索引处的元素。 |  
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder)(int, ISlide) | 将幻灯片从集合移动到指定位置。 |  
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder_1)(int, params ISlide[]) | 将幻灯片从集合移动到指定位置。幻灯片将根据在列表中出现的顺序，从索引开始放置。 |  
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray)() | 创建并返回一个包含所有幻灯片的数组。 |  
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray_1)(int, int) | 创建并返回一个包含指定范围内所有幻灯片的数组。要添加的第一张幻灯片的索引。要添加的幻灯片数量。 |  

### See Also  

* class [DomObject&lt;TParent&gt;](../domobject-1)  
* class [Presentation](../presentation)  
* interface [ISlideCollection](../islidecollection)  
* namespace [Aspose.Slides](../../aspose.slides)  
* assembly [Aspose.Slides](../../)  

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->  