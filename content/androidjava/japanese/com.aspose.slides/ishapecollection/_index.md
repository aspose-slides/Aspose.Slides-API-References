---
title: IShapeCollection
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: シェイプのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/ishapecollection/
---
**実装されているすべてのインターフェイス:**
com.aspose.slides.IGenericCollection
```
public interface IShapeCollection extends IGenericCollection<IShape>
```

シェイプのコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [getParentGroup()](#getParentGroup--) | shapes collection の親グループ shape オブジェクトを取得します。 |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | 新しい chart を作成し、サンプル シリーズ データと設定で初期化し、shape collection の末尾に追加します。 |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | 新しい chart を作成し、サンプル シリーズ データと設定で初期化し、shape collection の末尾に追加します。 |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | SmartArt ダイアグラムを作成し、shape collection の末尾に追加します。 |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | 新しい chart を作成し、サンプル シリーズ データと設定で初期化し、指定されたインデックスに shape collection に挿入します。 |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | 新しい chart を作成し、サンプル シリーズ データと設定で初期化し、指定されたインデックスに shape collection に挿入します。 |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | 新しい OLE オブジェクト フレームを作成し、shape collection の末尾に追加します。 |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | 新しい OLE オブジェクト フレームを作成し、shape collection の末尾に追加します。 |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | 新しい OLE オブジェクト フレームを作成し、指定されたインデックスに shape collection に挿入します。 |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | 新しい OLE オブジェクト フレームを作成し、指定されたインデックスに shape collection に挿入します。 |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | 新しい Zoom フレームを作成し、shape collection の末尾に追加します。 |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | 新しい Zoom フレームを作成し、shape collection の末尾に追加します。 |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | 新しい Zoom フレームを作成し、指定されたインデックスに shape collection に挿入します。 |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | 定義済み画像を使用した新しい Zoom フレームを作成し、指定されたインデックスに shape collection に挿入します。 |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | 新しい Section Zoom フレームを作成し、shape collection の末尾に追加します。 |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | 定義済み画像を使用した新しい Section Zoom フレームを作成し、shape collection の末尾に追加します。 |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | 新しい Section Zoom フレームを作成し、指定されたインデックスに shape collection に挿入します。 |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | 定義済み画像を使用した新しい Section Zoom フレームを作成し、指定されたインデックスに shape collection に挿入します。 |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | 新しい Summary Zoom フレームを作成し、shape collection の末尾に追加します。 |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | 新しい Summary Zoom フレームを作成し、指定されたインデックスに shape collection に挿入します。 |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | 新しい video フレームを作成し、shape collection の末尾に追加します。 |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | 新しい video フレームを作成し、shape collection の末尾に追加します。 |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | 新しい video フレームを作成し、指定されたインデックスに shape collection に挿入します。 |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | CD トラックにリンクされた新しい audio フレームを作成し、shape collection の末尾に追加します。 |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | CD トラックにリンクされた新しい audio フレームを作成し、指定されたインデックスに shape collection に挿入します。 |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | 外部 audio ファイルにリンクされた新しい audio フレームを作成し、shape collection の末尾に追加します。 |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | 外部 audio ファイルにリンクされた新しい audio フレームを作成し、指定されたインデックスに shape collection に挿入します。 |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | 埋め込み WAV ファイルを持つ新しい audio フレームを作成し、shape collection の末尾に追加します。 |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Presentation.Audios リストの既存 audio オブジェクトを使用して、新しい audio フレームを作成し、shape collection の末尾に追加します。 |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | 埋め込み WAV ファイルを持つ新しい audio フレームを作成し、指定されたインデックスに shape collection に挿入します。 |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Presentation.Audios リストの既存 audio オブジェクトを使用して、新しい audio フレームを作成し、指定されたインデックスに shape collection に挿入します。 |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | コレクション内で指定された shape の最初の出現のゼロベース インデックスを返します。 |
| [toArray()](#toArray--) | すべての shape を含む配列を作成して返します。 |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 指定された範囲のすべての shape を含む配列を作成して返します。 |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | 指定された shape を shape collection 内の新しい位置に移動します。 |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | 指定されたインデックスから始めて、指定された shapes を shape collection 内で移動し、配置します。 |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | デフォルトの書式設定を持つ新しい auto shape を作成し、shape collection の末尾に追加します。 |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | 新しい auto shape を作成し、デフォルト テンプレート書式で初期化することも可能で、shape collection の末尾に追加します。 |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | 数式コンテンツをホストする新しい四角形 auto shape を作成し、shape collection の末尾に追加します。 |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | デフォルト テンプレート書式を適用し、新しい auto shape を指定されたインデックスに shape collection に挿入します。 |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | デフォルト テンプレート スタイルで初期化することも可能で、新しい auto shape を指定されたインデックスに shape collection に挿入します。 |
| [addGroupShape()](#addGroupShape--) | 空の group shape を新しく作成し、shape collection の末尾に追加します。 |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | 指定された SVG 画像を個々の shape に変換し、新しい group shape を作成して、結果の group を shape collection の末尾に追加します。 |
| [insertGroupShape(int index)](#insertGroupShape-int-) | 空の group shape を新しく作成し、指定されたインデックスに shape collection に挿入します。 |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | デフォルト テンプレート スタイルを持つ新しい connector shape を作成し、shape collection の末尾に追加します。 |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | 新しい connector shape を作成し、デフォルト テンプレート スタイルを適用することも可能で、shape collection の末尾に追加します。 |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | デフォルト テンプレート スタイルを適用し、新しい connector shape を指定されたインデックスに shape collection に挿入します。 |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | デフォルト テンプレート スタイルを適用することも可能で、新しい connector shape を指定されたインデックスに shape collection に挿入します。 |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | 指定された画像を含む新しい picture frame を作成し、shape collection の末尾に追加します。 |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | 指定された画像を含む新しい picture frame を作成し、指定されたインデックスに shape collection に挿入します。 |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | 新しい table を作成し、shape collection の末尾に追加します。 |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | 新しい table を作成し、指定されたインデックスに shape collection に挿入します。 |
| [removeAt(int index)](#removeAt-int-) | 指定されたインデックスの shape を shape collection から削除します。 |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | 指定された shape の最初の出現を shape collection から削除します。 |
| [clear()](#clear--) | shape collection からすべての shape を削除します。 |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | 指定された shape のコピーを作成し、shape collection の末尾に追加します。 |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | 指定された shape のコピーを作成し、shape collection の末尾に追加します。 |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | 指定された shape のコピーを作成し、shape collection の末尾に追加します。 |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | 指定された shape のコピーを作成し、指定されたインデックスに shape collection に挿入します。 |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | 指定された shape のコピーを作成し、指定されたインデックスに shape collection に挿入します。 |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | 指定された shape のコピーを作成し、指定されたインデックスに shape collection に挿入します。 |

### get_Item(int index) {#get-Item-int-}
```
public abstract IShape get_Item(int index)
```

指定されたインデックスの要素を取得します。読み取り専用 [IShape](../../com.aspose.slides/ishape)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IShape](../../com.aspose.slides/ishape)

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

shapes collection の親 group shape オブジェクトを取得します。読み取り専用 [IGroupShape](../../com.aspose.slides/igroupshape)。

**戻り値:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height)
```

新しい chart を作成し、サンプル シリーズ データと設定で初期化し、shape collection の末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | int | 追加する chart のタイプ。 |
| x | float | 新しい chart の x 座標（ポイント）。 |
| y | float | 新しい chart の y 座標（ポイント）。 |
| width | float | chart の幅（ポイント）。 |
| height | float | chart の高さ（ポイント）。 |

**戻り値:**
[IChart](../../com.aspose.slides/ichart) - 新しく作成された [IChart](../../com.aspose.slides/ichart)。

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

新しい chart を作成し、サンプル シリーズ データと設定で初期化し、shape collection の末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | int | 追加する chart のタイプ。 |
| x | float | 新しい chart の x 座標（ポイント）。 |
| y | float | 新しい chart の y 座標（ポイント）。 |
| width | float | chart の幅（ポイント）。 |
| height | float | chart の高さ（ポイント）。 |
| initWithSample | boolean | true の場合、新しい chart をサンプル シリーズ データと設定で初期化します。false の場合、シリーズなしで最小設定のみで chart を作成し、作成が速くなります。 |

**戻り値:**
[IChart](../../com.aspose.slides/ichart) - 新しく作成された [IChart](../../com.aspose.slides/ichart)。

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public abstract ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

SmartArt ダイアグラムを作成し、shape collection の末尾に追加します。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       ISmartArt smart = slide.getShapes().addSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | ダイアグラムのフレームの x 座標（ポイント）。 |
| y | float | ダイアグラムのフレームの y 座標（ポイント）。 |
| width | float | ダイアグラムのフレームの幅（ポイント）。 |
| height | float | ダイアグラムのフレームの高さ（ポイント）。 |
| layoutType | int | SmartArt レイアウトのタイプ。 |

**戻り値:**
[ISmartArt](../../com.aspose.slides/ismartart) - 新しく作成された [ISmartArt](../../com.aspose.slides/ismartart)。

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index)
```

新しい chart を作成し、サンプル シリーズ データと設定で初期化し、指定されたインデックスに shape collection に挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | int | 作成する chart のタイプ。 |
| x | float | 新しい chart の x 座標（ポイント）。 |
| y | float | 新しい chart の y 座標（ポイント）。 |
| width | float | chart の幅（ポイント）。 |
| height | float | chart の高さ（ポイント）。 |
| index | int | shape collection 内で chart を挿入するゼロベース インデックス。 |

**戻り値:**
[IChart](../../com.aspose.slides/ichart) - 新しく作成された [IChart](../../com.aspose.slides/ichart)。

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

新しい chart を作成し、サンプル シリーズ データと設定で初期化し、指定されたインデックスに shape collection に挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | int | 作成する chart のタイプ。 |
| x | float | 新しい chart の x 座標（ポイント）。 |
| y | float | 新しい chart の y 座標（ポイント）。 |
| width | float | chart の幅（ポイント）。 |
| height | float | chart の高さ（ポイント）。 |
| index | int | shape collection 内で chart を挿入するゼロベース インデックス。 |
| initWithSample | boolean | true の場合、新しい chart をサンプル シリーズ データと設定で初期化します。false の場合、シリーズなしで最小設定のみで chart を作成し、作成が速くなります。 |

**戻り値:**
[IChart](../../com.aspose.slides/ichart) - 新しく作成された [IChart](../../com.aspose.slides/ichart)。

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

新しい OLE オブジェクト フレームを作成し、shape collection の末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しい OLE フレームの x 座標（ポイント）。 |
| y | float | 新しい OLE フレームの y 座標（ポイント）。 |
| width | float | 新しい OLE フレームの幅（ポイント）。 |
| height | float | 新しい OLE フレームの高さ（ポイント）。 |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | 埋め込み OLE データ情報（[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)）。 |

**戻り値:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 新しく作成された [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)。

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

新しい OLE オブジェクト フレームを作成し、shape collection の末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しい OLE フレームの x 座標（ポイント）。 |
| y | float | 新しい OLE フレームの y 座標（ポイント）。 |
| width | float | 新しい OLE フレームの幅（ポイント）。 |
| height | float | 新しい OLE フレームの高さ（ポイント）。 |
| className | java.lang.String | OLE オブジェクトのクラス名。 |
| path | java.lang.String | リンクされたファイルへのパス。

このパスはプレゼンテーションにそのまま保存されます。相対パスが指定された場合、別ディレクトリからプレゼンテーションを開くとファイルにアクセスできなくなります。 |

**戻り値:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 新しく作成された [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)。

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

新しい OLE オブジェクト フレームを作成し、指定されたインデックスに shape collection に挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | OLE オブジェクト フレームを挿入するゼロベース インデックス。 |
| x | float | 新しい OLE フレームの x 座標（ポイント）。 |
| y | float | 新しい OLE フレームの y 座標（ポイント）。 |
| width | float | 新しい OLE フレームの幅（ポイント）。 |
| height | float | 新しい OLE フレームの高さ（ポイント）。 |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | 埋め込み OLE データ情報（[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)）。 |

**戻り値:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 新しく作成された [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)。

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

新しい OLE オブジェクト フレームを作成し、指定されたインデックスに shape collection に挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | OLE オブジェクト フレームを挿入するゼロベース インデックス。 |
| x | float | 新しい OLE フレームの x 座標（ポイント）。 |
| y | float | 新しい OLE フレームの y 座標（ポイント）。 |
| width | float | 新しい OLE フレームの幅（ポイント）。 |
| height | float | 新しい OLE フレームの高さ（ポイント）。 |
| className | java.lang.String | OLE オブジェクトのクラス名。 |
| path | java.lang.String | リンクされたファイルへのパス。

このパスはプレゼンテーションにそのまま保存されます。相対パスが指定された場合、別ディレクトリからプレゼンテーションを開くとファイルにアクセスできなくなります。 |

**戻り値:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 新しく作成された [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)。

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

新しい Zoom フレームを作成し、shape collection の末尾に追加します。

--------------------

> ```
> この例は、コレクションの末尾に Zoom オブジェクトを追加することを示しています
>  （"Presentation.pptx" プレゼンテーションに少なくとも 2 つのスライドがあると仮定します）:
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しい Zoom フレームの x 座標（ポイント）。 |
| y | float | 新しい Zoom フレームの y 座標（ポイント）。 |
| width | float | 新しい Zoom フレームの幅（ポイント）。 |
| height | float | 新しい Zoom フレームの高さ（ポイント）。 |
| slide | [ISlide](../../com.aspose.slides/islide) | Zoom フレームが参照する [ISlide](../../com.aspose.slides/islide)。このプレゼンテーションに属している必要があります。 |

**戻り値:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - 新しく作成された [IZoomFrame](../../com.aspose.slides/izoomframe)。

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

新しい Zoom フレームを作成し、shape collection の末尾に追加します。

--------------------

> ```
> この例は、コレクションの末尾に Zoom オブジェクトを追加することを示しています
>  （"Presentation.pptx" プレゼンテーションに少なくとも 2 つのスライドがあると仮定します）:
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しい Zoom フレームの x 座標（ポイント）。 |
| y | float | 新しい Zoom フレームの y 座標（ポイント）。 |
| width | float | 新しい Zoom フレームの幅（ポイント）。 |
| height | float | 新しい Zoom フレームの高さ（ポイント）。 |
| slide | [ISlide](../../com.aspose.slides/islide) | Zoom フレームが参照する [ISlide](../../com.aspose.slides/islide)。このプレゼンテーションに属している必要があります。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 参照されたスライド [IPPImage](../../com.aspose.slides/ippimage) 用の画像。 |

**戻り値:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - 新しく作成された [IZoomFrame](../../com.aspose.slides/izoomframe)。

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

新しい Zoom フレームを作成し、指定されたインデックスに shape collection に挿入します。

--------------------

> ```
> この例は、コレクションの指定インデックスに Zoom オブジェクトを作成して挿入することを示しています
>  （"Presentation.pptx" プレゼンテーションに少なくとも 2 つのスライドがあると仮定します）:
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | Zoom フレームを挿入するゼロベース インデックス。 |
| x | float | 新しい Zoom フレームの x 座標（ポイント）。 |
| y | float | 新しい Zoom フレームの y 座標（ポイント）。 |
| width | float | 新しい Zoom フレームの幅（ポイント）。 |
| height | float | 新しい Zoom フレームの高さ（ポイント）。 |
| slide | [ISlide](../../com.aspose.slides/islide) | Zoom フレームが参照する [ISlide](../../com.aspose.slides/islide)。 |

**戻り値:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - 新しく作成された [IZoomFrame](../../com.aspose.slides/izoomframe)。

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

定義済み画像を使用した新しい Zoom フレームを作成し、指定されたインデックスに shape collection に挿入します。

--------------------

> ```
> この例は、コレクションの指定インデックスに Zoom オブジェクトを作成して挿入することを示しています
>  （"Presentation.pptx" プレゼンテーションに少なくとも 2 つのスライドがあると仮定します）:
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | Zoom フレームを挿入するゼロベース インデックス。 |
| x | float | 新しい Zoom フレームの x 座標（ポイント）。 |
| y | float | 新しい Zoom フレームの y 座標（ポイント）。 |
| width | float | 新しい Zoom フレームの幅（ポイント）。 |
| height | float | 新しい Zoom フレームの高さ（ポイント）。 |
| slide | [ISlide](../../com.aspose.slides/islide) | Zoom フレームが参照する [ISlide](../../com.aspose.slides/islide)。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 参照されたスライド [IPPImage](../../com.aspose.slides/ippimage) 用の画像。 |

**戻り値:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - 新しく作成された [IZoomFrame](../../com.aspose.slides/izoomframe)。

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

新しい Section Zoom フレームを作成し、shape collection の末尾に追加します。

--------------------

> ```
> この例は、コレクションの末尾に Section Zoom オブジェクトを追加することを示しています
>  (「Presentation.pptx」プレゼンテーションに少なくとも 2 つのセクションがあると仮定します):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しい Section Zoom フレームの x 座標（ポイント）。 |
| y | float | 新しい Section Zoom フレームの y 座標（ポイント）。 |
| width | float | 新しい Section Zoom フレームの幅（ポイント）。 |
| height | float | 新しい Section Zoom フレームの高さ（ポイント）。 |
| section | [ISection](../../com.aspose.slides/isection) | Section Zoom フレームが参照する [ISection](../../com.aspose.slides/isection)。このプレゼンテーションに属し、少なくとも 1 つのスライドを含む必要があります。 |

**戻り値:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 新しく作成された [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)。

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

定義済み画像を使用した新しい Section Zoom フレームを作成し、shape collection の末尾に追加します。

--------------------

> ```
> この例は、コレクションの末尾に Section Zoom オブジェクトを追加することを示しています
>  (「Presentation.pptx」プレゼンテーションに少なくとも 2 つのセクションがあると仮定します):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1), image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しい Section Zoom フレームの x 座標（ポイント）。 |
| y | float | 新しい Section Zoom フレームの y 座標（ポイント）。 |
| width | float | 新しい Section Zoom フレームの幅（ポイント）。 |
| height | float | 新しい Section Zoom フレームの高さ（ポイント）。 |
| section | [ISection](../../com.aspose.slides/isection) | Section Zoom フレームが参照する [ISection](../../com.aspose.slides/isection)。このプレゼンテーションに属し、少なくとも 1 つのスライドを含む必要があります。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Section Zoom フレーム内に表示する [IPPImage](../../com.aspose.slides/ippimage)。 |

**戻り値:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 新しく作成された [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)。

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

新しい Section Zoom フレームを作成し、指定されたインデックスに shape collection に挿入します。

--------------------

> ```
> この例は、コレクションの指定インデックスに Section Zoom オブジェクトを作成して挿入することを示しています
>  （「Presentation.pptx」プレゼンテーションに少なくとも 2 つのセクションがあると仮定します）:
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | Section Zoom フレームを挿入するゼロベース インデックス。 |
| x | float | 新しい Section Zoom フレームの x 座標（ポイント）。 |
| y | float | 新しい Section Zoom フレームの y 座標（ポイント）。 |
| width | float | 新しい Section Zoom フレームの幅（ポイント）。 |
| height | float | 新しい Section Zoom フレームの高さ（ポイント）。 |
| section | [ISection](../../com.aspose.slides/isection) | Section Zoom フレームが参照する [ISection](../../com.aspose.slides/isection)。このプレゼンテーションに属し、少なくとも 1 つのスライドを含む必要があります。 |

**戻り値:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 新しく作成された [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)。

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

定義済み画像を使用した新しい Section Zoom フレームを作成し、指定されたインデックスに shape collection に挿入します。

--------------------

> ```
> この例は、コレクションの指定インデックスに Section Zoom オブジェクトを作成して挿入することを示しています
>  (「Presentation.pptx」プレゼンテーションに少なくとも 2 つのセクションがあると仮定します):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | Section Zoom フレームを挿入するゼロベース インデックス。 |
| x | float | 新しい Section Zoom フレームの x 座標（ポイント）。 |
| y | float | 新しい Section Zoom フレームの y 座標（ポイント）。 |
| width | float | 新しい Section Zoom フレームの幅（ポイント）。 |
| height | float | 新しい Section Zoom フレームの高さ（ポイント）。 |
| section | [ISection](../../com.aspose.slides/isection) | Section Zoom フレームが参照する [ISection](../../com.aspose.slides/isection)。このプレゼンテーションに属し、少なくとも 1 つのスライドを含む必要があります。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Section Zoom フレーム内に表示する画像。 |

**戻り値:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 新しく作成された [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)。

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public abstract ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

新しい Summary Zoom フレームを作成し、shape collection の末尾に追加します。

--------------------

> ```
> この例は、コレクションの末尾に Summary Zoom オブジェクトを追加することを示しています
>  （「Presentation.pptx」プレゼンテーションに少なくとも 2 つのセクションがあると仮定します）:
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しい Summary Zoom フレームの x 座標（ポイント）。 |
| y | float | 新しい Summary Zoom フレームの y 座標（ポイント）。 |
| width | float | 新しい Summary Zoom フレームの幅（ポイント）。 |
| height | float | 新しい Summary Zoom フレームの高さ（ポイント）。 |

このメソッドは、プレゼンテーション内のすべてのセクションのサマリー リンクをまとめた Summary Zoom フレームを作成します。

**戻り値:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - 新しく作成された [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)。

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public abstract ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

新しい Summary Zoom フレームを作成し、指定されたインデックスに shape collection に挿入します。

--------------------

> ```
> この例は、コレクションの指定インデックスに Summary Zoom オブジェクトを作成して挿入することを示しています
>  （「Presentation.pptx」プレゼンテーションに少なくとも 2 つのセクションがあると仮定します）:
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | Summary Zoom フレームを挿入するゼロベース インデックス。 |
| x | float | 新しい Summary Zoom フレームの x 座標（ポイント）。 |
| y | float | 新しい Summary Zoom フレームの y 座標（ポイント）。 |
| width | float | 新しい Summary Zoom フレームの幅（ポイント）。 |
| height | float | 新しい Summary Zoom フレームの高さ（ポイント）。 |

このメソッドは、プレゼンテーション内のすべてのセクションのサマリー リンクをまとめた Summary Zoom フレームを作成します。

**戻り値:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - 新しく作成された [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)。

### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

新しい video フレームを作成し、shape collection の末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しい video フレームの x 座標（ポイント）。 |
| y | float | 新しい video フレームの y 座標（ポイント）。 |
| width | float | video フレームの幅（ポイント）。 |
| height | float | video フレームの高さ（ポイント）。 |
| fname | java.lang.String | 埋め込むビデオ ファイルのパスまたは名前。 |

**戻り値:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - 新しく作成された [IVideoFrame](../../com.aspose.slides/ivideoframe)。

### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

新しい video フレームを作成し、shape collection の末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しい video フレームの x 座標（ポイント）。 |
| y | float | 新しい video フレームの y 座標（ポイント）。 |
| width | float | video フレームの幅（ポイント）。 |
| height | float | video フレームの高さ（ポイント）。 |
| video | [IVideo](../../com.aspose.slides/ivideo) | video フレームに埋め込む [IVideo](../../com.aspose.slides/ivideo)。 |

**戻り値:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - 新しく作成された [IVideoFrame](../../com.aspose.slides/ivideoframe)。

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

新しい video フレームを作成し、指定されたインデックスに shape collection に挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | video フレームを挿入するゼロベース インデックス。 |
| x | float | 新しい video フレームの x 座標（ポイント）。 |
| y | float | 新しい video フレームの y 座標（ポイント）。 |
| width | float | video フレームの幅（ポイント）。 |
| height | float | video フレームの高さ（ポイント）。 |
| fname | java.lang.String | 埋め込むビデオ ファイルのパスまたは名前。 |

**戻り値:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - 新しく作成された [IVideoFrame](../../com.aspose.slides/ivideoframe)。

### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public abstract IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

CD トラックにリンクされた新しい audio フレームを作成し、shape collection の末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しい audio フレームの x 座標（ポイント）。 |
| y | float | 新しい audio フレームの y 座標（ポイント）。 |
| width | float | audio フレームの幅（ポイント）。 |
| height | float | audio フレームの高さ（ポイント）。 |

**戻り値:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新しく作成された [IAudioFrame](../../com.aspose.slides/iaudioframe)。

### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public abstract IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

CD トラックにリンクされた新しい audio フレームを作成し、指定されたインデックスに shape collection に挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | audio フレームを挿入するゼロベース インデックス。 |
| x | float | 新しい audio フレームの x 座標（ポイント）。 |
| y | float | 新しい audio フレームの y 座標（ポイント）。 |
| width | float | audio フレームの幅（ポイント）。 |
| height | float | audio フレームの高さ（ポイント）。 |

**戻り値:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新しく作成された [IAudioFrame](../../com.aspose.slides/iaudioframe)。

### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

外部 audio ファイルにリンクされた新しい audio フレームを作成し、shape collection の末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しい audio フレームの x 座標（ポイント）。 |
| y | float | 新しい audio フレームの y 座標（ポイント）。 |
| width | float | audio フレームの幅（ポイント）。 |
| height | float | audio フレームの高さ（ポイント）。 |
| fname | java.lang.String | リンクする外部 audio ファイルのパスまたは名前。 |

**戻り値:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新しく作成された [IAudioFrame](../../com.aspose.slides/iaudioframe)。

### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

外部 audio ファイルにリンクされた新しい audio フレームを作成し、指定されたインデックスに shape collection に挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | audio フレームを挿入するゼロベース インデックス。 |
| x | float | 新しい audio フレームの x 座標（ポイント）。 |
| y | float | 新しい audio フレームの y 座標（ポイント）。 |
| width | float | audio フレームの幅（ポイント）。 |
| height | float | audio フレームの高さ（ポイント）。 |
| fname | java.lang.String | リンクする外部 audio ファイルのパスまたは名前。 |

**戻り値:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新しく作成された [IAudioFrame](../../com.aspose.slides/iaudioframe)。

### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

埋め込み WAV ファイルを持つ新しい audio フレームを作成し、shape collection の末尾に追加します。埋め込み audio は Presentation.Audios コレクションに追加されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しい audio フレームの x 座標（ポイント）。 |
| y | float | 新しい audio フレームの y 座標（ポイント）。 |
| width | float | audio フレームの幅（ポイント）。 |
| height | float | audio フレームの高さ（ポイント）。 |
| audio_stream | java.io.InputStream | 埋め込む WAV 音声データを含む入力ストリーム。 |

**戻り値:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新しく作成された [IAudioFrame](../../com.aspose.slides/iaudioframe)。

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

新しい audio フレームを作成し、Presentation.Audios リストの既存 audio オブジェクトを使用して shape collection の末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しい audio フレームの x 座標（ポイント）。 |
| y | float | 新しい audio フレームの y 座標（ポイント）。 |
| width | float | audio フレームの幅（ポイント）。 |
| height | float | audio フレームの高さ（ポイント）。 |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Presentation.Audios コレクションからの [IAudio](../../com.aspose.slides/iaudio) インスタンス。 |

**戻り値:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新しく作成された [IAudioFrame](../../com.aspose.slides/iaudioframe)。

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

埋め込み WAV ファイルを持つ新しい audio フレームを作成し、指定されたインデックスに shape collection に挿入します。埋め込み audio は Presentation.Audios コレクションに追加されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | audio フレームを挿入するゼロベース インデックス。 |
| x | float | 新しい audio フレームの x 座標（ポイント）。 |
| y | float | 新しい audio フレームの y 座標（ポイント）。 |
| width | float | audio フレームの幅（ポイント）。 |
| height | float | audio フレームの高さ（ポイント）。 |
| audio_stream | java.io.InputStream | 埋め込む WAV 音声データを含む入力ストリーム。 |

**戻り値:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新しく作成された [IAudioFrame](../../com.aspose.slides/iaudioframe)。

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

既存の audio オブジェクトを使用して、新しい audio フレームを作成し、指定されたインデックスに shape collection に挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | audio フレームを挿入するゼロベース インデックス。 |
| x | float | 新しい audio フレームの x 座標（ポイント）。 |
| y | float | 新しい audio フレームの y 座標（ポイント）。 |
| width | float | audio フレームの幅（ポイント）。 |
| height | float | audio フレームの高さ（ポイント）。 |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Presentation.Audios コレクションから埋め込む [IAudio](../../com.aspose.slides/iaudio) インスタンス。 |

**戻り値:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新しく作成された [IAudioFrame](../../com.aspose.slides/iaudioframe)。

### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public abstract int indexOf(IShape shape)
```

コレクション内で指定された shape の最初の出現のゼロベース インデックスを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | コレクション内で探す shape。 |

**戻り値:**
int - 見つかった場合は shape のゼロベース インデックス、見つからない場合は \\u20131。

### toArray() {#toArray--}
```
public abstract IShape[] toArray()
```

すべての shape を含む配列を作成して返します。

**戻り値:**
com.aspose.slides.IShape[] - [IShape](../../com.aspose.slides/ishape) オブジェクトの配列。

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IShape[] toArray(int startIndex, int count)
```

指定された範囲のすべての shape を含む配列を作成して返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| startIndex | int | 返す最初の shape のインデックス。 |
| count | int | 返す shape の数。 |

**戻り値:**
com.aspose.slides.IShape[] - [IShape](../../com.aspose.slides/ishape) オブジェクトの配列。

### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public abstract void reorder(int index, IShape shape)
```

指定された shape を shape collection 内の新しい位置に移動します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | shape を配置するゼロベース ターゲット インデックス。 |
| shape | [IShape](../../com.aspose.slides/ishape) | コレクション内で移動する [IShape](../../com.aspose.slides/ishape)。 |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public abstract void reorder(int index, IShape[] shapes)
```

指定された shapes を shape collection 内で移動し、指定されたインデックスから配置します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 最初に配置する shape のゼロベース ターゲット インデックス。続く shapes は提供された順序で配置されます。 |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | コレクション内で移動する 1 つ以上の [IShape](../../com.aspose.slides/ishape) インスタンス。 |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

デフォルトの書式設定を持つ新しい auto shape を作成し、shape collection の末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shapeType | int | 追加する auto shape の [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | shape のフレームの x 座標（ポイント）。 |
| y | float | shape のフレームの y 座標（ポイント）。 |
| width | float | shape のフレームの幅（ポイント）。 |
| height | float | shape のフレームの高さ（ポイント）。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 新しく作成された [IAutoShape](../../com.aspose.slides/iautoshape)。

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

デフォルト テンプレート 書式で初期化することも可能な新しい auto shape を作成し、shape collection の末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shapeType | int | 追加する auto shape の [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | shape のフレームの x 座標（ポイント）。 |
| y | float | shape のフレームの y 座標（ポイント）。 |
| width | float | shape のフレームの幅（ポイント）。 |
| height | float | shape のフレームの高さ（ポイント）。 |
| createFromTemplate | boolean | true の場合、デフォルト テンプレート スタイル（シンプル スタイル、中央揃えテキスト、空でない名前）を新しい shape に適用します。false の場合、すべてのプロパティがデフォルト値に設定された shape を作成します。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 新しく作成された [IAutoShape](../../com.aspose.slides/iautoshape)。

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public abstract IAutoShape addMathShape(float x, float y, float width, float height)
```

数式コンテンツをホストする新しい四角形 auto shape を作成し、shape collection の末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | shape のフレームの x 座標（ポイント）。 |
| y | float | shape のフレームの y 座標（ポイント）。 |
| width | float | shape のフレームの幅（ポイント）。 |
| height | float | shape のフレームの高さ（ポイント）。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 新しく作成された [IAutoShape](../../com.aspose.slides/iautoshape)。

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

デフォルト テンプレート 書式を適用し、新しい auto shape を指定されたインデックスに shape collection に挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 新しい auto shape を挿入するゼロベース インデックス。 |
| shapeType | int | 挿入する auto shape の [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | shape のフレームの x 座標（ポイント）。 |
| y | float | shape のフレームの y 座標（ポイント）。 |
| width | float | shape のフレームの幅（ポイント）。 |
| height | float | shape のフレームの高さ（ポイント）。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 新しく作成された [IAutoShape](../../com.aspose.slides/iautoshape)。

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

デフォルト テンプレート スタイルで初期化することも可能な新しい auto shape を指定されたインデックスに shape collection に挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | auto shape を挿入するゼロベース インデックス。 |
| shapeType | int | 挿入する auto shape の [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | shape のフレームの x 座標（ポイント）。 |
| y | float | shape のフレームの y 座標（ポイント）。 |
| width | float | shape のフレームの幅（ポイント）。 |
| height | float | shape のフレームの高さ（ポイント）。 |
| createFromTemplate | boolean | true の場合、デフォルト テンプレート スタイル（空でない名前、シンプル スタイル、中央揃えテキスト）を適用します。false の場合、すべてのプロパティがデフォルトに設定された shape を作成します。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 新しく作成された [IAutoShape](../../com.aspose.slides/iautoshape)。

### addGroupShape() {#addGroupShape--}
```
public abstract IGroupShape addGroupShape()
```

空の group shape を新しく作成し、shape collection の末尾に追加します。グループのフレームは追加された shape に合わせて自動的に調整されます。

**戻り値:**
[IGroupShape](../../com.aspose.slides/igroupshape) - 新しく作成された [IGroupShape](../../com.aspose.slides/igroupshape)。

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public abstract IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

指定された SVG 画像を個々の shape に変換し、新しい group shape を作成して、結果の group を shape collection の末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | ベクタ コンテンツを含む [ISvgImage](../../com.aspose.slides/isvgimage)。 |
| x | float | グループのフレームの x 座標（ポイント）。 |
| y | float | グループのフレームの y 座標（ポイント）。 |
| width | float | グループのフレームの幅（ポイント）。 |
| height | float | グループのフレームの高さ（ポイント）。 |

**戻り値:**
[IGroupShape](../../com.aspose.slides/igroupshape) - 新しく作成された [IGroupShape](../../com.aspose.slides/igroupshape)。

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public abstract IGroupShape insertGroupShape(int index)
```

空の group shape を新しく作成し、指定されたインデックスに shape collection に挿入します。グループのフレームは追加された shape に合わせて自動的に調整されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | グループ shape を挿入するゼロベース インデックス。 |

**戻り値:**
[IGroupShape](../../com.aspose.slides/igroupshape) - 新しく作成された [IGroupShape](../../com.aspose.slides/igroupshape)。

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

デフォルト テンプレート スタイルを持つ新しい connector shape を作成し、shape collection の末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shapeType | int | 追加する connector shape の [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | connector のフレームの x 座標（ポイント）。 |
| y | float | connector のフレームの y 座標（ポイント）。 |
| width | float | connector のフレームの幅（ポイント）。 |
| height | float | connector のフレームの高さ（ポイント）。 |

**戻り値:**
[IConnector](../../com.aspose.slides/iconnector) - 新しく作成された [IConnector](../../com.aspose.slides/iconnector)。

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public abstract IConnector addConnector(int shapeType, 
    ... 
```

新しい connector shape を作成し、デフォルト テンプレート スタイルを適用することも可能で、shape collection の末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shapeType | int | 作成する connector shape の [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | connector のフレームの x 座標（ポイント）。 |
| y | float | connector のフレームの y 座標（ポイント）。 |
| width | float | connector のフレームの幅（ポイント）。 |
| height | float | connector のフレームの高さ（ポイント）。 |
| createFromTemplate | boolean | true の場合、デフォルト テンプレート スタイル（空でない名前、シンプル スタイル）を適用します。false の場合、デフォルト プロパティ値で connector を作成します。 |

**戻り値:**
[IConnector](../../com.aspose.slides/iconnector) - 新しく作成された [IConnector](../../com.aspose.slides/iconnector)。

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

デフォルト テンプレート 書式を適用し、新しい connector shape を指定されたインデックスに shape collection に挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | connector shape を挿入するゼロベース インデックス。 |
| shapeType | int | 挿入する connector shape の [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | connector のフレームの x 座標（ポイント）。 |
| y | float | connector のフレームの y 座標（ポイント）。 |
| width | float | connector のフレームの幅（ポイント）。 |
| height | float | connector のフレームの高さ（ポイント）。 |

**戻り値:**
[IConnector](../../com.aspose.slides/iconnector) - 新しく作成された [IConnector](../../com.aspose.slides/iconnector)。

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public abstract IConnector addConnector(int shapeType, 
    ... 
```

デフォルト テンプレート スタイルを適用することも可能な新しい connector shape を指定されたインデックスに shape collection に挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | connector shape を挿入するゼロベース インデックス。 |
| shapeType | int | 挿入する connector shape の [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | connector のフレームの x 座標（ポイント）。 |
| y | float | connector のフレームの y 座標（ポイント）。 |
| width | float | connector のフレームの幅（ポイント）。 |
| height | float | connector のフレームの高さ（ポイント）。 |
| createFromTemplate | boolean | true の場合、デフォルト テンプレート スタイル（空でない名前、シンプル スタイル）を適用します。false の場合、デフォルト プロパティ値で connector を作成します。 |

**戻り値:**
[IConnector](../../com.aspose.slides/iconnector) - 新しく作成された [IConnector](../../com.aspose.slides/iconnector)。

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

指定された画像を含む新しい picture frame を作成し、shape collection の末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) に含まれる shape タイプを指定（線系は除く）：ShapeType.Line, ShapeType.StraightConnector1, ... |
| x | float | picture frame の x 座標（ポイント）。 |
| y | float | picture frame の y 座標（ポイント）。 |
| width | float | picture frame の幅（ポイント）。 |
| height | float | picture frame の高さ（ポイント）。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | picture frame に表示する [IPPImage](../../com.aspose.slides/ippimage)。 |

**戻り値:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - 新しく作成された [IPictureFrame](../../com.aspose.slides/ipictureframe)。

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

指定された画像を含む新しい picture frame を作成し、指定されたインデックスに shape collection に挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | picture frame を挿入するゼロベース インデックス。 |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) に含まれる shape タイプを指定（線系は除く）：ShapeType.Line, ShapeType.StraightConnector1, ... |
| x | float | picture frame の x 座標（ポイント）。 |
| y | float | picture frame の y 座標（ポイント）。 |
| width | float | picture frame の幅（ポイント）。 |
| height | float | picture frame の高さ（ポイント）。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | picture frame に表示する [IPPImage](../../com.aspose.slides/ippimage)。 |

**戻り値:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - 新しく作成された [IPictureFrame](../../com.aspose.slides/ipictureframe)。

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public abstract ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

新しい table を作成し、shape collection の末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | table の x 座標（ポイント）。 |
| y | float | table の y 座標（ポイント）。 |
| columnWidths | double[] | table の列幅をポイントで表す double 配列。 |
| rowHeights | double[] | table の行高をポイントで表す double 配列。 |

**戻り値:**
[ITable](../../com.aspose.slides/itable) - 新しく作成された [ITable](../../com.aspose.slides/itable)。

### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public abstract ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

新しい table を作成し、指定されたインデックスに shape collection に挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | table を挿入するゼロベース インデックス。 |
| x | float | table の x 座標（ポイント）。 |
| y | float | table の y 座標（ポイント）。 |
| columnWidths | double[] | table の列幅をポイントで表す double 配列。 |
| rowHeights | double[] | table の行高をポイントで表す double 配列。 |

**戻り値:**
[ITable](../../com.aspose.slides/itable) - 新しく作成された [ITable](../../com.aspose.slides/itable)。

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

指定されたインデックスの shape を shape collection から削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除する shape のゼロベース インデックス。 |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public abstract void remove(IShape shape)
```

指定された shape の最初の出現を shape collection から削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | 削除する [IShape](../../com.aspose.slides/ishape)。 |

### clear() {#clear--}
```
public abstract void clear()
```

shape collection からすべての shape を削除します。

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

指定された shape のコピーを作成し、shape collection の末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | コピーする shape。 |
| x | float | コピーした shape のフレームの x 座標（ポイント）。 |
| y | float | コピーした shape のフレームの y 座標（ポイント）。 |
| width | float | コピーした shape のフレームの幅（ポイント）。 |
| height | float | コピーした shape のフレームの高さ（ポイント）。 |

**戻り値:**
[IShape](../../com.aspose.slides/ishape) - 新しく作成された [IShape](../../com.aspose.slides/ishape)。

### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y)
```

コピーした shape の幅と高さを保持したまま、指定された shape のコピーを作成し、shape collection の末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | コピーする [IShape](../../com.aspose.slides/ishape)。 |
| x | float | コピーした shape のフレームの x 座標（ポイント）。 |
| y | float | コピーした shape のフレームの y 座標（ポイント）。 |

**戻り値:**
[IShape](../../com.aspose.slides/ishape) - 新しく作成された [IShape](../../com.aspose.slides/ishape)。

### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public abstract IShape addClone(IShape sourceShape)
```

指定された shape のコピーを作成し、shape collection の末尾に追加します。コピーされた shape は元の位置とサイズを保持します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | コピーする [IShape](../../com.aspose.slides/ishape)。 |

**戻り値:**
[IShape](../../com.aspose.slides/ishape) - 新しく作成された [IShape](../../com.aspose.slides/ishape)。

### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

指定された shape のコピーを作成し、指定されたインデックスに shape collection に挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | コピーした shape を挿入するゼロベース インデックス。 |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | コピーする [IShape](../../com.aspose.slides/ishape)。 |
| x | float | コピーした shape のフレームの x 座標（ポイント）。 |
| y | float | コピーした shape のフレームの y 座標（ポイント）。 |
| width | float | コピーした shape のフレームの幅（ポイント）。 |
| height | float | コピーした shape のフレームの高さ（ポイント）。 |

**戻り値:**
[IShape](../../com.aspose.slides/ishape) - 新しく作成された [IShape](../../com.aspose.slides/ishape)。

### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y)
```

指定された shape のコピーを作成し、指定されたインデックスに shape collection に挿入します。コピーした shape は元の幅と高さを保持します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | コピーした shape を挿入するゼロベース インデックス。 |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | コピーする [IShape](../../com.aspose.slides/ishape)。 |
| x | float | コピーした shape のフレームの x 座標（ポイント）。 |
| y | float | コピーした shape のフレームの y 座標（ポイント）。 |

**戻り値:**
[IShape](../../com.aspose.slides/ishape) - 新しく作成された [IShape](../../com.aspose.slides/ishape)。

### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public abstract IShape insertClone(int index, IShape sourceShape)
```

指定された shape のコピーを作成し、指定されたインデックスに shape collection に挿入します。コピーされた shape は元の位置とサイズを保持します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | コピーした shape を挿入するゼロベース インデックス。 |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | コピーする [IShape](../../com.aspose.slides/ishape)。 |

**戻り値:**
[IShape](../../com.aspose.slides/ishape) - 新しく作成された [IShape](../../com.aspose.slides/ishape)。