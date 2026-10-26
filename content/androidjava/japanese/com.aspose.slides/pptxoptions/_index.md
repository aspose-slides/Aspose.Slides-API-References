---
title: PptxOptions
second_title: Aspose.Slides for Android の Java API リファレンス
description: OpenXml プレゼンテーション (PPTX、PPSX、POTX、PPTM、PPSM、POTM) の保存オプションを表します。
type: docs
url: /ja/com.aspose.slides/pptxoptions/
---
**継承:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IPptxOptions](../../com.aspose.slides/ipptxoptions), java.lang.Cloneable
```
public final class PptxOptions extends SaveOptions implements IPptxOptions, Cloneable
```

OpenXml プレゼンテーション (PPTX, PPSX, POTX, PPTM, PPSM, POTM) の保存オプションを表します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PptxOptions()](#PptxOptions--) | PptxOptions の新しいインスタンスを作成します |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getConformance()](#getConformance--) | Presentation ドキュメントが準拠する適合クラスを指定します。 |
| [setConformance(int value)](#setConformance-int-) | Presentation ドキュメントが準拠する適合クラスを指定します。 |
| [getZip64Mode()](#getZip64Mode--) | Presentation ドキュメントに ZIP64 形式を使用するかどうかを指定します。 |
| [setZip64Mode(int value)](#setZip64Mode-int-) | Presentation ドキュメントに ZIP64 形式を使用するかどうかを指定します。 |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | プレゼンテーションのサムネイルを更新するかどうかを指定します。 |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | プレゼンテーションのサムネイルを更新するかどうかを指定します。 |
| [getCompressionLevel()](#getCompressionLevel--) | プレゼンテーション ドキュメントを保存する際に使用される圧縮レベルを指定します。 |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | プレゼンテーション ドキュメントを保存する際に使用される圧縮レベルを指定します。 |
### PptxOptions() {#PptxOptions--}
```
public PptxOptions()
```

PptxOptions の新しいインスタンスを作成します

### getConformance() {#getConformance--}
```
public final int getConformance()
```

Presentation ドキュメントが準拠する適合クラスを指定します。デフォルト値は [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)です。

**戻り値:**
int
### setConformance(int value) {#setConformance-int-}
```
public final void setConformance(int value)
```

Presentation ドキュメントが準拠する適合クラスを指定します。デフォルト値は [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public final int getZip64Mode()
```

Presentation ドキュメントに ZIP64 形式を使用するかどうかを指定します。デフォルト値は [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)です。

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
public final void setZip64Mode(int value)
```

Presentation ドキュメントに ZIP64 形式を使用するかどうかを指定します。デフォルト値は [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)です。

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
public final boolean getRefreshThumbnail()
```

プレゼンテーションのサムネイルを更新するかどうかを指定します。読み取り/書き込み boolean。デフォルト値は **true**です。

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

**true** の場合、新しいサムネイルが生成されます。  
**false** の場合、現在のサムネイルがそのまま保存されます。

**戻り値:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public final void setRefreshThumbnail(boolean value)
```

プレゼンテーションのサムネイルを更新するかどうかを指定します。読み取り/書き込み boolean。デフォルト値は **true**です。

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

**true** の場合、新しいサムネイルが生成されます。  
**false** の場合、現在のサムネイルがそのまま保存されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public final int getCompressionLevel()
```

プレゼンテーション ドキュメントを保存する際に使用される圧縮レベルを指定します。デフォルト値は [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6)です。

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
public final void setCompressionLevel(int value)
```

プレゼンテーション ドキュメントを保存する際に使用される圧縮レベルを指定します。デフォルト値は [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6)です。

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