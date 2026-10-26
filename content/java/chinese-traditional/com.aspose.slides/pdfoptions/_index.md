---
title: PdfOptions
second_title: Aspose.Slides for Java API 參考文件
description: 提供控制簡報以 Pdf 格式儲存的選項。
type: docs
url: /zh-hant/com.aspose.slides/pdfoptions/
---
**繼承：**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**所有已實作的介面：**
[com.aspose.slides.IPdfOptions](../../com.aspose.slides/ipdfoptions)
```
public class PdfOptions extends SaveOptions implements IPdfOptions
```

提供控制簡報以 Pdf 格式儲存的選項。

--------------------

> ```
> The following example shows how to convert PowerPoint to PDF with custom options.
>  
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // 實例化 PdfOptions 類別
>      PdfOptions pdfOptions = new PdfOptions();
>      // 設定 JPEG 品質
>      pdfOptions.setJpegQuality((byte)90);
>      // 設定中繪檔的行為
>      pdfOptions.setSaveMetafilesAsPng(true);
>      // 設定文字壓縮等級
>      pdfOptions.setTextCompression(PdfTextCompression.Flate);
>      // 定義 PDF 標準
>      pdfOptions.setCompliance(PdfCompliance.Pdf15);
>      // 將簡報儲存為 PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with hidden slides.
>  
>  // 實例化表示 PowerPoint 檔案的 Presentation 類別
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // 實例化 PdfOptions 類別
>      PdfOptions pdfOptions = new PdfOptions();
>      // 加入隱藏投影片
>      pdfOptions.setShowHiddenSlides(true);
>      // 將簡報儲存為 PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to password protected PDF.
>  
>  // 實例化表示 PowerPoint 檔案的 Presentation 物件
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // 實例化 PdfOptions 類別
>      PdfOptions pdfOptions = new PdfOptions();
>      // 設定 PDF 密碼和存取權限
>      pdfOptions.setPassword("password");
>      pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>      // 將簡報儲存為 PDF
>      pres.save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with notes.
>  
>  // 實例化表示簡報檔案的 Presentation 物件
>  Presentation pres = new Presentation("SelectedSlides.pptx");
>  try {
>      Presentation auxPres = new Presentation();
>      try {
>          ISlide slide = pres.getSlides().get_Item(0);
>          auxPres.getSlides().insertClone(0, slide);
>          // 設定投影片類型與尺寸
>          auxPres.getSlideSize().setSize(612F, 792F, SlideSizeScaleType.EnsureFit);
>          PdfOptions pdfOptions = new PdfOptions();
>          pdfOptions.getNotesCommentsLayouting().setNotesPosition(NotesPositions.BottomFull);
>          auxPres.save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
>      } finally {
>          if (auxPres != null) auxPres.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## 建構函式

| 建構子 | 說明 |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | 預設建構函式。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | 取得或設定在匯出簡報時投影片在頁面上的放置模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | 取得或設定在匯出簡報時投影片在頁面上的放置模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [getInkOptions()](#getInkOptions--) | 提供控制匯出文件中墨跡對象外觀的選項。 |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 指定產生的文件是否應包含隱藏的投影片。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 指定產生的文件是否應包含隱藏的投影片。 |
| [getTextCompression()](#getTextCompression--) | 指定文件中所有文字內容使用的壓縮類型。 |
| [setTextCompression(int value)](#setTextCompression-int-) | 指定文件中所有文字內容使用的壓縮類型。 |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | 指出是否必須自動為每張圖片選擇最有效的壓縮（而非預設壓縮）。 |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | 指出是否必須自動為每張圖片選擇最有效的壓縮（而非預設壓縮）。 |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | 決定 Aspose.Slides 是否會為 ASCII (33..127) 文字嵌入常用字型。 |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | 決定 Aspose.Slides 是否會為 ASCII (33..127) 文字嵌入常用字型。 |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | 取得或設定一組使用者自訂的字型系列名稱，Aspose.Slides 應視為常用字型。 |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | 取得或設定一組使用者自訂的字型系列名稱，Aspose.Slides 應視為常用字型。 |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | 決定是否應嵌入字型的所有字元或僅使用子集。 |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | 決定是否應嵌入字型的所有字元或僅使用子集。 |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | 指出當字型不支援粗體樣式時，是否應將文字光柵化為位圖並儲存為 PDF。 |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | 指出當字型不支援粗體樣式時，是否應將文字光柵化為位圖並儲存為 PDF。 |
| [getJpegQuality()](#getJpegQuality--) | 取得或設定決定 PDF 文件內 JPEG 圖像品質的值。 |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | 取得或設定決定 PDF 文件內 JPEG 圖像品質的值。 |
| [getCompliance()](#getCompliance--) | 產生的 PDF 文件所需的符合等級。 |
| [setCompliance(int value)](#setCompliance-int-) | 產生的 PDF 文件所需的符合等級。 |
| [getPassword()](#getPassword--) | 設定使用者密碼以保護 PDF 文件。 |
| [setPassword(String value)](#setPassword-java.lang.String-) | 設定使用者密碼以保護 PDF 文件。 |
| [getAccessPermissions()](#getAccessPermissions--) | 包含一組旗標，用於指定文件在以使用者存取開啟時應授予哪些存取權限。 |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | 包含一組旗標，用於指定文件在以使用者存取開啟時應授予哪些存取權限。 |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | 設定為 true 時，將簡報中使用的所有中繪檔轉換為 PNG 圖像。 |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | 設定為 true 時，將簡報中使用的所有中繪檔轉換為 PNG 圖像。 |
| [getSufficientResolution()](#getSufficientResolution--) | 取得或設定決定 PDF 文件內圖像解析度的值。 |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | 取得或設定決定 PDF 文件內圖像解析度的值。 |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | 設定為 true 時，在每張投影片周圍繪製黑色框線。 |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | 設定為 true 時，在每張投影片周圍繪製黑色框線。 |
| [getImageTransparentColor()](#getImageTransparentColor--) | 取得或設定圖像的透明顏色。 |
| [setImageTransparentColor(Color value)](#setImageTransparentColor-java.awt.Color-) | 取得或設定圖像的透明顏色。 |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | 如果為 true，則將指定的透明顏色套用至圖像。 |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | 如果為 true，則將指定的透明顏色套用至圖像。 |
| [getIncludeOleData()](#getIncludeOleData--) | 設定為 true 時，將簡報中所有 OLE 資料轉換為結果 PDF 中的嵌入檔案。 |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | 設定為 true 時，將簡報中所有 OLE 資料轉換為結果 PDF 中的嵌入檔案。 |

### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```

預設建構函式。

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

取得或設定在匯出簡報時投影片在頁面上的放置模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回：**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

取得或設定在匯出簡報時投影片在頁面上的放置模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

提供控制匯出文件中墨跡對象外觀的選項。唯讀 [IInkOptions](../../com.aspose.slides/iinkoptions)

**返回：**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

指定產生的文件是否應包含隱藏的投影片。預設為 false。

**返回：**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

指定產生的文件是否應包含隱藏的投影片。預設為 false。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getTextCompression() {#getTextCompression--}
```
public final int getTextCompression()
```

指定文件中所有文字內容使用的壓縮類型。可讀寫 [PdfTextCompression](../../com.aspose.slides/pdftextcompression)。

--------------------

預設為 [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate)。

**返回：**
int
### setTextCompression(int value) {#setTextCompression-int-}
```
public final void setTextCompression(int value)
```

指定文件中所有文字內容使用的壓縮類型。可讀寫 [PdfTextCompression](../../com.aspose.slides/pdftextcompression)。

--------------------

預設為 [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public final boolean getBestImagesCompressionRatio()
```

指出是否必須自動為每張圖片選擇最有效的壓縮（而非預設壓縮）。如果設定為 true，則簡報中的每張圖片都會選擇最適合的壓縮演算法，從而使產生的 PDF 文件大小更小。

--------------------

最佳影像壓縮比的選取計算成本較高，且會佔用額外的記憶體，預設為 false。

--------------------

預設為 false。

**返回：**
boolean
### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public final void setBestImagesCompressionRatio(boolean value)
```

指出是否必須自動為每張圖片選擇最有效的壓縮（而非預設壓縮）。如果設定為 true，則簡報中的每張圖片都會選擇最適合的壓縮演算法，從而使產生的 PDF 文件大小更小。

--------------------

最佳影像壓縮比的選取計算成本較高，且會佔用額外的記憶體，預設為 false。

--------------------

預設為 false。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public final boolean getEmbedTrueTypeFontsForASCII()
```

決定 Aspose.Slides 是否會為 ASCII (33..127) 文字嵌入常用字型。字元代碼大於 127 的字型始終嵌入。常用字型清單包括 PDF 的基本 14 種字型以及使用者指定的其他字型。可讀寫 boolean。

--------------------

預設為 **true**。

**返回：**
boolean
### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public final void setEmbedTrueTypeFontsForASCII(boolean value)
```

決定 Aspose.Slides 是否會為 ASCII (33..127) 文字嵌入常用字型。字元代碼大於 127 的字型始終嵌入。常用字型清單包括 PDF 的基本 14 種字型以及使用者指定的其他字型。可讀寫 boolean。

--------------------

預設為 **true**。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public final String[] getAdditionalCommonFontFamilies()
```

取得或設定一組使用者自訂的字型系列名稱，Aspose.Slides 應視為常用字型。可讀寫 String[]。

**返回：**
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public final void setAdditionalCommonFontFamilies(String[] value)
```

取得或設定一組使用者自訂的字型系列名稱，Aspose.Slides 應視為常用字型。可讀寫 String[]。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public final boolean getEmbedFullFonts()
```

決定是否應嵌入字型的所有字元或僅使用子集。可讀寫 boolean。

--------------------

預設為 **false**。

**返回：**
boolean
### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public final void setEmbedFullFonts(boolean value)
```

決定是否應嵌入字型的所有字元或僅使用子集。可讀寫 boolean。

--------------------

預設為 **false**。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public final boolean getRasterizeUnsupportedFontStyles()
```

指出當字型不支援粗體樣式時，是否應將文字光柵化為位圖並儲存為 PDF。此方式可提升某些字型在產生的 PDF 中的文字品質。可讀寫 boolean。

--------------------

預設為 **false**。

**返回：**
boolean
### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public final void setRasterizeUnsupportedFontStyles(boolean value)
```

指出當字型不支援粗體樣式時，是否應將文字光柵化為位圖並儲存為 PDF。此方式可提升某些字型在產生的 PDF 中的文字品質。可讀寫 boolean。

--------------------

預設為 **false**。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

取得或設定決定 PDF 文件內 JPEG 圖像品質的值。可讀寫 byte。

--------------------

僅在文件包含 JPEG 圖像時有效。

使用此屬性可在以 PDF 格式儲存時取得或設定文件內圖像的品質。值範圍為 0 到 100，其中 0 表示品質最差但壓縮率最高，100 表示品質最佳但壓縮率最低。

預設值為 **100**。

**返回：**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

取得或設定決定 PDF 文件內 JPEG 圖像品質的值。可讀寫 byte。

--------------------

僅在文件包含 JPEG 圖像時有效。

使用此屬性可在以 PDF 格式儲存時取得或設定文件內圖像的品質。值範圍為 0 到 100，其中 0 表示品質最差但壓縮率最高，100 表示品質最佳但壓縮率最低。

預設值為 **100**。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```

產生的 PDF 文件所需的符合等級。可讀寫 [PdfCompliance](../../com.aspose.slides/pdfcompliance)。

--------------------

預設為 [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17)。

**返回：**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```

產生的 PDF 文件所需的符合等級。可讀寫 [PdfCompliance](../../com.aspose.slides/pdfcompliance)。

--------------------

預設為 [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

設定使用者密碼以保護 PDF 文件。可讀寫 String。

**返回：**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

設定使用者密碼以保護 PDF 文件。可讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public final int getAccessPermissions()
```

包含一組旗標，用於指定在以使用者存取開啟文件時應授予哪些存取權限。請參閱 [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions)。

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setPassword("my_password");
>  pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>  Presentation presentation = new Presentation();
>  try
>  {
>      presentation.save(pdfFilePath, SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**返回：**
int
### setAccessPermissions(int value) {#setAccessPermissions-int-}
```
public final void setAccessPermissions(int value)
```

包含一組旗標，用於指定在以使用者存取開啟文件時應授予哪些存取權限。請參閱 [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions)。

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setPassword("my_password");
>  pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>  Presentation presentation = new Presentation();
>  try
>  {
>      presentation.save(pdfFilePath, SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

設定為 true 時，將簡報中使用的所有中繪檔轉換為 PNG 圖像。可讀寫 boolean。

--------------------

預設為 **true**。Pdf 文件可以包含向量圖形與點陣圖像。如果 SaveMetafilesAsPng 設為 true，則來源中繪檔會轉換為 PNG 格式並以點陣圖形式儲存至 Pdf；若設定為 false，則來源中繪檔會轉換為 Pdf 向量圖形。每種方式各有優缺點。例如，轉換為 PNG 可能在文件縮放時導致品質損失；轉換為 Pdf 向量圖形則可能在 Pdf 瀏覽工具中產生效能問題。

**返回：**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

設定為 true 時，將簡報中使用的所有中繪檔轉換為 PNG 圖像。可讀寫 boolean。

--------------------

預設為 **true**。Pdf 文件可以包含向量圖形與點陣圖像。如果 SaveMetafilesAsPng 設為 true，則來源中繪檔會轉換為 PNG 格式並以點陣圖形式儲存至 Pdf；若設定為 false，則來源中繪檔會轉換為 Pdf 向量圖形。每種方式各有優缺點。例如，轉換為 PNG 可能在文件縮放時導致品質損失；轉換為 Pdf 向量圖形則可能在 Pdf 瀏覽工具中產生效能問題。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public final float getSufficientResolution()
```

取得或設定決定 PDF 文件內圖像解析度的值。可讀寫 float。

值說明：此參數的影響取決於多項因素。演算法會根據屬性值、來源圖像大小與圖像框架大小取得最佳輸出圖像尺寸。使用相似的屬性值可能得到相同結果。建議使用 16 或 32 的步長以獲得明顯效果。

--------------------

屬性會影響檔案大小、匯出時間與圖像品質。

預設值為 **96**。

**返回：**
float
### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public final void setSufficientResolution(float value)
```

取得或設定決定 PDF 文件內圖像解析度的值。可讀寫 float。

值說明：此參數的影響取決於多項因素。演算法會根據屬性值、來源圖像大小與圖像框架大小取得最佳輸出圖像尺寸。使用相似的屬性值可能得到相同結果。建議使用 16 或 32 的步長以獲得明顯效果。

--------------------

屬性會影響檔案大小、匯出時間與圖像品質。

預設值為 **96**。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

設定為 true 時，在每張投影片周圍繪製黑色框線。可讀寫 boolean。

--------------------

預設為 **false**。

**返回：**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

設定為 true 時，在每張投影片周圍繪製黑色框線。可讀寫 boolean。

--------------------

預設為 **false**。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public final Color getImageTransparentColor()
```

取得或設定圖像的透明顏色。

值說明：圖像透明的顏色。

**返回：**
java.awt.Color
### setImageTransparentColor(Color value) {#setImageTransparentColor-java.awt.Color-}
```
public final void setImageTransparentColor(Color value)
```

取得或設定圖像的透明顏色。

值說明：圖像透明的顏色。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.awt.Color |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public final boolean getApplyImageTransparent()
```

如果為 true，則將指定的透明顏色套用至圖像。

**返回：**
boolean
### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public final void setApplyImageTransparent(boolean value)
```

如果為 true，則將指定的透明顏色套用至圖像。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getIncludeOleData() {#getIncludeOleData--}
```
public final boolean getIncludeOleData()
```

設定為 true 時，將簡報中所有 OLE 資料轉換為結果 PDF 中的嵌入檔案。可讀寫 boolean 。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      options.setIncludeOleData(true);
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

預設為 **false** 。

**返回：**
boolean
### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public final void setIncludeOleData(boolean value)
```

設定為 true 時，將簡報中所有 OLE 資料轉換為結果 PDF 中的嵌入檔案。可讀寫 boolean 。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      options.setIncludeOleData(true);
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

預設為 **false** 。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |