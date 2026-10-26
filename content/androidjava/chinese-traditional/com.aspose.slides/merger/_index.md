---
title: Merger
second_title: Aspose.Slides for Android via Java API 參考
description: 代表一組用於將相同格式的 PowerPoint 簡報合併為單一檔案的方法。
type: docs
url: /zh-hant/com.aspose.slides/merger/
---
**繼承:**
java.lang.Object
```
public class Merger
```

代表一組用於將相同格式的 PowerPoint 簡報合併為單一檔案的方法。
## 方法

| 方法 | 說明 |
| --- | --- |
| [process(String[] inputFileNames, String outputFileName)](#process-java.lang.String---java.lang.String-) | 將多個相同格式的 PowerPoint 簡報合併為單一簡報檔案。 |
| [process(String[] inputFileNames, String outputFileName, ISaveOptions options)](#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-) | 將多個相同格式的 PowerPoint 簡報合併為單一簡報檔案。 |
| [process(String[] inputFileNames, OutputStream outputStream)](#process-java.lang.String---java.io.OutputStream-) | 將多個相同格式的 PowerPoint 簡報合併為單一簡報檔案。 |
| [process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)](#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-) | 將多個相同格式的 PowerPoint 簡報合併為單一簡報檔案。 |
### process(String[] inputFileNames, String outputFileName) {#process-java.lang.String---java.lang.String-}
```
public static void process(String[] inputFileNames, String outputFileName)
```

將多個相同格式的 PowerPoint 簡報合併為單一簡報檔案。

--------------------

> ```
> Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, "merged.ppt");
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | 輸入簡報檔案名稱的陣列。 |
| outputFileName | java.lang.String | 合併後產生的簡報檔案的輸出檔名。 |

### process(String[] inputFileNames, String outputFileName, ISaveOptions options) {#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, String outputFileName, ISaveOptions options)
```

將多個相同格式的 PowerPoint 簡報合併為單一簡報檔案。

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, "merged.pptx", options);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | 輸入簡報檔案名稱的陣列。 |
| outputFileName | java.lang.String | 合併後產生的簡報檔案的輸出檔名。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 定義合併簡報儲存方式的其他選項。 |

### process(String[] inputFileNames, OutputStream outputStream) {#process-java.lang.String---java.io.OutputStream-}
```
public static void process(String[] inputFileNames, OutputStream outputStream)
```

將多個相同格式的 PowerPoint 簡報合併為單一簡報檔案。

--------------------

> ```
> ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, stream);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | 輸入簡報檔案名稱的陣列。 |
| outputStream | java.io.OutputStream | 輸出串流。 |

### process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options) {#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)
```

將多個相同格式的 PowerPoint 簡報合併為單一簡報檔案。

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, stream, options);
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | 輸入簡報檔案名稱的陣列。 |
| outputStream | java.io.OutputStream | 輸出串流。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 定義合併簡報儲存方式的其他選項。 |