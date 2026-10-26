---
title: Presentation
second_title: Java API リファレンスを使用した Android 用 Aspose.Slides
description: Microsoft PowerPoint のプレゼンテーションを表します。
type: docs
url: /ja/com.aspose.slides/presentation/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IPresentation](../../com.aspose.slides/ipresentation), com.aspose.slides.IDOMObject
```
public final class Presentation implements IPresentation, IDOMObject
```

Microsoft PowerPoint プレゼンテーションを表します。

--------------------

> ```
> The following example shows how to create PowerPoint Presentation.
>   
>  // プレゼンテーションファイルを表す Presentation オブジェクトを作成します
>  Presentation pres = new Presentation();
>  try {
>      // 最初のスライドを取得
>      ISlide slide = pres.getSlides().get_Item(0);
>      // ラインタイプのオートシェイプを追加
>      slide.getShapes().addAutoShape(ShapeType.Line, 50, 150, 300, 0);
>      // プレゼンテーションファイルを保存
>      pres.save("NewPresentation_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>   
>   The following example shows how to open and save Presentation.
>   
>  // ppt、pptx、odp など、Presentation がサポートする任意のファイルをロード
>  Presentation pres = new Presentation("Sample.odp");
>  try {
>      // プレゼンテーションファイルを保存
>      pres.save("OutputPresenation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Presentation()](#Presentation--) | This constructor creates new presentation from scratch. |
| [Presentation(LoadOptions loadOptions)](#Presentation-com.aspose.slides.LoadOptions-) | This constructor creates new presentation from scratch. |
| [Presentation(InputStream stream)](#Presentation-java.io.InputStream-) | This constructor is the primary mechanism for reading an existing Presentation. |
| [Presentation(InputStream stream, LoadOptions loadOptions)](#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-) | This constructor is the primary mechanism for reading an existing Presentation. |
| [Presentation(String file)](#Presentation-java.lang.String-) | This constructor gets a source file path from which the contents of the Presentation are read. |
| [Presentation(String file, LoadOptions loadOptions)](#Presentation-java.lang.String-com.aspose.slides.LoadOptions-) | This constructor gets a source file path from which the contents of the Presentation are read. |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | 日時フィールドの内容を置き換える日付と時刻を取得または設定します。 |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | 日時フィールドの内容を置き換える日付と時刻を取得または設定します。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 実際の HeaderFooter マネージャーを返します。 |
| [getProtectionManager()](#getProtectionManager--) | このプレゼンテーションの権限マネージャーを取得します。 |
| [getSlides()](#getSlides--) | プレゼンテーションで定義されているすべてのスライドのリストを返します。 |
| [getSections()](#getSections--) | プレゼンテーションで定義されているすべてのスライドセクションのリストを返します。 |
| [getSlideSize()](#getSlideSize--) | スライドサイズオブジェクトを返します。 |
| [getNotesSize()](#getNotesSize--) | ノートスライドサイズオブジェクトを返します。 |
| [getLayoutSlides()](#getLayoutSlides--) | プレゼンテーションで定義されているすべてのレイアウトスライドのリストを返します。 |
| [getMasters()](#getMasters--) | プレゼンテーションで定義されているすべてのマスタースライドのリストを返します。 |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | ノートマスターマネージャーを返します。 |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | 配布資料マスターマネージャーを返します。 |
| [getFontsManager()](#getFontsManager--) | フォントマネージャーを返します。 |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | シェイプのデフォルトテキストスタイルを返します。 |
| [getCommentAuthors()](#getCommentAuthors--) | コメント作成者のコレクションを返します。 |
| [getDocumentProperties()](#getDocumentProperties--) | 標準およびカスタムのドキュメントプロパティを含む DocumentProperties オブジェクトを返します。 |
| [getImages()](#getImages--) | プレゼンテーション内のすべての画像のコレクションを返します。 |
| [getAudios()](#getAudios--) | プレゼンテーション内に埋め込まれたすべてのオーディオファイルのコレクションを返します。 |
| [getVideos()](#getVideos--) | プレゼンテーション内に埋め込まれたすべてのビデオファイルのコレクションを返します。 |
| [getSlideShowSettings()](#getSlideShowSettings--) | プレゼンテーションのスライドショー設定を返します。 |
| [getDigitalSignatures()](#getDigitalSignatures--) | プレゼンテーションに署名するために使用される署名のコレクションを返します。 |
| [getCustomData()](#getCustomData--) | プレゼンテーションのカスタムデータを返します。 |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | プレゼンテーション内のすべてのカスタムデータパーツを返します。 |
| [getVbaProject()](#getVbaProject--) | プレゼンテーションのマクロを含む VBA プロジェクトを取得または設定します。 |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | プレゼンテーションのマクロを含む VBA プロジェクトを取得または設定します。 |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | すべてのプレゼンテーションスライドに含まれるすべてのハイパーリンクへ簡単にアクセスできるようにします（マスター、レイアウト、ノートスライドは除く）。 |
| [getViewProperties()](#getViewProperties--) | プレゼンテーション全体のビュー プロパティを取得します。 |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | プレゼンテーションの最初のスライド番号を表します |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | プレゼンテーションの最初のスライド番号を表します |
| [getSensitivityLabels()](#getSensitivityLabels--) | プレゼンテーションドキュメントに適用された感度ラベルのコレクションを返します。 |
| [getSlideById(long id)](#getSlideById-long-) | ID により Slide、MasterSlide、または LayoutSlide を返します。 |
| [getSourceFormat()](#getSourceFormat--) | プレゼンテーションが読み込まれた形式に関する情報を返します。 |
| [getMasterTheme()](#getMasterTheme--) | マスターテーマを返します。 |
| [save(String fname, int format)](#save-java.lang.String-int-) | 指定された形式でプレゼンテーションのすべてのスライドをファイルに保存します。 |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | 指定された形式でプレゼンテーションのすべてのスライドをストリームに保存します。 |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | 指定された形式および追加オプションでプレゼンテーションのすべてのスライドをファイルに保存します。 |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | 指定された形式および追加オプションでプレゼンテーションのすべてのスライドをストリームに保存します。 |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | プレゼンテーションのすべてのスライドを XAML マークアップを表すファイルのセットに保存します。 |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | プレゼンテーションのすべてのスライドの Image オブジェクトを返します。 |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | 指定されたスライドのサムネイル Image オブジェクトを返します。 |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | カスタムスケーリングでプレゼンテーションのすべてのスライドのサムネイル Image オブジェクトを返します。 |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | 指定されたスライドのサムネイル Image オブジェクトをカスタムスケーリングで返します。 |
| [getImages(IRenderingOptions options, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | 指定されたサイズでプレゼンテーションのすべてのスライドのサムネイル Image オブジェクトを返します。 |
| [getImages(IRenderingOptions options, int[] slides, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-) | 指定されたスライドのサムネイル Image オブジェクトを指定されたサイズで返します。 |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | 指定されたスライドをページ番号を保持したまま、指定された形式でファイルに保存します。 |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | 指定されたスライドをページ番号を保持したまま、指定された形式でファイルに保存します。 |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | 指定されたスライドをページ番号を保持したまま、指定された形式でストリームに保存します。 |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | 指定されたスライドをページ番号を保持したまま、指定された形式でストリームに保存します。 |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | すべてのスライドのすべての対象シェイプ内のすべての段落で、同じ書式のランを結合します。 |
| [dispose()](#dispose--) | この Presentation オブジェクトが使用するすべてのリソースを解放します。 |
| [getPresentation()](#getPresentation--) | テキストの親プレゼンテーションを返します。 |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | サンプルテキストのすべての一致を指定された色でハイライトします。 |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | サンプルテキストのすべての一致を指定された色でハイライトします。 |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | 正規表現のすべての一致を指定された色でハイライトします。 |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | 指定されたテキストのすべての出現を別の指定されたテキストに置き換えます。 |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | 正規表現のすべての一致を指定された文字列に置き換えます。 |
### Presentation() {#Presentation--}
```
public Presentation()
```

このコンストラクタは、ゼロから新しいプレゼンテーションを作成します。作成されたプレゼンテーションには空のスライドが1枚含まれます。

### Presentation(LoadOptions loadOptions) {#Presentation-com.aspose.slides.LoadOptions-}
```
public Presentation(LoadOptions loadOptions)
```

このコンストラクタは、ゼロから新しいプレゼンテーションを作成します。作成されたプレゼンテーションには空のスライドが1枚含まれます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | 追加のロードオプション。 |

### Presentation(InputStream stream) {#Presentation-java.io.InputStream-}
```
public Presentation(InputStream stream)
```

このコンストラクタは、既存の Presentation を読み込む主な手段です。

--------------------

> ```
> FileInputStream fis = new FileInputStream("demo.pptx");
>  Presentation pres = new Presentation(fis);
>  fis.close();
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | 入力ストリーム。 |

### Presentation(InputStream stream, LoadOptions loadOptions) {#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-}
```
public Presentation(InputStream stream, LoadOptions loadOptions)
```

このコンストラクタは、既存の Presentation を読み込む主な手段です。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | 入力ストリーム。 |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | 追加のロードオプション。 |

### Presentation(String file) {#Presentation-java.lang.String-}
```
public Presentation(String file)
```

このコンストラクタは、Presentation の内容が読み込まれるソースファイルパスを取得します。

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| file | java.lang.String | 入力ファイル。 |

### Presentation(String file, LoadOptions loadOptions) {#Presentation-java.lang.String-com.aspose.slides.LoadOptions-}
```
public Presentation(String file, LoadOptions loadOptions)
```

このコンストラクタは、Presentation の内容が読み込まれるソースファイルパスを取得します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| file | java.lang.String | 入力ファイル。 |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | 追加のロードオプション。 |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public final Date getCurrentDateTime()
```

日時フィールドの内容を置き換える日付と時刻を取得または設定します。デフォルトではこの Presentation オブジェクトの作成時刻です。読み書き可能 java.util.Date。

**返り値:**
java.util.Date
### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public final void setCurrentDateTime(Date value)
```

日時フィールドの内容を置き換える日付と時刻を取得または設定します。デフォルトではこの Presentation オブジェクトの作成時刻です。読み書き可能 java.util.Date。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.util.Date |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを返します。読み取り専用 IDOMObject。

**返り値:**
com.aspose.slides.IDOMObject
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IPresentationHeaderFooterManager getHeaderFooterManager()
```

実際の HeaderFooter マネージャーを返します。読み取り専用 [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)。

--------------------

> ```
> The following example shows how to set footer visibility inside Slide of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IBaseSlideHeaderFooterManager headerFooterManager = pres.getSlides().get_Item(0).getHeaderFooterManager();
>      if (!headerFooterManager.isFooterVisible()) // Property IsFooterVisible は、スライドのフッタープレースホルダーが存在しないことを示すために使用されます。
>      {
>          headerFooterManager.setFooterVisibility(true); // Method SetFooterVisibility は、スライドのフッタープレースホルダーを表示可能にするために使用されます。
>      }
>      if (!headerFooterManager.isSlideNumberVisible()) // Property IsSlideNumberVisible は、スライドのページ番号プレースホルダーが存在しないことを示すために使用されます。
>      {
>          headerFooterManager.setSlideNumberVisibility(true); // Method SetSlideNumberVisibility は、スライドのページ番号プレースホルダーを表示可能にするために使用されます。
>      }
>      if (!headerFooterManager.isDateTimeVisible()) // Property IsDateTimeVisible は、スライドの日時プレースホルダーが存在しないことを示すために使用されます。
>      {
>          headerFooterManager.setDateTimeVisibility(true); // Method SetFooterVisibility は、スライドの日時プレースホルダーを表示可能にするために使用されます。
>      }
>      headerFooterManager.setFooterText("Footer text"); // Method SetFooterText は、スライドのフッタープレースホルダーにテキストを設定するために使用されます。
>      headerFooterManager.setDateTimeText("Date and time text"); // Method SetDateTimeText は、スライドの日時プレースホルダーにテキストを設定するために使用されます。
>      pres.save("Presentation.ppt", SaveFormat.Ppt);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set child footer visibility inside Slide.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IMasterSlideHeaderFooterManager headerFooterManager = pres.getMasters().get_Item(0).getHeaderFooterManager();
>      headerFooterManager.setFooterAndChildFootersVisibility(true); // Method SetFooterAndChildFootersVisibility は、マスタースライドとすべての子フッタープレースホルダーを表示可能にするために使用されます。
>      headerFooterManager.setSlideNumberAndChildSlideNumbersVisibility(true); // Method SetSlideNumberAndChildSlideNumbersVisibility は、マスタースライドとすべての子ページ番号プレースホルダーを表示可能にするために使用されます。
>      headerFooterManager.setDateTimeAndChildDateTimesVisibility(true); // Method SetDateTimeAndChildDateTimesVisibility は、マスタースライドとすべての子日時プレースホルダーを表示可能にするために使用されます。
> 
>      headerFooterManager.setFooterAndChildFootersText("Footer text"); // Method SetFooterAndChildFootersText は、マスタースライドとすべての子フッタープレースホルダーにテキストを設定するために使用されます。
>      headerFooterManager.setDateTimeAndChildDateTimesText("Date and time text"); // Method SetDateTimeAndChildDateTimesText は、マスタースライドとすべての子日時プレースホルダーにテキストを設定するために使用されます。
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**返り値:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)
### getProtectionManager() {#getProtectionManager--}
```
public final IProtectionManager getProtectionManager()
```

このプレゼンテーションの権限マネージャーを取得します。読み取り専用 [IProtectionManager](../../com.aspose.slides/iprotectionmanager)。

**返り値:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)
### getSlides() {#getSlides--}
```
public final ISlideCollection getSlides()
```

プレゼンテーションで定義されているすべてのスライドのリストを返します。読み取り専用 [ISlideCollection](../../com.aspose.slides/islidecollection)。

--------------------

> ```
> The following example shows how to set slides' background color of PowerPoint Presentation.
>  
>  // プレゼンテーション ファイルを表す Presentation クラスのインスタンスを作成します
>  Presentation pres = new Presentation();
>  try
>  {
>      // 最初の ISlide の背景色を青に設定します
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.BLUE);
>      pres.save("ContentBG_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set slides' background image of PowerPoint Presentation.
>  
>  // プレゼンテーション ファイルを表す Presentation クラスのインスタンスを作成します
>  Presentation pres = new Presentation("SetImageAsBackground.pptx");
>  try {
>      // 画像で背景を設定します
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Picture);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);
>      // 画像を設定します
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("Tulips.jpg");
>          // 画像をプレゼンテーションの画像コレクションに追加します
>          IPPImage imgx = pres.getImages().addImage(fos);
>          pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().getPicture().setImage(imgx);
>      } finally {
>          if (fos != null) fos.close();
>      }
>      // プレゼンテーションをディスクに書き込みます
>      pres.save("ContentBG_Img_out.pptx", SaveFormat.Pptx);
>  } catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add slide transition Presentation.
>  
>  // ソースプレゼンテーションファイルを読み込むための Presentation クラスのインスタンスを作成します
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // スライド 1 に円形トランジションを適用します
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // スライド 2 にコーム型トランジションを適用します
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // プレゼンテーションをディスクに書き込みます
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add advanced slide Transition.
>  
>  // プレゼンテーション ファイルを表す Presentation クラスのインスタンスを作成します
>  Presentation pres = new Presentation("BetterSlideTransitions.pptx");
>  try
>  {
>      // スライド 1 に円形トランジションを適用します
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // トランジション時間を 3 秒に設定します
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceAfterTime(3000);
>      // スライド 2 にコーム型トランジションを適用します
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // トランジション時間を 5 秒に設定します
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceAfterTime(5000);
>      // スライド 3 にズーム型トランジションを適用します
>      pres.getSlides().get_Item(2).getSlideShowTransition().setType(TransitionType.Zoom);
>      // トランジション時間を 7 秒に設定します
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceAfterTime(7000);
>      // プレゼンテーションをディスクに書き込みます
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**返り値:**
[ISlideCollection](../../com.aspose.slides/islidecollection)
### getSections() {#getSections--}
```
public final ISectionCollection getSections()
```

プレゼンテーションで定義されているすべてのスライドセクションのリストを返します。読み取り専用 [ISectionCollection](../../com.aspose.slides/isectioncollection)。

--------------------

> ```
> The following examples shows how to create Sections in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide defaultSlide = pres.getSlides().get_Item(0);
>      ISlide newSlide1 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide2 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide3 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide4 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISection section1 = pres.getSections().addSection("Section 1", newSlide1);
>      // section1 は newSlide2 で終了し、その後 section2 が開始されます
>      ISection section2 = pres.getSections().addSection("Section 2", newSlide3);
>      pres.save("pres-sections.pptx", SaveFormat.Pptx);
>      pres.getSections().reorderSectionWithSlides(section2, 0);
>      pres.save("pres-sections-moved.pptx", SaveFormat.Pptx);
>      pres.getSections().removeSectionWithSlides(section2);
>      pres.getSections().appendEmptySection("Last empty section");
>      pres.save("pres-section-with-empty.pptx",SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to changing the names of Sections.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISection section = pres.getSections().get_Item(0);
>      section.setName("My section");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返り値:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)
### getSlideSize() {#getSlideSize--}
```
public final ISlideSize getSlideSize()
```

スライドサイズオブジェクトを返します。読み取り専用 [ISlideSize](../../com.aspose.slides/islidesize)。

--------------------

> ```
> The following example shows how to change the slide size in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres-4x3-aspect-ratio.pptx");
>  try {
>      pres.getSlideSize().setSize(SlideSizeType.OnScreen16x9, SlideSizeScaleType.DoNotScale);
>      pres.save("pres-4x3-aspect-ratio.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set slide size with respect to content scaling for a PowerPoint Presentation.
>  
>  // プレゼンテーション ファイルを表す Presentation オブジェクトをインスタンス化します
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation auxPresentation = new Presentation();
>      try {
>          ISlide slide = presentation.getSlides().get_Item(0);
>          // 生成されたプレゼンテーションのスライドサイズを元のサイズに設定します
>          presentation.getSlideSize().setSize(540, 720, SlideSizeScaleType.EnsureFit); // Method SetSize は、コンテンツを拡大縮小してフィットさせるためにスライドサイズを設定する際に使用されます
>          presentation.getSlideSize().setSize(SlideSizeType.A4Paper, SlideSizeScaleType.Maximize); // Method SetSize は、コンテンツのサイズを最大化してスライドサイズを設定する際に使用されます
>          // プレゼンテーションをディスクに保存します
>          auxPresentation.save("Set_Size&Type_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (auxPresentation != null) auxPresentation.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  The following example shows how to specifying custom slide sizes in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getSlideSize().setSize(780, 540, SlideSizeScaleType.DoNotScale); // A4 用紙サイズ
>      pres.save("pres-a4-slide-size.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返り値:**
[ISlideSize](../../com.aspose.slides/islidesize)
### getNotesSize() {#getNotesSize--}
```
public final INotesSize getNotesSize()
```

ノートスライドサイズオブジェクトを返します。読み取り専用 [INotesSize](../../com.aspose.slides/inotessize)。

**返り値:**
[INotesSize](../../com.aspose.slides/inotessize)
### getLayoutSlides() {#getLayoutSlides--}
```
public final IGlobalLayoutSlideCollection getLayoutSlides()
```

プレゼンテーションで定義されているすべてのレイアウトスライドのリストを返します。読み取り専用 [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)。

--------------------

IMasterSlide.LayoutSlides プロパティを使用して、レイアウトスライドの追加/挿入/削除/クローンの代替 API にアクセスできます。

**返り値:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
### getMasters() {#getMasters--}
```
public final IMasterSlideCollection getMasters()
```

プレゼンテーションで定義されているすべてのマスタースライドのリストを返します。読み取り専用 [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)。

--------------------

> ```
> The following examples shows how to adding Images to Master Slides of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IMasterSlide masterSlide = slide.getLayoutSlide().getMasterSlide();
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          masterSlide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to change the background color of the master slide of PowerPoint Presentation.
>  
>  // プレゼンテーション ファイルを表す Presentation クラスのインスタンスを作成します
>  Presentation pres = new Presentation();
>  try
>  {
>      // マスター ISlide の背景色をフォレストグリーンに設定します
>      pres.getMasters().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.GREEN);
>      // プレゼンテーションをディスクに書き込みます
>      pres.save("SetSlideBackgroundMaster_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add slide layout to PowerPoint Presentation.
>  
>  // プレゼンテーション ファイルを表す Presentation クラスのインスタンスを作成します
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // レイアウトスライドのタイプで検索を試みます
>      IMasterLayoutSlideCollection layoutSlides = presentation.getMasters().get_Item(0).getLayoutSlides();
>      ILayoutSlide layoutSlide = null;
>      if (layoutSlides.getByType(SlideLayoutType.TitleAndObject) != null)
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.TitleAndObject);
>      else
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.Title);
> 
>      if (layoutSlide == null)
>      {
>          // プレゼンテーションに特定のタイプのレイアウトが含まれていない状況です。
>          // プレゼンテーション ファイルには Blank と Custom のレイアウトタイプのみが含まれています。
>          // ただし Custom タイプのレイアウトスライドは異なるスライド名を持っています、
>          // 例えば "Title", "Title and Content" などです。これらを使用することが可能です
>          // レイアウトスライド選択の名前として使用できます。
>          // プレースホルダーシェイプタイプの集合を使用することも可能です。例として、
>          // タイトルスライドは Title プレースホルダーのみを持つべきです。
>          for (ILayoutSlide titleAndObjectLayoutSlide : (Iterable) layoutSlides)
>          {
>              if ("Title and Object".equals(titleAndObjectLayoutSlide.getName()))
>              {
>                  layoutSlide = titleAndObjectLayoutSlide;
>                  break;
>              }
>          }
>          if (layoutSlide == null)
>          {
>              for (ILayoutSlide titleLayoutSlide : (Iterable) layoutSlides)
>              {
>                  if ("Title".equals(titleLayoutSlide.getName()))
>                  {
>                      layoutSlide = titleLayoutSlide;
>                      break;
>                  }
>              }
>              if (layoutSlide == null)
>              {
>                  layoutSlide = layoutSlides.getByType(SlideLayoutType.Blank);
>                  if (layoutSlide == null)
>                  {
>                      layoutSlide = layoutSlides.add(SlideLayoutType.TitleAndObject, "Title and Object");
>                  }
>              }
>          }
>      }
>      // 追加したレイアウトスライドで空のスライドを挿入します
>      presentation.getSlides().insertEmptySlide(0, layoutSlide);
>      // プレゼンテーションを保存します
>      presentation.save("AddLayoutSlides_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**返り値:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public final IMasterNotesSlideManager getMasterNotesSlideManager()
```

ノートマスターマネージャーを返します。読み取り専用 [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)。

**返り値:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)
### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public final IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

配布資料マスターマネージャーを返します。読み取り専用 [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)。

**返り値:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)
### getFontsManager() {#getFontsManager--}
```
public final IFontsManager getFontsManager()
```

フォントマネージャーを返します。読み取り専用 [IFontsManager](../../com.aspose.slides/ifontsmanager)。

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // プレゼンテーションを読み込みます
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // 置換対象のソースフォントを読み込みます
>      IFontData sourceFont = new FontData("Arial");
>      IFontData[] allFonts = pres.getFontsManager().getFonts();
>      for (IFontData font : allFonts)
>      {
>          boolean fontAlreadyEmbedded = false;
>          IFontData[] embeddedFonts = pres.getFontsManager().getEmbeddedFonts();
>          for (int i = 0; i < embeddedFonts.length; i++)
>          {
>              if (embeddedFonts[i].equals(font))
>              {
>                  fontAlreadyEmbedded = true;
>                  break;
>              }
>          }
>          if (!fontAlreadyEmbedded) {
>              pres.getFontsManager().addEmbeddedFont(font, EmbedFontCharacters.All);
>          }
>      }
>      // プレゼンテーションを保存します
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返り値:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)
### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public final ITextStyle getDefaultTextStyle()
```

シェイプのデフォルトテキストスタイルを返します。読み取り専用 [ITextStyle](../../com.aspose.slides/itextstyle)。

**返り値:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getCommentAuthors() {#getCommentAuthors--}
```
public final ICommentAuthorCollection getCommentAuthors()
```

コメント作成者のコレクションを返します。読み取り専用 [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)。

**返り値:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
### getDocumentProperties() {#getDocumentProperties--}
```
public final IDocumentProperties getDocumentProperties()
```

標準およびカスタムのドキュメントプロパティを含む DocumentProperties オブジェクトを返します。読み取り専用 [IDocumentProperties](../../com.aspose.slides/idocumentproperties)。

**返り値:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### getImages() {#getImages--}
```
public final IImageCollection getImages()
```

プレゼンテーション内のすべての画像のコレクションを返します。読み取り専用 [IImageCollection](../../com.aspose.slides/iimagecollection)。

--------------------

> ```
> The following examples shows how to add image as BLOB in PowerPoint Presentation.
>  
>  // 画像が追加される新しいプレゼンテーションを作成します。
>  Presentation pres = new Presentation();
>  try
>  {
>      // プレゼンテーションに含めたい大きな画像ファイルがあると想定します
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // 画像をプレゼンテーションに追加します - KeepLocked 動作を選択します、なぜなら
>          // 「largeImage.png」ファイルにアクセスするつもりはありません。
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // プレゼンテーションを保存します。大きなプレゼンテーションが出力される間、メモリ使用量は
>          // pres オブジェクトのライフサイクル全体で低く保たれます。
>          pres.save("presentationWithLargeImage.pptx", SaveFormat.Pptx);
>      }
>      finally
>      {
>          fip.close();
>      }
>  }
>  catch (java.io.IOException e) { }
>  finally
>  {
>      pres.dispose();
>  }
>  
>  The following examples add a hyperlink to an image in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          // プレゼンテーションに画像を追加します
>          IPPImage image = pres.getImages().addImage(fos);
>          // 以前に追加した画像を基にスライド 1 にピクチャーフレームを作成します
>          IPictureFrame pictureFrame = pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>          pictureFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>          pictureFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      } finally {
>          if (fos != null) fos.close();
>      }
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch (IOException e){ }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**返り値:**
[IImageCollection](../../com.aspose.slides/iimagecollection)
### getAudios() {#getAudios--}
```
public final IAudioCollection getAudios()
```

プレゼンテーション内に埋め込まれたすべてのオーディオファイルのコレクションを返します。読み取り専用 [IAudioCollection](../../com.aspose.slides/iaudiocollection)。

--------------------

> ```
> The following examples shows how to add a hyperlink to an audio file.
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("audio.mp3");
>          IAudio audio = pres.getAudios().addAudio(fos);
>          IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(10, 10, 100, 100, audio);
>          audioFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>          audioFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      } finally {
>          if (fos != null) fos.close();
>      }
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) {}
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**返り値:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)
### getVideos() {#getVideos--}
```
public final IVideoCollection getVideos()
```

