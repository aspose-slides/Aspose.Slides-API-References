---
title: IPptxOptions
second_title: Aspose.Slides for Java API 參考
description: 代表用於儲存 OpenXml 簡報 (PPTX、PPSX、POTX、PPTM、PPSM、POTM) 的選項。
type: docs
url: /zh-hant/com.aspose.slides/ipptxoptions/
---
**所有已實作的介面：**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptxOptions extends ISaveOptions
```

代表用於儲存 OpenXml presentations (PPTX、PPSX、POTX、PPTM、PPSM、POTM) 的選項。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getConformance()](#getConformance--) | 指定 Presentation 文件符合的相容等級。 |
| [setConformance(int value)](#setConformance-int-) | 指定 Presentation 文件符合的相容等級。 |
| [getZip64Mode()](#getZip64Mode--) | 指定 Presentation 文件是否使用 ZIP64 格式。 |
| [setZip64Mode(int value)](#setZip64Mode-int-) | 指定 Presentation 文件是否使用 ZIP64 格式。 |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | 指定是否重新整理簡報縮圖。 |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | 指定是否重新整理簡報縮圖。 |
| [getCompressionLevel()](#getCompressionLevel--) | 指定儲存簡報文件時使用的壓縮等級。 |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | 指定儲存簡報文件時使用的壓縮等級。 |
### getConformance() {#getConformance--}
```
public abstract int getConformance()
```


指定 Presentation 文件符合的相容等級。預設值為 [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**返回值:**
int
### setConformance(int value) {#setConformance-int-}
```
public abstract void setConformance(int value)
```


指定 Presentation 文件符合的相容等級。預設值為 [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public abstract int getZip64Mode()
```


指定 Presentation 文件是否使用 ZIP64 格式。預設值為 [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setZip64Mode(Zip64Mode.Always);
>      pres.save("demo-zip64.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回值:**
int
### setZip64Mode(int value) {#setZip64Mode-int-}
```
public abstract void setZip64Mode(int value)
```


指定 Presentation 文件是否使用 ZIP64 格式。預設值為 [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setZip64Mode(Zip64Mode.Always);
>      pres.save("demo-zip64.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getRefreshThumbnail() {#getRefreshThumbnail--}
```
public abstract boolean getRefreshThumbnail()
```


指定是否重新整理簡報縮圖。可讀寫布林值。預設值為 **true**。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setRefreshThumbnail(false);
>      pres.save("result_with_old_thumbnail.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

當選項值為 **true** 時，將產生新的縮圖。

當選項值為 **false** 時，當前縮圖將保持不變。

**返回值:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public abstract void setRefreshThumbnail(boolean value)
```


指定是否重新整理簡報縮圖。可讀寫布林值。預設值為 **true**。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setRefreshThumbnail(false);
>      pres.save("result_with_old_thumbnail.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

當選項值為 **true** 時，將產生新的縮圖。

當選項值為 **false** 時，當前縮圖將保持不變。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public abstract int getCompressionLevel()
```


指定儲存簡報文件時使用的壓縮等級。預設值為 [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6)。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setCompressionLevel(CompressionLevel.Level8);
>      pres.save("demo-level8.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

較高的壓縮等級會產生較小的檔案，但需要更多的處理時間。實際的壓縮比例取決於簡報的內容。

**返回值:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public abstract void setCompressionLevel(int value)
```


指定儲存簡報文件時使用的壓縮等級。預設值為 [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6)。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setCompressionLevel(CompressionLevel.Level8);
>      pres.save("demo-level8.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

較高的壓縮等級會產生較小的檔案，但需要更多的處理時間。實際的壓縮比例取決於簡報的內容。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |