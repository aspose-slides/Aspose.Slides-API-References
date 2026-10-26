---
title: ISlideCollection
second_title: Aspose.Slides for Java API 参考
description: 表示幻灯片集合。
type: docs
url: /zh/com.aspose.slides/islidecollection/
---
**已实现的接口：**
com.aspose.slides.IGenericCollection
```
public interface ISlideCollection extends IGenericCollection<ISlide>
```

表示一个幻灯片的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | 将指定幻灯片的副本添加到集合的末尾。 |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | 将指定幻灯片的副本添加到指定章节的末尾。 |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | 在集合的指定位置插入指定幻灯片的副本。 |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | 在集合的末尾添加一个新的空白幻灯片。 |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | 在集合的指定位置插入指定幻灯片的副本。 |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | 将指定幻灯片的副本添加到集合的末尾。 |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | 在集合的指定位置插入指定幻灯片的副本。 |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | 将指定源幻灯片的副本添加到集合的末尾。 |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | 在集合的指定位置插入指定源幻灯片的副本。 |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | 从集合中移除特定对象的第一次出现。 |
| [removeAt(int index)](#removeAt-int-) | 移除集合中指定索引处的元素。 |
| [toArray()](#toArray--) | 创建并返回包含所有幻灯片的数组。 |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 创建并返回包含指定范围内所有幻灯片的数组。 |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | 将幻灯片从集合中移动到指定位置。 |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | 将幻灯片从集合中移动到指定位置。 |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | 返回指定幻灯片在集合中的索引。 |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | 从 PDF 文档创建幻灯片并将其添加到集合的末尾。 |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | 在考虑 PDF 导入选项的情况下，从 PDF 文档创建幻灯片并将其添加到集合的末尾。 |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | 从 PDF 文档创建幻灯片并将其添加到集合的末尾。 |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | 从 PDF 文档创建幻灯片并将其添加到集合的末尾。 |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 从 HTML 文本创建幻灯片并将其添加到集合的末尾。 |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | 从 HTML 文本创建幻灯片并将其添加到集合的末尾。 |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 从 HTML 文本创建幻灯片并将其添加到集合的末尾。 |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | 从 HTML 文本创建幻灯片并将其添加到集合的末尾。 |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 从 HTML 文本创建幻灯片并将其插入到集合的指定位置。 |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | 从 HTML 文本创建幻灯片并将其插入到集合的指定位置。 |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 从 HTML 文本创建幻灯片并将其插入到集合的指定位置。 |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | 从 HTML 文本创建幻灯片并将其插入到集合的指定位置。 |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | 从 HTML 文本创建幻灯片并将其插入到集合的指定位置。 |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | 从 HTML 文本创建幻灯片并将其插入到集合的指定位置。 |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | 从 HTML 文本创建幻灯片并将其插入到集合的指定位置。 |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | 从 HTML 文本创建幻灯片并将其插入到集合的指定位置。 |

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

将指定幻灯片的副本添加到集合的末尾。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要克隆的幻灯片。 |

--------------------

在不同演示文稿之间克隆幻灯片时，幻灯片的母版也可能被克隆。内部注册表用于跟踪自动克隆的母版，以防止创建同一母版幻灯片的多个克隆。手动克隆母版幻灯片既不会被阻止也不会被注册。如果需要对克隆过程进行更细致的控制，请使用 \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) 或 \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) 来克隆幻灯片，[IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) 或 [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) 来克隆布局，以及 [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) 来克隆母版。

**返回值：**
[ISlide](../../com.aspose.slides/islide) - 新幻灯片。

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public abstract ISlide addClone(ISlide sourceSlide, ISection section)
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


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要克隆的幻灯片。 |
| section | [ISection](../../com.aspose.slides/isection) | 新幻灯片的章节。 |

**返回值：**
[ISlide](../../com.aspose.slides/islide) - 新幻灯片。

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide)
```

在集合的指定位置插入指定幻灯片的副本。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 新幻灯片的索引。 |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要克隆的幻灯片。 |

--------------------

在不同演示文稿之间克隆幻灯片时，幻灯片的母版也可能被克隆。内部注册表用于跟踪自动克隆的母版，以防止创建同一母版幻灯片的多个克隆。手动克隆母版幻灯片既不会被阻止也不会被注册。如果需要对克隆过程进行更细致的控制，请使用 \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) 或 \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) 来克隆幻灯片和 [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) 来克隆母版。

**返回值：**
[ISlide](../../com.aspose.slides/islide) - 插入的幻灯片。

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addEmptySlide(ILayoutSlide layout)
```

在集合的末尾添加一个新的空白幻灯片。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 幻灯片的布局。 |

**返回值：**
[ISlide](../../com.aspose.slides/islide) - 添加的幻灯片。

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

在集合的指定位置插入指定幻灯片的副本。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 新幻灯片的索引。 |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 幻灯片的布局。 |

**返回值：**
[ISlide](../../com.aspose.slides/islide) - 插入的幻灯片。

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

将指定幻灯片的副本添加到集合的末尾。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要克隆的幻灯片。 |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 新幻灯片的布局幻灯片。 |

**返回值：**
[ISlide](../../com.aspose.slides/islide) - 新幻灯片。

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

在集合的指定位置插入指定幻灯片的副本。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 新幻灯片的索引。 |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要克隆的幻灯片。 |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 新幻灯片的布局幻灯片。 |

**返回值：**
[ISlide](../../com.aspose.slides/islide) - 插入的幻灯片。

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

将指定源幻灯片的副本添加到集合的末尾。将自动从指定的母版中选择合适的布局（合适的布局是与源幻灯片布局具有相同 Type 或 Name 的布局）。如果指定的母版中没有合适的布局，则会克隆源幻灯片的布局（如果 allowCloneMissingLayout 为 true），否则会抛出 PptxEditException（如果 allowCloneMissingLayout 为 false）。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要克隆的幻灯片。 |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 新幻灯片的母版。 |
| allowCloneMissingLayout | boolean | 如果指定的母版中没有合适的布局，则会克隆源幻灯片的布局（如果 allowCloneMissingLayout 为 true），否则会抛出 PptxEditException（如果 allowCloneMissingLayout 为 false）。 |

**返回值：**
[ISlide](../../com.aspose.slides/islide) - 新幻灯片。

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

在集合的指定位置插入指定源幻灯片的副本。将自动从指定的母版中选择合适的布局（合适的布局是与源幻灯片布局具有相同 Type 或 Name 的布局）。如果指定的母版中没有合适的布局，则会克隆源幻灯片的布局（如果 allowCloneMissingLayout 为 true），否则会抛出 PptxEditException（如果 allowCloneMissingLayout 为 false）。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 新幻灯片的索引。 |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要克隆的幻灯片。 |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 新幻灯片的母版。 |
| allowCloneMissingLayout | boolean | 如果指定的母版中没有合适的布局，则会克隆源幻灯片的布局（如果 allowCloneMissingLayout 为 true），否则会抛出 PptxEditException（如果 allowCloneMissingLayout 为 false）。 |

**返回值：**
[ISlide](../../com.aspose.slides/islide) - 插入的幻灯片。

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public abstract void remove(ISlide value)
```

从集合中移除特定对象的第一次出现。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | 要从集合中移除的幻灯片。 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

移除集合中指定索引处的元素。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的元素的零基索引。 |

### toArray() {#toArray--}
```
public abstract ISlide[] toArray()
```

创建并返回包含所有幻灯片的数组。

**返回值：**
com.aspose.slides.ISlide[] - [ISlide](../../com.aspose.slides/islide) 的数组

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract ISlide[] toArray(int startIndex, int count)
```

创建并返回包含指定范围内所有幻灯片的数组。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startIndex | int | 第一个要添加的幻灯片的索引。 |
| count | int | 要添加的幻灯片数量。 |

**返回值：**
com.aspose.slides.ISlide[] - [ISlide](../../com.aspose.slides/islide) 的数组

### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public abstract void reorder(int index, ISlide slide)
```

将幻灯片从集合中移动到指定位置。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 目标索引。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 要移动的幻灯片。 |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public abstract void reorder(int index, ISlide[] slides)
```

将幻灯片从集合中移动到指定位置。幻灯片将从指定索引开始按其在列表中出现的顺序依次放置。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 目标索引。 |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | 要移动的幻灯片。 |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public abstract int indexOf(ISlide slide)
```

返回指定幻灯片在集合中的索引。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | 要查找的幻灯片。 |

**返回值：**
int - 幻灯片的索引；如果幻灯片不在此集合中则返回 -1。

### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public abstract ISlide[] addFromPdf(String path)
```

从 PDF 文档创建幻灯片并将其添加到集合的末尾。

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

**返回:**  
com.aspose.slides.ISlide[] - 已添加的幻灯片

### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

根据 pdf import options，从 PDF 文档创建幻灯片并将其添加到集合的末尾。

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


**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | java.lang.String | PDF 文档的路径 |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | PDF 导入的选项 |

**返回:**  
com.aspose.slides.ISlide[] - 已添加的幻灯片

### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

从 PDF 文档创建幻灯片并将其添加到集合的末尾。

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

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pdfStream | java.io.InputStream | 用于作为 PDF 文档来源的流 |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | PDF 导入的选项 |

**返回:**  
com.aspose.slides.ISlide[] - 已添加的幻灯片

### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream)
```

从 PDF 文档创建幻灯片并将其添加到集合的末尾。

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

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pdfStream | java.io.InputStream | 用于作为 PDF 文档来源的流 |

**返回:**  
com.aspose.slides.ISlide[] - 已添加的幻灯片

### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

从 HTML 文本创建幻灯片并将其添加到集合的末尾。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| htmlText | java.lang.String | 要添加的 HTML。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用于获取外部对象的回调对象。如果此参数为 null，将忽略所有外部对象。 |
| uri | java.lang.String | 指定 HTML 的 URI。用于解析相对链接。 |

**返回:**  
com.aspose.slides.ISlide[] - 已添加的幻灯片。

### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText)
```

从 HTML 文本创建幻灯片并将其添加到集合的末尾。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| htmlText | java.lang.String | 要添加的 HTML。 |

**返回:**  
com.aspose.slides.ISlide[] - 已添加的幻灯片

### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

从 HTML 文本创建幻灯片并将其添加到集合的末尾。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| htmlStream | java.io.InputStream | 用于作为 HTML 文件来源的流。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用于获取外部对象的回调对象。如果此参数为 null，将忽略所有外部对象。 |
| uri | java.lang.String | 指定 HTML 的 URI。用于解析相对链接。 |

**返回:**  
com.aspose.slides.ISlide[] - 已添加的幻灯片。

### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream)
```

从 HTML 文本创建幻灯片并将其添加到集合的末尾。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| htmlStream | java.io.InputStream | 用于作为 HTML 文件来源的流。 |

**返回:**  
com.aspose.slides.ISlide[] - 已添加的幻灯片

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

从 HTML 文本创建幻灯片并将其插入到集合中指定的位置。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入的位置。 |
| htmlText | java.lang.String | 要添加的 HTML。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用于获取外部对象的回调对象。如果此参数为 null，将忽略所有外部对象。 |
| uri | java.lang.String | 指定 HTML 的 URI。用于解析相对链接。 |

**返回:**  
com.aspose.slides.ISlide[] - 已添加的幻灯片。

### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText)
```

从 HTML 文本创建幻灯片并将其插入到集合中指定的位置。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入的位置。 |
| htmlText | java.lang.String | 要添加的 HTML。 |

**返回:**  
com.aspose.slides.ISlide[] - 已添加的幻灯片

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

从 HTML 文本创建幻灯片并将其插入到集合中指定的位置。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入的位置。 |
| htmlStream | java.io.InputStream | 用于作为 HTML 文件来源的流。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用于获取外部对象的回调对象。如果此参数为 null，将忽略所有外部对象。 |
| uri | java.lang.String | 指定 HTML 的 URI。用于解析相对链接。 |

**返回:**  
com.aspose.slides.ISlide[] - 已添加的幻灯片。

### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

从 HTML 文本创建幻灯片并将其插入到集合中指定的位置。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入的位置。 |
| htmlStream | java.io.InputStream | 用于作为 HTML 文件来源的流。 |

**返回:**  
com.aspose.slides.ISlide[] - 已添加的幻灯片

### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

从 HTML 文本创建幻灯片并将其插入到集合中指定的位置。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入的位置。 |
| htmlText | java.lang.String | 要添加的 HTML。 |
| useSlideWithIndexAsStart | boolean | 此标志决定插入的起始方式：从新幻灯片还是从指定索引的幻灯片开始。如果 **true**，则数据插入将从指定索引的幻灯片上的空白处开始；如果 **false**，则数据将添加到创建的幻灯片中。 |

**返回:**  
com.aspose.slides.ISlide[] - 已添加的幻灯片

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

从 HTML 文本创建幻灯片并将其插入到集合中指定的位置。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入的位置。 |
| htmlText | java.lang.String | 要添加的 HTML。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用于获取外部对象的回调对象。如果此参数为 null，将忽略所有外部对象。 |
| uri | java.lang.String | 指定 HTML 的 URI。用于解析相对链接。 |
| useSlideWithIndexAsStart | boolean | 此标志决定插入的起始方式：从新幻灯片还是从指定索引的幻灯片开始。如果 **true**，则数据插入将从指定索引的幻灯片上的空白处开始；如果 **false**，则数据将添加到创建的幻灯片中。 |

**返回:**  
com.aspose.slides.ISlide[] - 已添加的幻灯片。

### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

从 HTML 文本创建幻灯片并将其插入到集合中指定的位置。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入的位置。 |
| htmlStream | java.io.InputStream | 用于作为 HTML 文件来源的流。 |
| useSlideWithIndexAsStart | boolean | 此标志决定插入的起始方式：从新幻灯片还是从指定索引的幻灯片开始。如果 **true**，则数据插入将从指定索引的幻灯片上的空白处开始；如果 **false**，则数据将添加到创建的幻灯片中。 |

**返回:**  
com.aspose.slides.ISlide[] - 已添加的幻灯片

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

从 HTML 文本创建幻灯片并将其插入到集合中指定的位置。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入的位置。 |
| htmlStream | java.io.InputStream | 用于作为 HTML 文件来源的流。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用于获取外部对象的回调对象。如果此参数为 null，将忽略所有外部对象。 |
| uri | java.lang.String | 指定 HTML 的 URI。用于解析相对链接。 |
| useSlideWithIndexAsStart | boolean | 此标志决定插入的起始方式：从新幻灯片还是从指定索引的幻灯片开始。如果 **true**，则数据插入将从指定索引的幻灯片上的空白处开始；如果 **false**，则数据将添加到创建的幻灯片中。 |

**返回:**  
com.aspose.slides.ISlide[] - 已添加的幻灯片。