---
title: IPdfOptions
second_title: Aspose.Slides の Java API リファレンス
description: プレゼンテーションを PDF 形式で保存する方法を制御するオプションを提供します。
type: docs
url: /ja/com.aspose.slides/ipdfoptions/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPdfOptions extends ISaveOptions
```

プレゼンテーションを PDF 形式で保存する方法を制御するオプションを提供します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getTextCompression()](#getTextCompression--) | 文書内のすべてのテキスト コンテンツに使用される圧縮タイプを指定します。 |
| [setTextCompression(int value)](#setTextCompression-int-) | 文書内のすべてのテキスト コンテンツに使用される圧縮タイプを指定します。 |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | 各画像に対して、デフォルトの圧縮ではなく最も効果的な圧縮を自動的に選択すべきかどうかを示します。 |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | 各画像に対して、デフォルトの圧縮ではなく最も効果的な圧縮を自動的に選択すべきかどうかを示します。 |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | ASCII 文字 32-127 の TrueType フォントを埋め込むには **true** を設定します。 |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | ASCII 文字 32-127 の TrueType フォントを埋め込むには **true** を設定します。 |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。 |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Aspose.Slides が共通とみなすフォント ファミリのユーザー定義名の配列を取得または設定します。 |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Aspose.Slides が共通とみなすフォント ファミリのユーザー定義名の配列を取得または設定します。 |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | フォントのすべての文字を埋め込むか、使用したサブセットのみを埋め込むかを決定します。 |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | フォントのすべての文字を埋め込むか、使用したサブセットのみを埋め込むかを決定します。 |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | フォントが太字スタイルをサポートしていない場合に、テキストをビットマップとしてラスター化し PDF に保存すべきかどうかを示します。 |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | フォントが太字スタイルをサポートしていない場合に、テキストをビットマップとしてラスター化し PDF に保存すべきかどうかを示します。 |
| [getJpegQuality()](#getJpegQuality--) | PDF ドキュメント内の JPEG 画像の品質を決定する値を取得または設定します。 |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | PDF ドキュメント内の JPEG 画像の品質を決定する値を取得または設定します。 |
| [getCompliance()](#getCompliance--) | 生成された PDF ドキュメントの目的となる適合レベルを指定します。 |
| [setCompliance(int value)](#setCompliance-int-) | 生成された PDF ドキュメントの目的となる適合レベルを指定します。 |
| [getPassword()](#getPassword--) | PDF ドキュメントを保護するためのユーザーパスワードを設定します。 |
| [setPassword(String value)](#setPassword-java.lang.String-) | PDF ドキュメントを保護するためのユーザーパスワードを設定します。 |
| [getAccessPermissions()](#getAccessPermissions--) | ユーザーアクセスでドキュメントを開いたときに付与すべきアクセス権限を指定するフラグのセットを含みます。 |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | ユーザーアクセスでドキュメントを開いたときに付与すべきアクセス権限を指定するフラグのセットを含みます。 |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | プレゼンテーションで使用されているすべてのメタファイルを PNG 画像に変換するには **true** を設定します。 |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | プレゼンテーションで使用されているすべてのメタファイルを PNG 画像に変換するには **true** を設定します。 |
| [getSufficientResolution()](#getSufficientResolution--) | PDF ドキュメント内の画像の解像度を決定する値を取得または設定します。 |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | PDF ドキュメント内の画像の解像度を決定する値を取得または設定します。 |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | 各スライドの周囲に黒い枠線を描画するには **true** を設定します。 |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | 各スライドの周囲に黒い枠線を描画するには **true** を設定します。 |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | プレゼンテーションをエクスポートする際にスライドがページ上に配置されるモードを取得または設定します [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | プレゼンテーションをエクスポートする際にスライドがページ上に配置されるモードを取得または設定します [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [getImageTransparentColor()](#getImageTransparentColor--) | 画像の透過色を取得または設定します。 |
| [setImageTransparentColor(Color value)](#setImageTransparentColor-java.awt.Color-) | 画像の透過色を取得または設定します。 |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | **true** の場合、指定された透過色を画像に適用します。 |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | **true** の場合、指定された透過色を画像に適用します。 |
| [getInkOptions()](#getInkOptions--) | エクスポートされたドキュメント内のインク オブジェクトの外観を制御するオプションを提供します。 |
| [getIncludeOleData()](#getIncludeOleData--) | プレゼンテーションからすべての OLE データを変換し、結果の PDF に埋め込みファイルとして保存するには **true** を設定します。 |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | プレゼンテーションからすべての OLE データを変換し、結果の PDF に埋め込みファイルとして保存するには **true** を設定します。 |

### getTextCompression() {#getTextCompression--}
```
public abstract int getTextCompression()
```

文書内のすべてのテキスト コンテンツに使用される圧縮タイプを指定します。読み取り/書き込み [PdfTextCompression](../../com.aspose.slides/pdftextcompression)。

--------------------

デフォルトは [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate)。

**戻り値:**
int

### setTextCompression(int value) {#setTextCompression-int-}
```
public abstract void setTextCompression(int value)
```

文書内のすべてのテキスト コンテンツに使用される圧縮タイプを指定します。読み取り/書き込み [PdfTextCompression](../../com.aspose.slides/pdftextcompression)。

--------------------

デフォルトは [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public abstract boolean getBestImagesCompressionRatio()
```

各画像に対して、デフォルトの圧縮ではなく最も効果的な圧縮を自動的に選択すべきかどうかを示します。true に設定すると、プレゼンテーション内のすべての画像に対して最適な圧縮アルゴリズムが選択され、結果の PDF ドキュメントのサイズが小さくなります。

--------------------

最も効果的な画像圧縮率の選択は計算コストが高く、追加の RAM が必要です。このオプションはデフォルトで **false** です。

--------------------

デフォルトは **false**。

**戻り値:**
boolean

### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public abstract void setBestImagesCompressionRatio(boolean value)
```

各画像に対して、デフォルトの圧縮ではなく最も効果的な圧縮を自動的に選択すべきかどうかを示します。true に設定すると、プレゼンテーション内のすべての画像に対して最適な圧縮アルゴリズムが選択され、結果の PDF ドキュメントのサイズが小さくなります。

--------------------

最も効果的な画像圧縮率の選択は計算コストが高く、追加の RAM が必要です。このオプションはデフォルトで **false** です。

--------------------

デフォルトは **false**。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public abstract boolean getEmbedTrueTypeFontsForASCII()
```

ASCII 文字 32-127 の TrueType フォントを埋め込むには **true** を設定します。文字コード 127 より大きいフォントは常に埋め込まれます。読み取り/書き込み boolean。

--------------------

デフォルトは **true**。

**戻り値:**
boolean

### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public abstract void setEmbedTrueTypeFontsForASCII(boolean value)
```

ASCII 文字 32-127 の TrueType フォントを埋め込むには **true** を設定します。文字コード 127 より大きいフォントは常に埋め込まれます。読み取り/書き込み boolean。

--------------------

デフォルトは **true**。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

生成されたドキュメントに非表示スライドを含めるかどうかを指定します。デフォルトは **false**。

**戻り値:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

生成されたドキュメントに非表示スライドを含めるかどうかを指定します。デフォルトは **false**。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public abstract String[] getAdditionalCommonFontFamilies()
```

Aspose.Slides が共通とみなすフォント ファミリのユーザー定義名の配列を取得または設定します。読み取り/書き込み String[]。

**戻り値:**
java.lang.String[]

### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public abstract void setAdditionalCommonFontFamilies(String[] value)
```

Aspose.Slides が共通とみなすフォント ファミリのユーザー定義名の配列を取得または設定します。読み取り/書き込み String[]。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public abstract boolean getEmbedFullFonts()
```

フォントのすべての文字を埋め込むか、使用したサブセットのみを埋め込むかを決定します。読み取り/書き込み boolean。

--------------------

デフォルトは **false**。

**戻り値:**
boolean

### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public abstract void setEmbedFullFonts(boolean value)
```

フォントのすべての文字を埋め込むか、使用したサブセットのみを埋め込むかを決定します。読み取り/書き込み boolean。

--------------------

デフォルトは **false**。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public abstract boolean getRasterizeUnsupportedFontStyles()
```

