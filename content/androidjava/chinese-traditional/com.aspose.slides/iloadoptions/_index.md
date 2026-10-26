---
title: ILoadOptions
second_title: Aspose.Slides for Android via Java API Reference
description: 允許在載入簡報時指定其他選項（例如格式或預設字型）。
type: docs
url: /zh-hant/com.aspose.slides/iloadoptions/
---```
public interface ILoadOptions
```

允許在載入簡報時指定其他選項（例如格式或預設字型）。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | 取得或設定要載入的簡報格式。 |
| [setLoadFormat(int value)](#setLoadFormat-int-) | 取得或設定要載入的簡報格式。 |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | 取得或設定在未找到來源字型時使用的常規字型。 |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | 取得或設定在未找到來源字型時使用的常規字型。 |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | 取得或設定在未找到來源字型時使用的符號字型。 |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | 取得或設定在未找到來源字型時使用的符號字型。 |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | 取得或設定在未找到來源字型時使用的亞洲字型。 |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | 取得或設定在未找到來源字型時使用的亞洲字型。 |
| [getPassword()](#getPassword--) | 取得或設定密碼。 |
| [setPassword(String value)](#setPassword-java.lang.String-) | 取得或設定密碼。 |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | 如果簡報檔案受密碼保護，該屬性才有意義。 |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | 如果簡報檔案受密碼保護，該屬性才有意義。 |
| [getWarningCallback()](#getWarningCallback--) | 取得或設定接收警告並決定載入過程是否繼續或中止的物件。 |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | 取得或設定接收警告並決定載入過程是否繼續或中止的物件。 |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | 表示可用於管理大型二進位物件 (BLOB) 處理行為的選項，例如使用暫存檔或記憶體中最大 BLOB 位元組數。 |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | 表示可用於管理大型二進位物件 (BLOB) 處理行為的選項，例如使用暫存檔或記憶體中最大 BLOB 位元組數。 |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | 指定簡報使用的外部字型來源。 |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | 指定簡報使用的外部字型來源。 |
| [getInterruptionToken()](#getInterruptionToken--) | 用來監測中斷請求的代幣。 |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | 用來監測中斷請求的代幣。 |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | 取得或設定管理外部資源載入的回呼介面。 |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | 取得或設定管理外部資源載入的回呼介面。 |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | 表示可用於指定額外試算表行為的選項。 |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | 表示可用於指定額外試算表行為的選項。 |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | 取得或設定簡報文字的預設語言。 |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | 取得或設定簡報文字的預設語言。 |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | 判斷 Aspose.Slides 在載入簡報時是否會刪除所有嵌入的二進位物件。 |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | 判斷 Aspose.Slides 在載入簡報時是否會刪除所有嵌入的二進位物件。 |

### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

取得或設定要載入的簡報格式。可讀寫 [LoadFormat](../../com.aspose.slides/loadformat)。

**傳回值:**
int

### setLoadFormat(int value) {#setLoadFormat-int-}
```
public abstract void setLoadFormat(int value)
```

取得或設定要載入的簡報格式。可讀寫 [LoadFormat](../../com.aspose.slides/loadformat)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

取得或設定在未找到來源字型時使用的常規字型。可讀寫 String。

**傳回值:**
java.lang.String

### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```

取得或設定在未找到來源字型時使用的常規字型。可讀寫 String。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public abstract String getDefaultSymbolFont()
```

取得或設定在未找到來源字型時使用的符號字型。可讀寫 String。

**傳回值:**
java.lang.String

### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public abstract void setDefaultSymbolFont(String value)
```

取得或設定在未找到來源字型時使用的符號字型。可讀寫 String。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public abstract String getDefaultAsianFont()
```

取得或設定在未找到來源字型時使用的亞洲字型。可讀寫 String。

**傳回值:**
java.lang.String

### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public abstract void setDefaultAsianFont(String value)
```

取得或設定在未找到來源字型時使用的亞洲字型。可讀寫 String。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

取得或設定密碼。可讀寫 String。

值：密碼。

**傳回值:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

取得或設定密碼。可讀寫 String。

值：密碼。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public abstract boolean getOnlyLoadDocumentProperties()
```

如果簡報檔案受密碼保護，該屬性才有意義。值為 true 時表示只從加密的簡報檔案載入文件屬性且忽略密碼；值為 false 時表示使用正確密碼載入整個加密簡報。如果簡報未加密則始終忽略此屬性值。如果加密檔案的文件屬性不是公開的且屬性值為 true，則無法載入文件屬性，將拋出例外。可讀寫 boolean。

**傳回值:**
boolean

### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public abstract void setOnlyLoadDocumentProperties(boolean value)
```

如果簡報檔案受密碼保護，該屬性才有意義。值為 true 時表示只從加密的簡報檔案載入文件屬性且忽略密碼；值為 false 時表示使用正確密碼載入整個加密簡報。如果簡報未加密則始終忽略此屬性值。如果加密檔案的文件屬性不是公開的且屬性值為 true，則無法載入文件屬性，將拋出例外。可讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

取得或設定接收警告並決定載入過程是否繼續或中止的物件。可讀寫 [IWarningCallback](../../com.aspose.slides/iwarningcallback)。

**傳回值:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

取得或設定接收警告並決定載入過程是否繼續或中止的物件。可讀寫 [IWarningCallback](../../com.aspose.slides/iwarningcallback)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public abstract IBlobManagementOptions getBlobManagementOptions()
```

表示可用於管理大型二進位物件 (BLOB) 處理行為的選項，例如使用暫存檔或記憶體中最大 BLOB 位元組數。這些選項旨在為特定環境或需求設定最佳的效能/記憶體使用比例。

--------------------

Binary Large Object (BLOB) 是作為單一實體儲存的二進位資料——即 BLOB 可以是音訊、影片或簡報本身。

**傳回值:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)

### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public abstract void setBlobManagementOptions(IBlobManagementOptions value)
```

表示可用於管理大型二進位物件 (BLOB) 處理行為的選項，例如使用暫存檔或記憶體中最大 BLOB 位元組數。這些選項旨在為特定環境或需求設定最佳的效能/記憶體使用比例。

--------------------

Binary Large Object (BLOB) 是作為單一實體儲存的二進位資料——即 BLOB 可以是音訊、影片或簡報本身。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public abstract IFontSources getDocumentLevelFontSources()
```

指定簡報使用的外部字型來源。這些字型在簡報的整個生命週期內都可用，且不會與其他簡報共享。

**傳回值:**
[IFontSources](../../com.aspose.slides/ifontsources)

### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public abstract void setDocumentLevelFontSources(IFontSources value)
```

指定簡報使用的外部字型來源。這些字型在簡報的整個生命週期內都可用，且不會與其他簡報共享。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public abstract IInterruptionToken getInterruptionToken()
```

用來監測中斷請求的代幣。

--------------------

此代幣管理整個 [IPresentation](../../com.aspose.slides/ipresentation) 實例的生命週期。任何長時間執行的操作，例如簡報載入或儲存，皆會透過呼叫 [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) 方法的方式中斷 [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource)。

**傳回值:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)

### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public abstract void setInterruptionToken(IInterruptionToken value)
```

用來監測中斷請求的代幣。

--------------------

此代幣管理整個 [IPresentation](../../com.aspose.slides/ipresentation) 實例的生命週期。任何長時間執行的操作，例如簡報載入或儲存，皆會透過呼叫 [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) 方法的方式中斷 [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public abstract IResourceLoadingCallback getResourceLoadingCallback()
```

取得或設定管理外部資源載入的回呼介面。可讀寫 [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)。

**傳回值:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)

### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public abstract void setResourceLoadingCallback(IResourceLoadingCallback value)
```

取得或設定管理外部資源載入的回呼介面。可讀寫 [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public abstract ISpreadsheetOptions getSpreadsheetOptions()
```

表示可用於指定額外試算表行為的選項。

**傳回值:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)

### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public abstract void setSpreadsheetOptions(ISpreadsheetOptions value)
```

表示可用於指定額外試算表行為的選項。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public abstract String getDefaultTextLanguage()
```

取得或設定簡報文字的預設語言。可讀寫 String。

--------------------

> ```
> Example:
>   
>  // 使用載入選項來定義預設文字語系
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // 新增帶文字的矩形形狀
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // 檢查第一個段落的語言
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**傳回值:**
java.lang.String

### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public abstract void setDefaultTextLanguage(String value)
```

取得或設定簡報文字的預設語言。可讀寫 String。

--------------------

> ```
> Example:
>   
>  // 使用載入選項來定義預設文字語系
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // 新增帶文字的矩形形狀
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // 檢查第一個段落的語言
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public abstract boolean getDeleteEmbeddedBinaryObjects()
```

判斷 Aspose.Slides 在載入簡報時是否會刪除所有嵌入的二進位物件。

嵌入的二進位物件類型：

 *  
 *  
 *  

可讀寫 boolean。

--------------------

> ```
> 以下範例說明如何在不含任何嵌入二進位物件的情況下載入簡報。
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

**傳回值:**
boolean

### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public abstract void setDeleteEmbeddedBinaryObjects(boolean value)
```

判斷 Aspose.Slides 在載入簡報時是否會刪除所有嵌入的二進位物件。

嵌入的二進位物件類型：

 *  
 *  
 *  

可讀寫 boolean。

--------------------

> ```
> 以下範例說明如何在不含任何嵌入二進位物件的情況下載入簡報。
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

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |