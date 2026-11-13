---
title: IPresentation
second_title: Aspose.Slides for Java API 參考
description: 簡報文件
type: docs
url: /zh-hant/com.aspose.slides/ipresentation/
---
**所有實作的介面：**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent), com.aspose.ms.System.IDisposable
```
public interface IPresentation extends IPresentationComponent, System.IDisposable
```

簡報文件
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | 返回或設定用於替代日期時間欄位內容的日期和時間。 |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | 返回或設定用於替代日期時間欄位內容的日期和時間。 |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 返回簡報的 HeaderFooter 管理器。 |
| [getProtectionManager()](#getProtectionManager--) | 取得此簡報的權限管理器。 |
| [getSlides()](#getSlides--) | 返回簡報中定義的所有投影片清單。 |
| [getSections()](#getSections--) | 返回簡報中定義的所有投影片分段清單。 |
| [getSlideSize()](#getSlideSize--) | 返回投影片大小物件。 |
| [getNotesSize()](#getNotesSize--) | 返回備註投影片大小物件。 |
| [getLayoutSlides()](#getLayoutSlides--) | 返回簡報中定義的所有佈局投影片清單。 |
| [getMasters()](#getMasters--) | 返回簡報中定義的所有母片投影片清單。 |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | 返回備註母片管理器。 |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | 返回講義母片管理器。 |
| [getFontsManager()](#getFontsManager--) | 返回字型管理器。 |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | 返回形狀的預設文字樣式。 |
| [getCommentAuthors()](#getCommentAuthors--) | 返回評論作者的集合。 |
| [getDocumentProperties()](#getDocumentProperties--) | 返回包含標準與自訂文件屬性的 DocumentProperties 物件。 |
| [getImages()](#getImages--) | 返回簡報中所有影像的集合。 |
| [getAudios()](#getAudios--) | 返回簡報中所有內嵌音訊檔案的集合。 |
| [getVideos()](#getVideos--) | 返回簡報中所有內嵌影片檔案的集合。 |
| [getCustomData()](#getCustomData--) | 返回簡報的自訂資料。 |
| [getVbaProject()](#getVbaProject--) | 取得包含簡報巨集的 VBA 專案。 |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | 取得包含簡報巨集的 VBA 專案。 |
| [getSourceFormat()](#getSourceFormat--) | 返回有關簡報以何種格式載入的資訊。 |
| [getMasterTheme()](#getMasterTheme--) | 返回簡報的母版主題。 |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | 提供對簡報中所有投影片（不包括母片、佈局、備註投影片）內所有超連結的簡易存取。 |
| [getViewProperties()](#getViewProperties--) | 取得簡報全域檢視屬性。 |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | 代表簡報中的第一張投影片編號。 |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | 代表簡報中的第一張投影片編號。 |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | 返回簡報中所有自訂資料部件。 |
| [getDigitalSignatures()](#getDigitalSignatures--) | 返回用於簽署簡報的簽章集合。 |
| [getSensitivityLabels()](#getSensitivityLabels--) | 返回套用於簡報文件的敏感度標籤集合。 |
| [save(String fname, int format)](#save-java.lang.String-int-) | 將簡報的所有投影片儲存至指定格式的檔案。 |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | 將簡報的所有投影片以指定格式儲存至串流。 |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | 將簡報的所有投影片儲存至指定格式的檔案，並使用其他選項。 |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | 將簡報的所有投影片以指定格式儲存至串流，並使用其他選項。 |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | 將簡報中指定的投影片儲存至指定格式的檔案。 |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | 將簡報中指定的投影片儲存至指定格式的檔案。 |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | 將簡報中指定的投影片儲存至指定格式的串流。 |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | 將簡報中指定的投影片儲存至指定格式的串流。 |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | 將簡報的所有投影片儲存為一組代表 XAML 標記的檔案。 |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | 返回簡報所有投影片的縮圖圖像物件。 |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | 返回簡報中指定投影片的縮圖 IImage 物件。 |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | 返回簡報所有投影片的縮圖圖像物件，使用自訂縮放。 |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | 返回簡報中指定投影片的縮圖圖像物件，使用自訂縮放。 |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | 返回簡報所有投影片的縮圖圖像物件，使用指定尺寸。 |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | 返回簡報中指定投影片的縮圖圖像物件，使用指定尺寸。 |
| [getSlideById(long id)](#getSlideById-long-) | 根據 Id 返回投影片、母片或佈局投影片。 |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 將所有投影片中所有可接受形狀的所有段落中相同格式的文字串合併。 |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | 以指定顏色凸顯所有符合樣本文本的匹配項。 |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | 以指定顏色凸顯所有符合樣本文本的匹配項。 |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | 以指定顏色凸顯正規表達式的所有匹配項。 |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | 將所有指定文字的出現替換為另一指定文字。 |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | 將正規表達式的所有匹配項替換為指定字串。 |
| [refreshChartsData()](#refreshChartsData--) | 從來源工作簿重新載入簡報中所有圖表的資料。 |
| [refreshChartsData(boolean skipFailedCharts)](#refreshChartsData-boolean-) | 從來源工作簿重新載入簡報中所有圖表的資料。 |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

返回或設定用於替代日期時間欄位內容的日期和時間。預設為此 Presentation 物件建立時的時間。可讀寫 java.util.Date。

**傳回:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

返回或設定用於替代日期時間欄位內容的日期和時間。預設為此 Presentation 物件建立時的時間。可讀寫 java.util.Date。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

返回簡報的 HeaderFooter 管理器。唯讀 [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)。

**傳回:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

取得此簡報的權限管理器。唯讀 [IProtectionManager](../../com.aspose.slides/iprotectionmanager)。

**傳回:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

返回簡報中定義的所有投影片清單。唯讀 [ISlideCollection](../../com.aspose.slides/islidecollection)。

**傳回:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

返回簡報中定義的所有投影片分段清單。唯讀 [ISectionCollection](../../com.aspose.slides/isectioncollection)。

**傳回:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

返回投影片大小物件。唯讀 [ISlideSize](../../com.aspose.slides/islidesize)。

**傳回:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

返回備註投影片大小物件。唯讀 [INotesSize](../../com.aspose.slides/inotessize)。

**傳回:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

返回簡報中定義的所有佈局投影片清單。唯讀 [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)。

--------------------

您可以透過使用 IMasterSlide.LayoutSlides 屬性存取替代 API，以新增/插入/移除/複製佈局投影片。

**傳回:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

返回簡報中定義的所有母片投影片清單。唯讀 [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)。

**傳回:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

返回備註母片管理器。唯讀 [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)。

**傳回:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

返回講義母片管理器。唯讀 [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)。

**傳回:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

返回字型管理器。唯讀 [IFontsManager](../../com.aspose.slides/ifontsmanager)。

**傳回:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

返回形狀的預設文字樣式。唯讀 [ITextStyle](../../com.aspose.slides/itextstyle)。

**傳回:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

返回評論作者的集合。唯讀 [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)。

**傳回:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

返回包含標準與自訂文件屬性的 DocumentProperties 物件。唯讀 [IDocumentProperties](../../com.aspose.slides/idocumentproperties)。

**傳回:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

返回簡報中所有影像的集合。唯讀 [IImageCollection](../../com.aspose.slides/iimagecollection)。

**傳回:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

返回簡報中所有內嵌音訊檔案的集合。唯讀 [IAudioCollection](../../com.aspose.slides/iaudiocollection)。

**傳回:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

返回簡報中所有內嵌影片檔案的集合。唯讀 [IVideoCollection](../../com.aspose.slides/ivideocollection)。

**傳回:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

返回簡報的自訂資料。唯讀 [ICustomData](../../com.aspose.slides/icustomdata)。

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

返回有關簡報以何種格式載入的資訊。唯讀 [SourceFormat](../../com.aspose.slides/sourceformat)。

**傳回:**
int

### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

返回簡報的母版主題。唯讀 [IMasterTheme](../../com.aspose.slides/imastertheme)。

**傳回:**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

提供對簡報中所有投影片（不包括母片、佈局、備註投影片）內所有超連結的簡易存取。唯讀 [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)。

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

代表簡報中的第一張投影片編號。可讀寫 int。

**傳回:**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

代表簡報中的第一張投影片編號。可讀寫 int 。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

返回簡報中所有自訂資料部件。唯讀 ICustomXmlPart[]。

**傳回:**
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


**傳回:**
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
>      // 加入新的標籤
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // 從原則取得敏感度標籤 ID
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // 從原則取得 Azure AD 站台識別碼
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

將簡報的所有投影片儲存至指定格式的檔案。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fname | java.lang.String | 要建立的檔案路徑。 |
| format | int | 匯出資料的格式。 |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

將簡報的所有投影片以指定格式儲存至串流。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 輸出串流。 |
| format | int | 匯出資料的格式。 |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```
儲存簡報的所有投影片至指定格式的檔案，並可使用額外選項。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| fname | java.lang.String | 已建立檔案的路徑。 |
| format | int | 匯出資料的格式。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 其他格式選項。 |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```

儲存簡報的所有投影片至指定格式的串流，並可使用額外選項。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 輸出串流。 |
| format | int | 匯出資料的格式。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 其他格式選項。 |

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```

儲存簡報中指定的投影片至指定格式的檔案。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| fname | java.lang.String | 已建立檔案的路徑。 |
| slides | int[] | 投影片位置陣列，起始值為 1。 |
| format | int | 匯出資料的格式。 |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```

儲存簡報中指定的投影片至指定格式的檔案。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| fname | java.lang.String | 已建立檔案的路徑。 |
| slides | int[] | 投影片位置陣列，起始值為 1。 |
| format | int | 匯出資料的格式。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 其他格式選項。 |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```

儲存簡報中指定的投影片至指定格式的串流。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 輸出串流。 |
| slides | int[] | 投影片位置陣列，起始值為 1。 |
| format | int | 匯出資料的格式。 |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

儲存簡報中指定的投影片至指定格式的串流。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 輸出串流。 |
| slides | int[] | 投影片位置陣列，起始值為 1。 |
| format | int | 匯出資料的格式。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 其他格式選項。 |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
```

儲存簡報的所有投影片為一組代表 XAML 標記的檔案。

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
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | XAML 格式的選項。 |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage[] getImages(IRenderingOptions options)
```

傳回簡報所有投影片的縮圖影像物件。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 轉譯選項。 |

**傳回值:**
com.aspose.slides.IImage[] - IImage 物件。

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```

傳回指定投影片的縮圖 IImage 物件。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 轉譯選項。 |
| slides | int[] | 投影片位置陣列，起始值為 1。 |

**傳回值:**
com.aspose.slides.IImage[] - IImage 物件。

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

傳回簡報所有投影片的縮圖影像物件，可自訂縮放比例。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 轉譯選項。 |
| scaleX | float | 在 X 軸方向上縮放此縮圖的值。 |
| scaleY | float | 在 Y 軸方向上縮放此縮圖的值。 |

**傳回值:**
com.aspose.slides.IImage[] - Bitmap 物件。

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

傳回指定投影片的縮圖影像物件，可自訂縮放比例。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 轉譯選項。 |
| slides | int[] | 投影片位置陣列，起始值為 1。 |
| scaleX | float | 在 X 軸方向上縮放此縮圖的值。 |
| scaleY | float | 在 Y 軸方向上縮放此縮圖的值。 |

**傳回值:**
com.aspose.slides.IImage[] - IImage 物件。

### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```

傳回簡報所有投影片的縮圖影像物件，使用指定的大小。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 轉譯選項。 |
| imageSize | java.awt.Dimension | 要建立的影像大小。 |

**傳回值:**
com.aspose.slides.IImage[] - IImage 物件。

### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```

傳回指定投影片的縮圖影像物件，使用指定的大小。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 轉譯選項。 |
| slides | int[] | 投影片位置陣列，起始值為 1。 |
| imageSize | java.awt.Dimension | 要建立的影像大小。 |

**傳回值:**
com.aspose.slides.IImage[] - IImage 物件。

### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```

傳回依 Id 取得的 Slide、MasterSlide 或 LayoutSlide。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| id | long | 投影片的 Id。 |

**傳回值:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide 物件。

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

在所有投影片的所有可接受形狀內，將段落中具有相同格式的文字段落合併。

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public abstract void highlightText(String text, Color highlightColor)
```

以指定的顏色突顯所有符合樣本文本的匹配項目。

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // 突出顯示所有單獨的 'the' 出現
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
| highlightColor | java.awt.Color | 用於突顯文字的顏色。 |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

以指定的顏色突顯所有符合樣本文本的匹配項目。

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // 突出顯示所有單獨的 'the' 出現
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
| highlightColor | java.awt.Color | 用於突顯文字的顏色。 |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | 文字搜尋選項 [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 用於接收搜尋結果的回呼物件 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

以指定的顏色突顯正規表示式的所有匹配項目。

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // 突出顯示所有單獨的 'the' 出現
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| regex | java.util.regex.Pattern | 用於取得要突顯之字串的正規表示式 java.util.regex.Pattern。 |
| highlightColor | java.awt.Color | 用於突顯文字的顏色。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 用於接收搜尋結果的回呼物件 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

將指定文字的所有出現項目替換為另一指定文字。

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // 將所有單獨的 'the' 出現取代為 '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| oldText | java.lang.String | 要被取代的字串。 |
| newText | java.lang.String | 用於取代 oldText 所有出現項目的字串。 |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | 文字搜尋選項 [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 用於接收搜尋結果的回呼物件 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

將正規表示式的所有匹配項目替換為指定字串。

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // 將所有單獨的 'the' 出現取代為 '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| regex | java.util.regex.Pattern | 用於取得要取代之字串的正規表示式 java.util.regex.Pattern。 |
| newText | java.lang.String | 用於取代所有匹配項目的字串。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 用於接收搜尋結果的回呼物件 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### refreshChartsData() {#refreshChartsData--}
```
public abstract void refreshChartsData()
```

重新載入簡報中所有圖表的資料，從其來源活頁簿取得。

--------------------

> ```
> Presentation presentation = new Presentation("PresentationWithCharts.pptx");
>  try {
>      presentation.refreshChartsData();
>      presentation.save("PresentationWithCharts-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


### refreshChartsData(boolean skipFailedCharts) {#refreshChartsData-boolean-}
```
public abstract void refreshChartsData(boolean skipFailedCharts)
```

重新載入簡報中所有圖表的資料，從其來源活頁簿取得。

--------------------

> ```
> Presentation presentation = new Presentation("PresentationWithCharts.pptx");
>  try {
>      presentation.refreshChartsData();
>      presentation.save("PresentationWithCharts-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| skipFailedCharts | boolean | 決定在圖表更新失敗時是否繼續刷新程序。如果 true，會跳過導致例外的圖表；否則會傳遞例外。 |