---
title: FontsLoader
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 用於載入使用者自訂字型的類別。
type: docs
url: /zh-hant/com.aspose.slides/fontsloader/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IFontsLoader](../../com.aspose.slides/ifontsloader)
```
public final class FontsLoader implements IFontsLoader
```

用於載入使用者自訂字型的類別。應在建立任何簡報物件之前使用。

## 方法

| 方法 | 描述 |
| --- | --- |
| [loadExternalFonts(String[] directories)](#loadExternalFonts-java.lang.String---) | 新增搜尋字型的其他資料夾。 |
| [loadExternalFont(byte[] data)](#loadExternalFont-byte---) | 從二進位資料新增字型 |
| [getFontFolders()](#getFontFolders--) |  |
| [clearCache()](#clearCache--) |  |

### loadExternalFonts(String[] directories) {#loadExternalFonts-java.lang.String---}
```
public static void loadExternalFonts(String[] directories)
```

新增搜尋字型的其他資料夾。

--------------------

> ```
> The follow examples shows how to load custom fonts from .TTF
>  
>  String dataDir = "C:/Fonts";
>  // 搜尋字型的資料夾
>  String[] folders = new String[] { dataDir };
>  // 載入自訂字型目錄的字型
>  FontsLoader.loadExternalFonts(folders);
>  // 執行一些工作並進行簡報/投影片的渲染
>  Presentation pres = new Presentation("DefaultFonts.pptx");
>  try {
>      pres.save("NewFonts_out.pptx", SaveFormat.Pptx);
>      // 清除字型快取
>      FontsLoader.clearCache();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| directories | java.lang.String[] | 要讀取額外字型的目錄。 |

### loadExternalFont(byte[] data) {#loadExternalFont-byte---}
```
public static void loadExternalFont(byte[] data)
```

從二進位資料新增字型

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| data | byte[] | 字型的資料 |

### getFontFolders() {#getFontFolders--}
```
public static String[] getFontFolders()
```

取得字型資料夾。返回已使用 LoadExternalFonts 方法新增的資料夾以及系統字型資料夾

**傳回值:**
java.lang.String[] - 包含資料夾名稱的陣列

### clearCache() {#clearCache--}
```
public static void clearCache()
```

清除使用者自訂字型

--------------------

此方法需要清除使用者自訂字型的快取。