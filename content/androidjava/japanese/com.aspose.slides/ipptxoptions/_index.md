---
title: IPptxOptions
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: OpenXml プレゼンテーション (PPTX、PPSX、POTX、PPTM、PPSM、POTM) の保存オプションを表します。
type: docs
url: /ja/com.aspose.slides/ipptxoptions/
---
**すべての実装されたインターフェイス:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptxOptions extends ISaveOptions
```

OpenXml プレゼンテーション (PPTX、PPSX、POTX、PPTM、PPSM、POTM) の保存オプションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getConformance()](#getConformance--) | Presentation ドキュメントが準拠するコンフォーネンス クラスを指定します。 |
| [setConformance(int value)](#setConformance-int-) | Presentation ドキュメントが準拠するコンフォーネンス クラスを指定します。 |
| [getZip64Mode()](#getZip64Mode--) | Presentation ドキュメントで ZIP64 形式を使用するかどうかを指定します。 |
| [setZip64Mode(int value)](#setZip64Mode-int-) | Presentation ドキュメントで ZIP64 形式を使用するかどうかを指定します。 |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | presentation サムネイルを更新するかどうかを指定します。 |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | presentation サムネイルを更新するかどうかを指定します。 |
| [getCompressionLevel()](#getCompressionLevel--) | presentation ドキュメントを保存する際に使用される圧縮レベルを指定します。 |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | presentation ドキュメントを保存する際に使用される圧縮レベルを指定します。 |
### getConformance() {#getConformance--}
```
public abstract int getConformance()
```


Presentation ドキュメントが準拠するコンフォーネンス クラスを指定します。既定値は [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006) です。

**戻り値:**
int
### setConformance(int value) {#setConformance-int-}
```
public abstract void setConformance(int value)
```


Presentation ドキュメントが準拠するコンフォーネンス クラスを指定します。既定値は [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006) です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public abstract int getZip64Mode()
```


Presentation ドキュメントで ZIP64 形式を使用するかどうかを指定します。既定値は [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary) です。

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


**戻り値:**
int
### setZip64Mode(int value) {#setZip64Mode-int-}
```
public abstract void setZip64Mode(int value)
```


Presentation ドキュメントで ZIP64 形式を使用するかどうかを指定します。既定値は [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary) です。

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


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getRefreshThumbnail() {#getRefreshThumbnail--}
```
public abstract boolean getRefreshThumbnail()
```


presentation サムネイルを更新するかどうかを指定します。読み書き可能なブール値です。既定値は **true** です。

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

オプションの値が **true** の場合、新しいサムネイルが生成されます。

オプションの値が **false** の場合、現在のサムネイルはそのまま保存されます。

**戻り値:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public abstract void setRefreshThumbnail(boolean value)
```


presentation サムネイルを更新するかどうかを指定します。読み書き可能なブール値です。既定値は **true** です。

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

オプションの値が **true** の場合、新しいサムネイルが生成されます。

オプションの値が **false** の場合、現在のサムネイルはそのまま保存されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public abstract int getCompressionLevel()
```


presentation ドキュメントを保存する際に使用される圧縮レベルを指定します。既定値は [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6) です。

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

圧縮レベルが高いほどファイルは小さくなりますが、処理により時間がかかります。実際の圧縮率は presentation の内容に依存します。

**戻り値:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public abstract void setCompressionLevel(int value)
```


presentation ドキュメントを保存する際に使用される圧縮レベルを指定します。既定値は [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6) です。

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

圧縮レベルが高いほどファイルは小さくなりますが、処理により時間がかかります。実際の圧縮率は presentation の内容に依存します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |