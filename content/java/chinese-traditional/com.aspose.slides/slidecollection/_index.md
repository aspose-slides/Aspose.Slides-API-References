---
title: SlideCollection
second_title: Aspose.Slides for Java API 參考
description: 表示投影片的集合。
type: docs
url: /zh-hant/com.aspose.slides/slidecollection/
---
**繼承：**
java.lang.Object, com.aspose.slides.DomObject

**已實作的介面：**
[com.aspose.slides.ISlideCollection](../../com.aspose.slides/islidecollection)
```
public final class SlideCollection extends DomObject<Presentation> implements ISlideCollection
```

表示投影片的集合。

## 方法

| 方法 | 描述 |
| --- | --- |
| [size()](#size--) | 取得集合中實際包含的元素數量。 |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | 將指定投影片的副本新增至集合的末端。 |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | 將指定投影片的副本新增至指定章節的末端。 |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | 在集合的指定位置插入指定投影片的副本。 |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | 在集合的末端新增一個空的投影片。 |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | 在集合的指定位置插入指定投影片的副本。 |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | 將指定投影片的副本新增至集合的末端。 |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | 在集合的指定位置插入指定投影片的副本。 |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | 將指定來源投影片的副本新增至集合的末端。 |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | 在集合的指定位置插入指定來源投影片的副本。 |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | 從集合中移除第一個特定物件的出現。 |
| [removeAt(int index)](#removeAt-int-) | 移除集合中指定索引處的元素。 |
| [iterator()](#iterator--) | 返回一個用於遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 返回整個集合的 java 迭代器。 |
| [toArray()](#toArray--) | 建立並返回一個包含所有投影片的陣列。 |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 建立並返回一個包含指定範圍內所有投影片的陣列。 |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | 將投影片從集合中移動到指定位置。 |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | 將投影片從集合中移動到指定位置。 |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | 返回指定投影片在集合中的索引。 |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | 從 PDF 文件建立投影片並將它們新增至集合的末端。 |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | 根據 PDF 匯入選項，從 PDF 文件建立投影片並將它們新增至集合的末端。 |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | 從 PDF 文件建立投影片並將它們新增至集合的末端。 |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | 從 PDF 文件建立投影片並將它們新增至集合的末端。 |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 從 HTML 文字建立投影片並將它們新增至集合的末端。 |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | 從 HTML 文字建立投影片並將它們新增至集合的末端。 |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 從 HTML 文字建立投影片並將它們新增至集合的末端。 |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | 從 HTML 文字建立投影片並將它們新增至集合的末端。 |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 從 HTML 文字建立投影片並將它們插入至集合的指定位置。 |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | 從 HTML 文字建立投影片並將它們插入至集合的指定位置。 |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | 從 HTML 文字建立投影片並將它們插入至集合的指定位置。 |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | 從 HTML 文字建立投影片並將它們插入至集合的指定位置。 |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 從 HTML 文字建立投影片並將它們插入至集合的指定位置。 |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | 從 HTML 文字建立投影片並將它們插入至集合的指定位置。 |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | 從 HTML 文字建立投影片並將它們插入至集合的指定位置。 |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | 從 HTML 文字建立投影片並將它們插入至集合的指定位置。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將集合中的所有元素複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 返回一個值，指示對集合的存取是否已同步（執行緒安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |

### size() {#size--}
```
public final int size()
```

取得集合中實際包含的元素數量。唯讀 int。

**返回值：**
int

### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

取得指定索引處的元素。唯讀 [Slide](../../com.aspose.slides/slide)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回值：**
[ISlide](../../com.aspose.slides/islide)

### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public final ISlide addClone(ISlide sourceSlide)
```

將指定投影片的副本新增至集合的末端。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要克隆的投影片。 |

--------------------

在不同簡報之間複製投影片時，投影片的母片也可能被複製。內部註冊表用於追蹤自動複製的母片，以防止為同一母片投影片建立多個副本。手動複製母片投影片既不會被阻止，也不會被註冊。如果您需要對複製過程擁有更多控制，請使用 \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) 或 \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) 來複製投影片，[IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) 或 [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) 來複製版面配置，[IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) 來複製母片。

**返回值：**
[ISlide](../../com.aspose.slides/islide) - 新投影片。

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public final ISlide addClone(ISlide sourceSlide, ISection section)
```

將指定投影片的副本新增至指定章節的末端。

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
>      // 現在第二節包含第一張投影片的副本。
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要克隆的投影片。 |
| section | [ISection](../../com.aspose.slides/isection) | 新投影片的章節。 |

**返回值：**
[ISlide](../../com.aspose.slides/islide) - 新投影片。

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide)
```

在集合的指定位置插入指定投影片的副本。

> ```
> The following example shows how to clone at another position within Presentation.
>  
>  // Instantiate Presentation class that represents a presentation file
>  Presentation pres = new Presentation("CloneWithInSamePresentation.pptx");
>  try {
>      // Clone the desired slide to the end of the collection of slides in the same presentation
>      ISlideCollection slds = pres.getSlides();
>      // Clone the desired slide to the specified index in the same presentation
>      slds.insertClone(2, pres.getSlides().get_Item(1));
>      // Write the modified presentation to disk
>      pres.save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to clone at another position within Presentation.
>  
>  // Instantiate Presentation class to load the source presentation file
>  Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx");
>  try {
>      // Instantiate Presentation class for destination PPTX (where slide is to be cloned)
>      Presentation destPres = new Presentation();
>      try {
>          ISlideCollection slds = destPres.getSlides();
>          slds.insertClone(2, srcPres.getSlides().get_Item(0));
>          // Write the destination presentation to disk
>          destPres.save("Aspose2_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 新投影片的索引。 |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要克隆的投影片。 |

--------------------

在不同簡報之間複製投影片時，投影片的母片也可能被複製。內部註冊表用於追蹤自動複製的母片，以防止為同一母片投影片建立多個副本。手動複製母片投影片既不會被阻止，也不會被註冊。如果您需要對複製過程擁有更多控制，請使用 \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) 或 \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) 來複製投影片和 [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) 來複製母片。

**返回值：**
[ISlide](../../com.aspose.slides/islide) - 已插入的投影片。

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addEmptySlide(ILayoutSlide layout)
```

將新空的投影片新增至集合的末端。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 投影片的版面配置。 |

**返回值：**
[ISlide](../../com.aspose.slides/islide) - 已新增的投影片。

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

在集合的指定位置插入指定投影片的副本。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 新投影片的索引。 |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 投影片的版面配置。 |

**返回值：**
[ISlide](../../com.aspose.slides/islide) - 已插入的投影片。

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

將指定投影片的副本新增至集合的末端。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要克隆的投影片。 |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 新投影片的版面配置投影片。 |

**返回值：**
[ISlide](../../com.aspose.slides/islide) - 新投影片。

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

在集合的指定位置插入指定投影片的副本。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 新投影片的索引。 |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要克隆的投影片。 |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 新投影片的版面配置投影片。 |

**返回值：**
[ISlide](../../com.aspose.slides/islide) - 已插入的投影片。

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

將指定來源投影片的副本新增至集合的末端。系統會自動從指定的母片中選取適當的版面配置（適當的版面配置是與來源投影片版面配置具有相同類型或名稱的版面配置）。如果在指定的母片中找不到適當的版面配置，則會根據 allowCloneMissingLayout 的值執行以下操作：若為 true，則會克隆來源投影片的版面配置；若為 false，則拋出 PptxEditException。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要克隆的投影片。 |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 新投影片的母片。 |
| allowCloneMissingLayout | boolean | 如果在指定的母片中找不到適當的版面配置，則會克隆來源投影片的版面配置（當 allowCloneMissingLayout 為 true 時），或拋出 PptxEditException（當 allowCloneMissingLayout 為 false 時）。 |

**返回值：**
[ISlide](../../com.aspose.slides/islide) - 新投影片。

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

在集合的指定位置插入指定來源投影片的副本。系統會自動從指定的母片中選取適當的版面配置（適當的版面配置是與來源投影片版面配置具有相同類型或名稱的版面配置）。如果在指定的母片中找不到適當的版面配置，則會根據 allowCloneMissingLayout 的值執行以下操作：若為 true，則會克隆來源投影片的版面配置；若為 false，則拋出 PptxEditException。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 新投影片的索引。 |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要克隆的投影片。 |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 新投影片的母片。 |
| allowCloneMissingLayout | boolean | 如果在指定的母片中找不到適當的版面配置，則會克隆來源投影片的版面配置（當 allowCloneMissingLayout 為 true 時），或拋出 PptxEditException（當 allowCloneMissingLayout 為 false 時）。 |

**返回值：**
[ISlide](../../com.aspose.slides/islide) - 已插入的投影片。

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public final void remove(ISlide value)
```

從集合中移除第一個特定物件的出現。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | 要從集合中移除的投影片。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

移除集合中指定索引處的元素。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 要移除之元素的零基索引。 |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

返回一個遍歷集合的列舉器。

**返回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - 可用於遍歷集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

返回整個集合的 java 迭代器。

**返回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - 整個集合的 java.util.Iterator。

### toArray() {#toArray--}
```
public final ISlide[] toArray()
```

建立並返回一個包含所有投影片的陣列。

**返回值：**
com.aspose.slides.ISlide[] - [Slide](../../com.aspose.slides/slide) 的陣列。

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final ISlide[] toArray(int startIndex, int count)
```

建立並返回一個包含指定範圍內所有投影片的陣列。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| startIndex | int | 要加入之第一張投影片的索引。 |
| count | int | 要加入的投影片數量。 |

**返回值：**
com.aspose.slides.ISlide[] - [Slide](../../com.aspose.slides/slide) 的陣列。
### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public final void reorder(int index, ISlide slide)
```

將投影片從集合中移動到指定的位置。

**Parameters:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 目標索引。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 要移動的投影片。 |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public final void reorder(int index, ISlide[] slides)
```

將投影片從集合中移動到指定的位置。投影片將從索引開始依照它們在清單中出現的順序放置。

**Parameters:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 目標索引。 |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | 要移動的投影片。 |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public final int indexOf(ISlide slide)
```

傳回集合中指定投影片的索引。

**Parameters:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | 要尋找的投影片。 |

**Returns:**
int - 投影片的索引；若投影片不屬於此集合，則回傳 -1。

### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public final ISlide[] addFromPdf(String path)
```

從 PDF 文件建立投影片，並將它們新增至集合的末端。

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
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| path | java.lang.String | PDF 文件的路徑 |

**Returns:**
com.aspose.slides.ISlide[] - 已新增的投影片

### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

從 PDF 文件建立投影片，並根據 PDF 匯入選項將它們新增至集合的末端。

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
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| path | java.lang.String | PDF 文件的路徑 |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | PDF 匯入的選項 |

**Returns:**
com.aspose.slides.ISlide[] - 已新增的投影片

### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public final ISlide[] addFromPdf(InputStream pdfStream)
```

從 PDF 文件建立投影片，並將它們新增至集合的末端。

--------------------

> ```
> 範例：
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
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| pdfStream | java.io.InputStream | 用作 PDF 文件來源的串流。 |

**Returns:**
com.aspose.slides.ISlide[] - 已新增的投影片

### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

從 PDF 文件建立投影片，並將它們新增至集合的末端。

--------------------

> ```
> 範例：
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
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| pdfStream | java.io.InputStream | 用作 PDF 文件來源的串流。 |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | PDF 匯入的選項 |

**Returns:**
com.aspose.slides.ISlide[] - 已新增的投影片

### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

從 HTML 文字建立投影片，並將它們新增至集合的末端。

**Parameters:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| htmlText | java.lang.String | 要新增的 HTML。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用於擷取外部物件的回呼物件。若此參數為 null，則會忽略所有外部物件。 |
| uri | java.lang.String | 指定 HTML 的 URI。用於解析相對連結。 |

**Returns:**
com.aspose.slides.ISlide[] - 已新增的投影片。

### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText)
```

從 HTML 文字建立投影片，並將它們新增至集合的末端。

**Parameters:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| htmlText | java.lang.String | 要新增的 HTML。 |

**Returns:**
com.aspose.slides.ISlide[] - 已新增的投影片

### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

從 HTML 文字建立投影片，並將它們新增至集合的末端。

**Parameters:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| htmlStream | java.io.InputStream | 用作 HTML 檔案來源的 Stream 物件。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用於擷取外部物件的回呼物件。若此參數為 null，則會忽略所有外部物件。 |
| uri | java.lang.String | 指定 HTML 的 URI。用於解析相對連結。 |

**Returns:**
com.aspose.slides.ISlide[] - 已新增的投影片。

### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public final ISlide[] addFromHtml(InputStream htmlStream)
```

從 HTML 文字建立投影片，並將它們新增至集合的末端。

--------------------

> ```
> // 建立 Presentation 類別的實例。
>  Presentation pres = new Presentation();
>  try {
>      String html = new String(Files.readAllBytes(Paths.get("file.html")));
>      // 呼叫 AddFromHtml 方法並傳入 HTML 檔案。
>      pres.getSlides().addFromHtml(html);
>      // 使用 Save 方法將檔案儲存為 PowerPoint 文件。
>      pres.save("MyPresentation.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| htmlStream | java.io.InputStream | 用作 HTML 檔案來源的 Stream 物件。 |

**Returns:**
com.aspose.slides.ISlide[] - 已新增的投影片

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

從 HTML 文字建立投影片，並在指定位置插入至集合。

**Parameters:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 插入的位置。 |
| htmlText | java.lang.String | 要新增的 HTML。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用於擷取外部物件的回呼物件。若此參數為 null，則會忽略所有外部物件。 |
| uri | java.lang.String | 指定 HTML 的 URI。用於解析相對連結。 |

**Returns:**
com.aspose.slides.ISlide[] - 已新增的投影片。

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

從 HTML 文字建立投影片，並在指定位置插入至集合。

**Parameters:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 插入的位置。 |
| htmlText | java.lang.String | 要新增的 HTML。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用於擷取外部物件的回呼物件。若此參數為 null，則會忽略所有外部物件。 |
| uri | java.lang.String | 指定 HTML 的 URI。用於解析相對連結。 |
| useSlideWithIndexAsStart | boolean | 此旗標決定插入的起始方式：從新投影片或從具有指定索引的投影片開始。若為 **true**，資料插入將從具有指定索引的投影片上的空白處開始；若為 **false**，則資料將加入已建立的投影片。 |

**Returns:**
com.aspose.slides.ISlide[] - 已新增的投影片。

### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText)
```

從 HTML 文字建立投影片，並在指定位置插入至集合。

**Parameters:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 插入的位置。 |
| htmlText | java.lang.String | 要新增的 HTML。 |

**Returns:**
com.aspose.slides.ISlide[] - 已新增的投影片

### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

從 HTML 文字建立投影片，並在指定位置插入至集合。

**Parameters:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 插入的位置。 |
| htmlText | java.lang.String | 要新增的 HTML。 |
| useSlideWithIndexAsStart | boolean | 此旗標決定插入的起始方式：從新投影片或從具有指定索引的投影片開始。若為 **true**，資料插入將從具有指定索引的投影片上的空白處開始；若為 **false**，則資料將加入已建立的投影片。 |

**Returns:**
com.aspose.slides.ISlide[] - 已新增的投影片

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

從 HTML 文字建立投影片，並在指定位置插入至集合。

**Parameters:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 插入的位置。 |
| htmlStream | java.io.InputStream | 用作 HTML 檔案來源的 Stream 物件。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用於擷取外部物件的回呼物件。若此參數為 null，則會忽略所有外部物件。 |
| uri | java.lang.String | 指定 HTML 的 URI。用於解析相對連結。 |

**Returns:**
com.aspose.slides.ISlide[] - 已新增的投影片。

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

從 HTML 文字建立投影片，並在指定位置插入至集合。

**Parameters:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 插入的位置。 |
| htmlStream | java.io.InputStream | 用作 HTML 檔案來源的 Stream 物件。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用於擷取外部物件的回呼物件。若此參數為 null，則會忽略所有外部物件。 |
| uri | java.lang.String | 指定 HTML 的 URI。用於解析相對連結。 |
| useSlideWithIndexAsStart | boolean | 此旗標決定插入的起始方式：從新投影片或從具有指定索引的投影片開始。若為 **true**，資料插入將從具有指定索引的投影片上的空白處開始；若為 **false**，則資料將加入已建立的投影片。 |

**Returns:**
com.aspose.slides.ISlide[] - 已新增的投影片。

### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

從 HTML 文字建立投影片，並在指定位置插入至集合。

**Parameters:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 插入的位置。 |
| htmlStream | java.io.InputStream | 用作 HTML 檔案來源的 Stream 物件。 |

**Returns:**
com.aspose.slides.ISlide[] - 已新增的投影片

### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

從 HTML 文字建立投影片，並在指定位置插入至集合。

**Parameters:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 插入的位置。 |
| htmlStream | java.io.InputStream | 用作 HTML 檔案來源的 Stream 物件。 |
| useSlideWithIndexAsStart | boolean | 此旗標決定插入的起始方式：從新投影片或從具有指定索引的投影片開始。若為 **true**，資料插入將從具有指定索引的投影片上的空白處開始；若為 **false**，則資料將加入已建立的投影片。 |

**Returns:**
com.aspose.slides.ISlide[] - 已新增的投影片

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

將集合中的所有元素複製到指定的陣列。

**Parameters:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列。 |
| index | int | 目標陣列的起始索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

傳回一個值，表示對集合的存取是否已同步（執行緒安全）。唯讀布林值。

**Returns:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

傳回同步根。唯讀 Object。

**Returns:**
java.lang.Object