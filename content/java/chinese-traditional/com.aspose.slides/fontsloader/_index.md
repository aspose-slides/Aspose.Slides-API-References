---
title: FontsLoader
second_title: Aspose.Slides for Java API 參考
description: 用於載入使用者自訂字型的類別。
type: docs
url: /zh-hant/com.aspose.slides/fontsloader/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.IFontsLoader](../../com.aspose.slides/ifontsloader)
```
public final class FontsLoader implements IFontsLoader
```

此類別用於載入使用者自訂的字型。應在建立任何簡報物件之前使用。
## 方法

| 方法 | 說明 |
| --- | --- |
| [loadExternalFonts(String[] directories)](#loadExternalFonts-java.lang.String---) | 新增額外的資料夾以搜尋字型。 |
| [loadExternalFont(byte[] data)](#loadExternalFont-byte---) | 從二進位資料新增字型。 |
| [getFontFolders()](#getFontFolders--) | 取得字型資料夾。 |
| [clearCache()](#clearCache--) | 釋放使用者定義的所有自訂字型。 |
### loadExternalFonts(String[] directories) {#loadExternalFonts-java.lang.String---}
```
public static void loadExternalFonts(String[] directories)
```


新增額外的資料夾以搜尋字型。

--------------------

> ```
> The follow examples shows how to load custom fonts from .TTF
>  
>  String dataDir = "C:/Fonts";
>  // 用於搜尋字型的資料夾
>  String[] folders = new String[] { dataDir };
>  // 載入自訂字型資料夾
>  FontsLoader.loadExternalFonts(folders);
>  // 執行一些工作並進行簡報/投影片渲染
>  Presentation pres = new Presentation("DefaultFonts.pptx");
>  try {
>      pres.save("NewFonts_out.pptx", SaveFormat.Pptx);
>      // 清除字型快取
>      FontsLoader.clearCache();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| directories | java.lang.String[] | 用於讀取額外字型的目錄。 |

### loadExternalFont(byte[] data) {#loadExternalFont-byte---}
```
public static void loadExternalFont(byte[] data)
```


從二進位資料新增字型。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| data | byte[] | 字型資料 |

### getFontFolders() {#getFontFolders--}
```
public static String[] getFontFolders()
```


取得字型資料夾。返回已使用 LoadExternalFonts 方法加入的資料夾以及系統字型資料夾。

**返回：**
java.lang.String[] - 包含資料夾名稱的陣列
### clearCache() {#clearCache--}
```
public static void clearCache()
```


釋放使用者定義的所有自訂字型。

--------------------

此方法需要清除使用者定義的自訂字型快取。