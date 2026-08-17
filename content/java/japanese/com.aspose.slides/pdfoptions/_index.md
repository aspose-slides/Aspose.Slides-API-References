---
title: PdfOptions
second_title: Aspose.Slides for Java API リファレンス
description: プレゼンテーションが Pdf 形式で保存される方法を制御するオプションを提供します。
type: docs
url: /ja/com.aspose.slides/pdfoptions/
---
**継承:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IPdfOptions](../../com.aspose.slides/ipdfoptions)
```
public class PdfOptions extends SaveOptions implements IPdfOptions
```

プレゼンテーションを PDF 形式で保存する方法を制御するオプションを提供します。

--------------------

> ```
> The following example shows how to convert PowerPoint to PDF with custom options.
>  
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // PdfOptions クラスのインスタンスを作成します
>      PdfOptions pdfOptions = new PdfOptions();
>      // Jpeg の品質を設定します
>      pdfOptions.setJpegQuality((byte)90);
>      // メタファイルの動作を設定します
>      pdfOptions.setSaveMetafilesAsPng(true);
>      // テキスト圧縮レベルを設定します
>      pdfOptions.setTextCompression(PdfTextCompression.Flate);
>      // PDF 標準を定義します
>      pdfOptions.setCompliance(PdfCompliance.Pdf15);
>      // プレゼンテーションを PDF として保存します
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with hidden slides.
>  
>  // PowerPoint ファイルを表す Presentation クラスのインスタンスを作成します
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // PdfOptions クラスのインスタンスを作成します
>      PdfOptions pdfOptions = new PdfOptions();
>      // 非表示スライドを追加します
>      pdfOptions.setShowHiddenSlides(true);
>      // プレゼンテーションを PDF として保存します
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to password protected PDF.
>  
>  // PowerPoint ファイルを表す Presentation オブジェクトのインスタンスを作成します
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // PdfOptions クラスのインスタンスを作成します
>      PdfOptions pdfOptions = new PdfOptions();
>      // PDF のパスワードとアクセス権限を設定します
>      pdfOptions.setPassword("password");
>      pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>      // プレゼンテーションを PDF として保存します
>      pres.save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with notes.
>  
>  // プレゼンテーション ファイルを表す Presentation オブジェクトのインスタンスを作成します
>  Presentation pres = new Presentation("SelectedSlides.pptx");
>  try {
>      Presentation auxPres = new Presentation();
>      try {
>          ISlide slide = pres.getSlides().get_Item(0);
>          auxPres.getSlides().insertClone(0, slide);
>          // スライドのタイプとサイズを設定します
>          auxPres.getSlideSize().setSize(612F, 792F, SlideSizeScaleType.EnsureFit);
>          PdfOptions pdfOptions = new PdfOptions();
>          pdfOptions.getNotesCommentsLayouting().setNotesPosition(NotesPositions.BottomFull);
>          auxPres.save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
>      } finally {
>          if (auxPres != null) auxPres.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | デフォルトコンストラクタ。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | プレゼンテーションをエクスポートする際に、スライドがページ上に配置されるモードを取得または設定します [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | プレゼンテーションをエクスポートする際に、スライドがページ上に配置されるモードを取得または設定します [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [getInkOptions()](#getInkOptions--) | エクスポートされたドキュメント内の Ink オブジェクトの外観を制御するオプションを提供します。 |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。 |
| [getTextCompression()](#getTextCompression--) | ドキュメント内のすべてのテキスト コンテンツに使用される圧縮タイプを指定します。 |
| [setTextCompression(int value)](#setTextCompression-int-) | ドキュメント内のすべてのテキスト コンテンツに使用される圧縮タイプを指定します。 |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | 各画像に対して、デフォルトではなく最も効果的な圧縮を自動的に選択するかどうかを示します。 |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | 各画像に対して、デフォルトではなく最も効果的な圧縮を自動的に選択するかどうかを示します。 |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | Aspose.Slides が ASCII (33..127 のコード範囲) テキスト用に共通フォントを埋め込むかどうかを決定します。 |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | Aspose.Slides が ASCII (33..127 のコード範囲) テキスト用に共通フォントを埋め込むかどうかを決定します。 |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Aspose.Slides が共通と見なすフォント ファミリーのユーザー定義名の配列を取得または設定します。 |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Aspose.Slides が共通と見なすフォント ファミリーのユーザー定義名の配列を取得または設定します。 |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | フォントのすべての文字を埋め込むか、使用するサブセットだけを埋め込むかを決定します。 |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | フォントのすべての文字を埋め込むか、使用するサブセットだけを埋め込むかを決定します。 |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | フォントが太字スタイルをサポートしない場合に、テキストをビットマップとしてラスタライズし、PDF に保存すべきかどうかを示します。 |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | フォントが太字スタイルをサポートしない場合に、テキストをビットマップとしてラスタライズし、PDF に保存すべきかどうかを示します。 |
| [getJpegQuality()](#getJpegQuality--) | PDF ドキュメント内の JPEG 画像の品質を決定する値を取得または設定します。 |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | PDF ドキュメント内の JPEG 画像の品質を決定する値を取得または設定します。 |
| [getCompliance()](#getCompliance--) | 生成された PDF ドキュメントの希望する準拠レベルです。 |
| [setCompliance(int value)](#setCompliance-int-) | 生成された PDF ドキュメントの希望する準拠レベルです。 |
| [getPassword()](#getPassword--) | PDF ドキュメントを保護するユーザーパスワードを設定します。 |
| [setPassword(String value)](#setPassword-java.lang.String-) | PDF ドキュメントを保護するユーザーパスワードを設定します。 |
| [getAccessPermissions()](#getAccessPermissions--) | ドキュメントがユーザーアクセスで開かれたときに付与すべきアクセス権限を指定するフラグのセットを含みます。 |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | ドキュメントがユーザーアクセスで開かれたときに付与すべきアクセス権限を指定するフラグのセットを含みます。 |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | プレゼンテーションで使用されるすべてのメタファイルを PNG 画像に変換する場合は true を指定します。 |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | プレゼンテーションで使用されるすべてのメタファイルを PNG 画像に変換する場合は true を指定します。 |
| [getSufficientResolution()](#getSufficientResolution--) | PDF ドキュメント内の画像の解像度を決定する値を取得または設定します。 |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | PDF ドキュメント内の画像の解像度を決定する値を取得または設定します。 |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | 各スライドの周囲に黒い枠線を描画する場合は true を指定します。 |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | 各スライドの周囲に黒い枠線を描画する場合は true を指定します。 |
| [getImageTransparentColor()](#getImageTransparentColor--) | 画像の透過色を取得または設定します。 |
| [setImageTransparentColor(Color value)](#setImageTransparentColor-java.awt.Color-) | 画像の透過色を取得または設定します。 |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | true の場合、指定された透過色を画像に適用します。 |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | true の場合、指定された透過色を画像に適用します。 |
| [getIncludeOleData()](#getIncludeOleData--) | プレゼンテーションからすべての OLE データを変換し、生成された PDF に埋め込みファイルとして含める場合は true を指定します。 |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | プレゼンテーションからすべての OLE データを変換し、生成された PDF に埋め込みファイルとして含める場合は true を指定します。 |

### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```

デフォルトコンストラクタ。

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

プレゼンテーションをエクスポートする際に、スライドがページ上に配置されるモードを取得または設定します [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。

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
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

プレゼンテーションをエクスポートする際に、スライドがページ上に配置されるモードを取得または設定します [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。

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

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

エクスポートされたドキュメント内の Ink オブジェクトの外観を制御するオプションを提供します。読み取り専用 [IInkOptions](../../com.aspose.slides/iinkoptions)

**戻り値:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

生成されたドキュメントに非表示スライドを含めるかどうかを指定します。デフォルトは false です。

**戻り値:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

生成されたドキュメントに非表示スライドを含めるかどうかを指定します。デフォルトは false です。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getTextCompression() {#getTextCompression--}
```
public final int getTextCompression()
```

ドキュメント内のすべてのテキスト コンテンツに使用される圧縮タイプを指定します。読み書き [PdfTextCompression](../../com.aspose.slides/pdftextcompression)。

--------------------

デフォルトは [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate)。

**戻り値:**
int
### setTextCompression(int value) {#setTextCompression-int-}
```
public final void setTextCompression(int value)
```

ドキュメント内のすべてのテキスト コンテンツに使用される圧縮タイプを指定します。読み書き [PdfTextCompression](../../com.aspose.slides/pdftextcompression)。

--------------------

デフォルトは [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public final boolean getBestImagesCompressionRatio()
```

各画像に対して、デフォルトではなく最も効果的な圧縮を自動的に選択するかどうかを示します。true に設定すると、プレゼンテーション内のすべての画像について最適な圧縮アルゴリズムが選択され、結果として生成される PDF ドキュメントのサイズが小さくなります。

--------------------

最適な画像圧縮率の選択は計算コストが高く、追加の RAM を使用し、このオプションのデフォルトは false です。

--------------------

デフォルトは false。

**戻り値:**
boolean
### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public final void setBestImagesCompressionRatio(boolean value)
```

各画像に対して、デフォルトではなく最も効果的な圧縮を自動的に選択するかどうかを示します。true に設定すると、プレゼンテーション内のすべての画像について最適な圧縮アルゴリズムが選択され、結果として生成される PDF ドキュメントのサイズが小さくなります。

--------------------

最適な画像圧縮率の選択は計算コストが高く、追加の RAM を使用し、このオプションのデフォルトは false です。

--------------------

デフォルトは false。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public final boolean getEmbedTrueTypeFontsForASCII()
```

Aspose.Slides が ASCII (33..127 のコード範囲) テキスト用に共通フォントを埋め込むかどうかを決定します。文字コード 127 超のフォントは常に埋め込まれます。共通フォント一覧には PDF の基本 14 フォントと追加のユーザー指定フォントが含まれます。読み書き boolean。

--------------------

デフォルトは **true**。

**戻り値:**
boolean
### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public final void setEmbedTrueTypeFontsForASCII(boolean value)
```

Aspose.Slides が ASCII (33..127 のコード範囲) テキスト用に共通フォントを埋め込むかどうかを決定します。文字コード 127 超のフォントは常に埋め込まれます。共通フォント一覧には PDF の基本 14 フォントと追加のユーザー指定フォントが含まれます。読み書き boolean。

--------------------

デフォルトは **true**。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public final String[] getAdditionalCommonFontFamilies()
```

Aspose.Slides が共通と見なすフォント ファミリーのユーザー定義名の配列を取得または設定します。読み書き String[]。

**戻り値:**
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public final void setAdditionalCommonFontFamilies(String[] value)
```

Aspose.Slides が共通と見なすフォント ファミリーのユーザー定義名の配列を取得または設定します。読み書き String[]。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public final boolean getEmbedFullFonts()
```

フォントのすべての文字を埋め込むか、使用するサブセットだけを埋め込むかを決定します。読み書き boolean。

--------------------

デフォルトは **false**。

**戻り値:**
boolean
### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public final void setEmbedFullFonts(boolean value)
```

フォントのすべての文字を埋め込むか、使用するサブセットだけを埋め込むかを決定します。読み書き boolean。

--------------------

デフォルトは **false**。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public final boolean getRasterizeUnsupportedFontStyles()
```

フォントが太字スタイルをサポートしない場合に、テキストをビットマップとしてラスタライズし、PDF に保存すべきかどうかを示します。このアプローチは特定のフォントに対して、生成された PDF のテキスト品質を向上させることができます。読み書き boolean。

--------------------

デフォルトは **false**。

**戻り値:**
boolean
### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public final void setRasterizeUnsupportedFontStyles(boolean value)
```

フォントが太字スタイルをサポートしない場合に、テキストをビットマップとしてラスタライズし、PDF に保存すべきかどうかを示します。このアプローチは特定のフォントに対して、生成された PDF のテキスト品質を向上させることができます。読み書き boolean。

--------------------

デフォルトは **false**。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

PDF ドキュメント内の JPEG 画像の品質を決定する値を取得または設定します。読み書き byte。

--------------------

ドキュメントに JPEG 画像が含まれる場合にのみ効果があります。

このプロパティは、PDF 形式で保存する際にドキュメント内の画像の品質を取得または設定するために使用します。値は 0 から 100 の範囲で、0 は最低品質で最大圧縮、100 は最高品質で最小圧縮を意味します。

デフォルト値は **100** です。

**戻り値:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

PDF ドキュメント内の JPEG 画像の品質を決定する値を取得または設定します。読み書き byte。

--------------------

ドキュメントに JPEG 画像が含まれる場合にのみ効果があります。

このプロパティは、PDF 形式で保存する際にドキュメント内の画像の品質を取得または設定するために使用します。値は 0 から 100 の範囲で、0 は最低品質で最大圧縮、100 は最高品質で最小圧縮を意味します。

デフォルト値は **100** です。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```

生成された PDF ドキュメントの希望する準拠レベルです。読み書き [PdfCompliance](../../com.aspose.slides/pdfcompliance)。

--------------------

デフォルトは [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17)。

**戻り値:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```

生成された PDF ドキュメントの希望する準拠レベルです。読み書き [PdfCompliance](../../com.aspose.slides/pdfcompliance)。

--------------------

デフォルトは [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

PDF ドキュメントを保護するためのユーザーパスワードを設定します。読み書き String。

**戻り値:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

PDF ドキュメントを保護するためのユーザーパスワードを設定します。読み書き String。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public final int getAccessPermissions()
```

ドキュメントがユーザーアクセスで開かれたときに付与すべきアクセス権限を指定するフラグのセットを含みます。[PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions) を参照してください。

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
public final void setAccessPermissions(int value)
```

ドキュメントがユーザーアクセスで開かれたときに付与すべきアクセス権限を指定するフラグのセットを含みます。[PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions) を参照してください。

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


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

プレゼンテーションで使用されるすべてのメタファイルを PNG 画像に変換する場合は true を指定します。読み書き boolean。

--------------------

デフォルトは **true**。PDF ドキュメントはベクター グラフィックとラスタ画像の両方を含むことができます。SaveMetafilesAsPng が true に設定されている場合、元のメタファイル画像は PNG 形式に変換され、PDF にラスタ画像として保存されます。SaveMetafilesAsPng が false に設定されている場合、元のメタファイルは PDF ベクター グラフィックに変換されます。各アプローチには利点と欠点があります。たとえば、メタファイルを PNG に変換すると、生成されたドキュメントのスケーリング時に品質低下が起こる可能性があります。メタファイルを PDF ベクター グラフィックに変換すると、PDF ビューアのパフォーマンスに問題が生じる可能性があります。

**戻り値:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

プレゼンテーションで使用されるすべてのメタファイルを PNG 画像に変換する場合は true を指定します。読み書き boolean。

--------------------

デフォルトは **true**。PDF ドキュメントはベクター グラフィックとラスタ画像の両方を含むことができます。SaveMetafilesAsPng が true に設定されている場合、元のメタファイル画像は PNG 形式に変換され、PDF にラスタ画像として保存されます。SaveMetafilesAsPng が false に設定されている場合、元のメタファイルは PDF ベクター グラフィックに変換されます。各アプローチには利点と欠点があります。たとえば、メタファイルを PNG に変換すると、生成されたドキュメントのスケーリング時に品質低下が起こる可能性があります。メタファイルを PDF ベクター グラフィックに変換すると、PDF ビューアのパフォーマンスに問題が生じる可能性があります。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public final float getSufficientResolution()
```

PDF ドキュメント内の画像の解像度を決定する値を取得または設定します。読み書き float。

値: このパラメータの効果は複数の要因に依存します。アルゴリズムはプロパティ値、元画像サイズ、画像フレームサイズに基づいて最適な出力画像サイズを取得しようとします。類似のプロパティ値を使用すると同じ結果になることがあります。目に見える効果を得るためにステップ 16 または 32 の使用を推奨します。

--------------------

このプロパティはファイルサイズ、エクスポート時間、画像品質に影響します。

デフォルト値は **96** です。

**戻り値:**
float
### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public final void setSufficientResolution(float value)
```

PDF ドキュメント内の画像の解像度を決定する値を取得または設定します。読み書き float。

値: このパラメータの効果は複数の要因に依存します。アルゴリズムはプロパティ値、元画像サイズ、画像フレームサイズに基づいて最適な出力画像サイズを取得しようとします。類似のプロパティ値を使用すると同じ結果になることがあります。目に見える効果を得るためにステップ 16 または 32 の使用を推奨します。

--------------------

このプロパティはファイルサイズ、エクスポート時間、画像品質に影響します。

デフォルト値は **96** です。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

各スライドの周囲に黒いフレームを描画する場合は true を指定します。読み書き boolean。

--------------------

デフォルトは **false**。

**戻り値:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

各スライドの周囲に黒いフレームを描画する場合は true を指定します。読み書き boolean。

--------------------

デフォルトは **false**。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public final Color getImageTransparentColor()
```

画像の透過色を取得または設定します。

値: 画像の透明色です。

**戻り値:**
java.awt.Color
### setImageTransparentColor(Color value) {#setImageTransparentColor-java.awt.Color-}
```
public final void setImageTransparentColor(Color value)
```

画像の透過色を取得または設定します。

値: 画像の透明色です。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.awt.Color |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public final boolean getApplyImageTransparent()
```

true の場合、指定された透過色を画像に適用します。

**戻り値:**
boolean
### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public final void setApplyImageTransparent(boolean value)
```

true の場合、指定された透過色を画像に適用します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getIncludeOleData() {#getIncludeOleData--}
```
public final boolean getIncludeOleData()
```

プレゼンテーションからすべての OLE データを変換し、生成された PDF に埋め込みファイルとして含める場合は true を指定します。読み書き boolean。

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

デフォルトは **false** です。

**戻り値:**
boolean
### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public final void setIncludeOleData(boolean value)
```

プレゼンテーションからすべての OLE データを変換し、生成された PDF に埋め込みファイルとして含める場合は true を指定します。読み書き boolean。

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

デフォルトは **false** です。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |