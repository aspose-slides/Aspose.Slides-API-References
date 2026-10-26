---
title: IPresentation
second_title: Aspose.Slides for Java API リファレンス
description: プレゼンテーション ドキュメント
type: docs
url: /ja/com.aspose.slides/ipresentation/
---
**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent), com.aspose.ms.System.IDisposable
```
public interface IPresentation extends IPresentationComponent, System.IDisposable
```

Presentation document
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | datetime フィールドの内容を置き換える日付と時刻を取得または設定します。 |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | datetime フィールドの内容を置き換える日付と時刻を取得または設定します。 |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | プレゼンテーションの HeaderFooter マネージャを返します。 |
| [getProtectionManager()](#getProtectionManager--) | このプレゼンテーションの権限マネージャを取得します。 |
| [getSlides()](#getSlides--) | プレゼンテーションで定義されているすべてのスライドのリストを返します。 |
| [getSections()](#getSections--) | プレゼンテーションで定義されているすべてのスライド セクションのリストを返します。 |
| [getSlideSize()](#getSlideSize--) | スライド サイズ オブジェクトを返します。 |
| [getNotesSize()](#getNotesSize--) | ノート スライド サイズ オブジェクトを返します。 |
| [getLayoutSlides()](#getLayoutSlides--) | プレゼンテーションで定義されているすべてのレイアウト スライドのリストを返します。 |
| [getMasters()](#getMasters--) | プレゼンテーションで定義されているすべてのマスター スライドのリストを返します。 |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | ノート マスター マネージャを返します。 |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | 配布資料 マスター マネージャを返します。 |
| [getFontsManager()](#getFontsManager--) | フォント マネージャを返します。 |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | シェイプのデフォルト テキスト スタイルを返します。 |
| [getCommentAuthors()](#getCommentAuthors--) | コメント作成者のコレクションを返します。 |
| [getDocumentProperties()](#getDocumentProperties--) | 標準およびカスタム ドキュメント プロパティを含む DocumentProperties オブジェクトを返します。 |
| [getImages()](#getImages--) | プレゼンテーション内のすべての画像のコレクションを返します。 |
| [getAudios()](#getAudios--) | プレゼンテーション内のすべての埋め込みオーディオ ファイルのコレクションを返します。 |
| [getVideos()](#getVideos--) | プレゼンテーション内のすべての埋め込みビデオ ファイルのコレクションを返します。 |
| [getCustomData()](#getCustomData--) | プレゼンテーションのカスタム データを返します。 |
| [getVbaProject()](#getVbaProject--) | プレゼンテーション マクロを含む VBA プロジェクトを取得します。 |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | プレゼンテーション マクロを含む VBA プロジェクトを取得します。 |
| [getSourceFormat()](#getSourceFormat--) | プレゼンテーションが読み込まれた形式に関する情報を返します。 |
| [getMasterTheme()](#getMasterTheme--) | プレゼンテーションのマスター テーマを返します。 |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | すべてのプレゼンテーション スライドに含まれるすべてのハイパーリンクへの簡単なアクセスを提供します（マスター、レイアウト、ノート スライドは除く）。 |
| [getViewProperties()](#getViewProperties--) | プレゼンテーション全体の表示プロパティを取得します。 |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | プレゼンテーションの最初のスライド番号を表します。 |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | プレゼンテーションの最初のスライド番号を表します。 |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | プレゼンテーション内のすべてのカスタム データ パーツを返します。 |
| [getDigitalSignatures()](#getDigitalSignatures--) | プレゼンテーションに署名するために使用された署名のコレクションを返します。 |
| [getSensitivityLabels()](#getSensitivityLabels--) | プレゼンテーション ドキュメントに適用された感度ラベルのコレクションを返します。 |
| [save(String fname, int format)](#save-java.lang.String-int-) | 指定された形式でプレゼンテーションのすべてのスライドをファイルに保存します。 |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | 指定された形式でプレゼンテーションのすべてのスライドをストリームに保存します。 |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | 指定された形式で、追加オプションを使用してプレゼンテーションのすべてのスライドをファイルに保存します。 |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | 指定された形式で、追加オプションを使用してプレゼンテーションのすべてのスライドをストリームに保存します。 |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | 指定されたスライドを指定された形式でファイルに保存します。 |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | 指定されたスライドを指定された形式でファイルに保存します。 |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | 指定されたスライドを指定された形式でストリームに保存します。 |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | 指定されたスライドを指定された形式でストリームに保存します。 |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | プレゼンテーションのすべてのスライドを XAML マークアップを表すファイルのセットに保存します。 |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | プレゼンテーションのすべてのスライドのサムネイル画像オブジェクトを返します。 |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | 指定されたスライドのサムネイル IImage オブジェクトを返します。 |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | カスタム スケーリングでプレゼンテーションのすべてのスライドのサムネイル画像オブジェクトを返します。 |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | カスタム スケーリングで指定されたスライドのサムネイル画像オブジェクトを返します。 |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | 指定されたサイズでプレゼンテーションのすべてのスライドのサムネイル画像オブジェクトを返します。 |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | 指定されたサイズで指定されたスライドのサムネイル画像オブジェクトを返します。 |
| [getSlideById(long id)](#getSlideById-long-) | ID によって Slide、MasterSlide、または LayoutSlide を返します。 |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | すべてのスライド内のすべての許容可能なシェイプのすべての段落で、同じ書式設定のランを結合します。 |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | サンプルテキストのすべての一致箇所を指定された色でハイライトします。 |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | サンプルテキストのすべての一致箇所を指定された色でハイライトします。 |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | 正規表現のすべての一致箇所を指定された色でハイライトします。 |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | 指定されたテキストのすべての出現箇所を別の指定テキストに置換します。 |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | 正規表現のすべての一致箇所を指定された文字列に置換します。 |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

datetime フィールドの内容を置き換える日付と時刻を取得または設定します。デフォルトではこの Presentation オブジェクトの作成時の時刻です。**読み取り/書き込み可能** java.util.Date。

**戻り値:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

datetime フィールドの内容を置き換える日付と時刻を取得または設定します。デフォルトではこの Presentation オブジェクトの作成時の時刻です。**読み取り/書き込み可能** java.util.Date。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

プレゼンテーションの HeaderFooter マネージャを返します。**読み取り専用** [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)。

**戻り値:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

このプレゼンテーションの権限マネージャを取得します。**読み取り専用** [IProtectionManager](../../com.aspose.slides/iprotectionmanager)。

**戻り値:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

プレゼンテーションで定義されているすべてのスライドのリストを返します。**読み取り専用** [ISlideCollection](../../com.aspose.slides/islidecollection)。

**戻り値:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

プレゼンテーションで定義されているすべてのスライド セクションのリストを返します。**読み取り専用** [ISectionCollection](../../com.aspose.slides/isectioncollection)。

**戻り値:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

スライド サイズ オブジェクトを返します。**読み取り専用** [ISlideSize](../../com.aspose.slides/islidesize)。

**戻り値:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

ノート スライド サイズ オブジェクトを返します。**読み取り専用** [INotesSize](../../com.aspose.slides/inotessize)。

**戻り値:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

プレゼンテーションで定義されているすべてのレイアウト スライドのリストを返します。**読み取り専用** [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)。

--------------------

レイアウト スライドの追加/挿入/削除/クローンの代替 API にアクセスするには、IMasterSlide.LayoutSlides プロパティを使用してください。

**戻り値:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

プレゼンテーションで定義されているすべてのマスター スライドのリストを返します。**読み取り専用** [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)。

**戻り値:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

ノート マスター マネージャを返します。**読み取り専用** [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)。

**戻り値:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

配布資料 マスター マネージャを返します。**読み取り専用** [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)。

**戻り値:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

フォント マネージャを返します。**読み取り専用** [IFontsManager](../../com.aspose.slides/ifontsmanager)。

**戻り値:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

シェイプのデフォルト テキスト スタイルを返します。**読み取り専用** [ITextStyle](../../com.aspose.slides/itextstyle)。

**戻り値:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

コメント作成者のコレクションを返します。**読み取り専用** [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)。

**戻り値:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

標準およびカスタム ドキュメント プロパティを含む DocumentProperties オブジェクトを返します。**読み取り専用** [IDocumentProperties](../../com.aspose.slides/idocumentproperties)。

**戻り値:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

プレゼンテーション内のすべての画像のコレクションを返します。**読み取り専用** [IImageCollection](../../com.aspose.slides/iimagecollection)。

**戻り値:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

プレゼンテーション内のすべての埋め込みオーディオ ファイルのコレクションを返します。**読み取り専用** [IAudioCollection](../../com.aspose.slides/iaudiocollection)。

**戻り値:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

プレゼンテーション内のすべての埋め込みビデオ ファイルのコレクションを返します。**読み取り専用** [IVideoCollection](../../com.aspose.slides/ivideocollection)。

**戻り値:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

プレゼンテーションのカスタム データを返します。**読み取り専用** [ICustomData](../../com.aspose.slides/icustomdata)。

**戻り値:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```

プレゼンテーション マクロを含む VBA プロジェクトを取得します。**読み取り/書き込み可能** [IVbaProject](../../com.aspose.slides/ivbaproject)。

**戻り値:**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

プレゼンテーション マクロを含む VBA プロジェクトを取得します。**読み取り/書き込み可能** [IVbaProject](../../com.aspose.slides/ivbaproject)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

プレゼンテーションが読み込まれた形式に関する情報を返します。**読み取り専用** [SourceFormat](../../com.aspose.slides/sourceformat)。

**戻り値:**
int

### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

プレゼンテーションのマスター テーマを返します。**読み取り専用** [IMasterTheme](../../com.aspose.slides/imastertheme)。

**戻り値:**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

すべてのプレゼンテーション スライドに含まれるすべてのハイパーリンクへの簡単なアクセスを提供します（マスター、レイアウト、ノート スライドは除く）。**読み取り専用** [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)。

**戻り値:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

プレゼンテーション全体の表示プロパティを取得します。**読み取り専用** [IViewProperties](../../com.aspose.slides/iviewproperties)。

**戻り値:**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```

プレゼンテーションの最初のスライド番号を表します。**読み取り/書き込み可能** int。

**戻り値:**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

プレゼンテーションの最初のスライド番号を表します。**読み取り/書き込み可能** int。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

プレゼンテーション内のすべてのカスタム データ パーツを返します。**読み取り専用** ICustomXmlPart[]。

**戻り値:**
com.aspose.slides.ICustomXmlPart[]

### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

プレゼンテーションに署名するために使用された署名のコレクションを返します。**読み取り専用** [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)。

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          for (IDigitalSignature signature : pres.getDigitalSignatures())
>          {
>             System.out.println(signature.getCertificate().hashCode() + ", "
>                    + signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
>             allSignaturesAreValid &= signature.isValid();
>          }
>          if (allSignaturesAreValid)
>             System.out.println("Presentation is genuine, all signatures are valid.");
>          else
>             System.out.println("Presentation has been modified since signing.");
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabelCollection getSensitivityLabels()
```

プレゼンテーション ドキュメントに適用された感度ラベルのコレクションを返します。**読み取り専用** [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)。

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // 適用されたラベルを出力
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // 新しいラベルを追加
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // ポリシーから感度ラベルの ID を取得
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // ポリシーから Azure AD サイト識別子を取得
>      ISensitivityLabel label = sensitivityLabels.add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType.Privileged);
>      label.getContentMarkTypes().addItem(SensitivityLabelContentType.Footer);
> 
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)

### save(String fname, int format) {#save-java.lang.String-int-}
```
public abstract void save(String fname, int format)
```

指定された形式でプレゼンテーションのすべてのスライドをファイルに保存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fname | java.lang.String | 作成されたファイルへのパス。 |
| format | int | エクスポート データの形式。 |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

指定された形式でプレゼンテーションのすべてのスライドをストリームに保存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 出力ストリーム。 |
| format | int | エクスポート データの形式。 |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```

指定された形式で、追加オプションを使用してプレゼンテーションのすべてのスライドをファイルに保存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fname | java.lang.String | 作成されたファイルへのパス。 |
| format | int | エクスポート データの形式。 |
| options | com.aspose.slides.ISaveOptions | 保存オプション。 |
| format | int | エクスポートデータの形式。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 追加のフォーマットオプション。 |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```


プレゼンテーションのすべてのスライドを、指定された形式と追加オプションでストリームに保存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 出力ストリーム。 |
| format | int | エクスポートデータの形式。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 追加のフォーマットオプション。 |

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```


指定されたスライドを、指定された形式でファイルに保存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fname | java.lang.String | 作成されたファイルへのパス。 |
| slides | int[] | スライド位置の配列（1 から開始）。 |
| format | int | エクスポートデータの形式。 |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```


指定されたスライドを、指定された形式でファイルに保存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fname | java.lang.String | 作成されたファイルへのパス。 |
| slides | int[] | スライド位置の配列（1 から開始）。 |
| format | int | エクスポートデータの形式。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 追加のフォーマットオプション。 |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```


指定されたスライドを、指定された形式でストリームに保存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 出力ストリーム。 |
| slides | int[] | スライド位置の配列（1 から開始）。 |
| format | int | エクスポートデータの形式。 |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```


指定されたスライドを、指定された形式でストリームに保存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 出力ストリーム。 |
| slides | int[] | スライド位置の配列（1 から開始）。 |
| format | int | エクスポートデータの形式。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 追加のフォーマットオプション。 |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
```


プレゼンテーションのすべてのスライドを XAML マークアップを表す一連のファイルに保存します。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      XamlOptions xamlOptions = new XamlOptions();
>      xamlOptions.setExportHiddenSlides(true);
> 
>      pres.save(xamlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | XAML フォーマットオプション。 |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage[] getImages(IRenderingOptions options)
```


プレゼンテーションのすべてのスライドのサムネイル画像オブジェクトを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | レンダリングオプション。 |

**戻り値:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```


プレゼンテーションの指定されたスライドのサムネイル IImage オブジェクトを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | レンダリングオプション。 |
| slides | int[] | スライド位置の配列（1 から開始）。 |

**戻り値:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```


カスタムスケーリングでプレゼンテーションのすべてのスライドのサムネイル画像オブジェクトを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | レンダリングオプション。 |
| scaleX | float | X 軸方向にこのサムネイルを拡大縮小する値。 |
| scaleY | float | Y 軸方向にこのサムネイルを拡大縮小する値。 |

**戻り値:**
com.aspose.slides.IImage[] - Bitmap objects.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```


カスタムスケーリングで指定されたスライドのサムネイル画像オブジェクトを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | レンダリングオプション。 |
| slides | int[] | スライド位置の配列（1 から開始）。 |
| scaleX | float | X 軸方向にこのサムネイルを拡大縮小する値。 |
| scaleY | float | Y 軸方向にこのサムネイルを拡大縮小する値。 |

**戻り値:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```


指定されたサイズでプレゼンテーションのすべてのスライドのサムネイル画像オブジェクトを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | レンダリングオプション。 |
| imageSize | java.awt.Dimension | 作成する画像のサイズ。 |

**戻り値:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```


指定されたサイズで指定されたスライドのサムネイル画像オブジェクトを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | レンダリングオプション。 |
| slides | int[] | スライド位置の配列（1 から開始）。 |
| imageSize | java.awt.Dimension | 作成する画像のサイズ。 |

**戻り値:**
com.aspose.slides.IImage[] - IImage objects.

### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```


Id により Slide、MasterSlide、または LayoutSlide を返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| id | long | スライドの Id。 |

**戻り値:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```


すべてのスライドのすべての許容可能なシェイプ内のすべての段落で、同じ書式設定を持つランを結合します。

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public abstract void highlightText(String text, Color highlightColor)
```


指定された色でサンプルテキストのすべての一致箇所をハイライトします。

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // すべての個別の「the」出現箇所をハイライト
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | ハイライトするテキスト。 |
| highlightColor | java.awt.Color | テキストをハイライトする色。 |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```


指定された色でサンプルテキストのすべての一致箇所をハイライトします。

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // すべての個別の「the」出現箇所をハイライト
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | ハイライトするテキスト。 |
| highlightColor | java.awt.Color | テキストをハイライトする色。 |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | テキスト検索オプション [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 検索結果を受け取るコールバックオブジェクト [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```


指定された色で正規表現のすべての一致箇所をハイライトします。

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // すべての個別の「the」出現箇所をハイライト
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| regex | java.util.regex.Pattern | ハイライト対象の文字列を取得する正規表現 java.util.regex.Pattern。 |
| highlightColor | java.awt.Color | テキストをハイライトする色。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 検索結果を受け取るコールバックオブジェクト [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```


指定されたテキストのすべての出現箇所を別の指定テキストに置換します。

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // すべての個別の 'the' 出現箇所を '***' に置換
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| oldText | java.lang.String | 置換される文字列。 |
| newText | java.lang.String | oldText のすべての出現箇所を置換する文字列。 |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | テキスト検索オプション [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 検索結果を受け取るコールバックオブジェクト [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```


正規表現のすべての一致箇所を指定された文字列に置換します。

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // すべての個別の 'the' 出現箇所を '***' に置換
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| regex | java.util.regex.Pattern | 置換対象文字列を取得する正規表現 java.util.regex.Pattern。 |
| newText | java.lang.String | 置換対象の文字列のすべての出現箇所を置換する文字列。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 検索結果を受け取るコールバックオブジェクト [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |