---
title: IShapeCollection
second_title: Aspose.Slides for Java API リファレンス
description: 図形のコレクションを表します。
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
| [getParentGroup()](#getParentGroup--) | シェイプ コレクションの親グループ シェイプ オブジェクトを取得します。 |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | 新しいチャートを作成し、サンプル系列データと設定で初期化し、シェイプ コレクションの末尾に追加します。 |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | 新しいチャートを作成し、サンプル系列データと設定で初期化し、シェイプ コレクションの末尾に追加します。 |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | SmartArt 図を作成し、シェイプ コレクションの末尾に追加します。 |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | 新しいチャートを作成し、サンプル系列データと設定で初期化し、シェイプ コレクションの指定されたインデックスに挿入します。 |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | 新しいチャートを作成し、サンプル系列データと設定で初期化し、シェイプ コレクションの指定されたインデックスに挿入します。 |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | 新しい OLE オブジェクト フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | 新しい OLE オブジェクト フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | 新しい OLE オブジェクト フレームを作成し、シェイプ コレクションの指定されたインデックスに挿入します。 |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | 新しい OLE オブジェクト フレームを作成し、シェイプ コレクションの指定されたインデックスに挿入します。 |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | 新しい Zoom フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | 新しい Zoom フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | 新しい Zoom フレームを作成し、シェイプ コレクションの指定されたインデックスに挿入します。 |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | 事前定義された画像を使用した新しい Zoom フレームを作成し、シェイプ コレクションの指定されたインデックスに挿入します。 |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | 新しい Section Zoom フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | 事前定義された画像を使用した新しい Section Zoom フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | 新しい Section Zoom フレームを作成し、シェイプ コレクションの指定されたインデックスに挿入します。 |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | 事前定義された画像を使用した新しい Section Zoom フレームを作成し、シェイプ コレクションの指定されたインデックスに挿入します。 |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | 新しい Summary Zoom フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | 新しい Summary Zoom フレームを作成し、シェイプ コレクションの指定されたインデックスに挿入します。 |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | 新しいビデオ フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | 新しいビデオ フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | 新しいビデオ フレームを作成し、シェイプ コレクションの指定されたインデックスに挿入します。 |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | CD トラックにリンクされた新しいオーディオ フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | CD トラックにリンクされた新しいオーディオ フレームを作成し、シェイプ コレクションの指定されたインデックスに挿入します。 |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | 外部オーディオ ファイルにリンクされた新しいオーディオ フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | 外部オーディオ ファイルにリンクされた新しいオーディオ フレームを作成し、シェイプ コレクションの指定されたインデックスに挿入します。 |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | 埋め込み WAV ファイルを持つ新しいオーディオ フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Presentation.Audios リストの既存オーディオ オブジェクトを使用して、新しいオーディオ フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | 埋め込み WAV ファイルを持つ新しいオーディオ フレームを作成し、シェイプ コレクションの指定されたインデックスに挿入します。 |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Presentation.Audios リストの既存オーディオ オブジェクトを使用して、新しいオーディオ フレームを作成し、シェイプ コレクションの指定されたインデックスに挿入します。 |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | 指定されたシェイプがコレクション内で最初に出現するゼロベースインデックスを返します。 |
| [toArray()](#toArray--) | すべてのシェイプを含む配列を作成し、返します。 |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 指定された範囲のすべてのシェイプを含む配列を作成し、返します。 |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | 指定されたシェイプをシェイプ コレクション内の新しい位置に移動します。 |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | 指定されたシェイプをシェイプ コレクション内で移動し、指定されたインデックスから配置します。 |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | デフォルトの書式設定で新しいオート シェイプを作成し、シェイプ コレクションの末尾に追加します。 |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | 新しいオート シェイプを作成し、シェイプ コレクションの末尾に追加します。オプションでデフォルト テンプレート書式で初期化できます。 |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | 数式コンテンツをホストする新しい矩形オート シェイプを作成し、シェイプ コレクションの末尾に追加します。 |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | 新しいオート シェイプを作成し、デフォルト テンプレート書式を適用して、シェイプ コレクションの指定されたインデックスに挿入します。 |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | 新しいオート シェイプを作成し、オプションでデフォルト テンプレートスタイルで初期化し、シェイプ コレクションの指定されたインデックスに挿入します。 |
| [addGroupShape()](#addGroupShape--) | 空のグループ シェイプを新しく作成し、シェイプ コレクションの末尾に追加します。 |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | 新しいグループ シェイプを作成し、指定された SVG 画像を個別のシェイプに変換し、結果のグループをシェイプ コレクションの末尾に追加します。 |
| [insertGroupShape(int index)](#insertGroupShape-int-) | 空のグループ シェイプを新しく作成し、シェイプ コレクションの指定されたインデックスに挿入します。 |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | デフォルト テンプレートスタイルの新しいコネクタ シェイプを作成し、シェイプ コレクションの末尾に追加します。 |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | 新しいコネクタ シェイプを作成し、オプションでデフォルト テンプレートスタイルを適用し、シェイプ コレクションの末尾に追加します。 |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | 新しいコネクタ シェイプを作成し、デフォルト テンプレートスタイルを適用して、シェイプ コレクションの指定されたインデックスに挿入します。 |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | 新しいコネクタ シェイプを作成し、オプションでデフォルト テンプレートスタイルを適用し、シェイプ コレクションの指定されたインデックスに挿入します。 |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | 指定された画像を含む新しい画像フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | 指定された画像を含む新しい画像フレームを作成し、シェイプ コレクションの指定されたインデックスに挿入します。 |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | 新しいテーブルを作成し、シェイプ コレクションの末尾に追加します。 |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | 新しいテーブルを作成し、シェイプ コレクションの指定されたインデックスに挿入します。 |
| [removeAt(int index)](#removeAt-int-) | 指定されたインデックスのシェイプをシェイプ コレクションから削除します。 |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | 指定されたシェイプの最初の出現をシェイプ コレクションから削除します。 |
| [clear()](#clear--) | シェイプ コレクションからすべてのシェイプを削除します。 |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | 指定されたシェイプのコピーを作成し、シェイプ コレクションの末尾に追加します。 |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | 指定されたシェイプのコピーを作成し、シェイプ コレクションの末尾に追加します。 |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | 指定されたシェイプのコピーを作成し、シェイプ コレクションの末尾に追加します。 |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | 指定されたシェイプのコピーを作成し、シェイプ コレクションの指定されたインデックスに挿入します。 |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | 指定されたシェイプのコピーを作成し、シェイプ コレクションの指定されたインデックスに挿入します。 |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | 指定されたシェイプのコピーを作成し、シェイプ コレクションの指定されたインデックスに挿入します。 |

### get_Item(int index) {#get-Item-int-}
```
public abstract IShape get_Item(int index)
```

指定されたインデックスの要素を取得します。読み取り専用 [IShape](../../com.aspose.slides/ishape)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IShape](../../com.aspose.slides/ishape)

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

シェイプ コレクションの親グループ シェイプ オブジェクトを取得します。読み取り専用 [IGroupShape](../../com.aspose.slides/igroupshape)。

**戻り値:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height)
```

新しいチャートを作成し、サンプル系列データと設定で初期化し、シェイプ コレクションの末尾に追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| type | int | 追加するチャートのタイプ。 |
| x | float | 新しいチャートの X 座標（ポイント単位）。 |
| y | float | 新しいチャートの Y 座標（ポイント単位）。 |
| width | float | チャートの幅（ポイント単位）。 |
| height | float | チャートの高さ（ポイント単位）。 |

**戻り値:**
[IChart](../../com.aspose.slides/ichart) - The newly created [IChart](../../com.aspose.slides/ichart).

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

新しいチャートを作成し、サンプル系列データと設定で初期化し、シェイプ コレクションの末尾に追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| type | int | 追加するチャートのタイプ。 |
| x | float | 新しいチャートの X 座標（ポイント単位）。 |
| y | float | 新しいチャートの Y 座標（ポイント単位）。 |
| width | float | チャートの幅（ポイント単位）。 |
| height | float | チャートの高さ（ポイント単位）。 |
| initWithSample | boolean | true の場合、サンプル系列データと設定で初期化します。false の場合、系列なしで最小設定のみで作成し、作成が速くなります。 |

**戻り値:**
[IChart](../../com.aspose.slides/ichart) - The newly created [IChart](../../com.aspose.slides/ichart).

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public abstract ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

SmartArt 図を作成し、シェイプ コレクションの末尾に追加します。

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

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | 図のフレームの X 座標（ポイント単位）。 |
| y | float | 図のフレームの Y 座標（ポイント単位）。 |
| width | float | 図のフレームの幅（ポイント単位）。 |
| height | float | 図のフレームの高さ（ポイント単位）。 |
| layoutType | int | SmartArt のレイアウト タイプ。 |

**戻り値:**
[ISmartArt](../../com.aspose.slides/ismartart) - The newly created [ISmartArt](../../com.aspose.slides/ismartart).

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index)
```

新しいチャートを作成し、サンプル系列データと設定で初期化し、シェイプ コレクションの指定されたインデックスに挿入します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| type | int | 作成するチャートのタイプ。 |
| x | float | 新しいチャートの X 座標（ポイント単位）。 |
| y | float | 新しいチャートの Y 座標（ポイント単位）。 |
| width | float | 新しいチャートの幅（ポイント単位）。 |
| height | float | 新しいチャートの高さ（ポイント単位）。 |
| index | int | シェイプ コレクションに新しいチャートを挿入する zero-based インデックス。 |

**戻り値:**
[IChart](../../com.aspose.slides/ichart) - The newly created [IChart](../../com.aspose.slides/ichart).

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

新しいチャートを作成し、サンプル系列データと設定で初期化し、シェイプ コレクションの指定されたインデックスに挿入します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| type | int | 作成するチャートのタイプ。 |
| x | float | 新しいチャートの X 座標（ポイント単位）。 |
| y | float | 新しいチャートの Y 座標（ポイント単位）。 |
| width | float | 新しいチャートの幅（ポイント単位）。 |
| height | float | 新しいチャートの高さ（ポイント単位）。 |
| index | int | シェイプ コレクションに新しいチャートを挿入する zero-based インデックス。 |
| initWithSample | boolean | true の場合、サンプル系列データと設定で初期化します。false の場合、系列なしで最小設定のみで作成し、作成が速くなります。 |
| initWithSample | boolean | true の場合、新しいチャートをサンプルシリーズデータと設定で初期化します。false の場合、シリーズなしで最小限の設定だけでチャートを作成し、作成が速くなります。 |
**戻り値:**  
[IChart](../../com.aspose.slides/ichart) - 新しく作成された [IChart](../../com.aspose.slides/ichart).

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

新しい OLE オブジェクト フレームを作成し、シェイプ コレクションの末尾に追加します。

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しい OLE フレームの x 座標（ポイント単位）。 |
| y | float | 新しい OLE フレームの y 座標（ポイント単位）。 |
| width | float | 新しい OLE フレームの幅（ポイント単位）。 |
| height | float | 新しい OLE フレームの高さ（ポイント単位）。 |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | 埋め込み OLE データ情報（[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)）。 |

**戻り値:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 新しく作成された [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

新しい OLE オブジェクト フレームを作成し、シェイプ コレクションの末尾に追加します。

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しい OLE フレームの x 座標（ポイント単位）。 |
| y | float | 新しい OLE フレームの y 座標（ポイント単位）。 |
| width | float | 新しい OLE フレームの幅（ポイント単位）。 |
| height | float | 新しい OLE フレームの高さ（ポイント単位）。 |
| className | java.lang.String | OLE オブジェクトのクラス名。 |
| path | java.lang.String | リンクされたファイルへのパス。  

このパスはプレゼンテーションにそのまま保存されます。相対パスが指定された場合、別のディレクトリからプレゼンテーションを開くとファイルにアクセスできなくなります。 |

**戻り値:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 新しく作成された [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

新しい OLE オブジェクト フレームを作成し、指定したインデックスにシェイプ コレクションに挿入します。

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | OLE オブジェクト フレームを挿入するゼロベースのインデックス。 |
| x | float | 新しい OLE フレームの x 座標（ポイント単位）。 |
| y | float | 新しい OLE フレームの y 座標（ポイント単位）。 |
| width | float | 新しい OLE フレームの幅（ポイント単位）。 |
| height | float | 新しい OLE フレームの高さ（ポイント単位）。 |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | 埋め込み OLE データ情報（[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)）。 |

**戻り値:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 新しく作成された [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

新しい OLE オブジェクト フレームを作成し、指定したインデックスにシェイプ コレクションに挿入します。

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | OLE オブジェクト フレームを挿入するゼロベースのインデックス。 |
| x | float | 新しい OLE フレームの x 座標（ポイント単位）。 |
| y | float | 新しい OLE フレームの y 座標（ポイント単位）。 |
| width | float | 新しい OLE フレームの幅（ポイント単位）。 |
| height | float | 新しい OLE フレームの高さ（ポイント単位）。 |
| className | java.lang.String | OLE オブジェクトのクラス名。 |
| path | java.lang.String | リンクされたファイルへのパス。  

このパスはプレゼンテーションにそのまま保存されます。相対パスが指定された場合、別のディレクトリからプレゼンテーションを開くとファイルにアクセスできなくなります。 |

**戻り値:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 新しく作成された [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

新しいズーム フレームを作成し、シェイプ コレクションの末尾に追加します。

--------------------

> ```
> This example demonstrates adding a Zoom object to the end of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいズーム フレームの x 座標（ポイント単位）。 |
| y | float | 新しいズーム フレームの y 座標（ポイント単位）。 |
| width | float | 新しいズーム フレームの幅（ポイント単位）。 |
| height | float | 新しいズーム フレームの高さ（ポイント単位）。 |
| slide | [ISlide](../../com.aspose.slides/islide) | ズーム フレームが参照する [ISlide](../../com.aspose.slides/islide)。このプレゼンテーションに属している必要があります。 |

**戻り値:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - 新しく作成された [IZoomFrame](../../com.aspose.slides/izoomframe).

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

新しいズーム フレームを作成し、シェイプ コレクションの末尾に追加します。

--------------------

> ```
> This example demonstrates adding a Zoom object to the end of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいズーム フレームの x 座標（ポイント単位）。 |
| y | float | 新しいズーム フレームの y 座標（ポイント単位）。 |
| width | float | 新しいズーム フレームの幅（ポイント単位）。 |
| height | float | 新しいズーム フレームの高さ（ポイント単位）。 |
| slide | [ISlide](../../com.aspose.slides/islide) | ズーム フレームが参照する [ISlide](../../com.aspose.slides/islide)。このプレゼンテーションに属している必要があります。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 参照されたスライド [IPPImage](../../com.aspose.slides/ippimage) の画像。 |

**戻り値:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - 新しく作成された [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

新しいズーム フレームを作成し、指定したインデックスにシェイプ コレクションに挿入します。

--------------------

> ```
> この例は、コレクションの指定したインデックスに Zoom オブジェクトを作成および挿入する方法を示しています
>  (「Presentation.pptx」プレゼンテーションに少なくとも 2 枚のスライドがあると仮定します):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | ズーム フレームを挿入するゼロベースのインデックス。 |
| x | float | 新しいズーム フレームの x 座標（ポイント単位）。 |
| y | float | 新しいズーム フレームの y 座標（ポイント単位）。 |
| width | float | 新しいズーム フレームの幅（ポイント単位）。 |
| height | float | 新しいズーム フレームの高さ（ポイント単位）。 |
| slide | [ISlide](../../com.aspose.slides/islide) | ズーム フレームが参照する [ISlide](../../com.aspose.slides/islide)。 |

**戻り値:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - 新しく作成された [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

既定の画像を持つ新しいズーム フレームを作成し、指定したインデックスにシェイプ コレクションに挿入します。

--------------------

> ```
> This example demonstrates creation and inserting a Zoom object at the specified index of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | ズーム フレームを挿入するゼロベースのインデックス。 |
| x | float | 新しいズーム フレームの x 座標（ポイント単位）。 |
| y | float | 新しいズーム フレームの y 座標（ポイント単位）。 |
| width | float | 新しいズーム フレームの幅（ポイント単位）。 |
| height | float | 新しいズーム フレームの高さ（ポイント単位）。 |
| slide | [ISlide](../../com.aspose.slides/islide) | ズーム フレームが参照する [ISlide](../../com.aspose.slides/islide)。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 参照されたスライド [IPPImage](../../com.aspose.slides/ippimage) の画像。 |

**戻り値:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - 新しく作成された [IZoomFrame](../../com.aspose.slides/izoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

新しいセクション ズーム フレームを作成し、シェイプ コレクションの末尾に追加します。

--------------------

> ```
> This example demonstrates adding a Section Zoom object to the end of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいセクション ズーム フレームの x 座標（ポイント単位）。 |
| y | float | 新しいセクション ズーム フレームの y 座標（ポイント単位）。 |
| width | float | 新しいセクション ズーム フレームの幅（ポイント単位）。 |
| height | float | 新しいセクション ズーム フレームの高さ（ポイント単位）。 |
| section | [ISection](../../com.aspose.slides/isection) | セクション ズーム フレームが参照する [ISection](../../com.aspose.slides/isection)。このプレゼンテーションに属し、少なくとも1枚のスライドを含んでいる必要があります。 |

**戻り値:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 新しく作成された [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

既定の画像を持つ新しいセクション ズーム フレームを作成し、シェイプ コレクションの末尾に追加します。

--------------------

> ```
> この例は、コレクションの末尾に Section Zoom オブジェクトを追加する方法を示しています
>  （「Presentation.pptx」プレゼンテーションに少なくとも 2 つのセクションがあると想定します）:
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいセクション ズーム フレームの x 座標（ポイント単位）。 |
| y | float | 新しいセクション ズーム フレームの y 座標（ポイント単位）。 |
| width | float | 新しいセクション ズーム フレームの幅（ポイント単位）。 |
| height | float | 新しいセクション ズーム フレームの高さ（ポイント単位）。 |
| section | [ISection](../../com.aspose.slides/isection) | セクション ズーム フレームが参照する [ISection](../../com.aspose.slides/isection)。このプレゼンテーションに属し、少なくとも1枚のスライドを含んでいる必要があります。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | セクション ズーム フレーム内に表示する [IPPImage](../../com.aspose.slides/ippimage)。 |

**戻り値:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 新しく作成された [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

新しいセクション ズーム フレームを作成し、指定したインデックスにシェイプ コレクションに挿入します。

--------------------

> ```
> この例は、コレクションの指定したインデックスに Section Zoom オブジェクトを作成および挿入する方法を示しています
>  (「Presentation.pptx」プレゼンテーションに少なくとも 2 つのセクションがあると想定します):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | セクション ズーム フレームを挿入するゼロベースのインデックス。 |
| x | float | 新しいセクション ズーム フレームの x 座標（ポイント単位）。 |
| y | float | 新しいセクション ズーム フレームの y 座標（ポイント単位）。 |
| width | float | 新しいセクション ズーム フレームの幅（ポイント単位）。 |
| height | float | 新しいセクション ズーム フレームの高さ（ポイント単位）。 |
| section | [ISection](../../com.aspose.slides/isection) | セクション ズーム フレームが参照する [ISection](../../com.aspose.slides/isection)。このプレゼンテーションに属し、少なくとも1枚のスライドを含んでいる必要があります。 |

**戻り値:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 新しく作成された [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

既定の画像を持つ新しいセクション ズーム フレームを作成し、指定したインデックスにシェイプ コレクションに挿入します。

--------------------

> ```
> この例は、コレクションの指定したインデックスに Section Zoom オブジェクトを作成および挿入する方法を示しています
>  （「Presentation.pptx」プレゼンテーションに少なくとも 2 つのセクションがあると想定します）:
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | セクション ズーム フレームを挿入するゼロベースのインデックス。 |
| x | float | 新しいセクション ズーム フレームの x 座標（ポイント単位）。 |
| y | float | 新しいセクション ズーム フレームの y 座標（ポイント単位）。 |
| width | float | 新しいセクション ズーム フレームの幅（ポイント単位）。 |
| height | float | 新しいセクション ズーム フレームの高さ（ポイント単位）。 |
| section | [ISection](../../com.aspose.slides/isection) | セクション ズーム フレームが参照する [ISection](../../com.aspose.slides/isection)。このプレゼンテーションに属し、少なくとも1枚のスライドを含んでいる必要があります。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | セクション ズーム フレーム内に表示する画像。 |

**戻り値:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 新しく作成された [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public abstract ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

新しいサマリー ズーム フレームを作成し、シェイプ コレクションの末尾に追加します。

--------------------

> ```
> This example demonstrates adding a Summary Zoom object to the end of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいサマリー ズーム フレームの x 座標（ポイント単位）。 |
| y | float | 新しいサマリー ズーム フレームの y 座標（ポイント単位）。 |
| width | float | 新しいサマリー ズーム フレームの幅（ポイント単位）。 |
| height | float | 新しいサマリー ズーム フレームの高さ（ポイント単位）。 |
このメソッドは、プレゼンテーション内のすべてのセクションのサマリーリンクを集約するサマリーズームフレームを作成します。 |

**戻り値:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - 新しく作成された [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).
### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public abstract ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

新しい Summary Zoom フレームを作成し、指定されたインデックスで shape コレクションに挿入します。

--------------------

> ```
> This example demonstrates creation and inserting a Summary Zoom object at the specified index of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
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
| index | int | Summary Zoom フレームを挿入するゼロベースのインデックス。 |
| x | float | 新しい Summary Zoom フレームの X 座標（ポイント単位）。 |
| y | float | 新しい Summary Zoom フレームの Y 座標（ポイント単位）。 |
| width | float | 新しい Summary Zoom フレームの幅（ポイント単位）。 |
| height | float | 新しい Summary Zoom フレームの高さ（ポイント単位）。 |

--------------------

このメソッドは、プレゼンテーション内のすべてのセクションのサマリーリンクを集約するサマリーズームフレームを作成します。 |

**戻り値:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - 新しく作成された [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).
### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

新しいビデオフレームを作成し、shape コレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいビデオフレームの X 座標（ポイント単位）。 |
| y | float | 新しいビデオフレームの Y 座標（ポイント単位）。 |
| width | float | 新しいビデオフレームの幅（ポイント単位）。 |
| height | float | 新しいビデオフレームの高さ（ポイント単位）。 |
| fname | java.lang.String | 埋め込むビデオファイルのパスまたは名前。 |

**戻り値:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - 新しく作成された [IVideoFrame](../../com.aspose.slides/ivideoframe).
### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

新しいビデオフレームを作成し、shape コレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいビデオフレームの X 座標（ポイント単位）。 |
| y | float | 新しいビデオフレームの Y 座標（ポイント単位）。 |
| width | float | 新しいビデオフレームの幅（ポイント単位）。 |
| height | float | 新しいビデオフレームの高さ（ポイント単位）。 |
| video | [IVideo](../../com.aspose.slides/ivideo) | ビデオフレームに埋め込む [IVideo](../../com.aspose.slides/ivideo)。 |

**戻り値:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - 新しく作成された [IVideoFrame](../../com.aspose.slides/ivideoframe).
### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

新しいビデオフレームを作成し、指定されたインデックスで shape コレクションに挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | ビデオフレームを挿入するゼロベースのインデックス。 |
| x | float | 新しいビデオフレームの X 座標（ポイント単位）。 |
| y | float | 新しいビデオフレームの Y 座標（ポイント単位）。 |
| width | float | 新しいビデオフレームの幅（ポイント単位）。 |
| height | float | 新しいビデオフレームの高さ（ポイント単位）。 |
| fname | java.lang.String | 埋め込むビデオファイルのパスまたは名前。 |

**戻り値:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - 新しく作成された [IVideoFrame](../../com.aspose.slides/ivideoframe).
### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public abstract IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

CD トラックにリンクされた新しいオーディオフレームを作成し、shape コレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいオーディオフレームの X 座標（ポイント単位）。 |
| y | float | 新しいオーディオフレームの Y 座標（ポイント単位）。 |
| width | float | 新しいオーディオフレームの幅（ポイント単位）。 |
| height | float | 新しいオーディオフレームの高さ（ポイント単位）。 |

**戻り値:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新しく作成された [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public abstract IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

CD トラックにリンクされた新しいオーディオフレームを作成し、指定されたインデックスで shape コレクションに挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | オーディオフレームを挿入するゼロベースのインデックス。 |
| x | float | 新しいオーディオフレームの X 座標（ポイント単位）。 |
| y | float | 新しいオーディオフレームの Y 座標（ポイント単位）。 |
| width | float | 新しいオーディオフレームの幅（ポイント単位）。 |
| height | float | 新しいオーディオフレームの高さ（ポイント単位）。 |

**戻り値:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新しく作成された [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

外部オーディオファイルにリンクされた新しいオーディオフレームを作成し、shape コレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいオーディオフレームの X 座標（ポイント単位）。 |
| y | float | 新しいオーディオフレームの Y 座標（ポイント単位）。 |
| width | float | 新しいオーディオフレームの幅（ポイント単位）。 |
| height | float | 新しいオーディオフレームの高さ（ポイント単位）。 |
| fname | java.lang.String | リンクする外部オーディオファイルのパスまたは名前。 |

**戻り値:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新しく作成された [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

外部オーディオファイルにリンクされた新しいオーディオフレームを作成し、指定されたインデックスで shape コレクションに挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | オーディオフレームを挿入するゼロベースのインデックス。 |
| x | float | 新しいオーディオフレームの X 座標（ポイント単位）。 |
| y | float | 新しいオーディオフレームの Y 座標（ポイント単位）。 |
| width | float | 新しいオーディオフレームの幅（ポイント単位）。 |
| height | float | 新しいオーディオフレームの高さ（ポイント単位）。 |
| fname | java.lang.String | リンクする外部オーディオファイルのパスまたは名前。 |

**戻り値:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新しく作成された [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

埋め込み WAV ファイルを持つ新しいオーディオフレームを作成し、shape コレクションの末尾に追加します。埋め込みオーディオは Presentation.Audios コレクションに追加されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいオーディオフレームの X 座標（ポイント単位）。 |
| y | float | 新しいオーディオフレームの Y 座標（ポイント単位）。 |
| width | float | 新しいオーディオフレームの幅（ポイント単位）。 |
| height | float | 新しいオーディオフレームの高さ（ポイント単位）。 |
| audio_stream | java.io.InputStream | 埋め込む WAV オーディオデータを含む入力ストリーム。 |

**戻り値:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新しく作成された [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

既存の Presentation.Audios リストからオーディオ オブジェクトを使用して、新しいオーディオフレームを作成し、shape コレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいオーディオフレームの X 座標（ポイント単位）。 |
| y | float | 新しいオーディオフレームの Y 座標（ポイント単位）。 |
| width | float | 新しいオーディオフレームの幅（ポイント単位）。 |
| height | float | 新しいオーディオフレームの高さ（ポイント単位）。 |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Presentation.Audios コレクションからの [IAudio](../../com.aspose.slides/iaudio) インスタンス。 |

**戻り値:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新しく作成された [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

埋め込み WAV ファイルを持つ新しいオーディオフレームを作成し、指定されたインデックスで shape コレクションに挿入します。埋め込みオーディオは Presentation.Audios コレクションに追加されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | オーディオフレームを挿入するゼロベースのインデックス。 |
| x | float | 新しいオーディオフレームの X 座標（ポイント単位）。 |
| y | float | 新しいオーディオフレームの Y 座標（ポイント単位）。 |
| width | float | 新しいオーディオフレームの幅（ポイント単位）。 |
| height | float | 新しいオーディオフレームの高さ（ポイント単位）。 |
| audio_stream | java.io.InputStream | 埋め込む WAV オーディオデータを含む入力ストリーム。 |

**戻り値:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新しく作成された [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

既存の Presentation.Audios リストからオーディオ オブジェクトを使用して、新しいオーディオフレームを作成し、指定されたインデックスで shape コレクションに挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | オーディオフレームを挿入するゼロベースのインデックス。 |
| x | float | 新しいオーディオフレームの X 座標（ポイント単位）。 |
| y | float | 新しいオーディオフレームの Y 座標（ポイント単位）。 |
| width | float | 新しいオーディオフレームの幅（ポイント単位）。 |
| height | float | 新しいオーディオフレームの高さ（ポイント単位）。 |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Presentation.Audios コレクションから埋め込む [IAudio](../../com.aspose.slides/iaudio) インスタンス。 |

**戻り値:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新しく作成された [IAudioFrame](../../com.aspose.slides/iaudioframe).
### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public abstract int indexOf(IShape shape)
```

コレクション内で指定されたシェイプが最初に出現するゼロベースのインデックスを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | コレクション内で検索するシェイプ。 |

**戻り値:**
int - 見つかった場合は shape コレクション内でシェイプが最初に出現するゼロベースのインデックスを返し、見つからない場合は \\u20131 を返します。
### toArray() {#toArray--}
```
public abstract IShape[] toArray()
```

すべてのシェイプを含む配列を作成して返します。

**戻り値:**
com.aspose.slides.IShape[] - [IShape](../../com.aspose.slides/ishape) オブジェクトの配列。
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IShape[] toArray(int startIndex, int count)
```

指定された範囲内のすべてのシェイプを含む配列を作成して返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| startIndex | int | 返す最初のシェイプのインデックス。 |
| count | int | 返すシェイプの数。 |

**戻り値:**
com.aspose.slides.IShape[] - [IShape](../../com.aspose.slides/ishape) オブジェクトの配列。
### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public abstract void reorder(int index, IShape shape)
```

指定されたシェイプを shape コレクション内の新しい位置に移動します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | シェイプを配置するゼロベースのターゲット インデックス。 |
| shape | [IShape](../../com.aspose.slides/ishape) | コレクション内で移動する [IShape](../../com.aspose.slides/ishape)。 |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public abstract void reorder(int index, IShape[] shapes)
```

指定されたシェイプを shape コレクション内で移動し、指定されたインデックスから配置します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 最初の指定シェイプが配置されるゼロベースのターゲット インデックス。後続のシェイプは提供された順序で続きます。 |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | コレクション内で移動する 1 つ以上の [IShape](../../com.aspose.slides/ishape) インスタンス。 |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

デフォルトの書式設定で新しいオートシェイプを作成し、shape コレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shapeType | int | 追加するオートシェイプの [ShapeType](../../com.aspose.slides/shapetype)。
| x | float | shape のフレームの x 座標（ポイント）です。 |
| y | float | shape のフレームの y 座標（ポイント）です。 |
| width | float | shape のフレームの幅（ポイント）です。 |
| height | float | shape のフレームの高さ（ポイント）です。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 新しく作成された [IAutoShape](../../com.aspose.slides/iautoshape)。

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

新しい auto shape を作成し、shape コレクションの末尾に追加します。オプションでデフォルトテンプレートの書式設定で初期化できます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shapeType | int | 追加する auto shape の [ShapeType](../../com.aspose.slides/shapetype)です。 |
| x | float | shape のフレームの x 座標（ポイント）です。 |
| y | float | shape のフレームの y 座標（ポイント）です。 |
| width | float | shape のフレームの幅（ポイント）です。 |
| height | float | shape のフレームの高さ（ポイント）です。 |
| createFromTemplate | boolean | true の場合、デフォルトテンプレートのスタイリング（シンプルスタイル、中央揃えテキスト、空でない名前）を新しい shape に適用します。false の場合、すべてのプロパティをデフォルト値に設定した shape を作成します。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 新しく作成された [IAutoShape](../../com.aspose.slides/iautoshape)。

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public abstract IAutoShape addMathShape(float x, float y, float width, float height)
```

数式コンテンツを保持する新しい矩形 auto shape を作成し、shape コレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | shape のフレームの x 座標（ポイント）です。 |
| y | float | shape のフレームの y 座標（ポイント）です。 |
| width | float | shape のフレームの幅（ポイント）です。 |
| height | float | shape のフレームの高さ（ポイント）です。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 新しく作成された [IAutoShape](../../com.aspose.slides/iautoshape)。

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

新しい auto shape を作成し、指定されたインデックスに shape コレクションへ挿入します。デフォルトテンプレートの書式設定が適用されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 新しい auto shape を挿入するゼロベースインデックスです。 |
| shapeType | int | 挿入する auto shape の [ShapeType](../../com.aspose.slides/shapetype)です。 |
| x | float | shape のフレームの x 座標（ポイント）です。 |
| y | float | shape のフレームの y 座標（ポイント）です。 |
| width | float | shape のフレームの幅（ポイント）です。 |
| height | float | shape のフレームの高さ（ポイント）です。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 新しく作成された [IAutoShape](../../com.aspose.slides/iautoshape)。

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

新しい auto shape を作成し、指定されたインデックスに shape コレクションへ挿入します。オプションでデフォルトテンプレートのスタイリングで初期化できます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | auto shape を挿入するゼロベースインデックスです。 |
| shapeType | int | 挿入する auto shape の [ShapeType](../../com.aspose.slides/shapetype)です。 |
| x | float | shape のフレームの x 座標（ポイント）です。 |
| y | float | shape のフレームの y 座標（ポイント）です。 |
| width | float | shape のフレームの幅（ポイント）です。 |
| height | float | shape のフレームの高さ（ポイント）です。 |
| createFromTemplate | boolean | true の場合、デフォルトテンプレートのスタイリング（空でない名前、シンプルスタイル、中央揃えテキスト）を適用します。false の場合、すべてのプロパティをデフォルト値に設定した shape を作成します。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 新しく作成された [IAutoShape](../../com.aspose.slides/iautoshape)。

### addGroupShape() {#addGroupShape--}
```
public abstract IGroupShape addGroupShape()
```

新しい空の group shape を作成し、shape コレクションの末尾に追加します。group のフレームは追加された shape に合わせて自動的に調整されます。

**戻り値:**
[IGroupShape](../../com.aspose.slides/igroupshape) - 新しく作成された [IGroupShape](../../com.aspose.slides/igroupshape)。

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public abstract IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

新しい group shape を作成し、指定された SVG 画像を個別の shape に変換して、結果の group を shape コレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | shape に変換するベクタコンテンツを含む [ISvgImage](../../com.aspose.slides/isvgimage)です。 |
| x | float | group のフレームの x 座標（ポイント）です。 |
| y | float | group のフレームの y 座標（ポイント）です。 |
| width | float | group のフレームの幅（ポイント）です。 |
| height | float | group のフレームの高さ（ポイント）です。 |

**戻り値:**
[IGroupShape](../../com.aspose.slides/igroupshape) - 新しく作成された [IGroupShape](../../com.aspose.slides/igroupshape)。

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public abstract IGroupShape insertGroupShape(int index)
```

新しい空の group shape を作成し、指定されたインデックスに shape コレクションへ挿入します。group のフレームは追加された shape に合わせて自動的に調整されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | group shape を挿入するゼロベースインデックスです。 |

**戻り値:**
[IGroupShape](../../com.aspose.slides/igroupshape) - 新しく作成された [IGroupShape](../../com.aspose.slides/igroupshape)。

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

デフォルトテンプレートのスタイリングを持つ新しい connector shape を作成し、shape コレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shapeType | int | 追加する connector shape の [ShapeType](../../com.aspose.slides/shapetype)です。 |
| x | float | connector のフレームの x 座標（ポイント）です。 |
| y | float | connector のフレームの y 座標（ポイント）です。 |
| width | float | connector のフレームの幅（ポイント）です。 |
| height | float | connector のフレームの高さ（ポイント）です。 |

**戻り値:**
[IConnector](../../com.aspose.slides/iconnector) - 新しく作成された [IConnector](../../com.aspose.slides/iconnector)。

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

新しい connector shape を作成し、shape コレクションの末尾に追加します。オプションでデフォルトテンプレートのスタイリングを適用できます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shapeType | int | 作成する connector shape の [ShapeType](../../com.aspose.slides/shapetype)です。 |
| x | float | connector のフレームの x 座標（ポイント）です。 |
| y | float | connector のフレームの y 座標（ポイント）です。 |
| width | float | connector のフレームの幅（ポイント）です。 |
| height | float | connector のフレームの高さ（ポイント）です。 |
| createFromTemplate | boolean | true の場合、デフォルトテンプレートのスタイリング（空でない名前、シンプルスタイル）を適用します。false の場合、デフォルトプロパティ値で connector を作成します。 |

**戻り値:**
[IConnector](../../com.aspose.slides/iconnector) - 新しく作成された [IConnector](../../com.aspose.slides/iconnector)。

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

新しい connector shape を作成し、指定されたインデックスに shape コレクションへ挿入します。デフォルトテンプレートのスタイリングが適用されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | connector shape を挿入するゼロベースインデックスです。 |
| shapeType | int | 挿入する connector shape の [ShapeType](../../com.aspose.slides/shapetype)です。 |
| x | float | connector のフレームの x 座標（ポイント）です。 |
| y | float | connector のフレームの y 座標（ポイント）です。 |
| width | float | connector のフレームの幅（ポイント）です。 |
| height | float | connector のフレームの高さ（ポイント）です。 |

**戻り値:**
[IConnector](../../com.aspose.slides/iconnector) - 新しく作成された [IConnector](../../com.aspose.slides/iconnector)。

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

新しい connector shape を作成し、指定されたインデックスに shape コレクションへ挿入します。オプションでデフォルトテンプレートのスタイリングを適用できます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | connector shape を挿入するゼロベースインデックスです。 |
| shapeType | int | 挿入する connector shape の [ShapeType](../../com.aspose.slides/shapetype)です。 |
| x | float | connector のフレームの x 座標（ポイント）です。 |
| y | float | connector のフレームの y 座標（ポイント）です。 |
| width | float | connector のフレームの幅（ポイント）です。 |
| height | float | connector のフレームの高さ（ポイント）です。 |
| createFromTemplate | boolean | true の場合、デフォルトテンプレートのスタイリング（空でない名前、シンプルスタイル）を適用します。false の場合、デフォルトプロパティ値で connector を作成します。 |

**戻り値:**
[IConnector](../../com.aspose.slides/iconnector) - 新しく作成された [IConnector](../../com.aspose.slides/iconnector)。

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

指定された画像を含む新しい picture frame を作成し、shape コレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) に含める shape の種類を指定します（すべての線種は除く）：

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5。 |
| x | float | picture frame のフレームの x 座標（ポイント）です。 |
| y | float | picture frame のフレームの y 座標（ポイント）です。 |
| width | float | picture frame のフレームの幅（ポイント）です。 |
| height | float | picture frame のフレームの高さ（ポイント）です。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | picture frame に表示する [IPPImage](../../com.aspose.slides/ippimage)です。 |

**戻り値:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - 新しく作成された [IPictureFrame](../../com.aspose.slides/ipictureframe)。

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

指定された画像を含む新しい picture frame を作成し、指定されたインデックスに shape コレクションへ挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | picture frame を挿入するゼロベースインデックスです。 |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) に含める shape の種類を指定します（すべての線種は除く）：

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5。 |
| x | float | picture frame のフレームの x 座標（ポイント）です。 |
| y | float | picture frame のフレームの y 座標（ポイント）です。 |
| width | float | picture frame のフレームの幅（ポイント）です。 |
| height | float | picture frame のフレームの高さ（ポイント）です。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | picture frame に表示する [IPPImage](../../com.aspose.slides/ippimage)です。 |

**戻り値:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - 新しく作成された [IPictureFrame](../../com.aspose.slides/ipictureframe)。

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public abstract ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

新しい table を作成し、shape コレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | float | table のフレームの x 座標（ポイント）です。 |
| y | float | table のフレームの y 座標（ポイント）です。 |
| columnWidths | double[] | table の列の幅を表す double 配列（ポイント）です。 |
| rowHeights | double[] | table の行の高さを表す double 配列（ポイント）です。 |

**戻り値:**
[ITable](../../com.aspose.slides/itable) - 新しく作成された [ITable](../../com.aspose.slides/itable)。

### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public abstract ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```
新しいテーブルを作成し、指定したインデックスでシェイプ コレクションに挿入します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | テーブルを挿入するゼロベースのインデックス。 |
| x | float | テーブルの x 座標（ポイント単位）。 |
| y | float | テーブルの y 座標（ポイント単位）。 |
| columnWidths | double[] | テーブルの列幅を表す double の配列（ポイント単位）。 |
| rowHeights | double[] | テーブルの行高を表す double の配列（ポイント単位）。 |

**戻り値:**
[ITable](../../com.aspose.slides/itable) - 新しく作成された [ITable](../../com.aspose.slides/itable)。

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

指定されたインデックスにあるシェイプをシェイプ コレクションから削除します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 削除するシェイプのゼロベースインデックス。 |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public abstract void remove(IShape shape)
```

指定されたシェイプの最初の出現をシェイプ コレクションから削除します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | 削除する [IShape](../../com.aspose.slides/ishape)。 |

### clear() {#clear--}
```
public abstract void clear()
```

シェイプ コレクションからすべてのシェイプを削除します。

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

指定されたシェイプのコピーを作成し、シェイプ コレクションの末尾に追加します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | クローン対象のシェイプ。 |
| x | float | クローンしたシェイプのフレームの x 座標（ポイント単位）。 |
| y | float | クローンしたシェイプのフレームの y 座標（ポイント単位）。 |
| width | float | クローンしたシェイプのフレームの幅（ポイント単位）。 |
| height | float | クローンしたシェイプのフレームの高さ（ポイント単位）。 |

**戻り値:**
[IShape](../../com.aspose.slides/ishape) - 新しく作成された [IShape](../../com.aspose.slides/ishape)。

### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y)
```

指定されたシェイプのコピーを作成し、シェイプ コレクションの末尾に追加します。新しいシェイプは sourceShape の幅と高さを保持します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | クローン対象の [IShape](../../com.aspose.slides/ishape)。 |
| x | float | クローンしたシェイプのフレームの x 座標（ポイント単位）。 |
| y | float | クローンしたシェイプのフレームの y 座標（ポイント単位）。 |

**戻り値:**
[IShape](../../com.aspose.slides/ishape) - 新しく作成された [IShape](../../com.aspose.slides/ishape)。

### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public abstract IShape addClone(IShape sourceShape)
```

指定されたシェイプのコピーを作成し、シェイプ コレクションの末尾に追加します。クローンされたシェイプは元の位置とサイズを保持します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | クローン対象の [IShape](../../com.aspose.slides/ishape)。 |

**戻り値:**
[IShape](../../com.aspose.slides/ishape) - 新しく作成された [IShape](../../com.aspose.slides/ishape)。

### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

指定されたシェイプのコピーを作成し、指定したインデックスでシェイプ コレクションに挿入します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | クローンしたシェイプを挿入するゼロベースのインデックス。 |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | クローン対象の [IShape](../../com.aspose.slides/ishape)。 |
| x | float | クローンしたシェイプのフレームの x 座標（ポイント単位）。 |
| y | float | クローンしたシェイプのフレームの y 座標（ポイント単位）。 |
| width | float | クローンしたシェイプのフレームの幅（ポイント単位）。 |
| height | float | クローンしたシェイプのフレームの高さ（ポイント単位）。 |

**戻り値:**
[IShape](../../com.aspose.slides/ishape) - 新しく作成された [IShape](../../com.aspose.slides/ishape)。

### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y)
```

指定されたシェイプのコピーを作成し、指定したインデックスでシェイプ コレクションに挿入します。新しいシェイプは sourceShape の幅と高さを保持します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | クローンしたシェイプを挿入するゼロベースのインデックス。 |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | クローン対象の [IShape](../../com.aspose.slides/ishape)。 |
| x | float | クローンしたシェイプのフレームの x 座標（ポイント単位）。 |
| y | float | クローンしたシェイプのフレームの y 座標（ポイント単位）。 |

**戻り値:**
[IShape](../../com.aspose.slides/ishape) - 新しく作成された [IShape](../../com.aspose.slides/ishape)。

### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public abstract IShape insertClone(int index, IShape sourceShape)
```

指定されたシェイプのコピーを作成し、指定したインデックスでシェイプ コレクションに挿入します。クローンされたシェイプは元の位置とサイズを保持します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | クローンしたシェイプを挿入するゼロベースのインデックス。 |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | クローン対象の [IShape](../../com.aspose.slides/ishape)。 |

**戻り値:**
[IShape](../../com.aspose.slides/ishape) - 新しく作成された [IShape](../../com.aspose.slides/ishape)。