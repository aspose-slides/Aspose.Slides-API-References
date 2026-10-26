---
title: Presentation
second_title: Aspose.Slides for Android via Java API 參考
description: 表示 Microsoft PowerPoint 簡報。
type: docs
url: /zh-hant/com.aspose.slides/presentation/
---
**繼承:**
java.lang.Object

**已實作的介面:**
[com.aspose.slides.IPresentation](../../com.aspose.slides/ipresentation), com.aspose.slides.IDOMObject
```
public final class Presentation implements IPresentation, IDOMObject
```

表示 Microsoft PowerPoint 簡報。

--------------------

> ```
> The following example shows how to create PowerPoint Presentation.
>   
>  // 實例化一個表示簡報檔案的 Presentation 物件
>  Presentation pres = new Presentation();
>  try {
>      // 取得第一張投影片
>      ISlide slide = pres.getSlides().get_Item(0);
>      // 新增一個類型為線條的自動形狀
>      slide.getShapes().addAutoShape(ShapeType.Line, 50, 150, 300, 0);
>      // 儲存簡報檔案。
>      pres.save("NewPresentation_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>   
>   The following example shows how to open and save Presentation.
>   
>  // 載入 Presentation 中任何支援的檔案，例如 ppt、pptx、odp 等。
>  Presentation pres = new Presentation("Sample.odp");
>  try {
>      // 儲存簡報檔案。
>      pres.save("OutputPresenation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 建構函式

| 建構函式 | 描述 |
| --- | --- |
| [Presentation()](#Presentation--) | 此建構函式從頭開始建立新簡報。 |
| [Presentation(LoadOptions loadOptions)](#Presentation-com.aspose.slides.LoadOptions-) | 此建構函式從頭開始建立新簡報。 |
| [Presentation(InputStream stream)](#Presentation-java.io.InputStream-) | 此建構函式是讀取現有簡報的主要機制。 |
| [Presentation(InputStream stream, LoadOptions loadOptions)](#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-) | 此建構函式是讀取現有簡報的主要機制。 |
| [Presentation(String file)](#Presentation-java.lang.String-) | 此建構函式取得來源檔案路徑，用於讀取簡報內容。 |
| [Presentation(String file, LoadOptions loadOptions)](#Presentation-java.lang.String-com.aspose.slides.LoadOptions-) | 此建構函式取得來源檔案路徑，用於讀取簡報內容。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | 傳回或設定將取代日期時間欄位內容的日期和時間。 |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | 傳回或設定將取代日期時間欄位內容的日期和時間。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 傳回實際的 HeaderFooter 管理員。 |
| [getProtectionManager()](#getProtectionManager--) | 取得此簡報的權限管理員。 |
| [getSlides()](#getSlides--) | 傳回簡報中定義的所有投影片的清單。 |
| [getSections()](#getSections--) | 傳回簡報中定義的所有投影片區段的清單。 |
| [getSlideSize()](#getSlideSize--) | 傳回投影片大小物件。 |
| [getNotesSize()](#getNotesSize--) | 傳回註記投影片大小物件。 |
| [getLayoutSlides()](#getLayoutSlides--) | 傳回簡報中定義的所有版面投影片的清單。 |
| [getMasters()](#getMasters--) | 傳回簡報中定義的所有母片投影片的清單。 |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | 傳回註記母片管理員。 |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | 傳回講義母片管理員。 |
| [getFontsManager()](#getFontsManager--) | 傳回字型管理員。 |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | 傳回形狀的預設文字樣式。 |
| [getCommentAuthors()](#getCommentAuthors--) | 傳回評論作者的集合。 |
| [getDocumentProperties()](#getDocumentProperties--) | 傳回包含標準與自訂文件屬性的 DocumentProperties 物件。 |
| [getImages()](#getImages--) | 傳回簡報中所有影像的集合。 |
| [getAudios()](#getAudios--) | 傳回簡報中所有嵌入式音訊檔案的集合。 |
| [getVideos()](#getVideos--) | 傳回簡報中所有嵌入式視訊檔案的集合。 |
| [getSlideShowSettings()](#getSlideShowSettings--) | 傳回簡報的投影片放映設定。 |
| [getDigitalSignatures()](#getDigitalSignatures--) | 傳回用於簽署簡報的簽章集合。 |
| [getCustomData()](#getCustomData--) | 傳回簡報的自訂資料。 |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | 傳回簡報中的所有自訂資料部件。 |
| [getVbaProject()](#getVbaProject--) | 取得或設定包含簡報巨集的 VBA 專案。 |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | 取得或設定包含簡報巨集的 VBA 專案。 |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | 提供簡報所有投影片（不含母片、版面、註記投影片）中所有超連結的便捷存取。 |
| [getViewProperties()](#getViewProperties--) | 取得簡報範圍的檢視屬性。 |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | 表示簡報中的第一張投影片編號。 |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | 表示簡報中的第一張投影片編號。 |
| [getSensitivityLabels()](#getSensitivityLabels--) | 傳回套用於簡報文件的敏感度標籤集合。 |
| [getSlideById(long id)](#getSlideById-long-) | 依 Id 傳回投影片、母片或版面投影片。 |
| [getSourceFormat()](#getSourceFormat--) | 傳回簡報載入自何種格式的資訊。 |
| [getMasterTheme()](#getMasterTheme--) | 傳回母片主題。 |
| [save(String fname, int format)](#save-java.lang.String-int-) | 將簡報的所有投影片儲存為指定格式的檔案。 |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | 將簡報的所有投影片儲存至指定格式的資料流。 |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | 將簡報的所有投影片儲存為指定格式的檔案，並使用額外選項。 |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | 將簡報的所有投影片儲存至指定格式的資料流，並使用額外選項。 |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | 將簡報的所有投影片儲存為一組代表 XAML 標記的檔案。 |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | 傳回簡報所有投影片的 Image 物件。 |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | 傳回指定投影片的縮圖 Image 物件。 |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | 傳回簡報所有投影片的縮圖 Image 物件（使用自訂縮放）。 |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | 傳回指定投影片的縮圖 Image 物件（使用自訂縮放）。 |
| [getImages(IRenderingOptions options, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | 傳回簡報所有投影片的縮圖 Image 物件（使用指定大小）。 |
| [getImages(IRenderingOptions options, int[] slides, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-) | 傳回指定投影片的縮圖 Image 物件（使用指定大小）。 |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | 將指定的投影片儲存為具有指定格式且保留頁碼的檔案。 |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | 將指定的投影片儲存為具有指定格式且保留頁碼的檔案。 |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | 將指定的投影片儲存為具有指定格式且保留頁碼的資料流。 |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | 將指定的投影片儲存為具有指定格式且保留頁碼的資料流。 |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 將所有投影片中所有可接受形狀的段落中，格式相同的文字片段合併。 |
| [dispose()](#dispose--) | 釋放此 Presentation 物件使用的所有資源。 |
| [getPresentation()](#getPresentation--) | 傳回文字所屬的父簡報。 |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | 以指定的顏色突顯樣本文本的所有匹配項目。 |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | 以指定的顏色突顯樣本文本的所有匹配項目。 |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | 以指定的顏色突顯正規表達式的所有匹配項目。 |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | 將指定文本的所有出現處替換為另一個指定文本。 |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | 將正規表達式的所有匹配項目替換為指定字串。 |

### Presentation() {#Presentation--}
```
public Presentation()
```

此建構函式從頭開始建立新簡報。建立的簡報包含一張空白投影片。

### Presentation(LoadOptions loadOptions) {#Presentation-com.aspose.slides.LoadOptions-}
```
public Presentation(LoadOptions loadOptions)
```

此建構函式從頭開始建立新簡報。建立的簡報包含一張空白投影片。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | 額外的載入選項。 |

### Presentation(InputStream stream) {#Presentation-java.io.InputStream-}
```
public Presentation(InputStream stream)
```

此建構函式是讀取現有簡報的主要機制。

--------------------

> ```
> FileInputStream fis = new FileInputStream("demo.pptx");
>  Presentation pres = new Presentation(fis);
>  fis.close();
> ```

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 輸入資料流。 |

### Presentation(InputStream stream, LoadOptions loadOptions) {#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-}
```
public Presentation(InputStream stream, LoadOptions loadOptions)
```

此建構函式是讀取現有簡報的主要機制。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 輸入資料流。 |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | 額外的載入選項。 |

### Presentation(String file) {#Presentation-java.lang.String-}
```
public Presentation(String file)
```

此建構函式取得來源檔案路徑，用於讀取簡報內容。

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
> ```

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| file | java.lang.String | 輸入檔案。 |

### Presentation(String file, LoadOptions loadOptions) {#Presentation-java.lang.String-com.aspose.slides.LoadOptions-}
```
public Presentation(String file, LoadOptions loadOptions)
```

此建構函式取得來源檔案路徑，用於讀取簡報內容。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| file | java.lang.String | 輸入檔案。 |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | 額外的載入選項。 |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public final Date getCurrentDateTime()
```

傳回或設定將取代日期時間欄位內容的日期和時間。預設為此 Presentation 物件建立的時間。可讀寫 java.util.Date。

**傳回:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public final void setCurrentDateTime(Date value)
```

傳回或設定將取代日期時間欄位內容的日期和時間。預設為此 Presentation 物件建立的時間。可讀寫 java.util.Date。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

傳回 Parent_Immediate 物件。唯讀 IDOMObject。

**傳回:**
com.aspose.slides.IDOMObject

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IPresentationHeaderFooterManager getHeaderFooterManager()
```

傳回實際的 HeaderFooter 管理員。唯讀 [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)。

--------------------

> ```
> The following example shows how to set footer visibility inside Slide of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IBaseSlideHeaderFooterManager headerFooterManager = pres.getSlides().get_Item(0).getHeaderFooterManager();
>      if (!headerFooterManager.isFooterVisible()) // 屬性 IsFooterVisible 用於表示投影片的頁腳佔位符不存在。
>      {
>          headerFooterManager.setFooterVisibility(true); // 方法 SetFooterVisibility 用於使投影片的頁腳佔位符可見。
>      }
>      if (!headerFooterManager.isSlideNumberVisible()) // 屬性 IsSlideNumberVisible 用於表示投影片的頁碼佔位符不存在。
>      {
>          headerFooterManager.setSlideNumberVisibility(true); // 方法 SetSlideNumberVisibility 用於使投影片的頁碼佔位符可見。
>      }
>      if (!headerFooterManager.isDateTimeVisible()) // 屬性 IsDateTimeVisible 用於表示投影片的日期時間佔位符不存在。
>      {
>          headerFooterManager.setDateTimeVisibility(true); // 方法 SetFooterVisibility 用於使投影片的日期時間佔位符可見。
>      }
>      headerFooterManager.setFooterText("Footer text"); // 方法 SetFooterText 用於設定投影片頁腳佔位符的文字。
>      headerFooterManager.setDateTimeText("Date and time text"); // 方法 SetDateTimeText 用於設定投影片日期時間佔位符的文字。
>      pres.save("Presentation.ppt", SaveFormat.Ppt);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set child footer visibility inside Slide.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IMasterSlideHeaderFooterManager headerFooterManager = pres.getMasters().get_Item(0).getHeaderFooterManager();
>      headerFooterManager.setFooterAndChildFootersVisibility(true); // 方法 SetFooterAndChildFootersVisibility 用於使母片及所有子頁腳佔位符可見。
>      headerFooterManager.setSlideNumberAndChildSlideNumbersVisibility(true); // 方法 SetSlideNumberAndChildSlideNumbersVisibility 用於使母片及所有子頁碼佔位符可見。
>      headerFooterManager.setDateTimeAndChildDateTimesVisibility(true); // 方法 SetDateTimeAndChildDateTimesVisibility 用於使母片及所有子日期時間佔位符可見。
> 
>      headerFooterManager.setFooterAndChildFootersText("Footer text"); // 方法 SetFooterAndChildFootersText 用於設定母片及所有子頁腳佔位符的文字。
>      headerFooterManager.setDateTimeAndChildDateTimesText("Date and time text"); // 方法 SetDateTimeAndChildDateTimesText 用於設定母片及所有子日期時間佔位符的文字。
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**傳回:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public final IProtectionManager getProtectionManager()
```

取得此簡報的權限管理員。唯讀 [IProtectionManager](../../com.aspose.slides/iprotectionmanager)。

**傳回:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public final ISlideCollection getSlides()
```

