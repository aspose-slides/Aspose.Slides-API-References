---
title: MarkdownSaveOptions
second_title: Aspose.Slides for Android 之 Java API 參考
description: 表示控制簡報應如何儲存為 markdown 的選項。
type: docs
url: /zh-hant/com.aspose.slides/markdownsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)
```
public class MarkdownSaveOptions extends SaveOptions
```

表示控制如何將簡報儲存為 markdown 的選項。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation(presentationFileName);
>  try {
>      FileOutputStream stream = new FileOutputStream("MdFileForGitHubFlavor");
>      try {
>          MarkdownSaveOptions markdownSaveOptions = new MarkdownSaveOptions();
>          markdownSaveOptions.setShowHiddenSlides(true);
>          markdownSaveOptions.setShowSlideNumber(true);
>          markdownSaveOptions.setFlavor(Flavor.Github);
>          markdownSaveOptions.setExportType(MarkdownExportType.Sequential);
>          markdownSaveOptions.setNewLineType(NewLineType.Windows);
>          markdownSaveOptions.setBasePath(documentResourcesPath);
> 
>          pres.save(stream, new int[]{1, 2, 3, 4, 5, 6, 7, 8, 9}, SaveFormat.Md, markdownSaveOptions);
>      } finally {
>          if (stream != null) stream.close();
>      }
>  } catch (Exception e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) | 建構子。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getExportType()](#getExportType--) | 指定用於轉換簡報的 markdown 規格。 |
| [setExportType(int value)](#setExportType-int-) | 指定用於轉換簡報的 markdown 規格。 |
| [getBasePath()](#getBasePath--) | 指定將包含資源的文件儲存的基礎路徑。 |
| [setBasePath(String value)](#setBasePath-java.lang.String-) | 指定將包含資源的文件儲存的基礎路徑。 |
| [getImagesSaveFolderName()](#getImagesSaveFolderName--) | 指定儲存影像的資料夾名稱。 |
| [setImagesSaveFolderName(String value)](#setImagesSaveFolderName-java.lang.String-) | 指定儲存影像的資料夾名稱。 |
| [getNewLineType()](#getNewLineType--) | 指定產生的文件應使用的換行字元：\\\\r（Macintosh）、\\\\n（Unix）或\\\\r\\\\n（Windows）。 |
| [setNewLineType(int value)](#setNewLineType-int-) | 指定產生的文件應使用的換行字元：\\\\r（Macintosh）、\\\\n（Unix）或\\\\r\\\\n（Windows）。 |
| [getShowComments()](#getShowComments--) | 指定產生的文件是否顯示註解。 |
| [setShowComments(boolean value)](#setShowComments-boolean-) | 指定產生的文件是否顯示註解。 |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 指定產生的文件是否包含隱藏投影片。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 指定產生的文件是否包含隱藏投影片。 |
| [getShowSlideNumber()](#getShowSlideNumber--) | 指定產生的文件是否顯示每張投影片的編號。 |
| [setShowSlideNumber(boolean value)](#setShowSlideNumber-boolean-) | 指定產生的文件是否顯示每張投影片的編號。 |
| [getFlavor()](#getFlavor--) | 指定用於轉換簡報的 markdown 規格。 |
| [setFlavor(int value)](#setFlavor-int-) | 指定用於轉換簡報的 markdown 規格。 |
| [getSlideNumberFormat()](#getSlideNumberFormat--) | 取得或設定在 Markdown 輸出中投影片編號標題的格式字串。 |
| [setSlideNumberFormat(String value)](#setSlideNumberFormat-java.lang.String-) | 取得或設定在 Markdown 輸出中投影片編號標題的格式字串。 |
| [getHandleRepeatedSpaces()](#getHandleRepeatedSpaces--) | 指定在 Markdown 匯出期間如何處理重複的普通空格字元。 |
| [setHandleRepeatedSpaces(int value)](#setHandleRepeatedSpaces-int-) | 指定在 Markdown 匯出期間如何處理重複的普通空格字元。 |
| [getRemoveEmptyLines()](#getRemoveEmptyLines--) | 若設定為 true，則從最終的 Markdown 輸出中移除空行或僅含空白的行。 |
| [setRemoveEmptyLines(boolean value)](#setRemoveEmptyLines-boolean-) | 若設定為 true，則從最終的 Markdown 輸出中移除空行或僅含空白的行。 |
| [setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)](#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-) | 在 Markdown 匯出期間，對每個非 SVG 圖像（點陣圖或圖示檔）發生。 |
| [setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)](#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-) | 在 Markdown 匯出期間，對每個 SVG 圖像發生。 |
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```

建構子。

### getExportType() {#getExportType--}
```
public final int getExportType()
```

指定用於轉換簡報的 markdown 規格。預設為 TextOnly 。

**傳回值：**
int
### setExportType(int value) {#setExportType-int-}
```
public final void setExportType(int value)
```

指定用於轉換簡報的 markdown 規格。預設為 TextOnly 。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getBasePath() {#getBasePath--}
```
public final String getBasePath()
```

指定將包含資源的文件儲存的基礎路徑。預設為應用程式的目前目錄。

**傳回值：**
java.lang.String
### setBasePath(String value) {#setBasePath-java.lang.String-}
```
public final void setBasePath(String value)
```

指定將包含資源的文件儲存的基礎路徑。預設為應用程式的目前目錄。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getImagesSaveFolderName() {#getImagesSaveFolderName--}
```
public final String getImagesSaveFolderName()
```

指定儲存影像的資料夾名稱。預設為 Images 。

**傳回值：**
java.lang.String
### setImagesSaveFolderName(String value) {#setImagesSaveFolderName-java.lang.String-}
```
public final void setImagesSaveFolderName(String value)
```

指定儲存影像的資料夾名稱。預設為 Images 。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getNewLineType() {#getNewLineType--}
```
public final int getNewLineType()
```

指定產生的文件應使用的換行字元：\\\\r（Macintosh）、\\\\n（Unix）或\\\\r\\\\n（Windows）。預設為 Unix 。

**傳回值：**
int
### setNewLineType(int value) {#setNewLineType-int-}
```
public final void setNewLineType(int value)
```

指定產生的文件應使用的換行字元：\\\\r（Macintosh）、\\\\n（Unix）或\\\\r\\\\n（Windows）。預設為 Unix 。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final boolean getShowComments()
```

指定產生的文件是否顯示註解。預設為 false。

**傳回值：**
boolean
### setShowComments(boolean value) {#setShowComments-boolean-}
```
public final void setShowComments(boolean value)
```

指定產生的文件是否顯示註解。預設為 false。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

指定產生的文件是否包含隱藏投影片。預設為 false。

**傳回值：**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

指定產生的文件是否包含隱藏投影片。預設為 false。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getShowSlideNumber() {#getShowSlideNumber--}
```
public final boolean getShowSlideNumber()
```

指定產生的文件是否顯示每張投影片的編號。預設為 false。

**傳回值：**
boolean
### setShowSlideNumber(boolean value) {#setShowSlideNumber-boolean-}
```
public final void setShowSlideNumber(boolean value)
```

指定產生的文件是否顯示每張投影片的編號。預設為 false。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getFlavor() {#getFlavor--}
```
public final int getFlavor()
```

指定用於轉換簡報的 markdown 規格。預設為 Multi-markdown 。

**傳回值：**
int
### setFlavor(int value) {#setFlavor-int-}
```
public final void setFlavor(int value)
```

指定用於轉換簡報的 markdown 規格。預設為 Multi-markdown 。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getSlideNumberFormat() {#getSlideNumberFormat--}
```
public final String getSlideNumberFormat()
```

取得或設定在 Markdown 輸出中投影片編號標題的格式字串。格式必須包含「\{0\}」佔位符，該佔位符會在匯出時以投影片索引取代。範例：「\# Slide \{0\}」會產生「\# Slide 1」 、「\# Slide 2」等。

**傳回值：**
java.lang.String
### setSlideNumberFormat(String value) {#setSlideNumberFormat-java.lang.String-}
```
public final void setSlideNumberFormat(String value)
```

取得或設定在 Markdown 輸出中投影片編號標題的格式字串。格式必須包含「\{0\}」佔位符，該佔位符會在匯出時以投影片索引取代。範例：「\# Slide \{0\}」會產生「\# Slide 1」 、「\# Slide 2」等。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getHandleRepeatedSpaces() {#getHandleRepeatedSpaces--}
```
public final int getHandleRepeatedSpaces()
```

指定在 Markdown 匯出期間如何處理重複的普通空格字元。此屬性定義連續空格是：- 保持為普通空格字元，- 在普通空格與不換行空格實體（�）之間交替，或 - 在第一個之後全部以不換行空格取代，以在 Markdown 輸出中保留視覺對齊。預設值為 [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp)。

**傳回值：**
int
### setHandleRepeatedSpaces(int value) {#setHandleRepeatedSpaces-int-}
```
public final void setHandleRepeatedSpaces(int value)
```

指定在 Markdown 匯出期間如何處理重複的普通空格字元。此屬性定義連續空格是：- 保持為普通空格字元，- 在普通空格與不換行空格實體（�）之間交替，或 - 在第一個之後全部以不換行空格取代，以在 Markdown 輸出中保留視覺對齊。預設值為 [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getRemoveEmptyLines() {#getRemoveEmptyLines--}
```
public final boolean getRemoveEmptyLines()
```

若設定為 true，則從最終的 Markdown 輸出中移除空行或僅含空白的行。預設為 false。

**傳回值：**
boolean
### setRemoveEmptyLines(boolean value) {#setRemoveEmptyLines-boolean-}
```
public final void setRemoveEmptyLines(boolean value)
```

若設定為 true，則從最終的 Markdown 輸出中移除空行或僅含空白的行。預設為 false。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event) {#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-}
```
public final void setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)
```

在 Markdown 匯出期間，對每個非 SVG 圖像（點陣圖或圖示檔）發生。允許自訂圖像的儲存與參照方式。若未處理，圖像會以相對連結本地儲存。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| event | [MarkdownImageSavingHandler](../../com.aspose.slides/markdownimagesavinghandler) | Markdown 圖像儲存事件。 |

### setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event) {#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-}
```
public final void setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)
```

在 Markdown 匯出期間，對每個 SVG 圖像發生。允許覆寫預設的儲存與連結產生方式。若未處理，SVG 會以相對連結本地儲存。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| event | [MarkdownSvgImageSavingHandler](../../com.aspose.slides/markdownsvgimagesavinghandler) | Markdown SVG 圖像儲存事件。 |