プレゼンテーション内に埋め込まれたすべてのビデオファイルのコレクションを返します。読み取り専用 [IVideoCollection](../../com.aspose.slides/ivideocollection)。

--------------------

> ```
> The following examples shows how to create embedded Video Frame in a PowerPoint Presentation.
>  
>  // PPTX を表す Presentation クラスのインスタンスを作成します
>  Presentation pres = new Presentation();
>  try {
>      // 最初のスライドを取得
>      ISlide sld = pres.getSlides().get_Item(0);
>      // プレゼンテーションにビデオを埋め込む
>      IVideo vid = pres.getVideos().addVideo(new FileInputStream("Wildlife.mp4"));
>      // ビデオフレームを追加
>      IVideoFrame vf = sld.getShapes().addVideoFrame(50, 150, 300, 350, vid);
>      // ビデオフレームにビデオを設定
>      vf.setEmbeddedVideo(vid);
>      // ビデオの再生モードと音量を設定
>      vf.setPlayMode(VideoPlayModePreset.Auto);
>      vf.setVolume(AudioVolumeMode.Loud);
>      // PPTX ファイルをディスクに保存
>      pres.save("VideoFrame_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add a video passing path to the video file directly into AddVideoFrame method for PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide sld = pres.getSlides().get_Item(0);
>      IVideoFrame vf = sld.getShapes().addVideoFrame(50, 150, 300, 150, "video1.avi");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add large file through BLOB to a Presentation.
>  
>  // ビデオが追加される新しいプレゼンテーションを作成します
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fileStream = new FileInputStream("veryLargeVideo.avi");
>      try {
>          // プレゼンテーションにビデオを追加します - KeepLocked 動作を選択しました、なぜなら
>          // "veryLargeVideo.avi" ファイルにアクセスするつもりはありません。
>          IVideo video = pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addVideoFrame(0, 0, 480, 270, video);
>          // プレゼンテーションを保存します。大きなプレゼンテーションが出力される間、
>          // pres オブジェクトのライフサイクル全体でメモリ使用量は低く保たれます。
>          pres.save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
>      } finally {
>          if (fileStream != null) fileStream.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to export large file through BLOB from PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  // ソースファイルをロックし、メモリに読み込まない
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  // Presentation インスタンスを作成し、"hugePresentationWithAudiosAndVideos.pptx" ファイルをロックします。
>  Presentation pres = new Presentation("Large  Video File Test1.pptx", loadOptions);
>  try {
>      // 各ビデオをファイルに保存します。メモリ使用量の増加を防ぐために、
>      // プレゼンテーションのビデオストリームから新しく作成したビデオファイル用のストリームへデータを転送するバッファが必要です。
>      byte[] buffer = new byte[81024];
>      // ビデオを走査
>      for (int index = 0; index < pres.getVideos().size(); index++) {
>          IVideo video = pres.getVideos().get_Item(index);
>          // プレゼンテーションのビデオストリームを開きます。注意点として、意図的に video.BinaryData などのプロパティへのアクセスは避けました
>          // このプロパティはビデオ全体を含むバイト配列を返すため、メモリにバイトがロードされます。
>          // video.GetStream を使用します。これによりストリームが返され、ビデオ全体をメモリにロードする必要はありません。
>          InputStream presVideoStream = video.getStream();
>          try {
>              FileOutputStream outputFileStream = new FileOutputStream("video{index}.avi");
>              try {
>                  int bytesRead;
>                  while ((bytesRead = presVideoStream.read(buffer, 0, buffer.length)) > 0) {
>                      outputFileStream.write(buffer, 0, bytesRead);
>                  }
>              } finally {
>                  if (outputFileStream != null) outputFileStream.close();
>              }
>          } finally {
>              if (presVideoStream != null) presVideoStream.close();
>          }
>          // ビデオやプレゼンテーションのサイズに関係なく、メモリ消費は低く保たれます。
>      }
>      // 必要に応じて、音声ファイルにも同じ手順を適用できます。
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add a hyperlink to a video in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.avi")));
>      IVideoFrame videoFrame = pres.getSlides().get_Item(0).getShapes().addVideoFrame(10, 10, 100, 100, video);
>      videoFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      videoFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to create Video Frame with Video from Web Source in a PowerPoint Presentation.
>  
>  public static void run()
>  {
>      Presentation pres = new Presentation();
>      try {
>          addVideoFromYouTube(pres, "Tj75Arhq5ho");
>          pres.save("AddVideoFrameFromWebSource_out.pptx", SaveFormat.Pptx);
>      } catch(IOException e) {
>      } finally {
>          if (pres != null) pres.dispose();
>      }
>  }
>  private static void addVideoFromYouTube(Presentation pres, String videoId) throws IOException
>  {
>      // ビデオフレームを追加
>      IVideoFrame videoFrame = pres.getSlides().get_Item(0).getShapes().addVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
>      videoFrame.setPlayMode(VideoPlayModePreset.Auto);
> 
>      // サムネイルをロード
>      String thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
>      URL url = new URL(thumbnailUri);
>      URLConnection connection = url.openConnection();
>      connection.setConnectTimeout(5000);
>      connection.setReadTimeout(10000);
>      InputStream input = connection.getInputStream();
>      ByteArrayOutputStream output = new ByteArrayOutputStream();
>      try
>      {
>          byte[] buffer = new byte[8192];
>          for (int count; (count = input.read(buffer)) > 0; )
>          {
>              output.write(buffer, 0, count);
>          }
>          videoFrame.getPictureFormat().getPicture().setImage(pres.getImages().addImage(output.toByteArray()));
>      } finally {
>          if (input != null) input.close();
>          if (output != null) output.close();
>      }
>  }
>  
>  The following examples shows how to extract Video from slide of PowerPoint Presentation.
>  
>  // プレゼンテーション ファイルを表す Presentation オブジェクトをインスタンス化します
>  Presentation presentation = new Presentation("Video.pptx");
>  try {
>      for (ISlide slide : presentation.getSlides())
>      {
>          for (IShape shape : presentation.getSlides().get_Item(0).getShapes())
>          {
>              if (shape instanceof VideoFrame)
>              {
>                  IVideoFrame vf = (IVideoFrame) shape;
>                  String type = vf.getEmbeddedVideo().getContentType();
>                  int ss = type.lastIndexOf('/');
>                  type = type.substring(ss + 1);
>                  byte[] buffer = vf.getEmbeddedVideo().getBinaryData();
>                  FileOutputStream fop = new FileOutputStream("NewVideo_out." + type);
>                  try
>                  {
>                      fop.write(buffer);
>                      fop.flush();
>                      fop.close();
>                  }
>                  finally
>                  {
>                      if (presentation != null) presentation.dispose();
>                  }
>              }
>          }
>      }
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**返り値:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)
### getSlideShowSettings() {#getSlideShowSettings--}
```
public final SlideShowSettings getSlideShowSettings()
```

プレゼンテーションのスライドショー設定を返します。

**返り値:**
[SlideShowSettings](../../com.aspose.slides/slideshowsettings)
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final IDigitalSignatureCollection getDigitalSignatures()
```

プレゼンテーションに署名するために使用される署名のコレクションを返します。読み取り専用 [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)。

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
>                   + signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
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


**返り値:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

プレゼンテーションのカスタムデータを返します。読み取り専用 [ICustomData](../../com.aspose.slides/icustomdata)。

**返り値:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public final ICustomXmlPart[] getAllCustomXmlParts()
```

プレゼンテーション内のすべてのカスタムデータパーツを返します。読み取り専用 ICustomXmlPart[]。

--------------------

> ```
> The following examples show how to clear all custom xml parts from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("PresentationWithCustomXml.pptx");
>  try {
>      // すべてのカスタム XML パーツを反復処理します
>      for (ICustomXmlPart item : pres.getAllCustomXmlParts())
>      {
>          item.remove();
>      }
>      pres.save("out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**返り値:**
com.aspose.slides.ICustomXmlPart[]
### getVbaProject() {#getVbaProject--}
```
public final IVbaProject getVbaProject()
```

プレゼンテーションのマクロを含む VBA プロジェクトを取得または設定します。読み書き可能 [IVbaProject](../../com.aspose.slides/ivbaproject)。

**返り値:**
[IVbaProject](../../com.aspose.slides/ivbaproject)
### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public final void setVbaProject(IVbaProject value)
```

プレゼンテーションのマクロを含む VBA プロジェクトを取得または設定します。読み書き可能 [IVbaProject](../../com.aspose.slides/ivbaproject)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

すべてのプレゼンテーションスライドに含まれるすべてのハイパーリンクへ簡単にアクセスできるようにします（マスター、レイアウト、ノートスライドは除く）。読み取り専用 [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)。

**返り値:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getViewProperties() {#getViewProperties--}
```
public final IViewProperties getViewProperties()
```

プレゼンテーション全体のビュー プロパティを取得します。読み取り専用 [IViewProperties](../../com.aspose.slides/iviewproperties)。

**返り値:**
[IViewProperties](../../com.aspose.slides/iviewproperties)
### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public final int getFirstSlideNumber()
```

プレゼンテーションの最初のスライド番号を表します

**返り値:**
int
### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public final void setFirstSlideNumber(int value)
```

プレゼンテーションの最初のスライド番号を表します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabelCollection getSensitivityLabels()
```

プレゼンテーションドキュメントに適用された感度ラベルのコレクションを返します。読み取り専用 [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)。

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // 適用されたラベルを出力します
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // 新しいラベルを追加します
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // ポリシーから感度ラベル ID を取得します
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // ポリシーから Azure AD サイト識別子を取得します
>      ISensitivityLabel label = sensitivityLabels.add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType.Privileged);
>      label.getContentMarkTypes().addItem(SensitivityLabelContentType.Footer);
> 
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返り値:**
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
### getSlideById(long id) {#getSlideById-long-}
```
public final IBaseSlide getSlideById(long id)
```

ID により Slide、MasterSlide、または LayoutSlide を返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| id | long | スライドの ID。 |

**返り値:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide オブジェクト。
### getSourceFormat() {#getSourceFormat--}
```
public final int getSourceFormat()
```

プレゼンテーションが読み込まれた形式に関する情報を返します。読み取り専用 [SourceFormat](../../com.aspose.slides/sourceformat)。

**返り値:**
int
### getMasterTheme() {#getMasterTheme--}
```
public final IMasterTheme getMasterTheme()
```

マスターテーマを返します。読み取り専用 [IMasterTheme](../../com.aspose.slides/imastertheme)。

--------------------

> ```
> The following examples shows how to change a theme effect by altering parts of elements of PowerPoint Presentation.
>  
>  //プレゼンテーション ファイルを表すプレゼンテーション オブジェクトをインスタンス化します
>  Presentation pres = new Presentation("Subtle_Moderate_Intense.pptx");
>  try {
>      pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(0).getFillFormat().getSolidFillColor().setColor(Color.RED);
>      ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).setFillType(FillType.Solid);
>      ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getSolidFillColor().setColor(Color.GREEN);
>      ((EffectStyle)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getEffectFormat().getOuterShadowEffect().setDistance(10f);
>      pres.save("Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**返り値:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### save(String fname, int format) {#save-java.lang.String-int-}
```
public final void save(String fname, int format)
```

指定された形式でプレゼンテーションのすべてのスライドをファイルに保存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fname | java.lang.String | 作成するファイルへのパス。 |
| format | int | エクスポートデータの形式。 |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int format)
```

指定された形式でプレゼンテーションのすべてのスライドをストリームに保存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 出力ストリーム。 |
| format | int | エクスポートデータの形式。 |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int format, ISaveOptions options)
```

指定された形式および追加オプションでプレゼンテーションのすべてのスライドをファイルに保存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fname | java.lang.String | 作成するファイルへのパス。 |
| format | int | エクスポートデータの形式。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 追加の形式オプション。 |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int format, ISaveOptions options)
```

