---
title: Merger
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: 同一形式の PowerPoint プレゼンテーションを 1 つのファイルに結合するためのメソッド群を表します。
type: docs
url: /ja/com.aspose.slides/merger/
---
**継承:**  
java.lang.Object  
```
public class Merger
```

同じ形式の PowerPoint プレゼンテーションを 1 つのファイルに結合するためのメソッド群を表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [process(String[] inputFileNames, String outputFileName)](#process-java.lang.String---java.lang.String-) | 同じ形式の複数の PowerPoint プレゼンテーションを単一のプレゼンテーション ファイルに結合します。 |
| [process(String[] inputFileNames, String outputFileName, ISaveOptions options)](#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-) | 同じ形式の複数の PowerPoint プレゼンテーションを単一のプレゼンテーション ファイルに結合します。 |
| [process(String[] inputFileNames, OutputStream outputStream)](#process-java.lang.String---java.io.OutputStream-) | 同じ形式の複数の PowerPoint プレゼンテーションを単一のプレゼンテーション ファイルに結合します。 |
| [process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)](#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-) | 同じ形式の複数の PowerPoint プレゼンテーションを単一のプレゼンテーション ファイルに結合します。 |

### process(String[] inputFileNames, String outputFileName) {#process-java.lang.String---java.lang.String-}
```
public static void process(String[] inputFileNames, String outputFileName)
```

同じ形式の複数の PowerPoint プレゼンテーションを単一のプレゼンテーション ファイルに結合します。

--------------------

> ```
> Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, "merged.ppt");
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | 入力プレゼンテーション ファイル名の配列です。 |
| outputFileName | java.lang.String | 結合されたプレゼンテーション ファイルの出力ファイル名です。 |

### process(String[] inputFileNames, String outputFileName, ISaveOptions options) {#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, String outputFileName, ISaveOptions options)
```

同じ形式の複数の PowerPoint プレゼンテーションを単一のプレゼンテーション ファイルに結合します。

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, "merged.pptx", options);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | 入力プレゼンテーション ファイル名の配列です。 |
| outputFileName | java.lang.String | 結合されたプレゼンテーション ファイルの出力ファイル名です。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 結合されたプレゼンテーションの保存方法を定義する追加オプションです。 |

### process(String[] inputFileNames, OutputStream outputStream) {#process-java.lang.String---java.io.OutputStream-}
```
public static void process(String[] inputFileNames, OutputStream outputStream)
```

同じ形式の複数の PowerPoint プレゼンテーションを単一のプレゼンテーション ファイルに結合します。

--------------------

> ```
> ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, stream);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | 入力プレゼンテーション ファイル名の配列です。 |
| outputStream | java.io.OutputStream | 出力ストリームです。 |

### process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options) {#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)
```

同じ形式の複数の PowerPoint プレゼンテーションを単一のプレゼンテーション ファイルに結合します。

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, stream, options);
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | 入力プレゼンテーション ファイル名の配列です。 |
| outputStream | java.io.OutputStream | 出力ストリームです。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 結合されたプレゼンテーションの保存方法を定義する追加オプションです。 |