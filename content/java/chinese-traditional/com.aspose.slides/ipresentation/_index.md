---
title: IPresentation
second_title: Aspose.Slides for Java API 參考
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

| 方法 | 描述 |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | 返回或設定將取代日期時間欄位內容的日期和時間。 |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | 返回或設定將取代日期時間欄位內容的日期和時間。 |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 返回簡報的 HeaderFooter 管理器。 |
| [getProtectionManager()](#getProtectionManager--) | 取得此簡報的權限管理員。 |
| [getSlides()](#getSlides--) | 返回簡報中定義的所有投影片的清單。 |
| [getSections()](#getSections--) | 返回簡報中定義的所有投影片區段的清單。 |
| [getSlideSize()](#getSlideSize--) | 返回投影片尺寸物件。 |
| [getNotesSize()](#getNotesSize--) | 返回備註投影片尺寸物件。 |
| [getLayoutSlides()](#getLayoutSlides--) | 返回簡報中定義的所有版面投影片的清單。 |
| [getMasters()](#getMasters--) | 返回簡報中定義的所有母片投影片的清單。 |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | 返回備註母片管理器。 |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | 返回講義母片管理器。 |
| [getFontsManager()](#getFontsManager--) | 返回字體管理器。 |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | 返回形狀的預設文字樣式。 |
| [getCommentAuthors()](#getCommentAuthors--) | 返回評論作者的集合。 |
| [getDocumentProperties()](#getDocumentProperties--) | 返回包含標準和自訂文件屬性的 DocumentProperties 物件。 |
| [getImages()](#getImages--) | 返回簡報中所有影像的集合。 |
| [getAudios()](#getAudios--) | 返回簡報中所有嵌入式音訊檔案的集合。 |
| [getVideos()](#getVideos--) | 返回簡報中所有嵌入式影片檔案的集合。 |
| [getCustomData()](#getCustomData--) | 返回簡報的自訂資料。 |
| [getVbaProject()](#getVbaProject--) | 取得含簡報巨集的 VBA 專案。 |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | 取得含簡報巨集的 VBA 專案。 |
| [getSourceFormat()](#getSourceFormat--) | 返回簡報載入時使用的格式資訊。 |
| [getMasterTheme()](#getMasterTheme--) | 返回簡報的母片主題。 |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | 提供對所有投影片（不含母片、版面、備註投影片）內的超連結的簡易存取。 |
| [getViewProperties()](#getViewProperties--) | 取得簡報全域的檢視屬性。 |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | 表示簡報中的第一張投影片編號。 |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | 表示簡報中的第一張投影片編號。 |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | 返回簡報中的所有自訂資料部分。 |
| [getDigitalSignatures()](#getDigitalSignatures--) | 返回用於簽署簡報的簽章集合。 |
| [getSensitivityLabels()](#getSensitivityLabels--) | 返回套用於簡報文件的敏感度標籤集合。 |
| [save(String fname, int format)](#save-java.lang.String-int-) | 將簡報的所有投影片以指定格式儲存至檔案。 |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | 將簡報的所有投影片以指定格式儲存至串流。 |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | 將簡報的所有投影片以指定格式及其他選項儲存至檔案。 |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | 將簡報的所有投影片以指定格式及其他選項儲存至串流。 |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Saves specified slides of a presentation to a file with the specified format. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Saves specified slides of a presentation to a file with the specified format. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Saves specified slides of a presentation to a stream in the specified format. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Saves specified slides of a presentation to a stream in the specified format. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | 將簡報的所有投影片儲存為 XAML 標記檔案集合。 |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | 返回簡報所有投影片的縮圖影像物件。 |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Returns a Thumbnail IImage objects for specified slides of a presentation. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | 返回簡報所有投影片的縮圖影像物件（自訂縮放）。 |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Returns a Thumbnail Image objects for specified slides of a presentation with custom scaling. |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | 返回簡報所有投影片的縮圖影像物件（指定大小）。 |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | Returns a Thumbnail Image objects for specified slides of a presentation with specified size. |
| [getSlideById(long id)](#getSlideById-long-) | 透過 Id 返回投影片、母片投影片或版面投影片。 |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 將所有段落中具相同格式的文字跑合併於所有可接受形狀的投影片中。 |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | 以指定顏色突顯樣本文字的所有匹配項目。 |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | 以指定顏色突顯樣本文字的所有匹配項目。 |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | 以指定顏色突顯正規表達式的所有匹配項目。 |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | 将指定文字的所有出现取代为另一指定文字。 |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | 将正規表達式的所有匹配項目取代為指定字串。 |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

返回或設定將取代日期時間欄位內容的日期和時間。預設為此 Presentation 物件建立的時間。可讀寫 java.util.Date。

**返回：**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

返回或設定將取代日期時間欄位內容的日期和時間。預設為此 Presentation 物件建立的時間。可讀寫 java.util.Date。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

返回簡報的 HeaderFooter 管理器。唯讀 [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)。

**返回：**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

取得此簡報的權限管理員。唯讀 [IProtectionManager](../../com.aspose.slides/iprotectionmanager)。

**返回：**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

返回簡報中定義的所有投影片的清單。唯讀 [ISlideCollection](../../com.aspose.slides/islidecollection)。

**返回：**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

返回簡報中定義的所有投影片區段的清單。唯讀 [ISectionCollection](../../com.aspose.slides/isectioncollection)。

**返回：**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

返回投影片尺寸物件。唯讀 [ISlideSize](../../com.aspose.slides/islidesize)。

**返回：**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

返回備註投影片尺寸物件。唯讀 [INotesSize](../../com.aspose.slides/inotessize)。

**返回：**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

返回簡報中定義的所有版面投影片的清單。唯讀 [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)。

--------------------

您可以透過 IMasterSlide.LayoutSlides 屬性存取用於新增/插入/移除/複製版面投影片的替代 API。

**返回：**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

返回簡報中定義的所有母片投影片的清單。唯讀 [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)。

**返回：**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

返回備註母片管理器。唯讀 [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)。

**返回：**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

返回講義母片管理器。唯讀 [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)。

**返回：**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

返回字體管理器。唯讀 [IFontsManager](../../com.aspose.slides/ifontsmanager)。

**返回：**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

返回形狀的預設文字樣式。唯讀 [ITextStyle](../../com.aspose.slides/itextstyle)。

**返回：**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

返回評論作者的集合。唯讀 [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)。

**返回：**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

返回包含標準和自訂文件屬性的 DocumentProperties 物件。唯讀 [IDocumentProperties](../../com.aspose.slides/idocumentproperties)。

**返回：**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

返回簡報中所有影像的集合。唯讀 [IImageCollection](../../com.aspose.slides/iimagecollection)。

**返回：**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

返回簡報中所有嵌入式音訊檔案的集合。唯讀 [IAudioCollection](../../com.aspose.slides/iaudiocollection)。

**返回：**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

返回簡報中所有嵌入式影片檔案的集合。唯讀 [IVideoCollection](../../com.aspose.slides/ivideocollection)。

**返回：**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

返回簡報的自訂資料。唯讀 [ICustomData](../../com.aspose.slides/icustomdata)。

**返回：**
[ICustomData](../../com.aspose.slides/icustomdata)

### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```

取得含簡報巨集的 VBA 專案。可讀寫 [IVbaProject](../../com.aspose.slides/ivbaproject)。

**返回：**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

取得含簡報巨集的 VBA 專案。可讀寫 [IVbaProject](../../com.aspose.slides/ivbaproject)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

返回簡報載入時使用的格式資訊。唯讀 [SourceFormat](../../com.aspose.slides/sourceformat)。

**返回：**
int

### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

返回簡報的母片主題。唯讀 [IMasterTheme](../../com.aspose.slides/imastertheme)。

**返回：**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

提供對所有投影片（不含母片、版面、備註投影片）內的超連結的簡易存取。唯讀 [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)。

**返回：**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

取得簡報全域的檢視屬性。唯讀 [IViewProperties](../../com.aspose.slides/iviewproperties)。

**返回：**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```

表示簡報中的第一張投影片編號。可讀寫 int。

**返回：**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

表示簡報中的第一張投影片編號。可讀寫 int。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

返回簡報中的所有自訂資料部分。唯讀 ICustomXmlPart[]。

**返回：**
com.aspose.slides.ICustomXmlPart[]

### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

返回用於簽署簡報的簽章集合。唯讀 [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)。

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


**返回：**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabelCollection getSensitivityLabels()
```

返回套用於簡報文件的敏感度標籤集合。唯讀 [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)。

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
>      // 新增新標籤
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


**返回：**
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)

### save(String fname, int format) {#save-java.lang.String-int-}
```
public abstract void save(String fname, int format)
```

將簡報的所有投影片以指定格式儲存至檔案。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| fname | java.lang.String | 建立的檔案路徑。 |
| format | int | 匯出資料的格式。 |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

將簡報的所有投影片以指定格式儲存至串流。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 輸出串流。 |
| format | int | 匯出資料的格式。 |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```

將簡報的所有投影片以指定格式及其他選項儲存至檔案。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| fname | java.lang.String | 建立的檔案路徑。 |
| format | int | 匯出資料的格式。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 其他格式選項。 |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```

將簡報的所有投影片儲存至資料流，以指定的格式並使用其他選項。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | 輸出資料流。 |
| format | int | 匯出資料的格式。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 其他格式選項。 |

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```

將簡報中指定的投影片以指定的格式儲存到檔案中。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | 建立檔案的路徑。 |
| slides | int[] | 投影片位置的陣列，從 1 開始。 |
| format | int | 匯出資料的格式。 |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```

將簡報中指定的投影片以指定的格式儲存到檔案中。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | 建立檔案的路徑。 |
| slides | int[] | 投影片位置的陣列，從 1 開始。 |
| format | int | 匯出資料的格式。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 其他格式選項。 |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```

將簡報中指定的投影片以指定的格式儲存至資料流中。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | 輸出資料流。 |
| slides | int[] | 投影片位置的陣列，從 1 開始。 |
| format | int | 匯出資料的格式。 |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

將簡報中指定的投影片以指定的格式儲存至資料流中。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | 輸出資料流。 |
| slides | int[] | 投影片位置的陣列，從 1 開始。 |
| format | int | 匯出資料的格式。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 其他格式選項。 |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
```

將簡報的所有投影片儲存為表示 XAML 標記的一組檔案。

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
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | XAML 格式選項。 |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage[] getImages(IRenderingOptions options)
```

返回簡報所有投影片的縮圖影像物件。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 渲染選項。 |

**傳回:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```

返回簡報中指定投影片的縮圖 IImage 物件。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 渲染選項。 |
| slides | int[] | 投影片位置的陣列，從 1 開始。 |

**傳回:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

返回簡報所有投影片的縮圖影像物件，使用自訂縮放。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 渲染選項。 |
| scaleX | float | 在 x 軸方向上縮放此縮圖的值。 |
| scaleY | float | 在 y 軸方向上縮放此縮圖的值。 |

**傳回:**
com.aspose.slides.IImage[] - Bitmap objects.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

返回簡報中指定投影片的縮圖影像物件，使用自訂縮放。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 渲染選項。 |
| slides | int[] | 投影片位置的陣列，從 1 開始。 |
| scaleX | float | 在 x 軸方向上縮放此縮圖的值。 |
| scaleY | float | 在 y 軸方向上縮放此縮圖的值。 |

**傳回:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```

返回簡報所有投影片的縮圖影像物件，使用指定的大小。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 渲染選項。 |
| imageSize | java.awt.Dimension | 要建立的影像大小。 |

**傳回:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```

返回簡報中指定投影片的縮圖影像物件，使用指定的大小。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 渲染選項。 |
| slides | int[] | 投影片位置的陣列，從 1 開始。 |
| imageSize | java.awt.Dimension | 要建立的影像大小。 |

**傳回:**
com.aspose.slides.IImage[] - IImage objects.

### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```

根據 Id 返回 Slide、MasterSlide 或 LayoutSlide。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | long | 投影片的 Id。 |

**傳回:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

在所有投影片的所有可接受形狀的所有段落中，將具有相同格式的文字區段合併。

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public abstract void highlightText(String text, Color highlightColor)
```

以指定的顏色突顯樣本文本的所有匹配項目。

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // highlighting all separate 'the' occurrences
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | 要突顯的文字。 |
| highlightColor | java.awt.Color | 用於突顯文字的顏色。 |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

以指定的顏色突顯樣本文本的所有匹配項目。

--------------------

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
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | 要突顯的文字。 |
| highlightColor | java.awt.Color | 用於突顯文字的顏色。 |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | 文字搜尋選項 [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 接收搜尋結果的回呼物件 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

以指定的顏色突顯正規表達式的所有匹配項目。

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
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
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | 用於取得要突顯字串的正規表達式 java.util.regex.Pattern。 |
| highlightColor | java.awt.Color | 用於突顯文字的顏色。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 接收搜尋結果的回呼物件 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

將指定文字的所有出現取代為另一個指定文字。

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // 替換所有單獨的 'the' 出現為 '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| oldText | java.lang.String | 要被取代的字串。 |
| newText | java.lang.String | 用於取代 oldText 所有出現的字串。 |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | 文字搜尋選項 [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 接收搜尋結果的回呼物件 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

以指定的字串取代正規表達式的所有匹配項目。

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // 替換所有單獨的 'the' 出現為 '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | 用於取得要取代字串的正規表達式 java.util.regex.Pattern。 |
| newText | java.lang.String | 用於取代所有要被取代字串的字串。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 接收搜尋結果的回呼物件 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |