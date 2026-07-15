---
title: IPdfOptions
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 提供控制簡報以 PDF 格式儲存的選項。
type: docs
url: /zh-hant/com.aspose.slides/ipdfoptions/
---
**全部已實作的介面:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPdfOptions extends ISaveOptions
```

提供控制演示文稿以 PDF 格式儲存的選項。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getTextCompression()](#getTextCompression--) | 指定文件中所有文字內容所使用的壓縮類型。 |
| [setTextCompression(int value)](#setTextCompression-int-) | 指定文件中所有文字內容所使用的壓縮類型。 |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | 指出是否應自動為每張圖片選擇最有效的壓縮（而非預設壓縮）。 |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | 指出是否應自動為每張圖片選擇最有效的壓縮（而非預設壓縮）。 |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | True 以嵌入 ASCII 字元 32-127 的 TrueType 字型。 |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | True 以嵌入 ASCII 字元 32-127 的 TrueType 字型。 |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 指定產生的文件是否應包含隱藏投影片。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 指定產生的文件是否應包含隱藏投影片。 |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | 返回或設定 Aspose.Slides 應視為共用的字型系列之使用者自訂名稱陣列。 |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | 返回或設定 Aspose.Slides 應視為共用的字型系列之使用者自訂名稱陣列。 |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | 決定是否應嵌入字型的全部字元或僅使用子集。 |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | 決定是否應嵌入字型的全部字元或僅使用子集。 |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | 指示當字型不支援粗體樣式時，文字是否應以點陣圖光柵化並儲存為 PDF。 |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | 指示當字型不支援粗體樣式時，文字是否應以點陣圖光柵化並儲存為 PDF。 |
| [getJpegQuality()](#getJpegQuality--) | 返回或設定決定 PDF 文件內 JPEG 圖片品質的值。 |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | 返回或設定決定 PDF 文件內 JPEG 圖片品質的值。 |
| [getCompliance()](#getCompliance--) | 產生的 PDF 文件所需的符合等級。 |
| [setCompliance(int value)](#setCompliance-int-) | 產生的 PDF 文件所需的符合等級。 |
| [getPassword()](#getPassword--) | 設定使用者密碼以保護 PDF 文件。 |
| [setPassword(String value)](#setPassword-java.lang.String-) | 設定使用者密碼以保護 PDF 文件。 |
| [getAccessPermissions()](#getAccessPermissions--) | 包含一組旗標，指定在以使用者存取開啟文件時應授予的存取權限。 |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | 包含一組旗標，指定在以使用者存取開啟文件時應授予的存取權限。 |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True 以將簡報中使用的所有中繼檔案轉換為 PNG 圖像。 |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True 以將簡報中使用的所有中繼檔案轉換為 PNG 圖像。 |
| [getSufficientResolution()](#getSufficientResolution--) | 返回或設定決定 PDF 文件內圖像解析度的值。 |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | 返回或設定決定 PDF 文件內圖像解析度的值。 |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True 以在每張投影片周圍繪製黑色框線。 |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True 以在每張投影片周圍繪製黑色框線。 |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | 取得或設定匯出簡報時投影片在頁面上的排列模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | 取得或設定匯出簡報時投影片在頁面上的排列模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [getImageTransparentColor()](#getImageTransparentColor--) | 取得或設定圖像的透明顏色。 |
| [setImageTransparentColor(Integer value)](#setImageTransparentColor-java.lang.Integer-) | 取得或設定圖像的透明顏色。 |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | 若為 true，則將指定的透明顏色套用到圖像。 |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | 若為 true，則將指定的透明顏色套用到圖像。 |
| [getInkOptions()](#getInkOptions--) | 提供控制匯出文件中 Ink 物件外觀的選項。 |
| [getIncludeOleData()](#getIncludeOleData--) | True 以將簡報中的所有 OLE 資料轉換為結果 PDF 中的嵌入檔案。 |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | True 以將簡報中的所有 OLE 資料轉換為結果 PDF 中的嵌入檔案。 |

### getTextCompression() {#getTextCompression--}
```
public abstract int getTextCompression()
```

指定文件中所有文字內容所使用的壓縮類型。可讀寫 [PdfTextCompression](../../com.aspose.slides/pdftextcompression)。

--------------------

預設為 [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate)。

**傳回值:**
int

### setTextCompression(int value) {#setTextCompression-int-}
```
public abstract void setTextCompression(int value)
```

指定文件中所有文字內容所使用的壓縮類型。可讀寫 [PdfTextCompression](../../com.aspose.slides/pdftextcompression)。

--------------------

預設為 [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public abstract boolean getBestImagesCompressionRatio()
```

指出是否應自動為每張圖片選擇最有效的壓縮（而非預設壓縮）。如果設定為 true，將為簡報中的每張圖片選擇最合適的壓縮演算法，從而減少產生的 PDF 文件大小。

--------------------

最佳影像壓縮比的選擇計算成本較高，且會佔用額外的記憶體，此選項預設為 false。

--------------------

預設為 false。

**傳回值:**
boolean

### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public abstract void setBestImagesCompressionRatio(boolean value)
```

指出是否應自動為每張圖片選擇最有效的壓縮（而非預設壓縮）。如果設定為 true，將為簡報中的每張圖片選擇最合適的壓縮演算法，從而減少產生的 PDF 文件大小。

--------------------

最佳影像壓縮比的選擇計算成本較高，且會佔用額外的記憶體，此選項預設為 false。

--------------------

預設為 false。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public abstract boolean getEmbedTrueTypeFontsForASCII()
```

True 以嵌入 ASCII 字元 32-127 的 TrueType 字型。字元代碼大於 127 的字型一律嵌入。可讀寫布林值。

--------------------

預設為 **true**。

**傳回值:**
boolean

### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public abstract void setEmbedTrueTypeFontsForASCII(boolean value)
```

True 以嵌入 ASCII 字元 32-127 的 TrueType 字型。字元代碼大於 127 的字型一律嵌入。可讀寫布林值。

--------------------

預設為 **true**。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

指定產生的文件是否應包含隱藏投影片。預設為 false。

**傳回值:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

指定產生的文件是否應包含隱藏投影片。預設為 false。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public abstract String[] getAdditionalCommonFontFamilies()
```

返回或設定 Aspose.Slides 應視為共用的字型系列之使用者自訂名稱陣列。可讀寫 String[]。

**傳回值:**
java.lang.String[]

### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public abstract void setAdditionalCommonFontFamilies(String[] value)
```

返回或設定 Aspose.Slides 應視為共用的字型系列之使用者自訂名稱陣列。可讀寫 String[]。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public abstract boolean getEmbedFullFonts()
```

決定是否應嵌入字型的全部字元或僅使用子集。可讀寫布林值。

--------------------

預設為 **false**。

**傳回值:**
boolean

### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public abstract void setEmbedFullFonts(boolean value)
```

決定是否應嵌入字型的全部字元或僅使用子集。可讀寫布林值。

--------------------

預設為 **false**。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public abstract boolean getRasterizeUnsupportedFontStyles()
```

指示當字型不支援粗體樣式時，文字是否應以點陣圖光柵化並儲存為 PDF。此方法可提升某些字型在產生的 PDF 中的文字品質。可讀寫布林值。

--------------------

預設為 **false**。

**傳回值:**
boolean

### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public abstract void setRasterizeUnsupportedFontStyles(boolean value)
```

指示當字型不支援粗體樣式時，文字是否應以點陣圖光柵化並儲存為 PDF。此方法可提升某些字型在產生的 PDF 中的文字品質。可讀寫布林值。

--------------------

預設為 **false**。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

返回或設定決定 PDF 文件內 JPEG 圖片品質的值。可讀寫 byte。

--------------------

僅在文件包含 JPEG 圖片時有效。

使用此屬性於以 PDF 格式儲存文件時取得或設定圖像品質。值可介於 0 到 100，0 表示最差品質但最高壓縮，100 表示最佳品質但最低壓縮。

預設值為 **100**。

**傳回值:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

返回或設定決定 PDF 文件內 JPEG 圖片品質的值。可讀寫 byte。

--------------------

僅在文件包含 JPEG 圖片時有效。

使用此屬性於以 PDF 格式儲存文件時取得或設定圖像品質。值可介於 0 到 100，0 表示最差品質但最高壓縮，100 表示最佳品質但最低壓縮。

預設值為 **100**。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public abstract int getCompliance()
```

產生的 PDF 文件所需的符合等級。可讀寫 [PdfCompliance](../../com.aspose.slides/pdfcompliance)。

--------------------

預設為 [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17)。

**傳回值:**
int

### setCompliance(int value) {#setCompliance-int-}
```
public abstract void setCompliance(int value)
```

產生的 PDF 文件所需的符合等級。可讀寫 [PdfCompliance](../../com.aspose.slides/pdfcompliance)。

--------------------

預設為 [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

設定使用者密碼以保護 PDF 文件。可讀寫 String。

**傳回值:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

設定使用者密碼以保護 PDF 文件。可讀寫 String。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public abstract int getAccessPermissions()
```

包含一組旗標，指定在以使用者存取開啟文件時應授予的存取權限。見 [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions)。

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


**傳回值:**
int

### setAccessPermissions(int value) {#setAccessPermissions-int-}
```
public abstract void setAccessPermissions(int value)
```

包含一組旗標，指定在以使用者存取開啟文件時應授予的存取權限。見 [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions)。

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

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```

True 以將簡報中使用的所有中繼檔案轉換為 PNG 圖像。可讀寫布林值。

--------------------

預設為 **true**。Pdf 文件可以包含向量圖形和點陣圖像。若 SaveMetafilesAsPng 設為 true，則會將來源 Metafile 圖像轉換為 Png 格式，並以點陣圖方式儲存至 Pdf。若 SaveMetafilesAsPng 設為 false，則來源 Metafile 將轉換為 Pdf 向量圖形。每種方式皆有其優缺點。例如，若 Metafile 轉換為 PNG，則在文件縮放時可能會有品質損失。若 Metafile 轉換為 Pdf 向量圖形，則在 Pdf 檢視工具中可能出現效能問題。

**傳回值:**
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

True 以將簡報中使用的所有中繼檔案轉換為 PNG 圖像。可讀寫布林值。

--------------------

預設為 **true**。Pdf 文件可以包含向量圖形和點陣圖像。若 SaveMetafilesAsPng 設為 true，則會將來源 Metafile 圖像轉換為 Png 格式，並以點陣圖方式儲存至 Pdf。若 SaveMetafilesAsPng 設為 false，則來源 Metafile 將轉換為 Pdf 向量圖形。每種方式皆有其優缺點。例如，若 Metafile 轉換為 PNG，則在文件縮放時可能會有品質損失。若 Metafile 轉換為 Pdf 向量圖形，則在 Pdf 檢視工具中可能出現效能問題。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public abstract float getSufficientResolution()
```

返回或設定決定 PDF 文件內圖像解析度的值。可讀寫 float。

值：此參數的影響取決於若干因素。演算法會根據屬性值、來源影像大小與影像框大小，嘗試取得最佳輸出影像尺寸。使用相似的屬性值可能得到相同結果。建議使用 16 或 32 的步長以獲得明顯的效果。

--------------------

此屬性會影響檔案大小、匯出時間與影像品質。

預設值為 **96**。

**傳回值:**
float

### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public abstract void setSufficientResolution(float value)
```

返回或設定決定 PDF 文件內圖像解析度的值。可讀寫 float。

值：此參數的影響取決於若干因素。演算法會根據屬性值、來源影像大小與影像框大小，嘗試取得最佳輸出影像尺寸。使用相似的屬性值可能得到相同結果。建議使用 16 或 32 的步長以獲得明顯的效果。

--------------------

此屬性會影響檔案大小、匯出時間與影像品質。

預設值為 **96**。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

True 以在每張投影片周圍繪製黑色框線。可讀寫布林值。

--------------------

預設為 **false**。

**傳回值:**
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

True 以在每張投影片周圍繪製黑色框線。可讀寫布林值。

--------------------

預設為 **false**。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

取得或設定匯出簡報時投影片在頁面上的排列模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。

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

**傳回值:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

取得或設定匯出簡報時投影片在頁面上的排列模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。

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

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public abstract Integer getImageTransparentColor()
```

取得或設定圖像的透明顏色。

值：圖像的透明顏色。

**傳回值:**
java.lang.Integer

### setImageTransparentColor(Integer value) {#setImageTransparentColor-java.lang.Integer-}
```
public abstract void setImageTransparentColor(Integer value)
```

取得或設定圖像的透明顏色。

值：圖像的透明顏色。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public abstract boolean getApplyImageTransparent()
```

若為 true，則將指定的透明顏色套用到圖像。

**傳回值:**
boolean

### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public abstract void setApplyImageTransparent(boolean value)
```

若為 true，則將指定的透明顏色套用到圖像。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

提供控制匯出文件中 Ink 物件外觀的選項。唯讀 [IInkOptions](../../com.aspose.slides/iinkoptions)

**傳回值:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getIncludeOleData() {#getIncludeOleData--}
```
public abstract boolean getIncludeOleData()
```

True 以將簡報中的所有 OLE 資料轉換為結果 PDF 中的嵌入檔案。可讀寫布林。

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

預設為  **false** 。

**傳回值:**
boolean

### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public abstract void setIncludeOleData(boolean value)
```

True 以將簡報中的所有 OLE 資料轉換為結果 PDF 中的嵌入檔案。可讀寫布林。

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

預設為  **false** 。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |