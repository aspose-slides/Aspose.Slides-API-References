---
title: ISlideCollection
second_title: Aspose.Slides for Java API 參考
description: 表示投影片的集合。
type: docs
url: /zh-hant/com.aspose.slides/islidecollection/
---
**所有已實作的介面：**
com.aspose.slides.IGenericCollection
```
public interface ISlideCollection extends IGenericCollection<ISlide>
```

表示一個投影片的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | 將指定投影片的副本新增至集合的末端。 |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | 將指定投影片的副本新增至指定章節的末端。 |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | 將指定投影片的副本插入至集合的指定位置。 |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | 在集合的末端新增一個空白投影片。 |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | 將指定投影片的副本插入至集合的指定位置。 |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | 將指定投影片的副本新增至集合的末端。 |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | 將指定投影片的副本插入至集合的指定位置。 |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | 將指定來源投影片的副本新增至集合的末端。 |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | 將指定來源投影片的副本插入至集合的指定位置。 |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | 從集合中移除第一次出現的特定物件。 |
| [removeAt(int index)](#removeAt-int-) | 從集合中移除指定索引處的元素。 |
| [toArray()](#toArray--) | 建立並回傳包含所有投影片的陣列。 |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 建立並回傳包含指定範圍內所有投影片的陣列。 |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | 將投影片從集合移動至指定位置。 |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | 將投影片從集合移動至指定位置。 |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | 回傳指定投影片在集合中的索引。 |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | 從 PDF 文件建立投影片並將其新增至集合的末端。 |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | 根據 PDF 匯入選項，從 PDF 文件建立投影片並將其新增至集合的末端。 |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | 從 PDF 文件建立投影片並將其新增至集合的末端。 |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | 從 PDF 文件建立投影片並將其新增至集合的末端。 |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 從 HTML 文字建立投影片並將其新增至集合的末端。 |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | 從 HTML 文字建立投影片並將其新增至集合的末端。 |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 從 HTML 文字建立投影片並將其新增至集合的末端。 |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | 從 HTML 文字建立投影片並將其新增至集合的末端。 |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 從 HTML 文字建立投影片並將其插入至集合的指定位置。 |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | 從 HTML 文字建立投影片並將其插入至集合的指定位置。 |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 從 HTML 文字建立投影片並將其插入至集合的指定位置。 |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | 從 HTML 文字建立投影片並將其插入至集合的指定位置。 |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | 從 HTML 文字建立投影片並將其插入至集合的指定位置。 |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | 從 HTML 文字建立投影片並將其插入至集合的指定位置。 |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | 從 HTML 文字建立投影片並將其插入至集合的指定位置。 |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | 從 HTML 文字建立投影片並將其插入至集合的指定位置。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISlide get_Item(int index)
```

取得指定索引處的元素。唯讀 [ISlide](../../com.aspose.slides/islide)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回：**
[ISlide](../../com.aspose.slides/islide)
### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public abstract ISlide addClone(ISlide sourceSlide)
```

將指定投影片的副本新增至集合的末端。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要複製的投影片。 |

--------------------

在不同簡報之間複製投影片時，投影片的母片也可能被複製。系統內部登錄用於追蹤自動複製的母片，以防止同一母片產生多個複本。手動複製母片既不會被阻止，也不會被登錄。如果需要對複製過程有更大的控制，請使用 \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) 或 \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) 來複製投影片，[IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) 或 [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) 來複製版面配置，[IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) 來複製母片。 |
**傳回：**
[ISlide](../../com.aspose.slides/islide) - 新投影片。
### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public abstract ISlide addClone(ISlide sourceSlide, ISection section)
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
>      // 現在第二節包含第一張投影片的副本。
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要複製的投影片。 |
| section | [ISection](../../com.aspose.slides/isection) | 新投影片的章節。 |

**傳回：**
[ISlide](../../com.aspose.slides/islide) - 新投影片。
### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide)
```

將指定投影片的副本插入至集合的指定位置。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 新投影片的索引。 |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要複製的投影片。 |

--------------------

在不同簡報之間複製投影片時，投影片的母片也可能被複製。系統內部登錄用於追蹤自動複製的母片，以防止同一母片產生多個複本。手動複製母片既不會被阻止，也不會被登錄。如果需要對複製過程有更大的控制，請使用 \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) 或 \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) 來複製投影片，[IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) 來複製母片。 |
**傳回：**
[ISlide](../../com.aspose.slides/islide) - 已插入的投影片。
### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addEmptySlide(ILayoutSlide layout)
```

將新空白投影片新增至集合的末端。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 投影片的版面配置。 |

**傳回：**
[ISlide](../../com.aspose.slides/islide) - 已新增的投影片。
### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

將指定投影片的副本插入至集合的指定位置。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 新投影片的索引。 |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 投影片的版面配置。 |

**傳回：**
[ISlide](../../com.aspose.slides/islide) - 已插入的投影片。
### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

將指定投影片的副本新增至集合的末端。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要複製的投影片。 |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 新投影片的版面配置。 |

**傳回：**
[ISlide](../../com.aspose.slides/islide) - 新投影片。
### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

將指定投影片的副本插入至集合的指定位置。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 新投影片的索引。 |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要複製的投影片。 |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 新投影片的版面配置。 |

**傳回：**
[ISlide](../../com.aspose.slides/islide) - 已插入的投影片。
### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

將指定來源投影片的副本新增至集合的末端。系統會自動從指定的母片中選取適當的版面配置（適當的版面配置是與來源投影片版面配置具有相同類型或名稱的版面配置）。如果在指定的母片中找不到適當的版面配置，則會根據 allowCloneMissingLayout 的值決定是複製來源投影片的版面配置（為 true 時）或拋出 PptxEditException（為 false 時）。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要複製的投影片。 |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 新投影片的母片。 |
| allowCloneMissingLayout | boolean | 若指定母片中沒有適當的版面配置，則根據此參數決定是複製來源投影片的版面配置（為 true 時）或拋出 PptxEditException（為 false 時）。 |

**傳回：**
[ISlide](../../com.aspose.slides/islide) - 新投影片。
### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

將指定來源投影片的副本插入至集合的指定位置。系統會自動從指定的母片中選取適當的版面配置（適當的版面配置是與來源投影片版面配置具有相同類型或名稱的版面配置）。如果在指定的母片中找不到適當的版面配置，則會根據 allowCloneMissingLayout 的值決定是複製來源投影片的版面配置（為 true 時）或拋出 PptxEditException（為 false 時）。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 新投影片的索引。 |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要複製的投影片。 |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 新投影片的母片。 |
| allowCloneMissingLayout | boolean | 若指定母片中沒有適當的版面配置，則根據此參數決定是複製來源投影片的版面配置（為 true 時）或拋出 PptxEditException（為 false 時）。 |

**傳回：**
[ISlide](../../com.aspose.slides/islide) - 已插入的投影片。
### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public abstract void remove(ISlide value)
```

從集合中移除第一次出現的特定物件。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | 要從集合中移除的投影片。 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

從集合中移除指定索引處的元素。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要移除之元素的零基索引。 |

### toArray() {#toArray--}
```
public abstract ISlide[] toArray()
```

建立並回傳包含所有投影片的陣列。

**傳回：**
com.aspose.slides.ISlide[] - 包含 [ISlide](../../com.aspose.slides/islide) 的陣列
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract ISlide[] toArray(int startIndex, int count)
```

建立並回傳包含指定範圍內所有投影片的陣列。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| startIndex | int | 要加入的第一張投影片索引。 |
| count | int | 要加入的投影片數量。 |

**傳回：**
com.aspose.slides.ISlide[] - 包含 [ISlide](../../com.aspose.slides/islide) 的陣列
### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public abstract void reorder(int index, ISlide slide)
```

將投影片從集合移動至指定位置。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 目標索引。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 要移動的投影片。 |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public abstract void reorder(int index, ISlide[] slides)
```

將投影片從集合移動至指定位置。投影片會依照在清單中的出現順序，從指定的索引開始依序放置。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 目標索引。 |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | 要移動的投影片。 |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public abstract int indexOf(ISlide slide)
```

回傳指定投影片在集合中的索引。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | 要查找的投影片。 |

**傳回：**
int - 投影片的索引，若投影片不屬於此集合則為 -1
### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public abstract ISlide[] addFromPdf(String path)
```

從 PDF 文件建立投影片並將其新增至集合的末端。

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
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| path | java.lang.String | PDF 文件的路徑 |

**回傳值：**
com.aspose.slides.ISlide[] - Added slides
### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

根據 PDF 匯入選項，從 PDF 文件建立投影片並將其新增至集合的末端。

--------------------

> ```
> 範例：
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
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| path | java.lang.String | PDF 文件的路徑 |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | PDF 匯入選項 |

**回傳值：**
com.aspose.slides.ISlide[] - Added slides
### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

從 PDF 文件建立投影片並將其新增至集合的末端。

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
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| pdfStream | java.io.InputStream | 用作 PDF 文件來源的串流 |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | PDF 匯入選項 |

**回傳值：**
com.aspose.slides.ISlide[] - Added slides
### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream)
```

從 PDF 文件建立投影片並將其新增至集合的末端。

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


**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| pdfStream | java.io.InputStream | 用作 PDF 文件來源的串流 |

**回傳值：**
com.aspose.slides.ISlide[] - Added slides
### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

從 HTML 文字建立投影片並將其新增至集合的末端。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| htmlText | java.lang.String | 要加入的 HTML。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用於擷取外部物件的回呼物件。若此參數為 null，將忽略所有外部物件。 |
| uri | java.lang.String | 指定 HTML 的 URI。用於解析相對連結。 |

**回傳值：**
com.aspose.slides.ISlide[] - Added slides.
### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText)
```

從 HTML 文字建立投影片並將其新增至集合的末端。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| htmlText | java.lang.String | 要加入的 HTML。 |

**回傳值：**
com.aspose.slides.ISlide[] - Added slides
### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

從 HTML 文字建立投影片並將其新增至集合的末端。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| htmlStream | java.io.InputStream | 用作 HTML 檔案來源的串流。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用於擷取外部物件的回呼物件。若此參數為 null，將忽略所有外部物件。 |
| uri | java.lang.String | 指定 HTML 的 URI。用於解析相對連結。 |

**回傳值：**
com.aspose.slides.ISlide[] - Added slides.
### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream)
```

從 HTML 文字建立投影片並將其新增至集合的末端。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| htmlStream | java.io.InputStream | 用作 HTML 檔案來源的串流。 |

**回傳值：**
com.aspose.slides.ISlide[] - Added slides
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

從 HTML 文字建立投影片並將其插入至集合中的指定位置。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 插入的位置。 |
| htmlText | java.lang.String | 要加入的 HTML。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用於擷取外部物件的回呼物件。若此參數為 null，將忽略所有外部物件。 |
| uri | java.lang.String | 指定 HTML 的 URI。用於解析相對連結。 |

**回傳值：**
com.aspose.slides.ISlide[] - Added slides.
### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText)
```

從 HTML 文字建立投影片並將其插入至集合中的指定位置。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 插入的位置。 |
| htmlText | java.lang.String | 要加入的 HTML。 |

**回傳值：**
com.aspose.slides.ISlide[] - Added slides
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

從 HTML 文字建立投影片並將其插入至集合中的指定位置。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 插入的位置。 |
| htmlStream | java.io.InputStream | 用作 HTML 檔案來源的串流。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用於擷取外部物件的回呼物件。若此參數為 null，將忽略所有外部物件。 |
| uri | java.lang.String | 指定 HTML 的 URI。用於解析相對連結。 |

**回傳值：**
com.aspose.slides.ISlide[] - Added slides.
### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

從 HTML 文字建立投影片並將其插入至集合中的指定位置。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 插入的位置。 |
| htmlStream | java.io.InputStream | 用作 HTML 檔案來源的串流。 |

**回傳值：**
com.aspose.slides.ISlide[] - Added slides
### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

從 HTML 文字建立投影片並將其插入至集合中的指定位置。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 插入的位置。 |
| htmlText | java.lang.String | 要加入的 HTML。 |
| useSlideWithIndexAsStart | boolean | 此旗標決定插入的起始方式：從新投影片或從具有指定索引的投影片開始。若 **true**，則資料插入將從具有指定索引的投影片上的空白區域開始。若 **false**，則資料將加入已建立的投影片中。 |

**回傳值：**
com.aspose.slides.ISlide[] - Added slides
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

從 HTML 文字建立投影片並將其插入至集合中的指定位置。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 插入的位置。 |
| htmlText | java.lang.String | 要加入的 HTML。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用於擷取外部物件的回呼物件。若此參數為 null，將忽略所有外部物件。 |
| uri | java.lang.String | 指定 HTML 的 URI。用於解析相對連結。 |
| useSlideWithIndexAsStart | boolean | 此旗標決定插入的起始方式：從新投影片或從具有指定索引的投影片開始。若 **true**，則資料插入將從具有指定索引的投影片上的空白區域開始。若 **false**，則資料將加入已建立的投影片中。 |

**回傳值：**
com.aspose.slides.ISlide[] - Added slides.
### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

從 HTML 文字建立投影片並將其插入至集合中的指定位置。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 插入的位置。 |
| htmlStream | java.io.InputStream | 用作 HTML 檔案來源的串流。 |
| useSlideWithIndexAsStart | boolean | 此旗標決定插入的起始方式：從新投影片或從具有指定索引的投影片開始。若 **true**，則資料插入將從具有指定索引的投影片上的空白區域開始。若 **false**，則資料將加入已建立的投影片中。 |

**回傳值：**
com.aspose.slides.ISlide[] - Added slides
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

從 HTML 文字建立投影片並將其插入至集合中的指定位置。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 插入的位置。 |
| htmlStream | java.io.InputStream | 用作 HTML 檔案來源的串流。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用於擷取外部物件的回呼物件。若此參數為 null，將忽略所有外部物件。 |
| uri | java.lang.String | 指定 HTML 的 URI。用於解析相對連結。 |
| useSlideWithIndexAsStart | boolean | 此旗標決定插入的起始方式：從新投影片或從具有指定索引的投影片開始。若 **true**，則資料插入將從具有指定索引的投影片上的空白區域開始。若 **false**，則資料將加入已建立的投影片中。 |

**回傳值：**
com.aspose.slides.ISlide[] - Added slides.