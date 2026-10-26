---
title: SlideCollection
second_title: Aspose.Slides for Java API 参考
description: 表示一组幻灯片。
type: docs
url: /zh/com.aspose.slides/slidecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ISlideCollection](../../com.aspose.slides/islidecollection)
```
public final class SlideCollection extends DomObject<Presentation> implements ISlideCollection
```

表示一组幻灯片。

## 方法

| 方法 | 描述 |
| --- | --- |
| [size()](#size--) | 获取集合中实际包含的元素数量。 |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | 将指定幻灯片的副本添加到集合的末尾。 |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | 将指定幻灯片的副本添加到指定章节的末尾。 |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | 在集合的指定位置插入指定幻灯片的副本。 |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | 在集合的末尾添加一个新的空幻灯片。 |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | 在集合的指定位置插入指定幻灯片的副本。 |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | 将指定幻灯片的副本添加到集合的末尾。 |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | 在集合的指定位置插入指定幻灯片的副本。 |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | 将指定源幻灯片的副本添加到集合的末尾。 |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | 在集合的指定位置插入指定源幻灯片的副本。 |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | 从集合中移除第一次出现的特定对象。 |
| [removeAt(int index)](#removeAt-int-) | 移除集合中指定索引处的元素。 |
| [iterator()](#iterator--) | 返回遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 Java 迭代器。 |
| [toArray()](#toArray--) | 创建并返回包含所有幻灯片的数组。 |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 创建并返回包含指定范围内所有幻灯片的数组。 |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | 将幻灯片从集合移动到指定位置。 |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | 将幻灯片从集合移动到指定位置。 |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | 返回指定幻灯片在集合中的索引。 |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | 从 PDF 文档创建幻灯片并将其添加到集合的末尾。 |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | 在考虑 PDF 导入选项的情况下，从 PDF 文档创建幻灯片并将其添加到集合的末尾。 |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | 从 PDF 文档创建幻灯片并将其添加到集合的末尾。 |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | 从 PDF 文档创建幻灯片并将其添加到集合的末尾。 |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 从 HTML 文本创建幻灯片并将其添加到集合的末尾。 |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | 从 HTML 文本创建幻灯片并将其添加到集合的末尾。 |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 从 HTML 文本创建幻灯片并将其添加到集合的末尾。 |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | 从 HTML 文本创建幻灯片并将其添加到集合的末尾。 |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 从 HTML 文本创建幻灯片并在集合的指定位置插入它们。 |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | 从 HTML 文本创建幻灯片并在集合的指定位置插入它们。 |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | 从 HTML 文本创建幻灯片并在集合的指定位置插入它们。 |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | 从 HTML 文本创建幻灯片并在集合的指定位置插入它们。 |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 从 HTML 文本创建幻灯片并在集合的指定位置插入它们。 |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | 从 HTML 文本创建幻灯片并在集合的指定位置插入它们。 |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | 从 HTML 文本创建幻灯片并在集合的指定位置插入它们。 |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | 从 HTML 文本创建幻灯片并在集合的指定位置插入它们。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 将集合中的所有元素复制到指定数组。 |
| [isSynchronized()](#isSynchronized--) | 返回指示对集合的访问是否同步（线程安全）的值。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |

### size() {#size--}
```
public final int size()
```

获取集合中实际包含的元素数量。只读 int。

**返回值:**
int

### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

获取指定索引处的元素。只读 [Slide](../../com.aspose.slides/slide)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回值:**
[ISlide](../../com.aspose.slides/islide)

### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public final ISlide addClone(ISlide sourceSlide)
```

将指定幻灯片的副本添加到集合的末尾。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要克隆的幻灯片。 |

--------------------

当在不同演示文稿之间克隆幻灯片时，幻灯片的母版也可能被克隆。内部注册表用于跟踪自动克隆的母版，以防止同一母版幻灯片被多次克隆。手动克隆母版幻灯片既不会被阻止也不会被注册。如果需要更细致地控制克隆过程，请使用 \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) 或 \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) 来克隆幻灯片，[IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) 或 [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) 来克隆布局，[IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) 来克隆母版。 |

**返回值:**
[ISlide](../../com.aspose.slides/islide) - 新幻灯片。

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public final ISlide addClone(ISlide sourceSlide, ISection section)
```

将指定幻灯片的副本添加到指定章节的末尾。

--------------------

> ```
> IPresentation presentation = new Presentation();
>  try
>  {
>      presentation.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 50, 300, 100);
>      presentation.getSections().addSection("Section 1", presentation.getSlides().get_Item(0));
>      
>      ISection section2 = presentation.getSections().appendEmptySection("Section 2");
>      presentation.getSlides().addClone(presentation.getSlides().get_Item(0), section2);
>      
>      // 现在第二个章节包含了第一张幻灯片的副本。
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要克隆的幻灯片。 |
| section | [ISection](../../com.aspose.slides/isection) | 新幻灯片所属的章节。 |

**返回值:**
[ISlide](../../com.aspose.slides/islide) - 新幻灯片。

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide)
```

在集合的指定位置插入指定幻灯片的副本。

--------------------

> ```
> The following example shows how to clone at another position within Presentation.
>  
>  // 实例化表示演示文稿文件的 Presentation 类
>  Presentation pres = new Presentation("CloneWithInSamePresentation.pptx");
>  try {
>      // 将所需幻灯片克隆到同一演示文稿中幻灯片集合的末尾
>      ISlideCollection slds = pres.getSlides();
>      // 将所需幻灯片克隆到同一演示文稿中的指定索引位置
>      slds.insertClone(2, pres.getSlides().get_Item(1));
>      // 将修改后的演示文稿写入磁盘
>      pres.save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to clone at another position within Presentation.
>  
>  // 实例化 Presentation 类以加载源演示文稿文件
>  Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx");
>  try {
>      // 实例化用于目标 PPTX 的 Presentation 类（要克隆幻灯片的目标文件）
>      Presentation destPres = new Presentation();
>      try {
>          ISlideCollection slds = destPres.getSlides();
>          slds.insertClone(2, srcPres.getSlides().get_Item(0));
>          // 将目标演示文稿写入磁盘
>          destPres.save("Aspose2_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```


**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 新幻灯片的索引。 |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要克隆的幻灯片。 |

--------------------

当在不同演示文稿之间克隆幻灯片时，幻灯片的母版也可能被克隆。内部注册表用于跟踪自动克隆的母版，以防止同一母版幻灯片被多次克隆。手动克隆母版幻灯片既不会被阻止也不会被注册。如果需要更细致地控制克隆过程，请使用 \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) 或 \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) 来克隆幻灯片，[IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) 来克隆母版。 |

**返回值:**
[ISlide](../../com.aspose.slides/islide) - 插入的幻灯片。

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addEmptySlide(ILayoutSlide layout)
```

在集合的末尾添加一个新的空幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 幻灯片的布局。 |

**返回值:**
[ISlide](../../com.aspose.slides/islide) - 已添加的幻灯片。

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

在集合的指定位置插入指定幻灯片的副本。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 新幻灯片的索引。 |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 幻灯片的布局。 |

**返回值:**
[ISlide](../../com.aspose.slides/islide) - 插入的幻灯片。

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

将指定幻灯片的副本添加到集合的末尾。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要克隆的幻灯片。 |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 新幻灯片使用的布局幻灯片。 |

**返回值:**
[ISlide](../../com.aspose.slides/islide) - 新幻灯片。

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

在集合的指定位置插入指定幻灯片的副本。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 新幻灯片的索引。 |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要克隆的幻灯片。 |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 新幻灯片使用的布局幻灯片。 |

**返回值:**
[ISlide](../../com.aspose.slides/islide) - 插入的幻灯片。

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

将指定源幻灯片的副本添加到集合的末尾。会自动从指定的母版中选择合适的布局（合适的布局是类型或名称与源幻灯片布局相同的布局）。如果在指定母版中不存在合适的布局，则会克隆源幻灯片的布局（如果 allowCloneMissingLayout 为 true），否则抛出 PptxEditException（如果 allowCloneMissingLayout 为 false）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要克隆的幻灯片。 |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 新幻灯片所属的母版幻灯片。 |
| allowCloneMissingLayout | boolean | 如果在指定母版中没有合适的布局，则克隆源幻灯片的布局（allowCloneMissingLayout 为 true）或抛出 PptxEditException（allowCloneMissingLayout 为 false）。 |

**返回值:**
[ISlide](../../com.aspose.slides/islide) - 新幻灯片。

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

在集合的指定位置插入指定源幻灯片的副本。会自动从指定的母版中选择合适的布局（合适的布局是类型或名称与源幻灯片布局相同的布局）。如果在指定母版中不存在合适的布局，则会克隆源幻灯片的布局（如果 allowCloneMissingLayout 为 true），否则抛出 PptxEditException（如果 allowCloneMissingLayout 为 false）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 新幻灯片的索引。 |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要克隆的幻灯片。 |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 新幻灯片所属的母版幻灯片。 |
| allowCloneMissingLayout | boolean | 如果在指定母版中没有合适的布局，则克隆源幻灯片的布局（allowCloneMissingLayout 为 true）或抛出 PptxEditException（allowCloneMissingLayout 为 false）。 |

**返回值:**
[ISlide](../../com.aspose.slides/islide) - 插入的幻灯片。

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public final void remove(ISlide value)
```

从集合中移除第一次出现的特定对象。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | 要从集合中移除的幻灯片。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

移除集合中指定索引处的元素。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的元素的零基索引。 |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

返回遍历集合的枚举器。

**返回值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - 可用于遍历集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

返回整个集合的 Java 迭代器。

**返回值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - 用于整个集合的 java.util.Iterator。

### toArray() {#toArray--}
```
public final ISlide[] toArray()
```

创建并返回包含所有幻灯片的数组。

**返回值:**
com.aspose.slides.ISlide[] - [Slide](../../com.aspose.slides/slide) 的数组

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final ISlide[] toArray(int startIndex, int count)
```

创建并返回包含指定范围内所有幻灯片的数组。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startIndex | int | 要添加的第一张幻灯片的索引。 |
| count | int | 要添加的幻灯片数量。 |

**返回值:**
com.aspose.slides.ISlide[] - [Slide](../../com.aspose.slides/slide) 的数组
### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public final void reorder(int index, ISlide slide)
```

将幻灯片从集合中移动到指定位置。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 目标索引。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 要移动的幻灯片。 |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public final void reorder(int index, ISlide[] slides)
```

将幻灯片从集合中移动到指定位置。幻灯片将从 index 开始按它们在列表中出现的顺序放置。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 目标索引。 |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | 要移动的幻灯片。 |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public final int indexOf(ISlide slide)
```

返回集合中指定幻灯片的索引。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | 要查找的幻灯片。 |

**返回：**
int - 幻灯片的索引；如果幻灯片不在此集合中则返回 -1。

### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public final ISlide[] addFromPdf(String path)
```

从 PDF 文档创建幻灯片并将它们添加到集合的末尾。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getSlides().addFromPdf("document.pdf");
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | java.lang.String | PDF 文档的路径 |

**返回：**
com.aspose.slides.ISlide[] - 已添加的幻灯片

### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

从 PDF 文档创建幻灯片并根据 PDF 导入选项将它们添加到集合的末尾。

--------------------

> ```
> 示例：
>  
>  Presentation pres = new Presentation();
>  try {
>      PdfImportOptions pdfImportOptions = new PdfImportOptions();
>      pdfImportOptions.setDetectTables(true);
>      pres.getSlides().addFromPdf("document.pdf", pdfImportOptions);
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | java.lang.String | PDF 文档的路径 |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | PDF 导入的选项 |

**返回：**
com.aspose.slides.ISlide[] - 已添加的幻灯片

### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public final ISlide[] addFromPdf(InputStream pdfStream)
```

从 PDF 文档创建幻灯片并将它们添加到集合的末尾。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream stream = new FileInputStream("document.pdf");
>      pres.getSlides().addFromPdf(stream);
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pdfStream | java.io.InputStream | 将用作 PDF 文档来源的流 |

**返回：**
com.aspose.slides.ISlide[] - 已添加的幻灯片

### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

从 PDF 文档创建幻灯片并将它们添加到集合的末尾。

--------------------

> ```
> 示例：
>  
>  Presentation pres = new Presentation();
>  try {
>      PdfImportOptions pdfImportOptions = new PdfImportOptions();
>      pdfImportOptions.setDetectTables(true);
> 
>      FileInputStream stream = new FileInputStream("document.pdf");
>      pres.getSlides().addFromPdf(stream, pdfImportOptions);
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pdfStream | java.io.InputStream | 将用作 PDF 文档来源的流 |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | PDF 导入的选项 |

**返回：**
com.aspose.slides.ISlide[] - 已添加的幻灯片

### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

从 HTML 文本创建幻灯片并将它们添加到集合的末尾。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| htmlText | java.lang.String | 要添加的 HTML。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用于获取外部对象的回调对象。如果此参数为 null，则所有外部对象将被忽略。 |
| uri | java.lang.String | 指定 HTML 的 URI。用于解析相对链接。 |

**返回：**
com.aspose.slides.ISlide[] - 已添加的幻灯片。

### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText)
```

从 HTML 文本创建幻灯片并将它们添加到集合的末尾。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| htmlText | java.lang.String | 要添加的 HTML。 |

**返回：**
com.aspose.slides.ISlide[] - 已添加的幻灯片

### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

从 HTML 文本创建幻灯片并将它们添加到集合的末尾。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| htmlStream | java.io.InputStream | 将用作 HTML 文件来源的流对象。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用于获取外部对象的回调对象。如果此参数为 null，则所有外部对象将被忽略。 |
| uri | java.lang.String | 指定 HTML 的 URI。用于解析相对链接。 |

**返回：**
com.aspose.slides.ISlide[] - 已添加的幻灯片。

### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public final ISlide[] addFromHtml(InputStream htmlStream)
```

从 HTML 文本创建幻灯片并将它们添加到集合的末尾。

--------------------

> ```
> // 创建 Presentation 类的实例。
>  Presentation pres = new Presentation();
>  try {
>      String html = new String(Files.readAllBytes(Paths.get("file.html")));
>      // 调用 AddFromHtml 方法并传入 HTML 文件。
>      pres.getSlides().addFromHtml(html);
>      // 使用 Save 方法将文件保存为 PowerPoint 文档。
>      pres.save("MyPresentation.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| htmlStream | java.io.InputStream | 将用作 HTML 文件来源的流对象。 |

**返回：**
com.aspose.slides.ISlide[] - 已添加的幻灯片

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

从 HTML 文本创建幻灯片并将它们插入到集合的指定位置。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入位置。 |
| htmlText | java.lang.String | 要添加的 HTML。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用于获取外部对象的回调对象。如果此参数为 null，则所有外部对象将被忽略。 |
| uri | java.lang.String | 指定 HTML 的 URI。用于解析相对链接。 |

**返回：**
com.aspose.slides.ISlide[] - 已添加的幻灯片。

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

从 HTML 文本创建幻灯片并将它们插入到集合的指定位置。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入位置。 |
| htmlText | java.lang.String | 要添加的 HTML。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用于获取外部对象的回调对象。如果此参数为 null，则所有外部对象将被忽略。 |
| uri | java.lang.String | 指定 HTML 的 URI。用于解析相对链接。 |
| useSlideWithIndexAsStart | boolean | 此标志确定插入的起始方式：从新幻灯片或从具有指定索引的幻灯片开始。如果 **true**，则数据插入将从具有指定索引的幻灯片上的空白处开始。如果 **false**，则数据将添加到新创建的幻灯片中。 |

**返回：**
com.aspose.slides.ISlide[] - 已添加的幻灯片。

### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText)
```

从 HTML 文本创建幻灯片并将它们插入到集合的指定位置。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入位置。 |
| htmlText | java.lang.String | 要添加的 HTML。 |

**返回：**
com.aspose.slides.ISlide[] - 已添加的幻灯片

### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

从 HTML 文本创建幻灯片并将它们插入到集合的指定位置。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入位置。 |
| htmlText | java.lang.String | 要添加的 HTML。 |
| useSlideWithIndexAsStart | boolean | 此标志确定插入的起始方式：从新幻灯片或从具有指定索引的幻灯片开始。如果 **true**，则数据插入将从具有指定索引的幻灯片上的空白处开始。如果 **false**，则数据将添加到新创建的幻灯片中。 |

**返回：**
com.aspose.slides.ISlide[] - 已添加的幻灯片

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

从 HTML 文本创建幻灯片并将它们插入到集合的指定位置。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入位置。 |
| htmlStream | java.io.InputStream | 将用作 HTML 文件来源的流对象。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用于获取外部对象的回调对象。如果此参数为 null，则所有外部对象将被忽略。 |
| uri | java.lang.String | 指定 HTML 的 URI。用于解析相对链接。 |

**返回：**
com.aspose.slides.ISlide[] - 已添加的幻灯片。

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

从 HTML 文本创建幻灯片并将它们插入到集合的指定位置。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入位置。 |
| htmlStream | java.io.InputStream | 将用作 HTML 文件来源的流对象。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用于获取外部对象的回调对象。如果此参数为 null，则所有外部对象将被忽略。 |
| uri | java.lang.String | 指定 HTML 的 URI。用于解析相对链接。 |
| useSlideWithIndexAsStart | boolean | 此标志确定插入的起始方式：从新幻灯片或从具有指定索引的幻灯片开始。如果 **true**，则数据插入将从具有指定索引的幻灯片上的空白处开始。如果 **false**，则数据将添加到新创建的幻灯片中。 |

**返回：**
com.aspose.slides.ISlide[] - 已添加的幻灯片。

### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

从 HTML 文本创建幻灯片并将它们插入到集合的指定位置。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入位置。 |
| htmlStream | java.io.InputStream | 将用作 HTML 文件来源的流对象。 |

**返回：**
com.aspose.slides.ISlide[] - 已添加的幻灯片

### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

从 HTML 文本创建幻灯片并将它们插入到集合的指定位置。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入位置。 |
| htmlStream | java.io.InputStream | 将用作 HTML 文件来源的流对象。 |
| useSlideWithIndexAsStart | boolean | 此标志确定插入的起始方式：从新幻灯片或从具有指定索引的幻灯片开始。如果 **true**，则数据插入将从具有指定索引的幻灯片上的空白处开始。如果 **false**，则数据将添加到新创建的幻灯片中。 |

**返回：**
com.aspose.slides.ISlide[] - 已添加的幻灯片

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

将集合中的所有元素复制到指定数组中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目标数组。 |
| index | int | 目标数组中的起始索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

返回一个值，指示对集合的访问是否已同步（线程安全）。只读布尔值。

**返回：**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回同步根。只读对象。

**返回：**
java.lang.Object