傳回簡報中定義的所有投影片的清單。唯讀 [ISlideCollection](../../com.aspose.slides/islidecollection)。

--------------------

> ```
> The following example shows how to set slides' background color of PowerPoint Presentation.
>  
>  // 實例化代表簡報檔案的 Presentation 類別
>  Presentation pres = new Presentation();
>  try
>  {
>      // 設定第一張 ISlide 的背景顏色為藍色
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.BLUE);
>      pres.save("ContentBG_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set slides' background image of PowerPoint Presentation.
>  
>  // 實例化代表簡報檔案的 Presentation 類別
>  Presentation pres = new Presentation("SetImageAsBackground.pptx");
>  try {
>      // 以影像設定背景
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Picture);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);
>      // Add image to presentation's images collection
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("Tulips.jpg");
>          // 將影像加入簡報的影像集合
>          IPPImage imgx = pres.getImages().addImage(fos);
>          pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().getPicture().setImage(imgx);
>      } finally {
>          if (fos != null) fos.close();
>      }
>      // 將簡報寫入磁碟
>      pres.save("ContentBG_Img_out.pptx", SaveFormat.Pptx);
>  } catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add slide transition Presentation.
>  
>  // 實例化 Presentation 類別以載入來源簡報檔案
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // 在第 1 張投影片套用圓形類型過場效果
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // 在第 2 張投影片套用梳狀類型過場效果
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // 將簡報寫入磁碟
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add advanced slide Transition.
>  
>  // 實例化代表簡報檔案的 Presentation 類別
>  Presentation pres = new Presentation("BetterSlideTransitions.pptx");
>  try
>  {
>      // 在第 1 張投影片套用圓形類型過場效果
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // 設定過場時間為 3 秒
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceAfterTime(3000);
>      // 在第 2 張投影片套用梳狀類型過場效果
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // 設定過場時間為 5 秒
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceAfterTime(5000);
>      // 在第 3 張投影片套用縮放類型過場效果
>      pres.getSlides().get_Item(2).getSlideShowTransition().setType(TransitionType.Zoom);
>      // 設定過場時間為 7 秒
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceAfterTime(7000);
>      // 將簡報寫入磁碟
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**傳回:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public final ISectionCollection getSections()
```

傳回簡報中定義的所有投影片區段的清單。唯讀 [ISectionCollection](../../com.aspose.slides/isectioncollection)。

--------------------

> ```
> The following examples shows how to create Sections in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide defaultSlide = pres.getSlides().get_Item(0);
>      ISlide newSlide1 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide2 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide3 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide4 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISection section1 = pres.getSections().addSection("Section 1", newSlide1);
>      // section1 將在 newSlide2 結束，之後會開始 section2
>      ISection section2 = pres.getSections().addSection("Section 2", newSlide3);
>      pres.save("pres-sections.pptx", SaveFormat.Pptx);
>      pres.getSections().reorderSectionWithSlides(section2, 0);
>      pres.save("pres-sections-moved.pptx", SaveFormat.Pptx);
>      pres.getSections().removeSectionWithSlides(section2);
>      pres.getSections().appendEmptySection("Last empty section");
>      pres.save("pres-section-with-empty.pptx",SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to changing the names of Sections.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISection section = pres.getSections().get_Item(0);
>      section.setName("My section");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**傳回:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public final ISlideSize getSlideSize()
```

傳回投影片大小物件。唯讀 [ISlideSize](../../com.aspose.slides/islidesize)。

--------------------

> ```
> The following example shows how to change the slide size in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres-4x3-aspect-ratio.pptx");
>  try {
>      pres.getSlideSize().setSize(SlideSizeType.OnScreen16x9, SlideSizeScaleType.DoNotScale);
>      pres.save("pres-4x3-aspect-ratio.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set slide size with respect to content scaling for a PowerPoint Presentation.
>  
>  // 實例化一個代表簡報檔案的 Presentation 物件
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation auxPresentation = new Presentation();
>      try {
>          ISlide slide = presentation.getSlides().get_Item(0);
>          // 設定產生的簡報的投影片大小與來源相同
>          presentation.getSlideSize().setSize(540, 720, SlideSizeScaleType.EnsureFit); // 方法 SetSize 用於設定投影片大小，並縮放內容以確保適合
>          presentation.getSlideSize().setSize(SlideSizeType.A4Paper, SlideSizeScaleType.Maximize); // 方法 SetSize 用於設定投影片大小，並將內容最大化
>          // 將簡報儲存至磁碟
>          auxPresentation.save("Set_Size&Type_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (auxPresentation != null) auxPresentation.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  The following example shows how to specifying custom slide sizes in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getSlideSize().setSize(780, 540, SlideSizeScaleType.DoNotScale); // A4 紙張尺寸
>      pres.save("pres-a4-slide-size.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**傳回:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public final INotesSize getNotesSize()
```

傳回註記投影片大小物件。唯讀 [INotesSize](../../com.aspose.slides/inotessize)。

**傳回:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public final IGlobalLayoutSlideCollection getLayoutSlides()
```

傳回簡報中定義的所有版面投影片的清單。唯讀 [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)。

--------------------

您可以透過使用 IMasterSlide.LayoutSlides 屬性來存取用於新增/插入/移除/複製 版面投影片的替代 API。

**傳回:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public final IMasterSlideCollection getMasters()
```

傳回簡報中定義的所有母片投影片的清單。唯讀 [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)。

--------------------

> ```
> The following examples shows how to adding Images to Master Slides of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IMasterSlide masterSlide = slide.getLayoutSlide().getMasterSlide();
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          masterSlide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to change the background color of the master slide of PowerPoint Presentation.
>  
>  // 實例化代表簡報檔案的 Presentation 類別
>  Presentation pres = new Presentation();
>  try
>  {
>      // 將 Master ISlide 的背景顏色設為森林綠
>      pres.getMasters().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.GREEN);
>      // 將簡報寫入磁碟
>      pres.save("SetSlideBackgroundMaster_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add slide layout to PowerPoint Presentation.
>  
>  // 實例化代表簡報檔案的 Presentation 類別
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // 嘗試依版面投影片類型搜尋
>      IMasterLayoutSlideCollection layoutSlides = presentation.getMasters().get_Item(0).getLayoutSlides();
>      ILayoutSlide layoutSlide = null;
>      if (layoutSlides.getByType(SlideLayoutType.TitleAndObject) != null)
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.TitleAndObject);
>      else
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.Title);
> 
>      if (layoutSlide == null)
>      {
>          // 當簡報不包含某些類型的版面時的情況。
>          // 簡報檔案僅包含空白和自訂版面類型。
>          // 但自訂類型的版面投影片有不同的投影片名稱，
>          // 例如「Title」、「Title and Content」等，且可以使用這些
>          // 名稱來選取版面投影片。
>          // 也可以使用佔位形狀類型的集合。例如，
>          // Title 投影片應僅包含 Title 佔位形狀等。
>          for (ILayoutSlide titleAndObjectLayoutSlide : (Iterable) layoutSlides)
>          {
>              if ("Title and Object".equals(titleAndObjectLayoutSlide.getName()))
>              {
>                  layoutSlide = titleAndObjectLayoutSlide;
>                  break;
>              }
>          }
>          if (layoutSlide == null)
>          {
>              for (ILayoutSlide titleLayoutSlide : (Iterable) layoutSlides)
>              {
>                  if ("Title".equals(titleLayoutSlide.getName()))
>                  {
>                      layoutSlide = titleLayoutSlide;
>                      break;
>                  }
>              }
>              if (layoutSlide == null)
>              {
>                  layoutSlide = layoutSlides.getByType(SlideLayoutType.Blank);
>                  if (layoutSlide == null)
>                  {
>                      layoutSlide = layoutSlides.add(SlideLayoutType.TitleAndObject, "Title and Object");
>                  }
>              }
>          }
>      }
>      // 使用新增的版面投影片添加空白投影片
>      presentation.getSlides().insertEmptySlide(0, layoutSlide);
>      // 儲存簡報
>      presentation.save("AddLayoutSlides_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**傳回:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public final IMasterNotesSlideManager getMasterNotesSlideManager()
```

傳回註記母片管理員。唯讀 [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)。

**傳回:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public final IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

傳回講義母片管理員。唯讀 [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)。

**傳回:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public final IFontsManager getFontsManager()
```

傳回字型管理員。唯讀 [IFontsManager](../../com.aspose.slides/ifontsmanager)。

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // 載入簡報
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // 載入要取代的來源字型
>      IFontData sourceFont = new FontData("Arial");
>      IFontData[] allFonts = pres.getFontsManager().getFonts();
>      for (IFontData font : allFonts)
>      {
>          boolean fontAlreadyEmbedded = false;
>          IFontData[] embeddedFonts = pres.getFontsManager().getEmbeddedFonts();
>          for (int i = 0; i < embeddedFonts.length; i++)
>          {
>              if (embeddedFonts[i].equals(font))
>              {
>                  fontAlreadyEmbedded = true;
>                  break;
>              }
>          }
>          if (!fontAlreadyEmbedded) {
>              pres.getFontsManager().addEmbeddedFont(font, EmbedFontCharacters.All);
>          }
>      }
>      // 儲存簡報
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**傳回:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public final ITextStyle getDefaultTextStyle()
```

傳回形狀的預設文字樣式。唯讀 [ITextStyle](../../com.aspose.slides/itextstyle)。

**傳回:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public final ICommentAuthorCollection getCommentAuthors()
```

傳回評論作者的集合。唯讀 [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)。

**傳回:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public final IDocumentProperties getDocumentProperties()
```

傳回包含標準與自訂文件屬性的 DocumentProperties 物件。唯讀 [IDocumentProperties](../../com.aspose.slides/idocumentproperties)。

**傳回:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public final IImageCollection getImages()
```

傳回簡報中所有影像的集合。唯讀 [IImageCollection](../../com.aspose.slides/iimagecollection)。

--------------------

> ```
> The following examples shows how to add image as BLOB in PowerPoint Presentation.
>  
>  // 建立一個新的簡報，將加入影像。
>  Presentation pres = new Presentation();
>  try
>  {
>      // 假設我們有想要加入簡報的大的影像檔案
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // 讓我們將影像加入簡報 - 我們選擇 KeepLocked 行為，因為我們
>          // // 不打算存取 "largeImage.png" 檔案。
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // 儲存簡報。即使輸出大型簡報，記憶體消耗
>          // 在 pres 物件的生命週期中仍保持很低
>          pres.save("presentationWithLargeImage.pptx", SaveFormat.Pptx);
>      }
>      finally
>      {
>          fip.close();
>      }
>  }
>  catch (java.io.IOException e) { }
>  finally
>  {
>      pres.dispose();
>  }
>  
>  The following examples add a hyperlink to an image in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          // 將影像加入簡報
>          IPPImage image = pres.getImages().addImage(fos);
>          // 在第 1 張投影片上建立圖片框，基於先前加入的影像
>          IPictureFrame pictureFrame = pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>          pictureFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>          pictureFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      } finally {
>          if (fos != null) fos.close();
>      }
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch (IOException e){ }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**傳回:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public final IAudioCollection getAudios()
```

傳回簡報中所有嵌入式音訊檔案的集合。唯讀 [IAudioCollection](../../com.aspose.slides/iaudiocollection)。

--------------------

> ```
> The following examples shows how to add a hyperlink to an audio file.
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("audio.mp3");
>          IAudio audio = pres.getAudios().addAudio(fos);
>          IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(10, 10, 100, 100, audio);
>          audioFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>          audioFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      } finally {
>          if (fos != null) fos.close();
>      }
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) {}
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**傳回:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public final IVideoCollection getVideos()
```

傳回簡報中所有嵌入式視訊檔案的集合。唯讀 [IVideoCollection](../../com.aspose.slides/ivideocollection)。

--------------------

> ```
> The following examples shows how to create embedded Video Frame in a PowerPoint Presentation.
>  
>  // 實例化代表 PPTX 的 Presentation 類別
>  Presentation pres = new Presentation();
>  try {
>      // 取得第一張投影片
>      ISlide sld = pres.getSlides().get_Item(0);
>      // 在簡報中嵌入影片
>      IVideo vid = pres.getVideos().addVideo(new FileInputStream("Wildlife.mp4"));
>      // 新增影片框
>      IVideoFrame vf = sld.getShapes().addVideoFrame(50, 150, 300, 350, vid);
>      // 設定影片到影片框
>      vf.setEmbeddedVideo(vid);
>      // 設定影片的播放模式與音量
>      vf.setPlayMode(VideoPlayModePreset.Auto);
>      vf.setVolume(AudioVolumeMode.Loud);
>      // 將 PPTX 檔案寫入磁碟
>      pres.save("VideoFrame_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add a video passing path to the video file directly into AddVideoFrame method for PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide sld = pres.getSlides().get_Item(0);
>      IVideoFrame vf = sld.getShapes().addVideoFrame(50, 150, 300, 150, "video1.avi");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add large file through BLOB to a Presentation.
>  
>  // 建立一個新的簡報，將加入影片
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fileStream = new FileInputStream("veryLargeVideo.avi");
>      try {
>          // 讓我們將影片加入簡報 - 我們選擇 KeepLocked 行為，因為我們
>          // 不打算存取 "veryLargeVideo.avi" 檔案。
>          IVideo video = pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addVideoFrame(0, 0, 480, 270, video);
>          // 儲存簡報。即使輸出大型簡報，記憶體消耗
>          // 在 pres 物件的生命週期中保持低量
>          pres.save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
>      } finally {
>          if (fileStream != null) fileStream.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to export large file through BLOB from PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  // 鎖定來源檔案且不將其載入記憶體
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  // 建立 Presentation 實例，鎖定 "hugePresentationWithAudiosAndVideos.pptx" 檔案。
>  Presentation pres = new Presentation("Large  Video File Test1.pptx", loadOptions);
>  try {
>      // 讓我們將每個影片保存為檔案。為了防止高記憶體使用，我們需要一個緩衝區來傳輸資料
>      // 從簡報的影片串流到新建立的影片檔案的串流。
>      byte[] buffer = new byte[81024];
>      // 迭代影片
>      for (int index = 0; index < pres.getVideos().size(); index++) {
>          IVideo video = pres.getVideos().get_Item(index);
>          // 開啟簡報的影片串流。請注意，我們刻意避免存取屬性
>          // 如 video.BinaryData - 因為此屬性回傳包含完整影片的位元組陣列，接著
>          // 會將位元組載入記憶體。我們使用 video.GetStream，它會回傳 Stream，且不會
>          // 需要我們將完整影片載入記憶體。
>          InputStream presVideoStream = video.getStream();
>          try {
>              FileOutputStream outputFileStream = new FileOutputStream("video{index}.avi");
>              try {
>                  int bytesRead;
>                  while ((bytesRead = presVideoStream.read(buffer, 0, buffer.length)) > 0) {
>                      outputFileStream.write(buffer, 0, bytesRead);
>                  }
>              } finally {
>                  if (outputFileStream != null) outputFileStream.close();
>              }
>          } finally {
>              if (presVideoStream != null) presVideoStream.close();
>          }
>          // 無論影片或簡報大小如何，記憶體消耗都會保持低
>      }
>      // 如有需要，您可以對音訊檔案套用相同步驟。
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add a hyperlink to a video in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.avi")));
>      IVideoFrame videoFrame = pres.getSlides().get_Item(0).getShapes().addVideoFrame(10, 10, 100, 100, video);
>      videoFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      videoFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to create Video Frame with Video from Web Source in a PowerPoint Presentation.
>  
>  public static void run()
>  {
>      Presentation pres = new Presentation();
>      try {
>          addVideoFromYouTube(pres, "Tj75Arhq5ho");
>          pres.save("AddVideoFrameFromWebSource_out.pptx", SaveFormat.Pptx);
>      } catch(IOException e) {
>      } finally {
>          if (pres != null) pres.dispose();
>      }
>  }
>  private static void addVideoFromYouTube(Presentation pres, String videoId) throws IOException
>  {
>      // 新增 videoFrame
>      IVideoFrame videoFrame = pres.getSlides().get_Item(0).getShapes().addVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
>      videoFrame.setPlayMode(VideoPlayModePreset.Auto);
> 
>      // 載入縮圖
>      String thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
>      URL url = new URL(thumbnailUri);
>      URLConnection connection = url.openConnection();
>      connection.setConnectTimeout(5000);
>      connection.setReadTimeout(10000);
>      InputStream input = connection.getInputStream();
>      ByteArrayOutputStream output = new ByteArrayOutputStream();
>      try
>      {
>          byte[] buffer = new byte[8192];
>          for (int count; (count = input.read(buffer)) > 0; )
>          {
>              output.write(buffer, 0, count);
>          }
>          videoFrame.getPictureFormat().getPicture().setImage(pres.getImages().addImage(output.toByteArray()));
>      } finally {
>          if (input != null) input.close();
>          if (output != null) output.close();
>      }
>  }
>  
>  The following examples shows how to extract Video from slide of PowerPoint Presentation.
>  
>  // 實例化代表簡報檔案的 Presentation 物件
>  Presentation presentation = new Presentation("Video.pptx");
>  try {
>      for (ISlide slide : presentation.getSlides())
>      {
>          for (IShape shape : presentation.getSlides().get_Item(0).getShapes())
>          {
>              if (shape instanceof VideoFrame)
>              {
>                  IVideoFrame vf = (IVideoFrame) shape;
>                  String type = vf.getEmbeddedVideo().getContentType();
>                  int ss = type.lastIndexOf('/');
>                  type = type.substring(ss + 1);
>                  byte[] buffer = vf.getEmbeddedVideo().getBinaryData();
>                  FileOutputStream fop = new FileOutputStream("NewVideo_out." + type);
>                  try
>                  {
>                      fop.write(buffer);
>                      fop.flush();
>                      fop.close();
>                  }
>                  finally
>                  {
>                      if (presentation != null) presentation.dispose();
>                  }
>              }
>          }
>      }
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**傳回:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getSlideShowSettings() {#getSlideShowSettings--}
```
public final SlideShowSettings getSlideShowSettings()
```

傳回簡報的投影片放映設定。

**傳回:**
[SlideShowSettings](../../com.aspose.slides/slideshowsettings)

### getDigitalSignatures() {#getDigitalSignatures--}
```
public final IDigitalSignatureCollection getDigitalSignatures()
```

傳回用於簽署簡報的簽章集合。唯讀 [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)。

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          for (IDigitalSignature signature : pres.getDigitalSignatures())
>          {
>             System.out.println(signature.getCertificate().hashCode() + ", "
>                   + signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
>             allSignaturesAreValid &= signature.isValid();
>          }
>          if (allSignaturesAreValid)
>             System.out.println("Presentation is genuine, all signatures are valid.");
>          else
>             System.out.println("Presentation has been modified since signing.");
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**傳回:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)

### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

傳回簡報的自訂資料。唯讀 [ICustomData](../../com.aspose.slides/icustomdata)。

**傳回:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public final ICustomXmlPart[] getAllCustomXmlParts()
```

傳回簡報中的所有自訂資料部件。唯讀 ICustomXmlPart[]。

--------------------

> ```
> The following examples show how to clear all custom xml parts from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("PresentationWithCustomXml.pptx");
>  try {
>      // 遍歷所有自訂 XML 部件
>      for (ICustomXmlPart item : pres.getAllCustomXmlParts())
>      {
>          item.remove();
>      }
>      pres.save("out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```

**傳回:**
com.aspose.slides.ICustomXmlPart[]

### getVbaProject() {#getVbaProject--}
```
public final IVbaProject getVbaProject()
```

取得或設定包含簡報巨集的 VBA 專案。可讀寫 [IVbaProject](../../com.aspose.slides/ivbaproject)。

**傳回:**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public final void setVbaProject(IVbaProject value)
```

取得或設定包含簡報巨集的 VBA 專案。可讀寫 [IVbaProject](../../com.aspose.slides/ivbaproject)。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

提供簡報所有投影片（不含母片、版面、註記投影片）中所有超連結的便捷存取。唯讀 [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)。

**傳回:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public final IViewProperties getViewProperties()
```

取得簡報範圍的檢視屬性。唯讀 [IViewProperties](../../com.aspose.slides/iviewproperties)。

**傳回:**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public final int getFirstSlideNumber()
```

表示簡報中的第一張投影片編號

**傳回:**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public final void setFirstSlideNumber(int value)
```

表示簡報中的第一張投影片編號

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabelCollection getSensitivityLabels()
```

傳回套用於簡報文件的敏感度標籤集合。唯讀 [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)。

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // 列印已套用的標籤
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // 新增標籤
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // 從原則取得敏感度標籤 Id
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // 從原則取得 Azure AD 站點識別碼
>      ISensitivityLabel label = sensitivityLabels.add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType.Privileged);
>      label.getContentMarkTypes().addItem(SensitivityLabelContentType.Footer);
> 
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**傳回:**
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)

### getSlideById(long id) {#getSlideById-long-}
```
public final IBaseSlide getSlideById(long id)
```

依 Id 傳回投影片、母片或版面投影片。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| id | long | 投影片的 Id。 |

**傳回:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide 物件。

### getSourceFormat() {#getSourceFormat--}
```
public final int getSourceFormat()
```

傳回簡報載入自何種格式的資訊。唯讀 [SourceFormat](../../com.aspose.slides/sourceformat)。

**傳回:**
int

### getMasterTheme() {#getMasterTheme--}
```
public final IMasterTheme getMasterTheme()
```

傳回母片主題。唯讀 [IMasterTheme](../../com.aspose.slides/imastertheme)。

--------------------

> ```
> 以下範例顯示如何透過變更 PowerPoint 簡報元素的部分來修改主題效果。
>  
>  //實例化代表簡報檔案的 Presentation 物件
>  Presentation pres = new Presentation("Subtle_Moderate_Intense.pptx");
>  try {
>      pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(0).getFillFormat().getSolidFillColor().setColor(Color.RED);
>      ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).setFillType(FillType.Solid);
>      ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getSolidFillColor().setColor(Color.GREEN);
>      ((EffectStyle)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getEffectFormat().getOuterShadowEffect().setDistance(10f);
>      pres.save("Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**傳回:**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### save(String fname, int format) {#save-java.lang.String-int-}
```
public final void save(String fname, int format)
```

將簡報的所有投影片儲存為指定格式的檔案。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| fname | java.lang.String | 要建立的檔案路徑。 |
| format | int | 匯出資料的格式。 |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int format)
```

將簡報的所有投影片儲存至指定格式的資料流。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 輸出資料流。 |
| format | int | 匯出資料的格式。 |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int format, ISaveOptions options)
```

將簡報的所有投影片儲存為指定格式的檔案，並使用額外選項。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| fname | java.lang.String | 要建立的檔案路徑。 |
| format | int | 匯出資料的格式。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 額外的格式選項。 |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int format, ISaveOptions options)
```

將簡報的所有投影片儲存至指定格式的資料流，並使用額外選項。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 輸出資料流。 |
| format | int | 匯出資料的格式。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 額外的格式選項。 |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public final void save(IXamlOptions options)
```

將簡報的所有投影片儲存為一組代表 XAML 標記的檔案。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      XamlOptions xamlOptions = new XamlOptions();
>      xamlOptions.setExportHiddenSlides(true);
> 
>      pres.save(xamlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | XAML 格式選項。 |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public final IImage[] getImages(IRenderingOptions options)
```

傳回簡報所有投影片的 Image 物件。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff 選項。 |

**傳回:**
com.aspose.slides.IImage[] - Image 物件。

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides)
```

傳回指定投影片的縮圖 Image 物件。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff 選項。 |
| slides | int[] | 投影片位置陣列，從 1 開始。 |

**傳回:**
com.aspose.slides.IImage[] - Image 物件。

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

傳回簡報所有投影片的縮圖 Image 物件（使用自訂縮放）。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff 選項。 |
| scaleX | float | 在 X 軸方向的縮放比例。 |
| scaleY | float | 在 Y 軸方向的縮放比例。 |

**傳回:**
com.aspose.slides.IImage[] - Image 物件。

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

傳回指定投影片的縮圖 Image 物件（使用自訂縮放）。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff 選項。 |
| slides | int[] | 投影片位置陣列，從 1 開始。 |
| scaleX | float | 在 X 軸方向的縮放比例。 |
| scaleY | float | 在 Y 軸方向的縮放比例。 |

**傳回:**
com.aspose.slides.IImage[] - Image 物件。

### getImages(IRenderingOptions options, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public final IImage[] getImages(IRenderingOptions options, Size imageSize)
```

傳回簡報所有投影片的縮圖 Image 物件（使用指定大小）。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff 選項。 |
| imageSize | [Size](../../com.aspose.slides.android/size) | 要建立的影像大小。 |

**傳回:**
com.aspose.slides.IImage[] - Image 物件。

### getImages(IRenderingOptions options, int[] slides, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, Size imageSize)
```

傳回指定投影片的縮圖 Image 物件（使用指定大小）。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff 選項。 |
| slides | int[] | 投影片位置陣列，從 1 開始。 |
| imageSize | [Size](../../com.aspose.slides.android/size) | 要建立的影像大小。 |

**傳回:**
com.aspose.slides.IImage[] - Image 物件。

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public final void save(String fname, int[] slides, int format)
```

將指定的投影片儲存為具有指定格式且保留頁碼的檔案。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| fname | java.lang.String | 要建立的檔案路徑。 |
| slides | int[] | 投影片位置陣列，從 1 開始。 |
| format | int | 匯出資料的格式。 |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int[] slides, int format, ISaveOptions options)
```

將指定的投影片儲存為具有指定格式且保留頁碼的檔案。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| fname | java.lang.String | 要建立的檔案路徑。 |
| slides | int[] | 投影片位置陣列，從 1 開始。 |
| format | int | 匯出資料的格式。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 額外的格式選項。 |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public final void save(OutputStream stream, int[] slides, int format)
```

將指定的投影片儲存為具有指定格式且保留頁碼的資料流。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 輸出資料流。 |
| slides | int[] | 投影片位置陣列，從 1 開始。 |
| format | int | 匯出資料的格式。 |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

將指定的投影片儲存為具有指定格式且保留頁碼的資料流。

--------------------

> ```
> The following example shows how to convert PowerPoint to PNG.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail().compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PNG with custom dimensions.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      float scaleX = 2f;
>      float scaleY = 2f;
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail(scaleX, scaleY).compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PNG with custom size.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      com.aspose.slides.android.Size size = new com.aspose.slides.android.Size(960, 720);
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail(size).compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 輸出資料流。 |
| slides | int[] | 投影片位置陣列，從 1 開始。 |
| format | int | 匯出資料的格式。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 額外的格式選項。 |

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

將所有投影片中所有可接受形狀的段落中，格式相同的文字片段合併。

### dispose() {#dispose--}
```
public final void dispose()
```

釋放此 Presentation 物件使用的所有資源。

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

傳回文字所屬的父簡報。唯讀 [IPresentation](../../com.aspose.slides/ipresentation)。

**傳回:**
[IPresentation](../../com.aspose.slides/ipresentation)

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public final void highlightText(String text, Integer highlightColor)
```

以指定的顏色突顯樣本文本的所有匹配項目。

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // 突顯所有單獨的 'the' 出現
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要突顯的文字。 |
| highlightColor | java.lang.Integer | 用於突顯文字的顏色。 |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

以指定的顏色突顯樣本文本的所有匹配項目。

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // 突顯所有單獨的 'the' 出現
>      presentation.highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要突顯的文字。 |
| highlightColor | java.lang.Integer | 用於突顯文字的顏色。 |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | 文字搜尋選項 [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 接收搜尋結果的回呼物件 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

以指定的顏色突顯正規表達式的所有匹配項目。

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // 突顯所有長度為 10 個字元或更長的單詞
>      presentation.highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| regex | java.util.regex.Pattern | 用於取得要突顯字串的正規表達式。 |
| highlightColor | java.lang.Integer | 用於突顯文字的顏色。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 接收搜尋結果的回呼物件 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

將指定文本的所有出現處替換為另一個指定文本。

> ```
>     The  ...  ...
```

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| oldText | java.lang.String | 要被取代的字串。 |
| newText | java.lang.String | 用來取代 oldText 所有出現處的字串。 |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | 文字搜尋選項 [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 接收搜尋結果的回呼物件 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

將正規表達式的所有匹配項目替換為指定字串。

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // 用 '***' 替換所有長度為 10 個字元或更長的單詞
>      presentation.replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| regex | java.util.regex.Pattern | 用於取得要取代字串的正規表達式。 |
| newText | java.lang.String | 用來取代所有符合字串的字串。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 接收搜尋結果的回呼物件 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |