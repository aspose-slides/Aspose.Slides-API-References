---
title: LoadOptions
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 允許在載入簡報時指定其他選項，例如格式或預設字型。
type: docs
url: /zh-hant/com.aspose.slides/loadoptions/
---
**繼承：**
java.lang.Object

**所有實作的介面：**
[com.aspose.slides.ILoadOptions](../../com.aspose.slides/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

允許在載入簡報時指定其他選項（例如格式或預設字型）。

## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | 建立新的預設載入選項。 |
| [LoadOptions(int loadFormat)](#LoadOptions-int-) | 建立新的載入選項。 |

## 方法

| 方法 | 說明 |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | 取得或設定要載入的簡報格式。 |
| [setLoadFormat(int value)](#setLoadFormat-int-) | 取得或設定要載入的簡報格式。 |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | 取得或設定當找不到來源字型時使用的常規字型。 |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | 取得或設定當找不到來源字型時使用的常規字型。 |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | 取得或設定當找不到來源字型時使用的符號字型。 |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | 取得或設定當找不到來源字型時使用的符號字型。 |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | 取得或設定當找不到來源字型時使用的亞洲字型。 |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | 取得或設定當找不到來源字型時使用的亞洲字型。 |
| [getPassword()](#getPassword--) | 取得或設定密碼。 |
| [setPassword(String value)](#setPassword-java.lang.String-) | 取得或設定密碼。 |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | 此屬性在簡報檔案受密碼保護時才有意義。 |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | 此屬性在簡報檔案受密碼保護時才有意義。 |
| [getWarningCallback()](#getWarningCallback--) | 取得或設定接收警告並決定載入過程是否繼續或中止的物件。 |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | 取得或設定接收警告並決定載入過程是否繼續或中止的物件。 |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | 表示可用於管理二進位大型物件 (BLOB) 處理行為的選項，例如使用暫存檔或在記憶體中限制 BLOB 的最大位元組數。 |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | 表示可用於管理二進位大型物件 (BLOB) 處理行為的選項，例如使用暫存檔或在記憶體中限制 BLOB 的最大位元組數。 |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | 指定簡報使用的外部字型來源。 |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | 指定簡報使用的外部字型來源。 |
| [getInterruptionToken()](#getInterruptionToken--) | 用於監視中斷請求的 token。 |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | 用於監視中斷請求的 token。 |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | 取得或設定管理外部資源載入的回呼介面。 |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | 取得或設定管理外部資源載入的回呼介面。 |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | 取得試算表的選項。 |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | 取得試算表的選項。 |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | 取得或設定簡報文字的預設語言。 |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | 取得或設定簡報文字的預設語言。 |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | 判斷 Aspose.Slides 在載入簡報時是否會刪除所有嵌入的二進位物件。 |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | 判斷 Aspose.Slides 在載入簡報時是否會刪除所有嵌入的二進位物件。 |

### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


建立新的預設載入選項。

### LoadOptions(int loadFormat) {#LoadOptions-int-}
```
public LoadOptions(int loadFormat)
```


建立新的載入選項。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| loadFormat | int | 要載入的簡報格式。 |

### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```


取得或設定要載入的簡報格式。讀/寫 [LoadFormat](../../com.aspose.slides/loadformat)。

**傳回：**
int

### setLoadFormat(int value) {#setLoadFormat-int-}
```
public final void setLoadFormat(int value)
```


取得或設定要載入的簡報格式。讀/寫 [LoadFormat](../../com.aspose.slides/loadformat)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```


取得或設定當找不到來源字型時使用的常規字型。讀/寫 String。

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // 使用載入選項定義預設的常規字型和亞洲字型
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // 載入簡報
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // 產生投影片縮圖
>      android.graphics.Bitmap slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("output_out.png");
>          slideImage.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
>      // 產生 PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // 產生 XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**傳回：**
java.lang.String

### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```


取得或設定當找不到來源字型時使用的常規字型。讀/寫 String。

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // 使用載入選項定義預設的常規字型與亞洲字型
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // 載入簡報
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // 產生投影片縮圖
>      android.graphics.Bitmap slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("output_out.png");
>          slideImage.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
>      // 產生 PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // 產生 XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public final String getDefaultSymbolFont()
```


取得或設定當找不到來源字型時使用的符號字型。讀/寫 String。

**傳回：**
java.lang.String

### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public final void setDefaultSymbolFont(String value)
```


取得或設定當找不到來源字型時使用的符號字型。讀/寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public final String getDefaultAsianFont()
```


取得或設定當找不到來源字型時使用的亞洲字型。讀/寫 String。

**傳回：**
java.lang.String

### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public final void setDefaultAsianFont(String value)
```


取得或設定當找不到來源字型時使用的亞洲字型。讀/寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


取得或設定密碼。讀/寫 String。

--------------------

> ```
> 以下範例程式碼示範如何開啟受密碼保護的 PowerPoint 簡報。
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // 使用已解密的簡報
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


值：密碼。

**傳回：**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


取得或設定密碼。讀/寫 String。

--------------------

> ```
> 以下範例程式碼示範如何開啟受密碼保護的 PowerPoint 簡報。
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // 使用已解密的簡報
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


值：密碼。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public final boolean getOnlyLoadDocumentProperties()
```


此屬性在簡報檔案受密碼保護時才有意義。值為 true 時表示僅從加密的簡報檔案載入文件屬性，忽略密碼；值為 false 時表示使用正確的密碼載入整個加密的簡報。若簡報未加密則此屬性值始終被忽略。若加密檔案的文件屬性不是公開的且屬性值為 true，則無法載入文件屬性，並會拋出例外。讀/寫 boolean。

**傳回：**
boolean

### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public final void setOnlyLoadDocumentProperties(boolean value)
```


此屬性在簡報檔案受密碼保護時才有意義。值為 true 時表示僅從加密的簡報檔案載入文件屬性，忽略密碼；值為 false 時表示使用正確的密碼載入整個加密的簡報。若簡報未加密則此屬性值始終被忽略。若加密檔案的文件屬性不是公開的且屬性值為 true，則無法載入文件屬性，並會拋出例外。讀/寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```


取得或設定接收警告並決定載入過程是否繼續或中止的物件。讀/寫 [IWarningCallback](../../com.aspose.slides/iwarningcallback)。

**傳回：**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```


取得或設定接收警告並決定載入過程是否繼續或中止的物件。讀/寫 [IWarningCallback](../../com.aspose.slides/iwarningcallback)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public final IBlobManagementOptions getBlobManagementOptions()
```


表示可用於管理二進位大型物件 (BLOB) 處理行為的選項，例如使用暫存檔或在記憶體中限制 BLOB 的最大位元組數。這些選項旨在為特定環境或需求設定最佳的效能/記憶體使用比例。

--------------------

Binary Large Object (BLOB) 是以單一實體儲存的二進位資料 — 例如 BLOB 可以是音訊、影片或簡報本身。

**傳回：**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)

### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public final void setBlobManagementOptions(IBlobManagementOptions value)
```


表示可用於管理二進位大型物件 (BLOB) 處理行為的選項，例如使用暫存檔或在記憶體中限制 BLOB 的最大位元組數。這些選項旨在為特定環境或需求設定最佳的效能/記憶體使用比例。

--------------------

Binary Large Object (BLOB) 是以單一實體儲存的二進位資料 — 例如 BLOB 可以是音訊、影片或簡報本身。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public final IFontSources getDocumentLevelFontSources()
```


指定簡報使用的外部字型來源。這些字型在簡報生命週期內皆可使用，且不會與其他簡報共享。

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  File file = new File("customfonts/CustomFont1.ttf");
>  byte memoryFont1[] = new byte[(int) file.length()];
>  BufferedInputStream bis = new BufferedInputStream(new FileInputStream(file));
>  DataInputStream dis = new DataInputStream(bis);
>  dis.readFully(memoryFont1);
>  file = new File("customfonts/CustomFont2.ttf");
>  byte memoryFont2[] = new byte[(int) file.length()];
>  bis = new BufferedInputStream(new FileInputStream(file));
>  dis = new DataInputStream(bis);
>  dis.readFully(memoryFont2);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  //work with the presentation
>  //CustomFont1, CustomFont2 as well as fonts from assets\fonts & global\fonts folders and their subfolders are available to the presentation
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**傳回：**
[IFontSources](../../com.aspose.slides/ifontsources)

### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public final void setDocumentLevelFontSources(IFontSources value)
```


指定簡報使用的外部字型來源。這些字型在簡報生命週期內皆可使用，且不會與其他簡報共享。

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  File file = new File("customfonts/CustomFont1.ttf");
>  byte memoryFont1[] = new byte[(int) file.length()];
>  BufferedInputStream bis = new BufferedInputStream(new FileInputStream(file));
>  DataInputStream dis = new DataInputStream(bis);
>  dis.readFully(memoryFont1);
>  file = new File("customfonts/CustomFont2.ttf");
>  byte memoryFont2[] = new byte[(int) file.length()];
>  bis = new BufferedInputStream(new FileInputStream(file));
>  dis = new DataInputStream(bis);
>  dis.readFully(memoryFont2);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  //使用簡報
>  //CustomFont1、CustomFont2 以及來自 assets\fonts 與 global\fonts 資料夾及其子資料夾的字型可在簡報中使用
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public final IInterruptionToken getInterruptionToken()
```


用於監視中斷請求的 token。

--------------------

此 token 管理整個 [IPresentation](../../com.aspose.slides/ipresentation) 實例的生命週期。任何長時間執行的作業，例如載入或儲存簡報，都會透過呼叫 [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) 方法來中斷 [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource)。

**傳回：**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)

### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public final void setInterruptionToken(IInterruptionToken value)
```


用於監視中斷請求的 token。

--------------------

此 token 管理整個 [IPresentation](../../com.aspose.slides/ipresentation) 實例的生命週期。任何長時間執行的作業，例如載入或儲存簡報，都會透過呼叫 [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) 方法來中斷 [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public final IResourceLoadingCallback getResourceLoadingCallback()
```


取得或設定管理外部資源載入的回呼介面。讀/寫 [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)。

**傳回：**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)

### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public final void setResourceLoadingCallback(IResourceLoadingCallback value)
```


取得或設定管理外部資源載入的回呼介面。讀/寫 [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final ISpreadsheetOptions getSpreadsheetOptions()
```


取得試算表的選項。例如，這些選項會影響圖表的公式計算。

**傳回：**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)

### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public final void setSpreadsheetOptions(ISpreadsheetOptions value)
```


取得試算表的選項。例如，這些選項會影響圖表的公式計算。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public final String getDefaultTextLanguage()
```


取得或設定簡報文字的預設語言。讀/寫 String。

--------------------

> ```
> Example:
>   
>  // 使用載入選項定義預設文字語系
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // 新增帶文字的矩形形狀
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // 檢查第一段文字語言
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**傳回：**
java.lang.String

### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public final void setDefaultTextLanguage(String value)
```


取得或設定簡報文字的預設語言。讀/寫 String。

--------------------

> ```
> Example:
>   
>  // 使用載入選項定義預設文字語系
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // 新增帶文字的矩形形狀
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // 檢查第一段文字語言
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public final boolean getDeleteEmbeddedBinaryObjects()
```


判斷 Aspose.Slides 在載入簡報時是否會刪除所有嵌入的二進位物件。

The types of the embedded binary objects:

讀/寫 boolean 。

--------------------

> ```
> 以下範例示範如何載入簡報且不包含任何嵌入的二進位物件。
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

預設為 **false** 。

**傳回：**
boolean

### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public final void setDeleteEmbeddedBinaryObjects(boolean value)
```


判斷 Aspose.Slides 在載入簡報時是否會刪除所有嵌入的二進位物件。

The types of the embedded binary objects:

讀/寫 boolean 。

--------------------

> ```
> 以下範例示範如何載入簡報且不包含任何嵌入的二進位物件。
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
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