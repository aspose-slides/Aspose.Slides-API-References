---
title: PdfOptions
second_title: Aspose.Slides for Android 的 Java API 參考
description: 提供控制簡報以 Pdf 格式儲存方式的選項。
type: docs
url: /zh-hant/com.aspose.slides/pdfoptions/
---
**繼承：**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**全部已實作的介面：**
[com.aspose.slides.IPdfOptions](../../com.aspose.slides/ipdfoptions)
```
public class PdfOptions extends SaveOptions implements IPdfOptions
```

提供控制呈現檔案以 Pdf 格式儲存的選項。

--------------------

> ```
> 以下範例說明如何使用自訂選項將 PowerPoint 轉換為 PDF。
>  
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // 實例化 PdfOptions 類別
>      PdfOptions pdfOptions = new PdfOptions();
>      // 設定 JPEG 品質
>      pdfOptions.setJpegQuality((byte)90);
>      // 設定中繼檔案的行為
>      pdfOptions.setSaveMetafilesAsPng(true);
>      // 設定文字壓縮層級
>      pdfOptions.setTextCompression(PdfTextCompression.Flate);
>      // 定義 PDF 標準
>      pdfOptions.setCompliance(PdfCompliance.Pdf15);
>      // 將簡報另存為 PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
> 以下範例說明如何將 PowerPoint 轉換為包含隱藏投影片的 PDF。
>  
>  // 實例化代表 PowerPoint 檔案的 Presentation 類別
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // 實例化 PdfOptions 類別
>      PdfOptions pdfOptions = new PdfOptions();
>      // 加入隱藏投影片
>      pdfOptions.setShowHiddenSlides(true);
>      // 將簡報另存為 PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
> 以下範例說明如何將 PowerPoint 轉換為受密碼保護的 PDF。
>  
>  // 實例化代表 PowerPoint 檔案的 Presentation 物件
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // 實例化 PdfOptions 類別
>      PdfOptions pdfOptions = new PdfOptions();
>      // 設定 PDF 密碼與存取權限
>      pdfOptions.setPassword("password");
>      pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>      // 將簡報另存為 PDF
>      pres.save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
> 以下範例說明如何將 PowerPoint 轉換為帶有備註的 PDF。
>  
>  // 實例化代表簡報檔案的 Presentation 物件
>  Presentation pres = new Presentation("SelectedSlides.pptx");
>  try {
>      Presentation auxPres = new Presentation();
>      try {
>          ISlide slide = pres.getSlides().get_Item(0);
>          auxPres.getSlides().insertClone(0, slide);
>          // 設定投影片類型與大小
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

| 建構函式 | 說明 |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | 預設建構函式。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | 取得或設定在匯出簡報 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) 時，投影片在頁面上的排列模式。 |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | 取得或設定在匯出簡報 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) 時，投影片在頁面上的排列模式。 |
| [getInkOptions()](#getInkOptions--) | 提供控制匯出文件中墨跡物件外觀的選項。 |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 指定產生的文件是否應包含隱藏投影片。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 指定產生的文件是否應包含隱藏投影片。 |
| [getTextCompression()](#getTextCompression--) | 指定文件中所有文字內容使用的壓縮類型。 |
| [setTextCompression(int value)](#setTextCompression-int-) | 指定文件中所有文字內容使用的壓縮類型。 |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | 指示是否自動為每張圖像選擇最有效的壓縮（取代預設）。 |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | 指示是否自動為每張圖像選擇最有效的壓縮（取代預設）。 |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | 決定 Aspose.Slides 是否會為 ASCII (33..127 代碼範圍) 文字嵌入通用字型。 |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | 決定 Aspose.Slides 是否會為 ASCII (33..127 代碼範圍) 文字嵌入通用字型。 |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | 取得或設定 Aspose.Slides 應視為通用的字型家族之使用者自訂名稱陣列。 |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | 取得或設定 Aspose.Slides 應視為通用的字型家族之使用者自訂名稱陣列。 |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | 決定是否應嵌入字型的全部字元或僅使用子集。 |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | 決定是否應嵌入字型的全部字元或僅使用子集。 |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | 指示當字型不支援粗體樣式時，文字是否應以點陣圖方式光柵化並儲存為 PDF。 |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | 指示當字型不支援粗體樣式時，文字是否應以點陣圖方式光柵化並儲存為 PDF。 |
| [getJpegQuality()](#getJpegQuality--) | 取得或設定決定 PDF 文件內 JPEG 圖像品質的值。 |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | 取得或設定決定 PDF 文件內 JPEG 圖像品質的值。 |
| [getCompliance()](#getCompliance--) | 產生的 PDF 文件所需的合規等級。 |
| [setCompliance(int value)](#setCompliance-int-) | 產生的 PDF 文件所需的合規等級。 |
| [getPassword()](#getPassword--) | 設定使用者密碼以保護 PDF 文件。 |
| [setPassword(String value)](#setPassword-java.lang.String-) | 設定使用者密碼以保護 PDF 文件。 |
| [getAccessPermissions()](#getAccessPermissions--) | 包含一組旗標，指定在以使用者身分開啟文件時應授予的存取權限。 |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | 包含一組旗標，指定在以使用者身分開啟文件時應授予的存取權限。 |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | 若為 true，則將簡報中使用的所有中繼檔案轉換為 PNG 圖像。 |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | 若為 true，則將簡報中使用的所有中繼檔案轉換為 PNG 圖像。 |
| [getSufficientResolution()](#getSufficientResolution--) | 取得或設定決定 PDF 文件內圖像解析度的值。 |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | 取得或設定決定 PDF 文件內圖像解析度的值。 |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | 若為 true，則在每張投影片周圍繪製黑色框線。 |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | 若為 true，則在每張投影片周圍繪製黑色框線。 |
| [getImageTransparentColor()](#getImageTransparentColor--) | 取得或設定圖像的透明顏色。 |
| [setImageTransparentColor(Integer value)](#setImageTransparentColor-java.lang.Integer-) | 取得或設定圖像的透明顏色。 |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | 若為 true，則將指定的透明顏色套用於圖像。 |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | 若為 true，則將指定的透明顏色套用於圖像。 |
| [getIncludeOleData()](#getIncludeOleData--) | 若為 true，則將簡報中所有 OLE 資料轉換為結果 PDF 中的嵌入檔案。 |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | 若為 true，則將簡報中所有 OLE 資料轉換為結果 PDF 中的嵌入檔案。 |

### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```

預設建構函式。

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

取得或設定在匯出簡報 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) 時，投影片在頁面上的排列模式。

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

**傳回值：**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

取得或設定在匯出簡報 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) 時，投影片在頁面上的排列模式。

--------------------

> ```
> 範例：
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

提供控制匯出文件中墨跡物件外觀的選項。唯讀 [IInkOptions](../../com.aspose.slides/iinkoptions)

**傳回值：**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

指定產生的文件是否應包含隱藏投影片。預設為 false。

**傳回值：**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

指定產生的文件是否應包含隱藏投影片。預設為 false。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getTextCompression() {#getTextCompression--}
```
public final int getTextCompression()
```

指定文件中所有文字內容使用的壓縮類型。讀寫 [PdfTextCompression](../../com.aspose.slides/pdftextcompression)。

--------------------

預設為 [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate)。

**傳回值：**
int
### setTextCompression(int value) {#setTextCompression-int-}
```
public final void setTextCompression(int value)
```

指定文件中所有文字內容使用的壓縮類型。讀寫 [PdfTextCompression](../../com.aspose.slides/pdftextcompression)。

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

指示是否自動為每張圖像選擇最有效的壓縮（取代預設）。若設為 true，則簡報中每張圖像皆會自動選擇最適當的壓縮演算法，從而減小產生的 PDF 文件大小。

--------------------

最佳圖像壓縮比的選取計算量大且會佔用額外的記憶體，此選項預設為 false。

--------------------

預設為 false。

**傳回值：**
boolean
### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public final void setBestImagesCompressionRatio(boolean value)
```

指示是否自動為每張圖像選擇最有效的壓縮（取代預設）。若設為 true，則簡報中每張圖像皆會自動選擇最適當的壓縮演算法，從而減小產生的 PDF 文件大小。

--------------------

最佳圖像壓縮比的選取計算量大且會佔用額外的記憶體，此選項預設為 false。

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

決定 Aspose.Slides 是否會為 ASCII (33..127 代碼範圍) 文字嵌入通用字型。字元代碼大於 127 的字型始終會被嵌入。通用字型清單包括 PDF 的基本 14 種字型以及使用者指定的其他字型。讀寫 boolean。

--------------------

預設為 **true**。

**傳回值：**
boolean
### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public final void setEmbedTrueTypeFontsForASCII(boolean value)
```

決定 Aspose.Slides 是否會為 ASCII (33..127 代碼範圍) 文字嵌入通用字型。字元代碼大於 127 的字型始終會被嵌入。通用字型清單包括 PDF 的基本 14 種字型以及使用者指定的其他字型。讀寫 boolean。

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

取得或設定 Aspose.Slides 應視為通用的字型家族之使用者自訂名稱陣列。讀寫 String[]。

**傳回值：**
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public final void setAdditionalCommonFontFamilies(String[] value)
```

取得或設定 Aspose.Slides 應視為通用的字型家族之使用者自訂名稱陣列。讀寫 String[]。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public final boolean getEmbedFullFonts()
```

決定是否應嵌入字型的全部字元或僅使用子集。讀寫 boolean。

--------------------

預設為 **false**。

**傳回值：**
boolean
### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public final void setEmbedFullFonts(boolean value)
```

決定是否應嵌入字型的全部字元或僅使用子集。讀寫 boolean。

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

指示當字型不支援粗體樣式時，文字是否應以點陣圖方式光柵化並儲存為 PDF。此方式可提升特定字型在產生 PDF 後的文字品質。讀寫 boolean。

--------------------

預設為 **false**。

**傳回值：**
boolean
### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public final void setRasterizeUnsupportedFontStyles(boolean value)
```

指示當字型不支援粗體樣式時，文字是否應以點陣圖方式光柵化並儲存為 PDF。此方式可提升特定字型在產生 PDF 後的文字品質。讀寫 boolean。

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

取得或設定決定 PDF 文件內 JPEG 圖像品質的值。讀寫 byte。

--------------------

僅當文件包含 JPEG 圖像時才會生效。

使用此屬性可在以 PDF 格式儲存文件時取得或設定圖像的品質。值範圍為 0 到 100，0 代表最差品質但最大壓縮，100 代表最佳品質但最小壓縮。

預設值為 **100**。

**傳回值：**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

取得或設定決定 PDF 文件內 JPEG 圖像品質的值。讀寫 byte。

--------------------

僅當文件包含 JPEG 圖像時才會生效。

使用此屬性可在以 PDF 格式儲存文件時取得或設定圖像的品質。值範圍為 0 到 100，0 代表最差品質但最大壓縮，100 代表最佳品質但最小壓縮。

預設值為 **100**。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```

產生的 PDF 文件所需的合規等級。讀寫 [PdfCompliance](../../com.aspose.slides/pdfcompliance)。

--------------------

預設為 [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17)。

**傳回值：**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```

產生的 PDF 文件所需的合規等級。讀寫 [PdfCompliance](../../com.aspose.slides/pdfcompliance)。

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

設定使用者密碼以保護 PDF 文件。讀寫 String。

**傳回值：**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

設定使用者密碼以保護 PDF 文件。讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public final int getAccessPermissions()
```

包含一組旗標，指定在以使用者身分開啟文件時應授予的存取權限。請參閱 [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions)。

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

**傳回值：**
int
### setAccessPermissions(int value) {#setAccessPermissions-int-}
```
public final void setAccessPermissions(int value)
```

包含一組旗標，指定在以使用者身分開啟文件時應授予的存取權限。請參閱 [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions)。

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

若為 true，則將簡報中所有中繼檔案轉換為 PNG 圖像。讀寫 boolean。

--------------------

預設為 **true**。Pdf 文件可以同時包含向量圖形與點陣圖像。若 SaveMetafilesAsPng 設為 true，則來源的 Metafile 圖像會轉換為 PNG 格式並以點陣圖方式儲存至 Pdf；若設定為 false，則來源 Metafile 會轉換為 Pdf 向量圖形。兩種方式皆有其優缺點。例如，將 Metafile 轉換為 PNG 可能在文件縮放時出現品質損失；將 Metafile 轉換為 Pdf 向量圖形則可能導致 Pdf 檢視工具的效能問題。

**傳回值：**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

若為 true，則將簡報中所有中繼檔案轉換為 PNG 圖像。讀寫 boolean。

--------------------

預設為 **true**。Pdf 文件可以同時包含向量圖形與點陣圖像。若 SaveMetafilesAsPng 設為 true，則來源的 Metafile 圖像會轉換為 PNG 格式並以點陣圖方式儲存至 Pdf；若設定為 false，則來源 Metafile 會轉換為 Pdf 向量圖形。兩種方式皆有其優缺點。例如，將 Metafile 轉換為 PNG 可能在文件縮放時出現品質損失；將 Metafile 轉換為 Pdf 向量圖形則可能導致 Pdf 檢視工具的效能問題。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public final float getSufficientResolution()
```

取得或設定決定 PDF 文件內圖像解析度的值。讀寫 float。

Value: 此參數的效果取決於多項因素。演算法會根據屬性值、來源圖像大小與圖像框架大小取得最佳輸出圖像尺寸。使用相似的屬性值可能產生相同結果。建議使用 16 或 32 的步長以取得顯著效果。

--------------------

屬性會影響檔案大小、匯出時間與圖像品質。

預設值為 **96**。

**傳回值：**
float
### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public final void setSufficientResolution(float value)
```

取得或設定決定 PDF 文件內圖像解析度的值。讀寫 float。

Value: 此參數的效果取決於多項因素。演算法會根據屬性值、來源圖像大小與圖像框架大小取得最佳輸出圖像尺寸。使用相似的屬性值可能產生相同結果。建議使用 16 或 32 的步長以取得顯著效果。

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

若為 true，則在每張投影片周圍繪製黑色框線。讀寫 boolean。

--------------------

預設為 **false**。

**傳回值：**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

若為 true，則在每張投影片周圍繪製黑色框線。讀寫 boolean。

--------------------

預設為 **false**。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public final Integer getImageTransparentColor()
```

取得或設定圖像的透明顏色。

Value: 圖像的透明顏色。

**傳回值：**
java.lang.Integer
### setImageTransparentColor(Integer value) {#setImageTransparentColor-java.lang.Integer-}
```
public final void setImageTransparentColor(Integer value)
```

取得或設定圖像的透明顏色。

Value: 圖像的透明顏色。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public final boolean getApplyImageTransparent()
```

若為 true，將指定的透明顏色套用於圖像。

**傳回值：**
boolean
### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public final void setApplyImageTransparent(boolean value)
```

若為 true，將指定的透明顏色套用於圖像。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getIncludeOleData() {#getIncludeOleData--}
```
public final boolean getIncludeOleData()
```

若為 true，則將簡報中所有 OLE 資料轉換為結果 PDF 中的嵌入檔案。讀寫  boolean 。

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

**傳回值：**
boolean
### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public final void setIncludeOleData(boolean value)
```

若為 true，則將簡報中所有 OLE 資料轉換為結果 PDF 中的嵌入檔案。讀寫  boolean 。

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