フォントが太字スタイルをサポートしていない場合に、テキストをビットマップとしてラスター化し PDF に保存すべきかどうかを示します。このアプローチは特定のフォントで PDF のテキスト品質を向上させることがあります。読み取り/書き込み boolean。

--------------------

デフォルトは **false**。

**戻り値:**
boolean

### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public abstract void setRasterizeUnsupportedFontStyles(boolean value)
```

フォントが太字スタイルをサポートしていない場合に、テキストをビットマップとしてラスター化し PDF に保存すべきかどうかを示します。このアプローチは特定のフォントで PDF のテキスト品質を向上させることがあります。読み取り/書き込み boolean。

--------------------

デフォルトは **false**。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

PDF ドキュメント内の JPEG 画像の品質を決定する値を取得または設定します。読み取り/書き込み byte。

--------------------

ドキュメントに JPEG 画像が含まれている場合にのみ影響します。

このプロパティを使用して、PDF 形式で保存する際の画像品質を設定します。値は 0 から 100 の範囲で、0 は最低品質で最大圧縮、100 は最高品質で最小圧縮を意味します。

デフォルト値は **100**。

**戻り値:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

PDF ドキュメント内の JPEG 画像の品質を決定する値を取得または設定します。読み取り/書き込み byte。

--------------------

ドキュメントに JPEG 画像が含まれている場合にのみ影響します。

このプロパティを使用して、PDF 形式で保存する際の画像品質を設定します。値は 0 から 100 の範囲で、0 は最低品質で最大圧縮、100 は最高品質で最小圧縮を意味します。

デフォルト値は **100**。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public abstract int getCompliance()
```

生成された PDF ドキュメントの目的となる適合レベルを指定します。読み取り/書き込み [PdfCompliance](../../com.aspose.slides/pdfcompliance)。

--------------------

デフォルトは [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17)。

**戻り値:**
int

### setCompliance(int value) {#setCompliance-int-}
```
public abstract void setCompliance(int value)
```

生成された PDF ドキュメントの目的となる適合レベルを指定します。読み取り/書き込み [PdfCompliance](../../com.aspose.slides/pdfcompliance)。

--------------------

デフォルトは [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

PDF ドキュメントを保護するためのユーザーパスワードを設定します。読み取り/書き込み String。

**戻り値:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

PDF ドキュメントを保護するためのユーザーパスワードを設定します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public abstract int getAccessPermissions()
```

ユーザーアクセスでドキュメントを開いたときに付与すべきアクセス権限を指定するフラグのセットを含みます。[PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions) を参照。

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setPassword("my_password");
>  pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>  Presentation presentation = new Presentation();
>  try
>  {
>      presentation.save(pdfFilePath, SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**戻り値:**
int

### setAccessPermissions(int value) {#setAccessPermissions-int-}
```
public abstract void setAccessPermissions(int value)
```

ユーザーアクセスでドキュメントを開いたときに付与すべきアクセス権限を指定するフラグのセットを含みます。[PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions) を参照。

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setPassword("my_password");
>  pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>  Presentation presentation = new Presentation();
>  try
>  {
>      presentation.save(pdfFilePath, SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```

プレゼンテーションで使用されているすべてのメタファイルを PNG 画像に変換するには **true** を設定します。読み取り/書き込み boolean。

--------------------

デフォルトは **true**。Pdf ドキュメントはベクター グラフィックスとラスター画像の両方を含めることができます。SaveMetafilesAsPng が **true** の場合、元の Metafile 画像は PNG 形式に変換され、Pdf にラスター画像として保存されます。**false** の場合、元の Metafile は Pdf ベクター グラフィックスに変換されます。各アプローチには長所と短所があります。たとえば、Metafile を PNG に変換すると、結果のドキュメントの拡大縮小時に品質が低下する可能性があります。Metafile を Pdf ベクター グラフィックスに変換すると、Pdf ビューアーでのパフォーマンス問題が発生する可能性があります。

**戻り値:**
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

プレゼンテーションで使用されているすべてのメタファイルを PNG 画像に変換するには **true** を設定します。読み取り/書き込み boolean。

--------------------

デフォルトは **true**。Pdf ドキュメントはベクター グラフィックスとラスター画像の両方を含めることができます。SaveMetafilesAsPng が **true** の場合、元の Metafile 画像は PNG 形式に変換され、Pdf にラスター画像として保存されます。**false** の場合、元の Metafile は Pdf ベクター グラフィックスに変換されます。各アプローチには長所と短所があります。たとえば、Metafile を PNG に変換すると、結果のドキュメントの拡大縮小時に品質が低下する可能性があります。Metafile を Pdf ベクター グラフィックスに変換すると、Pdf ビューアーでのパフォーマンス問題が発生する可能性があります。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public abstract float getSufficientResolution()
```

PDF ドキュメント内の画像の解像度を決定する値を取得または設定します。読み取り/書き込み float。

値: このパラメーターの効果は複数の要因に依存します。アルゴリズムはプロパティ値、元画像のサイズ、画像フレームのサイズに基づいて最適な出力画像サイズを算出しようとします。類似のプロパティ値を使用すると同じ結果になることがあります。目に見える効果を得るにはステップ 16 または 32 を推奨します。

--------------------

プロパティはファイルサイズ、エクスポート時間、画像品質に影響します。

デフォルト値は **96**。

**戻り値:**
float

### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public abstract void setSufficientResolution(float value)
```

PDF ドキュメント内の画像の解像度を決定する値を取得または設定します。読み取り/書き込み float。

値: このパラメーターの効果は複数の要因に依存します。アルゴリズムはプロパティ値、元画像のサイズ、画像フレームのサイズに基づいて最適な出力画像サイズを算出しようとします。類似のプロパティ値を使用すると同じ結果になることがあります。目に見える効果を得るにはステップ 16 または 32 を推奨します。

--------------------

プロパティはファイルサイズ、エクスポート時間、画像品質に影響します。

デフォルト値は **96**。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

各スライドの周囲に黒い枠線を描画するには **true** を設定します。読み取り/書き込み boolean。

--------------------

デフォルトは **false**。

**戻り値:**
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

各スライドの周囲に黒い枠線を描画するには **true** を設定します。読み取り/書き込み boolean。

--------------------

デフォルトは **false**。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

プレゼンテーションをエクスポートする際にスライドがページ上に配置されるモードを取得または設定します [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

プレゼンテーションをエクスポートする際にスライドがページ上に配置されるモードを取得または設定します [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public abstract Color getImageTransparentColor()
```

画像の透過色を取得または設定します。

値: 画像の透過色。

**戻り値:**
java.awt.Color

### setImageTransparentColor(Color value) {#setImageTransparentColor-java.awt.Color-}
```
public abstract void setImageTransparentColor(Color value)
```

画像の透過色を取得または設定します。

値: 画像の透過色。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.awt.Color |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public abstract boolean getApplyImageTransparent()
```

**true** の場合、指定された透過色を画像に適用します。

**戻り値:**
boolean

### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public abstract void setApplyImageTransparent(boolean value)
```

**true** の場合、指定された透過色を画像に適用します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

エクスポートされたドキュメント内のインク オブジェクトの外観を制御するオプションを提供します。読み取り専用 [IInkOptions](../../com.aspose.slides/iinkoptions)

**戻り値:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getIncludeOleData() {#getIncludeOleData--}
```
public abstract boolean getIncludeOleData()
```

プレゼンテーションからすべての OLE データを変換し、結果の PDF に埋め込みファイルとして保存するには **true** を設定します。読み取り/書き込み boolean。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      options.setIncludeOleData(true);
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

デフォルトは **false** 。

**戻り値:**
boolean

### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public abstract void setIncludeOleData(boolean value)
```

プレゼンテーションからすべての OLE データを変換し、結果の PDF に埋め込みファイルとして保存するには **true** を設定します。読み取り/書き込み boolean。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      options.setIncludeOleData(true);
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

デフォルトは **false** 。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |