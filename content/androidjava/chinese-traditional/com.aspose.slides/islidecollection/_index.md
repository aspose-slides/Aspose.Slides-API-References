---
title: ISlideCollection
second_title: Aspose.Slides for Android via Java API 參考
description: 表示投影片的集合。
type: docs
url: /zh-hant/com.aspose.slides/islidecollection/
---
**已實作的介面：**
com.aspose.slides.IGenericCollection
```
public interface ISlideCollection extends IGenericCollection<ISlide>
```

表示投影片的集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | 將指定投影片的副本新增至集合的末端。 |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | 將指定投影片的副本新增至指定區段的末端。 |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | 在集合的指定位置插入指定投影片的副本。 |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | 在集合的末端新增一張空白投影片。 |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | 在集合的指定位置插入指定投影片的副本。 |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | 將指定投影片的副本新增至集合的末端。 |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | 在集合的指定位置插入指定投影片的副本。 |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | 將指定來源投影片的副本新增至集合的末端。 |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | 在集合的指定位置插入指定來源投影片的副本。 |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | 從集合中移除第一個出現的特定物件。 |
| [removeAt(int index)](#removeAt-int-) | 從集合中移除指定索引處的元素。 |
| [toArray()](#toArray--) | 建立並返回包含所有投影片的陣列。 |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 建立並返回包含指定範圍內所有投影片的陣列。 |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | 將投影片從集合中移動到指定位置。 |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | 將投影片從集合中移動到指定位置。投影片將從索引開始依照在清單中的出現順序放置。 |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | 返回指定投影片在集合中的索引。 |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | 從 PDF 文件建立投影片，並將它們新增至集合的末端。 |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | 從 PDF 文件建立投影片，並依據 PDF 匯入選項將它們新增至集合的末端。 |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | 從 PDF 文件建立投影片，並將它們新增至集合的末端。 |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | 從 PDF 文件建立投影片，並將它們新增至集合的末端。 |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 從 HTML 文字建立投影片，並將它們新增至集合的末端。 |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | 從 HTML 文字建立投影片，並將它們新增至集合的末端。 |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 從 HTML 文字建立投影片，並將它們新增至集合的末端。 |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | 從 HTML 文字建立投影片，並將它們新增至集合的末端。 |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 從 HTML 文字建立投影片，並在集合的指定位置插入它們。 |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | 從 HTML 文字建立投影片，並在集合的指定位置插入它們。 |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 從 HTML 文字建立投影片，並在集合的指定位置插入它們。 |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | 從 HTML 文字建立投影片，並在集合的指定位置插入它們。 |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | 從 HTML 文字建立投影片，並在集合的指定位置插入它們。 |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | 從 HTML 文字建立投影片，並在集合的指定位置插入它們。 |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | 從 HTML 文字建立投影片，並在集合的指定位置插入它們。 |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | 從 HTML 文字建立投影片，並在集合的指定位置插入它們。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISlide get_Item(int index)
```

取得指定索引處的元素。唯讀 [ISlide](../../com.aspose.slides/islide)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回值：**
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

在不同簡報之間複製投影片時，投影片的母片也可能被複製。內部註冊表用於追蹤自動複製的母片，以防止同一母片產生多個複製。手動複製母片既不會被阻止，也不會被註冊。如果您需要對複製過程有更多控制，請使用 \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) 或 \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) 來複製投影片，[IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) 或 [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) 來複製版面配置，[IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) 來複製母片。 

**傳回值：**
[ISlide](../../com.aspose.slides/islide) - 新的投影片。
### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public abstract ISlide addClone(ISlide sourceSlide, ISection section)
```

將指定投影片的副本新增至指定區段的末端。

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
>      // 現在第二個區段包含第一張投影片的副本。
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要複製的投影片。 |
| section | [ISection](../../com.aspose.slides/isection) | 新投影片所屬的區段。 |

**傳回值：**
[ISlide](../../com.aspose.slides/islide) - 新的投影片。
### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide)
```

在集合的指定位置插入指定投影片的副本。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 新投影片的索引。 |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要複製的投影片。 |

--------------------

在不同簡報之間複製投影片時，投影片的母片也可能被複製。內部註冊表用於追蹤自動複製的母片，以防止同一母片產生多個複製。手動複製母片既不會被阻止，也不會被註冊。如果您需要對複製過程有更多控制，請使用 \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) 或 \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) 來複製投影片，[IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) 來複製母片。 

**傳回值：**
[ISlide](../../com.aspose.slides/islide) - 插入的投影片。
### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addEmptySlide(ILayoutSlide layout)
```

在集合的末端新增一張空白投影片。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 投影片使用的版面配置。 |

**傳回值：**
[ISlide](../../com.aspose.slides/islide) - 新增的投影片。
### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

在集合的指定位置插入指定投影片的副本。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 新投影片的索引。 |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 投影片使用的版面配置。 |

**傳回值：**
[ISlide](../../com.aspose.slides/islide) - 插入的投影片。
### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

將指定投影片的副本新增至集合的末端。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要複製的投影片。 |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 新投影片所使用的版面配置。 |

**傳回值：**
[ISlide](../../com.aspose.slides/islide) - 新的投影片。
### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

在集合的指定位置插入指定投影片的副本。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 新投影片的索引。 |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要複製的投影片。 |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 新投影片所使用的版面配置。 |

**傳回值：**
[ISlide](../../com.aspose.slides/islide) - 插入的投影片。
### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

將指定來源投影片的副本新增至集合的末端。系統會自動依據指定的母片選取相符的版面配置（相同類型或名稱的版面配置）。如果指定的母片中沒有相符的版面配置，則會依據 **allowCloneMissingLayout** 參數決定：為 **true** 時會複製來源投影片的版面配置，為 **false** 時拋出 **PptxEditException**。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要複製的投影片。 |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 新投影片所屬的母片。 |
| allowCloneMissingLayout | boolean | 如果指定的母片中沒有相符的版面配置，則根據此參數決定：為 **true** 時會複製來源投影片的版面配置，為 **false** 時拋出 **PptxEditException**。 |

**傳回值：**
[ISlide](../../com.aspose.slides/islide) - 新的投影片。
### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

在集合的指定位置插入指定來源投影片的副本。系統會自動依據指定的母片選取相符的版面配置（相同類型或名稱的版面配置）。如果指定的母片中沒有相符的版面配置，則會依據 **allowCloneMissingLayout** 參數決定：為 **true** 時會複製來源投影片的版面配置，為 **false** 時拋出 **PptxEditException**。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 新投影片的索引。 |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | 要複製的投影片。 |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 新投影片所屬的母片。 |
| allowCloneMissingLayout | boolean | 如果指定的母片中沒有相符的版面配置，則根據此參數決定：為 **true** 時會複製來源投影片的版面配置，為 **false** 時拋出 **PptxEditException**。 |

**傳回值：**
[ISlide](../../com.aspose.slides/islide) - 插入的投影片。
### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public abstract void remove(ISlide value)
```

從集合中移除第一個出現的特定物件。

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

建立並返回包含所有投影片的陣列。

**傳回值：**
com.aspose.slides.ISlide[] - [ISlide](../../com.aspose.slides/islide) 的陣列
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract ISlide[] toArray(int startIndex, int count)
```

建立並返回包含指定範圍內所有投影片的陣列。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| startIndex | int | 首張要加入之投影片的索引。 |
| count | int | 要加入的投影片數量。 |

**傳回值：**
com.aspose.slides.ISlide[] - [ISlide](../../com.aspose.slides/islide) 的陣列
### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public abstract void reorder(int index, ISlide slide)
```

將投影片從集合中移動到指定位置。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 目標索引。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 要移動的投影片。 |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public abstract void reorder(int index, ISlide[] slides)
```

將投影片從集合中移動到指定位置。投影片將從索引開始依照在清單中的出現順序放置。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 目標索引。 |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | 要移動的投影片。 |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public abstract int indexOf(ISlide slide)
```

返回指定投影片在集合中的索引。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | 要查找的投影片。 |

**傳回值：**
int - 投影片的索引；如果投影片不屬於此集合，則返回 -1。
### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public abstract ISlide[] addFromPdf(String path)
```

從 PDF 文件建立投影片，並將它們新增至集合的末端。

--------------------

> ```
> 範例：
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
com.aspose.slides.ISlide[] - 新增的投影片
### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

從 PDF 文件建立投影片，並依據 PDF 匯入選項將它們新增至集合的末端。

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
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | java.lang.String | PDF 文件的路徑 |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | PDF 匯入選項 |

**傳回值：**
com.aspose.slides.ISlide[] - 新增的投影片
### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
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

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pdfStream | java.io.InputStream | 用作 PDF 文件來源的資料流 |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | PDF 匯入選項 |

**傳回值：**
com.aspose.slides.ISlide[] - 新增的投影片
### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream)
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

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pdfStream | java.io.InputStream | 用作 PDF 文件來源的資料流 |

**傳回值：**
com.aspose.slides.ISlide[] - 新增的投影片
### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

從 HTML 文字建立投影片，並將它們新增至集合的末端。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| htmlText | java.lang.String | 要新增的 HTML。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用於取得外部資源的回呼物件。若為 null，則會忽略所有外部資源。 |
| uri | java.lang.String | 指定 HTML 的 URI，用於解析相對連結。 |

**傳回值：**
com.aspose.slides.ISlide[] - 新增的投影片。
### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText)
```

從 HTML 文字建立投影片，並將它們新增至集合的末端。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| htmlText | java.lang.String | 要新增的 HTML。 |

**傳回值：**
com.aspose.slides.ISlide[] - 新增的投影片
### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

從 HTML 文字建立投影片，並將它們新增至集合的末端。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| htmlStream | java.io.InputStream | 用作 HTML 檔案來源的資料流 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用於取得外部資源的回呼物件。若為 null，則會忽略所有外部資源。 |
| uri | java.lang.String | 指定 HTML 的 URI，用於解析相對連結。 |

**傳回值：**
com.aspose.slides.ISlide[] - 新增的投影片。
### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream)
```

從 HTML 文字建立投影片，並將它們新增至集合的末端。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| htmlStream | java.io.InputStream | 用作 HTML 檔案來源的資料流 |

**傳回值：**
com.aspose.slides.ISlide[] - 新增的投影片
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

從 HTML 文字建立投影片，並在集合的指定位置插入它們。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 插入位置。 |
| htmlText | java.lang.String | 要新增的 HTML。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用於取得外部資源的回呼物件。若為 null，則會忽略所有外部資源。 |
| uri | java.lang.String | 指定 HTML 的 URI，用於解析相對連結。 |

**傳回值：**
com.aspose.slides.ISlide[] - 新增的投影片。
### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText)
```

從 HTML 文字建立投影片，並在集合的指定位置插入它們。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 插入位置。 |
| htmlText | java.lang.String | 要新增的 HTML。 |

**傳回值：**
com.aspose.slides.ISlide[] - 新增的投影片
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

從 HTML 文字建立投影片，並在集合的指定位置插入它們。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 插入位置。 |
| htmlStream | java.io.InputStream | 用作 HTML 檔案來源的資料流 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用於取得外部資源的回呼物件。若為 null，則會忽略所有外部資源。 |
| uri | java.lang.String | 指定 HTML 的 URI，用於解析相對連結。 |

**傳回值：**
com.aspose.slides.ISlide[] - 新增的投影片。
### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

從 HTML 文字建立投影片，並在集合的指定位置插入它們。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 插入位置。 |
| htmlStream | java.io.InputStream | 用作 HTML 檔案來源的資料流 |

**傳回值：**
com.aspose.slides.ISlide[] - 新增的投影片
### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

從 HTML 文字建立投影片，並在集合的指定位置插入它們。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 插入位置。 |
| htmlText | java.lang.String | 要新增的 HTML。 |
| useSlideWithIndexAsStart | boolean | 此旗標決定插入的起始方式：從新投影片開始或從具有指定索引的投影片開始。如果 **true**，則資料插入會從具有指定索引之投影片的空白區域開始；如果 **false**，則資料會加入新建立的投影片。 |

**傳回值：**
com.aspose.slides.ISlide[] - 新增的投影片
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

從 HTML 文字建立投影片，並在集合的指定位置插入它們。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 插入位置。 |
| htmlText | java.lang.String | 要新增的 HTML。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用於取得外部資源的回呼物件。若為 null，則會忽略所有外部資源。 |
| uri | java.lang.String | 指定 HTML 的 URI，用於解析相對連結。 |
| useSlideWithIndexAsStart | boolean | 此旗標決定插入的起始方式：從新投影片開始或從具有指定索引的投影片開始。如果 **true**，則資料插入會從具有指定索引之投影片的空白區域開始；如果 **false**，則資料會加入新建立的投影片。 |

**傳回值：**
com.aspose.slides.ISlide[] - 新增的投影片。
### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

從 HTML 文字建立投影片，並在集合的指定位置插入它們。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 插入位置。 |
| htmlStream | java.io.InputStream | 用作 HTML 檔案來源的資料流 |
| useSlideWithIndexAsStart | boolean | 此旗標決定插入的起始方式：從新投影片開始或從具有指定索引的投影片開始。如果 **true**，則資料插入會從具有指定索引之投影片的空白區域開始；如果 **false**，則資料會加入新建立的投影片。 |

**傳回值：**
com.aspose.slides.ISlide[] - 新增的投影片
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

從 HTML 文字建立投影片，並在集合的指定位置插入它們。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 插入位置。 |
| htmlStream | java.io.InputStream | 用作 HTML 檔案來源的資料流 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 用於取得外部資源的回呼物件。若為 null，則會忽略所有外部資源。 |
| uri | java.lang.String | 指定 HTML 的 URI，用於解析相對連結。 |
| useSlideWithIndexAsStart | boolean | 此旗標決定插入的起始方式：從新投影片開始或從具有指定索引的投影片開始。如果 **true**，則資料插入會從具有指定索引之投影片的空白區域開始；如果 **false**，則資料會加入新建立的投影片。 |

**傳回值：**
com.aspose.slides.ISlide[] - 新增的投影片。