---
title: SlideCollection
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示投影片的集合。
type: docs
url: /zh-hant/com.aspose.slides/slidecollection/
---
**繼承：**
java.lang.Object, com.aspose.slides.DomObject

**已實作的所有介面：**
[com.aspose.slides.ISlideCollection](../../com.aspose.slides/islidecollection)
```
public final class SlideCollection extends DomObject<Presentation> implements ISlideCollection
```

表示一個投影片集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [size()](#size--) | 取得集合中實際包含的元素數量。 |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | 將指定投影片的副本新增至集合的末端。 |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | 將指定投影片的副本新增至指定章節的末端。 |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | 在集合的指定位置插入指定投影片的副本。 |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | 在集合的末端新增一個空白投影片。 |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | 在集合的指定位置插入指定投影片的副本。 |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | 將指定投影片的副本新增至集合的末端。 |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | 在集合的指定位置插入指定投影片的副本。 |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | 將指定來源投影片的副本新增至集合的末端。 |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | 在集合的指定位置插入指定來源投影片的副本。 |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | 從集合中移除特定物件的第一次出現。 |
| [removeAt(int index)](#removeAt-int-) | 移除集合中指定索引處的元素。 |
| [iterator()](#iterator--) | 傳回可遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |
| [toArray()](#toArray--) | 建立並傳回包含所有投影片的陣列。 |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 建立並傳回包含指定範圍內所有投影片的陣列。 |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | 將投影片從集合中移動至指定位置。 |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | 将投影片从集合中移动到指定位置。 |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | 傳回集合中指定投影片的索引。 |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | 從 PDF 文件建立投影片並將它們新增至集合的末端。 |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | 從 PDF 文件建立投影片並考慮 PDF 匯入選項後將它們新增至集合的末端。 |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | 從 PDF 文件建立投影片並將它們新增至集合的末端。 |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | 從 PDF 文件建立投影片並將它們新增至集合的末端。 |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 從 HTML 文字建立投影片並將它們新增至集合的末端。 |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | 從 HTML 文字建立投影片並將它們新增至集合的末端。 |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 從 HTML 文字建立投影片並將它們新增至集合的末端。 |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | 從 HTML 文字建立投影片並將它們新增至集合的末端。 |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 從 HTML 文字建立投影片並插入至集合的指定位置。 |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | 從 HTML 文字建立投影片並插入至集合的指定位置。 |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | 從 HTML 文字建立投影片並插入至集合的指定位置。 |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | 從 HTML 文字建立投影片並插入至集合的指定位置。 |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 從 HTML 文字建立投影片並插入至集合的指定位置。 |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | 從 HTML 文字建立投影片並插入至集合的指定位置。 |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | 從 HTML 文字建立投影片並插入至集合的指定位置。 |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | 從 HTML 文字建立投影片並插入至集合的指定位置。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將集合中的所有元素複製到指定陣列。 |
| [isSynchronized()](#isSynchronized--) | 傳回一個表示集合存取是否同步（執行緒安全）的值。 |
| [getSyncRoot()](#getSyncRoot--) | 傳回同步根。 |

### size() {#size--}
```
public final int size()
```


取得集合中實際包含的元素數量。唯讀 int。

**傳回值：**
int

### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```


取得指定索引處的元素。唯讀 [Slide](../../com.aspose.slides/slide)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回值：**
[ISlide](../../com.aspose.slides/islide)

### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public final ISlide addClone(ISlide sourceSlide)
```


將指定投影片的副本新增至集合的末端。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要克隆的投影片。

--------------------

當在不同簡報之間克隆投影片時，投影片的母片也可能被克隆。內部註冊表用於自動追蹤已克隆的母片，以防止產生同一母片的多個克隆。手動克隆母片既不會被阻止也不會被註冊。若需要對克隆過程有更多控制，請使用 `#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide)` 或 `#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean)` 來克隆投影片，[IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) 或 [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) 來克隆版面，[IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) 來克隆母片。 |

**傳回值：**
[ISlide](../../com.aspose.slides/islide) - 新的投影片。

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public final ISlide addClone(ISlide sourceSlide, ISection section)
```


將指定投影片的副本新增至指定章節的末端。

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
>      // 現在第二個章節包含第一張投影片的副本。
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要克隆的投影片。 |
| section | [ISection](../../com.aspose.slides/isection) | 新投影片的章節。 |

**傳回值：**
[ISlide](../../com.aspose.slides/islide) - 新的投影片。

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide)
```


在集合的指定位置插入指定投影片的副本。

--------------------

> ```
> The following example shows how to clone at another position within Presentation.
>  
>  // 實例化代表簡報檔案的 Presentation 類別
>  Presentation pres = new Presentation("CloneWithInSamePresentation.pptx");
>  try {
>      // 將所需的投影片複製到同一簡報中投影片集合的末端
>      ISlideCollection slds = pres.getSlides();
>      // 將所需的投影片複製到同一簡報中指定的索引位置
>      slds.insertClone(2, pres.getSlides().get_Item(1));
>      // 將修改後的簡報寫入磁碟
>      pres.save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to clone at another position within Presentation.
>  
>  // 實例化 Presentation 類別以載入來源簡報檔案
>  Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx");
>  try {
>      // 實例化用於目標 PPTX（投影片將被複製到此處）的 Presentation 類別
>      Presentation destPres = new Presentation();
>      try {
>          ISlideCollection slds = destPres.getSlides();
>          slds.insertClone(2, srcPres.getSlides().get_Item(0));
>          // 將目標簡報寫入磁碟
>          destPres.save("Aspose2_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 新投影片的索引。 |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要克隆的投影片。

--------------------

當在不同簡報之間克隆投影片時，投影片的母片也可能被克隆。內部註冊表用於自動追蹤已克隆的母片，以防止產生同一母片的多個克隆。手動克隆母片既不會被阻止也不會被註冊。若需要對克隆過程有更多控制，請使用 `#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide)` 或 `#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean)` 來克隆投影片，[IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) 來克隆母片。 |

**傳回值：**
[ISlide](../../com.aspose.slides/islide) - 插入的投影片。

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addEmptySlide(ILayoutSlide layout)
```


在集合的末端新增一個空白投影片。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 投影片的版面配置。 |

**傳回值：**
[ISlide](../../com.aspose.slides/islide) - 新增的投影片。

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertEmptySlide(int index, ILayoutSlide layout)
```


在集合的指定位置插入指定版面的投影片副本。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 新投影片的索引。 |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 投影片的版面配置。 |

**傳回值：**
[ISlide](../../com.aspose.slides/islide) - 插入的投影片。

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```


將指定投影片的副本新增至集合的末端。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要克隆的投影片。 |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 新投影片的版面配置。 |

**傳回值：**
[ISlide](../../com.aspose.slides/islide) - 新的投影片。

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```


在集合的指定位置插入指定投影片的副本。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 新投影片的索引。 |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要克隆的投影片。 |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 新投影片的版面配置。 |

**傳回值：**
[ISlide](../../com.aspose.slides/islide) - 插入的投影片。

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```


將指定來源投影片的副本新增至集合的末端。將自動從指定的母片中選取適當的版面（適當的版面是與來源投影片版面具有相同類型或名稱的版面）。如果在指定的母片中沒有適當的版面，則會克隆來源投影片的版面（若 allowCloneMissingLayout 為 true），否則拋出 PptxEditException（若 allowCloneMissingLayout 為 false）。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要克隆的投影片。 |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 新投影片的母片。 |
| allowCloneMissingLayout | boolean | 若在指定的母片中沒有適當的版面，則會克隆來源投影片的版面（若 allowCloneMissingLayout 為 true），否則拋出 PptxEditException（若 allowCloneMissingLayout 為 false）。 |

**傳回值：**
[ISlide](../../com.aspose.slides/islide) - 新的投影片。

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```


在集合的指定位置插入指定來源投影片的副本。將自動從指定的母片中選取適當的版面（適當的版面是與來源投影片版面具有相同類型或名稱的版面）。如果在指定的母片中沒有適當的版面，則會克隆來源投影片的版面（若 allowCloneMissingLayout 為 true），否則拋出 PptxEditException（若 allowCloneMissingLayout 為 false）。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 新投影片的索引。 |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要克隆的投影片。 |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 新投影片的母片。 |
| allowCloneMissingLayout | boolean | 若在指定的母片中沒有適當的版面，則會克隆來源投影片的版面（若 allowCloneMissingLayout 為 true），否則拋出 PptxEditException（若 allowCloneMissingLayout 為 false）。 |

**傳回值：**
[ISlide](../../com.aspose.slides/islide) - 插入的投影片。

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public final void remove(ISlide value)
```


從集合中移除特定物件的第一次出現。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | 要從集合中移除的投影片。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


移除集合中指定索引處的元素。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要移除的元素的零基索引。 |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```


傳回可遍歷集合的列舉器。

**傳回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - 可用於遍歷集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```


傳回整個集合的 java 迭代器。

**傳回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - 用於整個集合的 java.util.Iterator。

### toArray() {#toArray--}
```
public final ISlide[] toArray()
```


建立並傳回包含所有投影片的陣列。

**傳回值：**
com.aspose.slides.ISlide[] - [Slide](../../com.aspose.slides/slide) 陣列

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final ISlide[] toArray(int startIndex, int count)
```


建立並傳回指定範圍內所有投影片的陣列。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| startIndex | int | 要加入的第一張投影片的索引。 |
| count | int | 要加入的投影片數量。 |

**傳回值：**
com.aspose.slides.ISlide[] - [Slide](../../com.aspose.slides/slide) 陣列

### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public final void reorder(int index, ISlide slide)
```


將投影片從集合中移動至指定位置。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 目標索引。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 要移動的投影片。

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public final void reorder(int index, ISlide[] slides)
```


將投影片從集合中移動至指定位置。投影片將從指定索引開始，依照它們在列表中出現的順序排列。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 目標索引。 |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | 要移動的投影片。

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public final int indexOf(ISlide slide)
```


傳回集合中指定投影片的索引。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | 要尋找的投影片。 |

**傳回值：**
int - 投影片的索引，若投影片不屬於此集合則為 -1。

### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public final ISlide[] addFromPdf(String path)
```


從 PDF 文件建立投影片並將它們新增至集合的末端。

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

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | java.lang.String | PDF 文件的路徑 |

**傳回值：**
com.aspose.slides.ISlide[] - 已新增的投影片

### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```


從 PDF 文件建立投影片並考慮 PDF 匯入選項後將它們新增至集合的末端。

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

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | java.lang.String | PDF 文件的路徑 |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | PDF 匯入選項 |

**傳回值：**
com.aspose.slides.ISlide[] - 已新增的投影片

### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public final ISlide[] addFromPdf(InputStream pdfStream)
```


從 PDF 文件建立投影片並將它們新增至集合的末端。

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


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pdfStream | java.io.InputStream | 用作 PDF 文件來源的串流 |

**傳回值：**
com.aspose.slides.ISlide[] - 已新增的投影片

### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```


從 PDF 文件建立投影片並將它們新增至集合的末端。

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


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pdfStream | java.io.InputStream | 用作 PDF 文件來源的串流 |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | PDF 匯入選項 |

**傳回值：**
com.aspose.slides.ISlide[] - 已新增的投影片

### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```


從 HTML 文字建立投影片並將它們新增至集合的末端。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| htmlText | java.lang.String | 要加入的 HTML。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用於取得外部物件的回呼物件。如果此參數為 null，則會忽略所有外部物件。 |
| uri | java.lang.String | 指定 HTML 的 URI，用於解析相對連結。 |

**傳回值：**
com.aspose.slides.ISlide[] - 已新增的投影片。

### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText)
```


從 HTML 文字建立投影片並將它們新增至集合的末端。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| htmlText | java.lang.String | 要加入的 HTML。 |

**傳回值：**
com.aspose.slides.ISlide[] - 已新增的投影片

### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```


從 HTML 文字建立投影片並將它們新增至集合的末端。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| htmlStream | java.io.InputStream | 用作 HTML 檔案來源的串流。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用於取得外部物件的回呼物件。如果此參數為 null，則會忽略所有外部物件。 |
| uri | java.lang.String | 指定 HTML 的 URI，用於解析相對連結。 |

**傳回值：**
com.aspose.slides.ISlide[] - 已新增的投影片。

### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public final ISlide[] addFromHtml(InputStream htmlStream)
```


從 HTML 文字建立投影片並將它們新增至集合的末端。

--------------------

> ```
> // 建立 Presentation 類別的實例。
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("file.html");
>          // 呼叫 AddFromHtml 方法並傳遞 HTML 檔案。
>          pres.getSlides().addFromHtml(fos);
>          // 使用 Save 方法將檔案儲存為 PowerPoint 文件。
>          pres.save("MyPresentation.pptx", SaveFormat.Pptx);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| htmlStream | java.io.InputStream | 用作 HTML 檔案來源的串流。 |

**傳回值：**
com.aspose.slides.ISlide[] - 已新增的投影片

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```


從 HTML 文字建立投影片並插入至集合的指定位置。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要插入的位置。 |
| htmlText | java.lang.String | 要加入的 HTML。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用於取得外部物件的回呼物件。如果此參數為 null，則會忽略所有外部物件。 |
| uri | java.lang.String | 指定 HTML 的 URI，用於解析相對連結。 |

**傳回值：**
com.aspose.slides.ISlide[] - 已新增的投影片。

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```


從 HTML 文字建立投影片並插入至集合的指定位置。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要插入的位置。 |
| htmlText | java.lang.String | 要加入的 HTML。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用於取得外部物件的回呼物件。如果此參數為 null，則會忽略所有外部物件。 |
| uri | java.lang.String | 指定 HTML 的 URI，用於解析相對連結。 |
| useSlideWithIndexAsStart | boolean | 此旗標決定如何開始插入：從新投影片開始或從具有指定索引的投影片開始。若 **true**，則資料插入將從具有指定索引的投影片的空白區域開始；若 **false**，則資料將加入至新建立的投影片。 |

**傳回值：**
com.aspose.slides.ISlide[] - 已新增的投影片。

### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText)
```


從 HTML 文字建立投影片並插入至集合的指定位置。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要插入的位置。 |
| htmlText | java.lang.String | 要加入的 HTML。 |

**傳回值：**
com.aspose.slides.ISlide[] - 已新增的投影片

### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```


從 HTML 文字建立投影片並插入至集合的指定位置。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要插入的位置。 |
| htmlText | java.lang.String | 要加入的 HTML。 |
| useSlideWithIndexAsStart | boolean | 此旗標決定如何開始插入：從新投影片開始或從具有指定索引的投影片開始。若 **true**，則資料插入將從具有指定索引的投影片的空白區域開始；若 **false**，則資料將加入至新建立的投影片。 |

**傳回值：**
com.aspose.slides.ISlide[] - 已新增的投影片

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```


從 HTML 文字建立投影片並插入至集合的指定位置。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要插入的位置。 |
| htmlStream | java.io.InputStream | 用作 HTML 檔案來源的串流。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用於取得外部物件的回呼物件。如果此參數為 null，則會忽略所有外部物件。 |
| uri | java.lang.String | 指定 HTML 的 URI，用於解析相對連結。 |

**傳回值：**
com.aspose.slides.ISlide[] - 已新增的投影片。

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```


從 HTML 文字建立投影片並插入至集合的指定位置。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要插入的位置。 |
| htmlStream | java.io.InputStream | 用作 HTML 檔案來源的串流。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用於取得外部物件的回呼物件。如果此參數為 null，則會忽略所有外部物件。 |
| uri | java.lang.String | 指定 HTML 的 URI，用於解析相對連結。 |
| useSlideWithIndexAsStart | boolean | 此旗標決定如何開始插入：從新投影片開始或從具有指定索引的投影片開始。若 **true**，則資料插入將從具有指定索引的投影片的空白區域開始；若 **false**，則資料將加入至新建立的投影片。 |

**傳回值：**
com.aspose.slides.ISlide[] - 已新增的投影片。

### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream)
```


從 HTML 文字建立投影片並插入至集合的指定位置。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要插入的位置。 |
| htmlStream | java.io.InputStream | 用作 HTML 檔案來源的串流。 |

**傳回值：**
com.aspose.slides.ISlide[] - 已新增的投影片

### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```


從 HTML 文字建立投影片並插入至集合的指定位置。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要插入的位置。 |
| htmlStream | java.io.InputStream | 用作 HTML 檔案來源的串流。 |
| useSlideWithIndexAsStart | boolean | 此旗標決定如何開始插入：從新投影片開始或從具有指定索引的投影片開始。若 **true**，則資料插入將從具有指定索引的投影片的空白區域開始；若 **false**，則資料將加入至新建立的投影片。 |

**傳回值：**
com.aspose.slides.ISlide[] - 已新增的投影片

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


將集合中的所有元素複製到指定陣列。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列。 |
| index | int | 目標陣列的起始索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


傳回一個表示集合存取是否同步（執行緒安全）的值。唯讀 boolean。

**傳回值：**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


傳回同步根。唯讀 Object。

**傳回值：**
java.lang.Object