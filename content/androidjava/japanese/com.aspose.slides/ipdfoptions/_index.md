---
title: IPdfOptions
second_title: Java API リファレンスによる Android 用 Aspose.Slides
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
| [getTextCompression()](#getTextCompression--) | ドキュメント内のすべてのテキストコンテンツに使用される圧縮タイプを指定します。 |
| [setTextCompression(int value)](#setTextCompression-int-) | ドキュメント内のすべてのテキストコンテンツに使用される圧縮タイプを指定します。 |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | 各画像に対してデフォルトではなく最も効果的な圧縮を自動的に選択するかどうかを示します。 |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | 各画像に対してデフォルトではなく最も効果的な圧縮を自動的に選択するかどうかを示します。 |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | ASCII 文字 32-127 用に TrueType フォントを埋め込む場合は true を指定します。 |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | ASCII 文字 32-127 用に TrueType フォントを埋め込む場合は true を指定します。 |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。 |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Aspose.Slides が共通とみなすフォントファミリのユーザー定義名の配列を取得または設定します。 |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Aspose.Slides が共通とみなすフォントファミリのユーザー定義名の配列を取得または設定します。 |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | フォントのすべての文字を埋め込むか、使用されたサブセットのみを埋め込むかを決定します。 |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | フォントのすべての文字を埋め込むか、使用されたサブセットのみを埋め込むかを決定します。 |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | フォントが太字スタイルをサポートしない場合に、テキストをビットマップとしてラスタライズし PDF に保存するかどうかを示します。 |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | フォントが太字スタイルをサポートしない場合に、テキストをビットマップとしてラスタライズし PDF に保存するかどうかを示します。 |
| [getJpegQuality()](#getJpegQuality--) | PDF ドキュメント内の JPEG 画像の品質を決定する値を取得または設定します。 |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | PDF ドキュメント内の JPEG 画像の品質を決定する値を取得または設定します。 |
| [getCompliance()](#getCompliance--) | 生成された PDF ドキュメントの希望する適合レベル。 |
| [setCompliance(int value)](#setCompliance-int-) | 生成された PDF ドキュメントの希望する適合レベル。 |
| [getPassword()](#getPassword--) | PDF ドキュメントを保護するためのユーザーパスワードを設定します。 |
| [setPassword(String value)](#setPassword-java.lang.String-) | PDF ドキュメントを保護するためのユーザーパスワードを設定します。 |
| [getAccessPermissions()](#getAccessPermissions--) | ユーザーアクセスでドキュメントを開く際に付与されるアクセス許可を指定するフラグのセットを含みます。 |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | ユーザーアクセスでドキュメントを開く際に付与されるアクセス許可を指定するフラグのセットを含みます。 |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | プレゼンテーションで使用されるすべてのメタファイルを PNG 画像に変換する場合は true を指定します。 |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | プレゼンテーションで使用されるすべてのメタファイルを PNG 画像に変換する場合は true を指定します。 |
| [getSufficientResolution()](#getSufficientResolution--) | PDF ドキュメント内の画像の解像度を決定する値を取得または設定します。 |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | PDF ドキュメント内の画像の解像度を決定する値を取得または設定します。 |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | 各スライドの周囲に黒いフレームを描画する場合は true を指定します。 |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | 各スライドの周囲に黒いフレームを描画する場合は true を指定します。 |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | プレゼンテーションをエクスポートする際にスライドがページ上に配置されるモードを取得または設定します [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | プレゼンテーションをエクスポートする際にスライドがページ上に配置されるモードを取得または設定します [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [getImageTransparentColor()](#getImageTransparentColor--) | 画像の透過色を取得または設定します。 |
| [setImageTransparentColor(Integer value)](#setImageTransparentColor-java.lang.Integer-) | 画像の透過色を取得または設定します。 |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | true の場合、指定された透過色を画像に適用します。 |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | true の場合、指定された透過色を画像に適用します。 |
| [getInkOptions()](#getInkOptions--) | エクスポートされたドキュメント内のインクオブジェクトの外観を制御するオプションを提供します。 |
| [getIncludeOleData()](#getIncludeOleData--) | プレゼンテーションからすべての OLE データを変換し、結果の PDF に埋め込まれたファイルとして保存する場合は true を指定します。 |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | プレゼンテーションからすべての OLE データを変換し、結果の PDF に埋め込まれたファイルとして保存する場合は true を指定します。 |
### getTextCompression() {#getTextCompression--}
```
public abstract int getTextCompression()
```


ドキュメント内のすべてのテキストコンテンツに使用される圧縮タイプを指定します。 読み取り/書き込み [PdfTextCompression](../../com.aspose.slides/pdftextcompression)。

--------------------

既定は [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate)。

**戻り値:**
int
### setTextCompression(int value) {#setTextCompression-int-}
```
public abstract void setTextCompression(int value)
```


ドキュメント内のすべてのテキストコンテンツに使用される圧縮タイプを指定します。 読み取り/書き込み [PdfTextCompression](../../com.aspose.slides/pdftextcompression)。

--------------------

既定は [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public abstract boolean getBestImagesCompressionRatio()
```


各画像に対してデフォルトではなく最も効果的な圧縮を自動的に選択するかどうかを示します。 true に設定すると、プレゼンテーション内の各画像に最適な圧縮アルゴリズムが選択され、結果の PDF ドキュメントのサイズが小さくなります。

--------------------

最適な画像圧縮率の選択は計算コストが高く、余分な RAM が必要となり、このオプションはデフォルトで false です。

--------------------

既定は false。

**戻り値:**
boolean
### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public abstract void setBestImagesCompressionRatio(boolean value)
```


各画像に対してデフォルトではなく最も効果的な圧縮を自動的に選択するかどうかを示します。 true に設定すると、プレゼンテーション内の各画像に最適な圧縮アルゴリズムが選択され、結果の PDF ドキュメントのサイズが小さくなります。

--------------------

最適な画像圧縮率の選択は計算コストが高く、余分な RAM が必要となり、このオプションはデフォルトで false です。

--------------------

既定は false。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public abstract boolean getEmbedTrueTypeFontsForASCII()
```


ASCII 文字 32-127 用に TrueType フォントを埋め込む場合は true を指定します。 127 より大きい文字コードのフォントは常に埋め込まれます。 読み取り/書き込み boolean。

--------------------

既定は **true**。

**戻り値:**
boolean
### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public abstract void setEmbedTrueTypeFontsForASCII(boolean value)
```


ASCII 文字 32-127 用に TrueType フォントを埋め込む場合は true を指定します。 127 より大きい文字コードのフォントは常に埋め込まれます。 読み取り/書き込み boolean。

--------------------

既定は **true**。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```


生成されたドキュメントに非表示スライドを含めるかどうかを指定します。 既定は false。

**戻り値:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```


生成されたドキュメントに非表示スライドを含めるかどうかを指定します。 既定は false。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public abstract String[] getAdditionalCommonFontFamilies()
```


Aspose.Slides が共通とみなすフォントファミリのユーザー定義名の配列を取得または設定します。 読み取り/書き込み String[]。

**戻り値:**
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public abstract void setAdditionalCommonFontFamilies(String[] value)
```


Aspose.Slides が共通とみなすフォントファミリのユーザー定義名の配列を取得または設定します。 読み取り/書き込み String[]。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public abstract boolean getEmbedFullFonts()
```


フォントのすべての文字を埋め込むか、使用されたサブセットのみを埋め込むかを決定します。 読み取り/書き込み boolean。

--------------------

既定は **false**。

**戻り値:**
boolean
### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public abstract void setEmbedFullFonts(boolean value)
```


フォントのすべての文字を埋め込むか、使用されたサブセットのみを埋め込むかを決定します。 読み取り/書き込み boolean。

--------------------

既定は **false**。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public abstract boolean getRasterizeUnsupportedFontStyles()
```


フォントが太字スタイルをサポートしない場合に、テキストをビットマップとしてラスタライズし PDF に保存するかどうかを示します。 このアプローチは特定のフォントでテキストの品質を向上させることがあります。 読み取り/書き込み boolean。

--------------------

既定は **false**。

**戻り値:**
boolean
### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public abstract void setRasterizeUnsupportedFontStyles(boolean value)
```


フォントが太字スタイルをサポートしない場合に、テキストをビットマップとしてラスタライズし PDF に保存するかどうかを示します。 このアプローチは特定のフォントでテキストの品質を向上させることがあります。 読み取り/書き込み boolean。

--------------------

既定は **false**。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```


PDF ドキュメント内の JPEG 画像の品質を決定する値を取得または設定します。 読み取り/書き込み byte。

--------------------

ドキュメントに JPEG 画像が含まれている場合にのみ効果があります。

PDF 形式で保存する際に、ドキュメント内の画像の品質を取得または設定するためにこのプロパティを使用します。 値は 0 から 100 の範囲で、0 は最低品質で最大圧縮、100 は最高品質で最小圧縮を意味します。

既定値は **100**。

**戻り値:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```


PDF ドキュメント内の JPEG 画像の品質を決定する値を取得または設定します。 読み取り/書き込み byte。

--------------------

ドキュメントに JPEG 画像が含まれている場合にのみ効果があります。

PDF 形式で保存する際に、ドキュメント内の画像の品質を取得または設定するためにこのプロパティを使用します。 値は 0 から 100 の範囲で、0 は最低品質で最大圧縮、100 は最高品質で最小圧縮を意味します。

既定値は **100**。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public abstract int getCompliance()
```


生成された PDF ドキュメントの希望する適合レベル。 読み取り/書き込み [PdfCompliance](../../com.aspose.slides/pdfcompliance)。

--------------------

既定は [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17)。

**戻り値:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public abstract void setCompliance(int value)
```


生成された PDF ドキュメントの希望する適合レベル。 読み取り/書き込み [PdfCompliance](../../com.aspose.slides/pdfcompliance)。

--------------------

既定は [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```


PDF ドキュメントを保護するためのユーザーパスワードを設定します。 読み取り/書き込み String。

**戻り値:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```


PDF ドキュメントを保護するためのユーザーパスワードを設定します。 読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public abstract int getAccessPermissions()
```


ユーザーアクセスでドキュメントを開く際に付与されるアクセス許可を指定するフラグのセットを含みます。 [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions) を参照してください。

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


ユーザーアクセスでドキュメントを開く際に付与されるアクセス許可を指定するフラグのセットを含みます。 [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions) を参照してください。

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


プレゼンテーションで使用されるすべてのメタファイルを PNG 画像に変換する場合は true を指定します。 読み取り/書き込み boolean。

--------------------

既定は **true**。 Pdf ドキュメントはベクター グラフィックとラスタ画像の両方を含むことができます。 SaveMetafilesAsPng が true の場合、元のメタファイル画像は PNG 形式に変換され、ラスタ画像として Pdf に保存されます。 SaveMetafilesAsPng が false の場合、元のメタファイルは Pdf のベクター グラフィックに変換されます。各アプローチには利点と欠点があります。たとえば、メタファイルを PNG に変換すると、結果のドキュメントの拡大縮小時に品質が失われる可能性があります。メタファイルを Pdf のベクター グラフィックに変換すると、Pdf ビューアでのパフォーマンスに問題が生じる可能性があります。

**戻り値:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```


プレゼンテーションで使用されるすべてのメタファイルを PNG 画像に変換する場合は true を指定します。 読み取り/書き込み boolean。

--------------------

既定は **true**。 Pdf ドキュメントはベクター グラフィックとラスタ画像の両方を含むことができます。 SaveMetafilesAsPng が true の場合、元のメタファイル画像は PNG 形式に変換され、ラスタ画像として Pdf に保存されます。 SaveMetafilesAsPng が false の場合、元のメタファイルは Pdf のベクター グラフィックに変換されます。各アプローチには利点と欠点があります。たとえば、メタファイルを PNG に変換すると、結果のドキュメントの拡大縮小時に品質が失われる可能性があります。メタファイルを Pdf のベクター グラフィックに変換すると、Pdf ビューアでのパフォーマンスに問題が生じる可能性があります。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public abstract float getSufficientResolution()
```


PDF ドキュメント内の画像の解像度を決定する値を取得または設定します。 読み取り/書き込み float。

値: このパラメーターの効果は複数の要因に依存します。アルゴリズムはプロパティ値、元画像サイズ、画像フレームサイズに基づいて最適な出力画像サイズを取得しようとします。類似のプロパティ値を使用すると同じ結果になることがあります。可視効果を得るためにステップ 16 または 32 の使用が推奨されます。

--------------------

プロパティはファイルサイズ、エクスポート時間、画像品質に影響します。

既定値は **96**。

**戻り値:**
float
### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public abstract void setSufficientResolution(float value)
```


PDF ドキュメント内の画像の解像度を決定する値を取得または設定します。 読み取り/書き込み float。

値: このパラメーターの効果は複数の要因に依存します。アルゴリズムはプロパティ値、元画像サイズ、画像フレームサイズに基づいて最適な出力画像サイズを取得しようとします。類似のプロパティ値を使用すると同じ結果になることがあります。可視効果を得るためにステップ 16 または 32 の使用が推奨されます。

--------------------

プロパティはファイルサイズ、エクスポート時間、画像品質に影響します。

既定値は **96**。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```


各スライドの周囲に黒いフレームを描画する場合は true を指定します。 読み取り/書き込み boolean。

--------------------

既定は **false**。

**戻り値:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```


各スライドの周囲に黒いフレームを描画する場合は true を指定します。 読み取り/書き込み boolean。

--------------------

既定は **false**。

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
public abstract Integer getImageTransparentColor()
```


画像の透過色を取得または設定します。

値: 画像の透過色です。

**戻り値:**
java.lang.Integer
### setImageTransparentColor(Integer value) {#setImageTransparentColor-java.lang.Integer-}
```
public abstract void setImageTransparentColor(Integer value)
```


画像の透過色を取得または設定します。

値: 画像の透過色です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public abstract boolean getApplyImageTransparent()
```


true の場合、指定された透過色を画像に適用します。

**戻り値:**
boolean
### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public abstract void setApplyImageTransparent(boolean value)
```


true の場合、指定された透過色を画像に適用します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```


エクスポートされたドキュメント内のインクオブジェクトの外観を制御するオプションを提供します。 読み取り専用 [IInkOptions](../../com.aspose.slides/iinkoptions)

**戻り値:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getIncludeOleData() {#getIncludeOleData--}
```
public abstract boolean getIncludeOle

```


プレゼンテーションからすべての OLE データを変換し、結果の PDF に埋め込まれたファイルとして保存する場合は true を指定します。 読み取り/書き込み  boolean 。

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

既定は  **false** 。

**戻り値:**
boolean
### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public abstract void setIncludeOleData(boolean value)
```


プレゼンテーションからすべての OLE データを変換し、結果の PDF に埋め込まれたファイルとして保存する場合は true を指定します。 読み取り/書き込み  boolean 。

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

既定は  **false** 。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |