---
title: ISlideCollection
second_title: Aspose.Slides for Android via Java API 参考
description: 表示一个幻灯片集合。
type: docs
url: /zh/com.aspose.slides/islidecollection/
---
**所有实现的接口：**
com.aspose.slides.IGenericCollection
```
public interface ISlideCollection extends IGenericCollection<ISlide>
```

表示一个幻灯片集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | 向集合的末尾添加指定幻灯片的副本。 |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | 向指定章节的末尾添加指定幻灯片的副本。 |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | 在集合的指定位置插入指定幻灯片的副本。 |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | 向集合的末尾添加一个新的空白幻灯片。 |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | 在集合的指定位置插入指定幻灯片的副本。 |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | 向集合的末尾添加指定幻灯片的副本。 |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | 在集合的指定位置插入指定幻灯片的副本。 |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | 向集合的末尾添加指定来源幻灯片的副本。 |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | 在集合的指定位置插入指定来源幻灯片的副本。 |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | 从集合中移除第一次出现的特定对象。 |
| [removeAt(int index)](#removeAt-int-) | 移除集合中指定索引处的元素。 |
| [toArray()](#toArray--) | 创建并返回包含所有幻灯片的数组。 |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 创建并返回包含指定范围内所有幻灯片的数组。 |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | 将幻灯片从集合中移动到指定位置。 |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | 将幻灯片从集合中移动到指定位置。 |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | 返回集合中指定幻灯片的索引。 |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | 从 PDF 文档创建幻灯片并将其添加到集合的末尾。 |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | 根据 PDF 导入选项，从 PDF 文档创建幻灯片并将其添加到集合的末尾。 |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | 从 PDF 文档创建幻灯片并将其添加到集合的末尾。 |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | 从 PDF 文档创建幻灯片并将其添加到集合的末尾。 |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 从 HTML 文本创建幻灯片并将其添加到集合的末尾。 |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | 从 HTML 文本创建幻灯片并将其添加到集合的末尾。 |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 从 HTML 文本创建幻灯片并将其添加到集合的末尾。 |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | 从 HTML 文本创建幻灯片并将其添加到集合的末尾。 |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 从 HTML 文本创建幻灯片并在集合的指定位置插入它们。 |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | 从 HTML 文本创建幻灯片并在集合的指定位置插入它们。 |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 从 HTML 文本创建幻灯片并在集合的指定位置插入它们。 |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | 从 HTML 文本创建幻灯片并在集合的指定位置插入它们。 |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | 从 HTML 文本创建幻灯片并在集合的指定位置插入它们。 |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | 从 HTML 文本创建幻灯片并在集合的指定位置插入它们。 |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | 从 HTML 文本创建幻灯片并在集合的指定位置插入它们。 |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | 从 HTML 文本创建幻灯片并在集合的指定位置插入它们。 |

### get_Item(int index) {#get-Item-int-}
```
public abstract ISlide get_Item(int index)
```

获取指定索引处的元素。只读 [ISlide](../../com.aspose.slides/islide)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回值：**
[ISlide](../../com.aspose.slides/islide)

### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public abstract ISlide addClone(ISlide sourceSlide)
```

向集合的末尾添加指定幻灯片的副本。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要克隆的幻灯片。 |

--------------------

在不同演示文稿之间克隆幻灯片时，幻灯片的母版也可以被克隆。内部注册表用于跟踪自动克隆的母版，以防止创建同一母版幻灯片的多个克隆。手动克隆母版幻灯片既不会被阻止也不会被注册。如果需要对克隆过程进行更细致的控制，请使用 \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) 或 \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) 来克隆幻灯片，[IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) 或 [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) 用于克隆布局，[IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) 用于克隆母版。

**返回值：**
[ISlide](../../com.aspose.slides/islide) - 新幻灯片。

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public abstract ISlide addClone(ISlide sourceSlide, ISection section)
```

向指定章节的末尾添加指定幻灯片的副本。

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
>      // 现在第二章节包含第一张幻灯片的副本。
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide to clone. |
| section | [ISection](../../com.aspose.slides/isection) | Section for a new slide. |

**Returns:**
[ISlide](../../com.aspose.slides/islide) - New slide.
### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide)
```

Inserts a copy of a specified slide to specified position of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of new slide. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide to clone.

--------------------

When cloning a slide between different presentations slide's master can be cloned too. Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide. Manual cloning of master slides will be neither prevented nor registered. If you need more control over cloning process use \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) or \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) for cloning slides and [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) for cloning masters. |

**Returns:**
[ISlide](../../com.aspose.slides/islide) - Inserted slide.
### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addEmptySlide(ILayoutSlide layout)
```

Adds a new empty slide to the end of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout for a slide. |

**Returns:**
[ISlide](../../com.aspose.slides/islide) - Added slide.
### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

Inserts a copy of a specified slide to specified position of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of a new slide. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout for a slide. |

**Returns:**
[ISlide](../../com.aspose.slides/islide) - Inserted slide.
### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

Adds a copy of a specified slide to the end of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide to clone. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout slide for a new slide. |

**Returns:**
[ISlide](../../com.aspose.slides/islide) - New slide.
### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

Inserts a copy of a specified slide to specified position of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of new slide. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide to clone. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout slide for a new slide. |

**Returns:**
[ISlide](../../com.aspose.slides/islide) - Inserted slide.
### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Adds a copy of a specified source slide to the end of the collection. Appropriate layout will be selected automatically from the specified master (appropriate layout is the layout with the same Type or Name as of layout of the source slide). If there is no appropriate layout then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide to clone. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slide for a new slide. |
| allowCloneMissingLayout | boolean | If there is no appropriate layout in specified master then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false). |

**Returns:**
[ISlide](../../com.aspose.slides/islide) - New slide.
### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Inserts a copy of a specified source slide to specified position of the collection. Appropriate layout will be selected automatically from the specified master (appropriate layout is the layout with the same Type or Name as of layout of the source slide). If there is no appropriate layout then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of new slide. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide to clone. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slide for a new slide. |
| allowCloneMissingLayout | boolean | If there is no appropriate layout in specified master then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false). |

**Returns:**
[ISlide](../../com.aspose.slides/islide) - Inserted slide.
### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public abstract void remove(ISlide value)
```

Removes the first occurrence of a specific object from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | The slide to remove from the collection. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Removes the element at the specified index of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element to remove. |

### toArray() {#toArray--}
```
public abstract ISlide[] toArray()
```

Creates and returns an array with all slides in it.

**Returns:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract ISlide[] toArray(int startIndex, int count)
```

Creates and returns an array with all slides from the specified range in it.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | An index of a first slide to add. |
| count | int | A number of slides to add. |

**Returns:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)
### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public abstract void reorder(int index, ISlide slide)
```

Moves slide from the collection to the specified position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Target index. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide to move. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public abstract void reorder(int index, ISlide[] slides)
```

Moves slides from the collection to the specified position. Slides will be placed starting from index in order they appear in list.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Target index. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | Slides to move. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public abstract int indexOf(ISlide slide)
```

Returns an index of the specified slide in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide to find. |

**Returns:**
int - Index of a slide or -1 if slide not from this collection.
### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public abstract ISlide[] addFromPdf(String path)
```

Creates slides from the PDF document and adds them to the end of the collection.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | A path to the PDF document |

**Returns:**
com.aspose.slides.ISlide[] - Added slides
### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

Creates slides from the PDF document and adds them to the end of the collection considering the pdf import options.

--------------------

> ```
> Example:
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | A path to the PDF document |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Options for pdf import |

**Returns:**
com.aspose.slides.ISlide[] - Added slides
### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

Creates slides from the PDF document and adds them to the end of the collection.

--------------------

> ```
> Example:
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdfStream | java.io.InputStream | A stream which will be used as a source of the PDF document |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Options for pdf import |

**Returns:**
com.aspose.slides.ISlide[] - Added slides
### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream)
```

Creates slides from the PDF document and adds them to the end of the collection.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdfStream | java.io.InputStream | A stream which will be used as a source of the PDF document |

**Returns:**
com.aspose.slides.ISlide[] - Added slides
### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

Creates slides from HTML text and adds them to the end of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlText | java.lang.String | Html to add. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | java.lang.String | An URI of the specified HTML. Used to resolve relative links. |

**Returns:**
com.aspose.slides.ISlide[] - Added slides.
### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText)
```

Creates slides from HTML text and adds them to the end of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlText | java.lang.String | Html to add. |

**Returns:**
com.aspose.slides.ISlide[] - Added slides
### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Creates slides from HTML text and adds them to the end of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlStream | java.io.InputStream | A Stream object which will be used as a source of a HTML file. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | java.lang.String | An URI of the specified HTML. Used to resolve relative links. |

**Returns:**
com.aspose.slides.ISlide[] - Added slides.
### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream)
```
Creates slides from HTML text and adds them to the end of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlStream | java.io.InputStream | A Stream object which will be used as a source of a HTML file. |

**Returns:**
com.aspose.slides.ISlide[] - Added slides
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

Creates slides from HTML text and inserts them to the collection at the specified position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Position to insert. |
| htmlText | java.lang.String | Html to add. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | java.lang.String | An URI of the specified HTML. Used to resolve relative links. |

**Returns:**
com.aspose.slides.ISlide[] - Added slides.
### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText)
```

Creates slides from HTML text and inserts them to the collection at the specified position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Position to insert. |
| htmlText | java.lang.String | Html to add. |

**Returns:**
com.aspose.slides.ISlide[] - Added slides
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Creates slides from HTML text and inserts them to the collection at the specified position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Position to insert. |
| htmlStream | java.io.InputStream | A Stream object which will be used as a source of a HTML file. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | java.lang.String | An URI of the specified HTML. Used to resolve relative links. |

**Returns:**
com.aspose.slides.ISlide[] - Added slides.
### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

Creates slides from HTML text and inserts them to the collection at the specified position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Position to insert. |
| htmlStream | java.io.InputStream | A Stream object which will be used as a source of a HTML file. |

**Returns:**
com.aspose.slides.ISlide[] - Added slides
### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

Creates slides from HTML text and inserts them to the collection at the specified position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Position to insert. |
| htmlText | java.lang.String | Html to add. |
| useSlideWithIndexAsStart | boolean | This flag determines how to start insertion: from a new slide or from the slide with the specified index. If **true**, then data insertion will start from an empty space on the slide with the specified index. If **false**, then data will be added to the created slides. |

**Returns:**
com.aspose.slides.ISlide[] - Added slides
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Creates slides from HTML text and inserts them to the collection at the specified position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Position to insert. |
| htmlText | java.lang.String | Html to add. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | java.lang.String | An URI of the specified HTML. Used to resolve relative links. |
| useSlideWithIndexAsStart | boolean | This flag determines how to start insertion: from a new slide or from the slide with the specified index. If **true**, then data insertion will start from an empty space on the slide with the specified index. If **false**, then data will be added to the created slides. |

**Returns:**
com.aspose.slides.ISlide[] - Added slides.
### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

Creates slides from HTML text and inserts them to the collection at the specified position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Position to insert. |
| htmlStream | java.io.InputStream | A Stream object which will be used as a source of a HTML file. |
| useSlideWithIndexAsStart | boolean | This flag determines how to start insertion: from a new slide or from the slide with the specified index. If **true**, then data insertion will start from an empty space on the slide with the specified index. If **false**, then data will be added to the created slides. |

**Returns:**
com.aspose.slides.ISlide[] - Added slides
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)

从 HTML 文本创建幻灯片并在集合的指定位置插入它们。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入的位置。 |
| htmlStream | java.io.InputStream | 将用作 HTML 文件源的流对象。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用于获取外部对象的回调对象。如果此参数为 null，将忽略所有外部对象。 |
| uri | java.lang.String | 指定 HTML 的 URI。用于解析相对链接。 |
| useSlideWithIndexAsStart | boolean | 此标志决定插入的起始方式：从新幻灯片或从指定索引的幻灯片开始。如果 **true**，则数据插入将从指定索引的幻灯片上的空白位置开始。如果 **false**，则数据将添加到创建的幻灯片中。 |

**返回值：**
com.aspose.slides.ISlide[] - 已添加的幻灯片。