指定された形式および追加オプションでプレゼンテーションのすべてのスライドをストリームに保存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 出力ストリーム。 |
| format | int | エクスポートデータの形式。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 追加の形式オプション。 |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public final void save(IXamlOptions options)
```

プレゼンテーションのすべてのスライドを XAML マークアップを表すファイルのセットに保存します。

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
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | XAML 形式オプション。 |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public final IImage[] getImages(IRenderingOptions options)
```

プレゼンテーションのすべてのスライドの Image オブジェクトを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff オプション。 |

**返り値:**
com.aspose.slides.IImage[] - Image オブジェクト。
### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides)
```

指定されたスライドのサムネイル Image オブジェクトを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff オプション。 |
| slides | int[] | 1 から開始するスライド位置の配列。 |

**返り値:**
com.aspose.slides.IImage[] - Image オブジェクト。
### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

カスタムスケーリングでプレゼンテーションのすべてのスライドのサムネイル Image オブジェクトを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff オプション。 |
| scaleX | float | X 軸方向にこのサムネイルを拡大縮小する値。 |
| scaleY | float | Y 軸方向にこのサムネイルを拡大縮小する値。 |

**返り値:**
com.aspose.slides.IImage[] - Image オブジェクト。
### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

指定されたスライドのサムネイル Image オブジェクトをカスタムスケーリングで返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff オプション。 |
| slides | int[] | 1 から開始するスライド位置の配列。 |
| scaleX | float | X 軸方向にこのサムネイルを拡大縮小する値。 |
| scaleY | float | Y 軸方向にこのサムネイルを拡大縮小する値。 |

**返り値:**
com.aspose.slides.IImage[] - Image オブジェクト。
### getImages(IRenderingOptions options, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public final IImage[] getImages(IRenderingOptions options, Size imageSize)
```

指定されたサイズでプレゼンテーションのすべてのスライドのサムネイル Image オブジェクトを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff オプション。 |
| imageSize | [Size](../../com.aspose.slides.android/size) | 作成する画像のサイズ。 |

**返り値:**
com.aspose.slides.IImage[] - Image オブジェクト。
### getImages(IRenderingOptions options, int[] slides, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, Size imageSize)
```

指定されたスライドのサムネイル Image オブジェクトを指定されたサイズで返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff オプション。 |
| slides | int[] | 1 から開始するスライド位置の配列。 |
| imageSize | [Size](../../com.aspose.slides.android/size) | 作成する画像のサイズ。 |

**返り値:**
com.aspose.slides.IImage[] - Image オブジェクト。
### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public final void save(String fname, int[] slides, int format)
```

指定されたスライドをページ番号を保持したまま、指定された形式でファイルに保存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fname | java.lang.String | 作成するファイルへのパス。 |
| slides | int[] | 1 から開始するスライド位置の配列。 |
| format | int | エクスポートデータの形式。 |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int[] slides, int format, ISaveOptions options)
```

指定されたスライドをページ番号を保持したまま、指定された形式でファイルに保存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fname | java.lang.String | 作成するファイルへのパス。 |
| slides | int[] | 1 から開始するスライド位置の配列。 |
| format | int | エクスポートデータの形式。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 追加の形式オプション。 |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public final void save(OutputStream stream, int[] slides, int format)
```

指定されたスライドをページ番号を保持したまま、指定された形式でストリームに保存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 出力ストリーム。 |
| slides | int[] | 1 から開始するスライド位置の配列。 |
| format | int | エクスポートデータの形式。 |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

指定されたスライドをページ番号を保持したまま、指定された形式でストリームに保存します。

--------------------

> ```
> The following example shows how to convert PowerPoint to PNG.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail().compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PNG with custom dimensions.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      float scaleX = 2f;
>      float scaleY = 2f;
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail(scaleX, scaleY).compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PNG with custom size.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      com.aspose.slides.android.Size size = new com.aspose.slides.android.Size(960, 720);
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail(size).compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 出力ストリーム。 |
| slides | int[] | 1 から開始するスライド位置の配列。 |
| format | int | エクスポートデータの形式。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 追加の形式オプション。 |

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

すべてのスライドのすべての対象シェイプ内のすべての段落で、同じ書式のランを結合します。

### dispose() {#dispose--}
```
public  final  void  dispose()
```

この Presentation オブジェクトが使用するすべてのリソースを解放します。

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

テキストの親プレゼンテーションを返します。読み取り専用 [IPresentation](../../com.aspose.slides/ipresentation)。

**返り値:**
[IPresentation](../../com.aspose.slides/ipresentation)
### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public final void highlightText(String text, Integer highlightColor)
```

サンプルテキストのすべての一致を指定された色でハイライトします。

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // すべての個別の 'the' の出現箇所をハイライト
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
| highlightColor | java.lang.Integer | テキストをハイライトする色。 |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

サンプルテキストのすべての一致を指定された色でハイライトします。

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // すべての個別の 'the' の出現箇所をハイライト
>      presentation.highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | ハイライトするテキスト。 |
| highlightColor | java.lang.Integer | テキストをハイライトする色。 |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | テキスト検索オプション [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 検索結果を受け取るコールバックオブジェクト [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

正規表現のすべての一致を指定された色でハイライトします。

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // 10文字以上のすべての単語をハイライト
>      presentation.highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| regex | java.util.regex.Pattern | ハイライト対象文字列を取得する正規表現。 |
| highlightColor | java.lang.Integer | テキストをハイライトする色。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 検索結果を受け取るコールバックオブジェクト [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

指定されたテキストのすべての出現を別の指定されたテキストに置き換えます。

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Replace all separate 'the' occurrences with '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| oldText | java.lang.String | 置換対象の文字列。 |
| newText | java.lang.String | oldText のすべての出現を置き換える文字列。 |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | テキスト検索オプション [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 検索結果を受け取るコールバックオブジェクト [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

正規表現のすべての一致を指定された文字列に置き換えます。

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // 10文字以上のすべての単語を '***' に置き換えます
>      presentation.replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| regex | java.util.regex.Pattern | 置換対象文字列を取得する正規表現。 |
| newText | java.lang.String | 置換対象文字列のすべての出現を置き換える文字列。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 検索結果を受け取るコールバックオブジェクト [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |