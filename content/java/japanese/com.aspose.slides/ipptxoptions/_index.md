---
title: IPptxOptions
second_title: Aspose.Slides for Java API リファレンス
description: OpenXml プレゼンテーション（PPTX、PPSX、POTX、PPTM、PPSM、POTM）を保存するためのオプションを表します。
type: docs
url: /ja/com.aspose.slides/ipptxoptions/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptxOptions extends ISaveOptions
```

プレゼンテーション (PPTX, PPSX, POTX, PPTM, PPSM, POTM) の OpenXml 形式での保存オプションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getConformance()](#getConformance--) | プレゼンテーション ドキュメントが準拠するコンフォーマンス クラスを指定します。 |
| [setConformance(int value)](#setConformance-int-) | プレゼンテーション ドキュメントが準拠するコンフォーマンス クラスを指定します。 |
| [getZip64Mode()](#getZip64Mode--) | プレゼンテーション ドキュメントで ZIP64 形式を使用するかどうかを指定します。 |
| [setZip64Mode(int value)](#setZip64Mode-int-) | プレゼンテーション ドキュメントで ZIP64 形式を使用するかどうかを指定します。 |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | プレゼンテーション サムネイルを更新するかどうかを指定します。 |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | プレゼンテーション サムネイルを更新するかどうかを指定します。 |
| [getCompressionLevel()](#getCompressionLevel--) | プレゼンテーション ドキュメントの保存時に使用する圧縮レベルを指定します。 |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | プレゼンテーション ドキュメントの保存時に使用する圧縮レベルを指定します。 |
### getConformance() {#getConformance--}
```
public abstract int getConformance()
```

プレゼンテーション ドキュメントが準拠するコンフォーマンス クラスを指定します。デフォルト値は [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**戻り値:**
int
### setConformance(int value) {#setConformance-int-}
```
public abstract void setConformance(int value)
```

プレゼンテーション ドキュメントが準拠するコンフォーマンス クラスを指定します。デフォルト値は [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public abstract int getZip64Mode()
```

プレゼンテーション ドキュメントで ZIP64 形式を使用するかどうかを指定します。デフォルト値は [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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

プレゼンテーション ドキュメントで ZIP64 形式を使用するかどうかを指定します。デフォルト値は [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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

プレゼンテーション サムネイルを更新するかどうかを指定します。読み書き可能なブール値。デフォルト値は **true**。

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

オプションの値が **false** の場合、現在のサムネイルがそのまま保存されます。

**戻り値:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public abstract void setRefreshThumbnail(boolean value)
```

プレゼンテーション サムネイルを更新するかどうかを指定します。読み書き可能なブール値。デフォルト値は **true**。

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

オプションの値が **false** の場合、現在のサムネイルがそのまま保存されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public abstract int getCompressionLevel()
```

プレゼンテーション ドキュメントの保存時に使用する圧縮レベルを指定します。デフォルト値は [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6)。

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

圧縮レベルが高いほどファイルは小さくなりますが、処理時間が長くなります。実際の圧縮率はプレゼンテーションの内容に依存します。

**戻り値:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public abstract void setCompressionLevel(int value)
```

プレゼンテーション ドキュメントの保存時に使用する圧縮レベルを指定します。デフォルト値は [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6)。

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

圧縮レベルが高いほどファイルは小さくなりますが、処理時間が長くなります。実際の圧縮率はプレゼンテーションの内容に依存します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |