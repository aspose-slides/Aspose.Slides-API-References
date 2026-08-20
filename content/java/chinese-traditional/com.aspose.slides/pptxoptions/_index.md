---
title: PptxOptions
second_title: Aspose.Slides for Java API 參考
description: 表示用於儲存 OpenXml 簡報（PPTX、PPSX、POTX、PPTM、PPSM、POTM）的選項。
type: docs
url: /zh-hant/com.aspose.slides/pptxoptions/
---
**繼承:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**所有已實作的介面:**
[com.aspose.slides.IPptxOptions](../../com.aspose.slides/ipptxoptions), java.lang.Cloneable
```
public final class PptxOptions extends SaveOptions implements IPptxOptions, Cloneable
```

表示用於儲存 OpenXml 簡報 (PPTX, PPSX, POTX, PPTM, PPSM, POTM) 的選項。

## 建構子

| Constructor | Description |
| --- | --- |
| [PptxOptions()](#PptxOptions--) | 建立 PptxOptions 的新實例 |
## 方法

| Method | Description |
| --- | --- |
| [getConformance()](#getConformance--) | 指定簡報文件所符合的相容等級類別。 |
| [setConformance(int value)](#setConformance-int-) | 指定簡報文件所符合的相容等級類別。 |
| [getZip64Mode()](#getZip64Mode--) | 指定簡報文件是否使用 ZIP64 格式。 |
| [setZip64Mode(int value)](#setZip64Mode-int-) | 指定簡報文件是否使用 ZIP64 格式。 |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | 指定是否重新整理簡報縮圖。 |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | 指定是否重新整理簡報縮圖。 |
| [getCompressionLevel()](#getCompressionLevel--) | 指定儲存簡報文件時使用的壓縮等級。 |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | 指定儲存簡報文件時使用的壓縮等級。 |
### PptxOptions() {#PptxOptions--}
```
public PptxOptions()
```


建立 PptxOptions 的新實例

### getConformance() {#getConformance--}
```
public final int getConformance()
```


指定簡報文件所符合的相容等級類別。預設值為 [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**傳回值:**
int
### setConformance(int value) {#setConformance-int-}
```
public final void setConformance(int value)
```


指定簡報文件所符合的相容等級類別。預設值為 [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getZip64Mode() {#getZip64Mode--}
```
public final int getZip64Mode()
```


指定簡報文件是否使用 ZIP64 格式。預設值為 [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

--------------------

> ```
> 範例：
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

**傳回值:**
int
### setZip64Mode(int value) {#setZip64Mode-int-}
```
public final void setZip64Mode(int value)
```


指定簡報文件是否使用 ZIP64 格式。預設值為 [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

--------------------

> ```
> 範例：
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
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getRefreshThumbnail() {#getRefreshThumbnail--}
```
public final boolean getRefreshThumbnail()
```


指定是否重新整理簡報縮圖。可讀寫 boolean。預設值為 **true**。

--------------------

> ```
> 範例：
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

當選項值為 **false** 時，將保留目前的縮圖不變。

**傳回值:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public final void setRefreshThumbnail(boolean value)
```


指定是否重新整理簡報縮圖。可讀寫 boolean。預設值為 **true**。

--------------------

> ```
> 範例：
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

當選項值為 **false** 時，將保留目前的縮圖不變。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getCompressionLevel() {#getCompressionLevel--}
```
public final int getCompressionLevel()
```


指定儲存簡報文件時使用的壓縮等級。預設值為 [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6)。

--------------------

> ```
> 範例：
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

較高的壓縮等級會產生較小的檔案，但需要更多的處理時間。實際的壓縮比取決於簡報的內容。

**傳回值:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public final void setCompressionLevel(int value)
```


指定儲存簡報文件時使用的壓縮等級。預設值為 [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6)。

--------------------

> ```
> 範例：
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

較高的壓縮等級會產生較小的檔案，但需要更多的處理時間。實際的壓縮比取決於簡報的內容。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |