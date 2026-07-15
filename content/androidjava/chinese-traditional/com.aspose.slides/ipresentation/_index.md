---
title: IPresentation
second_title: Aspose.Slides for Android via Java API 參考
description: 簡報文件
type: docs
url: /zh-hant/com.aspose.slides/ipresentation/
---
**所有已實作的介面：**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent), com.aspose.ms.System.IDisposable
```
public interface IPresentation extends IPresentationComponent, System.IDisposable
```

簡報文件
## 方法

| 方法 | 說明 |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | 傳回或設定將取代日期時間欄位內容的日期和時間。 |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | 傳回或設定將取代日期時間欄位內容的日期和時間。 |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 傳回簡報的 HeaderFooter 管理器。 |
| [getProtectionManager()](#getProtectionManager--) | 取得此簡報權限的管理器。 |
| [getSlides()](#getSlides--) | 傳回簡報中定義的所有投影片的清單。 |
| [getSections()](#getSections--) | 傳回簡報中定義的所有投影片區段的清單。 |
| [getSlideSize()](#getSlideSize--) | 傳回投影片尺寸物件。 |
| [getNotesSize()](#getNotesSize--) | 傳回備註投影片尺寸物件。 |
| [getLayoutSlides()](#getLayoutSlides--) | 傳回簡報中定義的所有版面投影片的清單。 |
| [getMasters()](#getMasters--) | 傳回簡報中定義的所有母片投影片的清單。 |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | 傳回備註母片管理器。 |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | 傳回講義母片管理器。 |
| [getFontsManager()](#getFontsManager--) | 傳回字型管理器。 |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | 傳回形狀的預設文字樣式。 |
| [getCommentAuthors()](#getCommentAuthors--) | 傳回評論作者的集合。 |
| [getDocumentProperties()](#getDocumentProperties--) | 傳回 DocumentProperties 物件，其中包含標準和自訂文件屬性。 |
| [getImages()](#getImages--) | 傳回簡報中所有影像的集合。 |
| [getAudios()](#getAudios--) | 傳回簡報中所有內嵌音訊檔案的集合。 |
| [getVideos()](#getVideos--) | 傳回簡報中所有內嵌視訊檔案的集合。 |
| [getCustomData()](#getCustomData--) | 傳回簡報的自訂資料。 |
| [getVbaProject()](#getVbaProject--) | 取得包含簡報巨集的 VBA 專案。 |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | 取得包含簡報巨集的 VBA 專案。 |
| [getSourceFormat()](#getSourceFormat--) | 傳回簡報所載入的檔案格式資訊。 |
| [getMasterTheme()](#getMasterTheme--) | 傳回簡報的母片主題。 |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | 提供簡便的方式存取所有簡報投影片（不含母片、版面、備註投影片）中的超連結。 |
| [getViewProperties()](#getViewProperties--) | 取得簡報全域檢視屬性。 |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | 表示簡報中的第一張投影片編號。 |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | 表示簡報中的第一張投影片編號。 |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | 傳回簡報中所有自訂資料部件。 |
| [getDigitalSignatures()](#getDigitalSignatures--) | 傳回用於簽署簡報的簽章集合。 |
| [getSensitivityLabels()](#getSensitivityLabels--) | 傳回套用於簡報文件的敏感度標籤集合。 |
| [save(String fname, int format)](#save-java.lang.String-int-) | 將簡報的所有投影片存檔為指定格式的檔案。 |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | 將簡報的所有投影片以指定格式寫入串流。 |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | 將簡報的所有投影片存檔為指定格式的檔案，並使用其他選項。 |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | 將簡報的所有投影片以指定格式寫入串流，並使用其他選項。 |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Saves specified slides of a presentation to a file with the specified format. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Saves specified slides of a presentation to a file with the specified format. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Saves specified slides of a presentation to a stream in the specified format. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Saves specified slides of a presentation to a stream in the specified format. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | 將簡報的所有投影片存為一組表示 XAML 標記的檔案。 |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | 傳回簡報所有投影片的縮圖影像物件。 |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | 傳回指定投影片的縮圖 IImage 物件。 |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | 傳回簡報所有投影片的縮圖影像物件，使用自訂比例。 |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | 傳回指定投影片的縮圖影像物件，使用自訂比例。 |
| [getImages(IRenderingOptions options, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | 傳回簡報所有投影片的縮圖影像物件，使用指定尺寸。 |
| [getImages(IRenderingOptions options, int[] slides, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-) | 傳回指定投影片的縮圖影像物件，使用指定尺寸。 |
| [getSlideById(long id)](#getSlideById-long-) | 傳回依 Id 取得的 Slide、MasterSlide 或 LayoutSlide。 |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 合併所有投影片中所有可接受形狀的段落內格式相同的文字區塊。 |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | 使用指定顏色突顯所有符合樣本文字的項目。 |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | 使用指定顏色突顯所有符合樣本文字的項目。 |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | 使用指定顏色突顯所有符合正規表達式的項目。 |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | 將所有指定文字的出現處取代為另一指定文字。 |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | 將所有符合正規表達式的項目取代為指定字串。 |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

傳回或設定將取代日期時間欄位內容的日期和時間。預設為此 Presentation 物件建立的時間。可讀寫 java.util.Date。

**傳回:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

傳回或設定將取代日期時間欄位內容的日期和時間。預設為此 Presentation 物件建立的時間。可讀寫 java.util.Date。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

傳回簡報的 HeaderFooter 管理器。唯讀 [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)。

**傳回:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

取得此簡報權限的管理器。唯讀 [IProtectionManager](../../com.aspose.slides/iprotectionmanager)。

**傳回:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

傳回簡報中定義的所有投影片的清單。唯讀 [ISlideCollection](../../com.aspose.slides/islidecollection)。

**傳回:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

傳回簡報中定義的所有投影片區段的清單。唯讀 [ISectionCollection](../../com.aspose.slides/isectioncollection)。

**傳回:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

傳回投影片尺寸物件。唯讀 [ISlideSize](../../com.aspose.slides/islidesize)。

**傳回:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

傳回備註投影片尺寸物件。唯讀 [INotesSize](../../com.aspose.slides/inotessize)。

**傳回:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

傳回簡報中定義的所有版面投影片的清單。唯讀 [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)。

--------------------

您可以透過使用 IMasterSlide.LayoutSlides 屬性來存取用於新增/插入/移除/複製 版面投影片的替代 API。

**傳回:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

傳回簡報中定義的所有母片投影片的清單。唯讀 [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)。

**傳回:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

傳回備註母片管理器。唯讀 [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)。

**傳回:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

傳回講義母片管理器。唯讀 [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)。

**傳回:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

傳回字型管理器。唯讀 [IFontsManager](../../com.aspose.slides/ifontsmanager)。

**傳回:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

傳回形狀的預設文字樣式。唯讀 [ITextStyle](../../com.aspose.slides/itextstyle)。

**傳回:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

傳回評論作者的集合。唯讀 [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)。

**傳回:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

傳回 DocumentProperties 物件，其中包含標準和自訂文件屬性。唯讀 [IDocumentProperties](../../com.aspose.slides/idocumentproperties)。

**傳回:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

傳回簡報中所有影像的集合。唯讀 [IImageCollection](../../com.aspose.slides/iimagecollection)。

**傳回:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

傳回簡報中所有內嵌音訊檔案的集合。唯讀 [IAudioCollection](../../com.aspose.slides/iaudiocollection)。

**傳回:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

傳回簡報中所有內嵌視訊檔案的集合。唯讀 [IVideoCollection](../../com.aspose.slides/ivideocollection)。

**傳回:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

傳回簡報的自訂資料。唯讀 [ICustomData](../../com.aspose.slides/icustomdata)。

**傳回:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```

取得包含簡報巨集的 VBA 專案。可讀寫 [IVbaProject](../../com.aspose.slides/ivbaproject)。

**傳回:**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

取得包含簡報巨集的 VBA 專案。可讀寫 [IVbaProject](../../com.aspose.slides/ivbaproject)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

傳回簡報所載入的檔案格式資訊。唯讀 [SourceFormat](../../com.aspose.slides/sourceformat)。

**傳回:**
int

### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

傳回簡報的母片主題。唯讀 [IMasterTheme](../../com.aspose.slides/imastertheme)。

**傳回:**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

提供簡便的方式存取所有簡報投影片（不含母片、版面、備註投影片）中的超連結。唯讀 [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)。

**傳回:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

取得簡報全域檢視屬性。唯讀 [IViewProperties](../../com.aspose.slides/iviewproperties)。

**傳回:**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```

表示簡報中的第一張投影片編號。可讀寫 int。

**傳回:**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

表示簡報中的第一張投影片編號。可讀寫 int。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

傳回簡報中所有自訂資料部件。唯讀 ICustomXmlPart[]。

**傳回:**
com.aspose.slides.ICustomXmlPart[]

### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
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
>                    + signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
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

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabelCollection getSensitivityLabels()
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
>      // 新增新的標籤
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

### save(String fname, int format) {#save-java.lang.String-int-}
```
public abstract void save(String fname, int format)
```

將簡報的所有投影片存檔為指定格式的檔案。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fname | java.lang.String | 要建立的檔案路徑。 |
| format | int | 匯出資料的格式。 |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

將簡報的所有投影片以指定格式寫入串流。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 輸出串流。 |
| format | int | 匯出資料的格式。 |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```

將簡報的所有投影片存檔為指定格式的檔案，並使用其他選項。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fname | java.lang.String | 要建立的檔案路徑。 |
| format | int | 匯出資料的格式。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 其他格式選項。 |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```

將簡報的所有投影片以指定格式寫入串流，並使用其他選項。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 輸出串流。 |
| format | int | 匯出資料的格式。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 其他格式選項。 |

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```

將指定投影片存檔為指定格式的檔案。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fname | java.lang.String | 要建立的檔案路徑。 |
| slides | int[] | 投影片位置陣列，起始編號為 1。 |
| format | int | 匯出資料的格式。 |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```

將指定投影片存檔為指定格式的檔案。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fname | java.lang.String | 要建立的檔案路徑。 |
| slides | int[] | 投影片位置陣列，起始編號為 1。 |
| format | int | 匯出資料的格式。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 其他格式選項。 |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```

將指定投影片以指定格式寫入串流。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 輸出串流。 |
| slides | int[] | 投影片位置陣列，起始編號為 1。 |
| format | int | 匯出資料的格式。 |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

將指定投影片以指定格式寫入串流。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 輸出串流。 |
| slides | int[] | 投影片位置陣列，起始編號為 1。 |
| format | int | 匯出資料的格式。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 其他格式選項。 |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
```

將簡報的所有投影片存為一組表示 XAML 標記的檔案。

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
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | XAML 格式的選項。 |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage[] getImages(IRenderingOptions options)
```

傳回簡報所有投影片的縮圖影像物件。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 渲染選項。 |

**傳回:**
com.aspose.slides.IImage[] - IImage 物件。

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```

傳回指定投影片的縮圖 IImage 物件。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 渲染選項。 |
| slides | int[] | 投影片位置陣列，起始編號為 1。 |

**傳回:**
com.aspose.slides.IImage[] - IImage 物件。

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

傳回簡報所有投影片的縮圖影像物件，使用自訂比例。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 渲染選項。 |
| scaleX | float | 在 X 軸方向上縮放此縮圖的比例值。 |
| scaleY | float | 在 Y 軸方向上縮放此縮圖的比例值。 |

**傳回:**
com.aspose.slides.IImage[] - Bitmap 物件。

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

傳回指定投影片的縮圖影像物件，使用自訂比例。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 渲染選項。 |
| slides | int[] | 投影片位置陣列，起始編號為 1。 |
| scaleX | float | 在 X 軸方向上縮放此縮圖的比例值。 |
| scaleY | float | 在 Y 軸方向上縮放此縮圖的比例值。 |

**傳回:**
com.aspose.slides.IImage[] - IImage 物件。

### getImages(IRenderingOptions options, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, Size imageSize)
```

傳回簡報所有投影片的縮圖影像物件，使用指定尺寸。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 渲染選項。 |
| imageSize | [Size](../../com.aspose.slides.android/size) | 要建立的影像尺寸。 |

**傳回:**
com.aspose.slides.IImage[] - IImage 物件。

### getImages(IRenderingOptions options, int[] slides, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Size imageSize)
```

傳回指定投影片的縮圖影像物件，使用指定尺寸。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 渲染選項。 |
| slides | int[] | 投影片位置陣列，起始編號為 1。 |
| imageSize | [Size](../../com.aspose.slides.android/size) | 要建立的影像尺寸。 |

**傳回:**
com.aspose.slides.IImage[] - IImage 物件。

### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```

傳回依 Id 取得的 Slide、MasterSlide 或 LayoutSlide。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| id | long | 投影片的 Id。 |

**傳回:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide 物件。

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

合併所有投影片中所有可接受形狀的段落內格式相同的文字區塊。

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public abstract void highlightText(String text, Integer highlightColor)
```

使用指定顏色突顯所有符合樣本文字的項目。

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // 突顯所有獨立的 'the' 出現位置
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 要突顯的文字。 |
| highlightColor | java.lang.Integer | 用於突顯文字的顏色。 |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

使用指定顏色突顯所有符合樣本文字的項目。

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // 突顯所有獨立的 'the' 出現位置
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 要突顯的文字。 |
| highlightColor | java.lang.Integer | 用於突顯文字的顏色。 |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | 文字搜尋選項 [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 接收搜尋結果的回呼物件 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

使用指定顏色突顯所有符合正規表達式的項目。

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // 突顯所有獨立的 'the' 出現位置
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| regex | java.util.regex.Pattern | 用於取得要突顯字串的正規表達式。 |
| highlightColor | java.lang.Integer | 用於突顯文字的顏色。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 接收搜尋結果的回呼物件 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

將所有指定文字的出現處取代為另一指定文字。

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // 將所有獨立的 'the' 出現取代為 '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| oldText | java.lang.String | 要被取代的字串。 |
| newText | java.lang.String | 用於取代 oldText 所有出現處的字串。 |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | 文字搜尋選項 [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 接收搜尋結果的回呼物件 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

將所有符合正規表達式的項目取代為指定字串。

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // 將所有獨立的 'the' 出現取代為 '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| regex | java.util.regex.Pattern | 用於取得要取代字串的正規表達式。 |
| newText | java.lang.String | 用於取代所有被取代字串的字串。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 接收搜尋結果的回呼物件 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |