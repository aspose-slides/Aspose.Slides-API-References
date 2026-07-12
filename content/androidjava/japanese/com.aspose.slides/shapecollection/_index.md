---
title: ShapeCollection
second_title: Aspose.Slides for Android 用 Java API リファレンス
description: シェイプのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/shapecollection/
---
**継承:**  
java.lang.Object, com.aspose.slides.DomObject

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IShapeCollection](../../com.aspose.slides/ishapecollection)  
```
public final class ShapeCollection extends DomObject<GroupShape> implements IShapeCollection
```

シェイプのコレクションを表します。  
## メソッド

| メソッド | 説明 |
| --- | --- |
| [size()](#size--) | コレクションに実際に含まれる要素数を取得します。 |
| [get_Item(int index)](#get-Item-int-) | 指定したインデックスの要素を取得します。 |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | 新しいチャートを作成し、サンプルシリーズデータと設定で初期化し、シェイプコレクションの末尾に追加します。 |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | 新しいチャートを作成し、サンプルシリーズデータと設定で初期化し、シェイプコレクションの末尾に追加します。 |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | SmartArt 図形を作成し、シェイプコレクションの末尾に追加します。 |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | 新しいチャートを作成し、サンプルシリーズデータと設定で初期化し、指定したインデックスに挿入します。 |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | 新しいチャートを作成し、サンプルシリーズデータと設定で初期化し、指定したインデックスに挿入します。 |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | 新しいズーム フレームを作成し、シェイプコレクションの末尾に追加します。 |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | 新しいズーム フレームを作成し、シェイプコレクションの末尾に追加します。 |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | 新しいズーム フレームを作成し、指定したインデックスに挿入します。 |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | 事前に定義された画像を持つ新しいズーム フレームを作成し、指定したインデックスに挿入します。 |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | 新しいセクション ズーム フレームを作成し、シェイプコレクションの末尾に追加します。 |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | 事前に定義された画像を持つ新しいセクション ズーム フレームを作成し、シェイプコレクションの末尾に追加します。 |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | 新しいセクション ズーム フレームを作成し、指定したインデックスに挿入します。 |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | 事前に定義された画像を持つ新しいセクション ズーム フレームを作成し、指定したインデックスに挿入します。 |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | 新しいサマリー ズーム フレームを作成し、シェイプコレクションの末尾に追加します。 |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | 新しいサマリー ズーム フレームを作成し、指定したインデックスに挿入します。 |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | 新しい OLE オブジェクト フレームを作成し、シェイプコレクションの末尾に追加します。 |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | 新しい OLE オブジェクト フレームを作成し、シェイプコレクションの末尾に追加します。 |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | 新しい OLE オブジェクト フレームを作成し、指定したインデックスに挿入します。 |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | 新しい OLE オブジェクト フレームを作成し、指定したインデックスに挿入します。 |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | 新しいビデオ フレームを作成し、シェイプコレクションの末尾に追加します。 |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | 新しいビデオ フレームを作成し、シェイプコレクションの末尾に追加します。 |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | 新しいビデオ フレームを作成し、指定したインデックスに挿入します。 |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | CD トラックにリンクした新しいオーディオ フレームを作成し、シェイプコレクションの末尾に追加します。 |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | CD トラックにリンクした新しいオーディオ フレームを作成し、指定したインデックスに挿入します。 |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | 外部オーディオ ファイルにリンクした新しいオーディオ フレームを作成し、シェイプコレクションの末尾に追加します。 |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | 外部オーディオ ファイルにリンクした新しいオーディオ フレームを作成し、指定したインデックスに挿入します。 |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | 埋め込み WAV ファイルを持つ新しいオーディオ フレームを作成し、シェイプコレクションの末尾に追加します。 |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | 埋め込み WAV ファイルを持つ新しいオーディオ フレームを作成し、指定したインデックスに挿入します。 |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Presentation.Audios リストから既存のオーディオ オブジェクトを使用して新しいオーディオ フレームを作成し、シェイプコレクションの末尾に追加します。 |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Presentation.Audios リストから既存のオーディオ オブジェクトを使用して新しいオーディオ フレームを作成し、指定したインデックスに挿入します。 |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | 指定したシェイプがコレクション内に最初に現れる位置のゼロベースインデックスを返します。 |
| [toArray()](#toArray--) | すべてのシェイプを含む配列を作成して返します。 |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 指定した範囲のすべてのシェイプを含む配列を作成して返します。 |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | 指定したシェイプをシェイプコレクション内の新しい位置に移動します。 |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | 指定したシェイプをコレクション内で移動し、指定インデックスから順に配置します。 |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | デフォルトの書式設定で新しいオート シェイプを作成し、シェイプコレクションの末尾に追加します。 |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | デフォルトのテンプレート書式でオプション初期化しながら、新しいオート シェイプを作成してコレクションの末尾に追加します。 |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | 数式コンテンツを保持する矩形オート シェイプを作成し、シェイプコレクションの末尾に追加します。 |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | デフォルトのテンプレート書式を適用して、新しいオート シェイプを指定インデックスに挿入します。 |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | デフォルトのテンプレートスタイリングでオプション初期化しながら、新しいオート シェイプを指定インデックスに挿入します。 |
| [addGroupShape()](#addGroupShape--) | 空のグループ シェイプを作成し、コレクションの末尾に追加します。 |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | 指定された SVG 画像を個々のシェイプに変換し、結果のグループをコレクションの末尾に追加します。 |
| [insertGroupShape(int index)](#insertGroupShape-int-) | 空のグループ シェイプを作成し、指定インデックスに挿入します。 |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | デフォルトのテンプレートスタイリングで新しいコネクタ シェイプを作成し、コレクションの末尾に追加します。 |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | デフォルトのテンプレートスタイリングでオプション初期化しながら、新しいコネクタ シェイプをコレクションの末尾に追加します。 |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | デフォルトのテンプレートスタイリングを適用して、新しいコネクタ シェイプを指定インデックスに挿入します。 |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | デフォルトのテンプレートスタイリングでオプション初期化しながら、新しいコネクタ シェイプを指定インデックスに挿入します。 |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | 指定された画像を含む新しいピクチャ フレームを作成し、コレクションの末尾に追加します。 |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | 指定された画像を含む新しいピクチャ フレームを作成し、指定インデックスに挿入します。 |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | 新しいテーブルを作成し、コレクションの末尾に追加します。 |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | 新しいテーブルを作成し、指定インデックスに挿入します。 |
| [removeAt(int index)](#removeAt-int-) | 指定インデックスのシェイプをコレクションから削除します。 |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | 指定されたシェイプの最初の出現をコレクションから削除します。 |
| [clear()](#clear--) | コレクション内のすべてのシェイプを削除します。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の Java イテレータを返します。 |
| [getParentGroup()](#getParentGroup--) | シェイプ コレクションの親グループ シェイプ オブジェクトを取得します。 |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | 指定されたシェイプのコピーを作成し、コレクションの末尾に追加します。 |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | 指定されたシェイプのコピーを作成し、コレクションの末尾に追加します。 |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | 指定されたシェイプのコピーを作成し、コレクションの末尾に追加します。 |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | 指定されたシェイプのコピーを作成し、指定インデックスに挿入します。 |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | 指定されたシェイプのコピーを作成し、指定インデックスに挿入します。 |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | 指定されたシェイプのコピーを作成し、指定インデックスに挿入します。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | コレクション内のすべての要素を指定配列にコピーします。 |
| [isSynchronized()](#isSynchronized--) | コレクションへのアクセスが同期化されているか (スレッドセーフ) を示す値を返します。 |
| [getSyncRoot()](#getSyncRoot--) | 同期ルートを返します。 |

### size() {#size--}
```
public final int size()
```

コレクションに実際に含まれる要素数を取得します。読み取り専用 int .

**戻り値:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final IShape get_Item(int index)
```

指定したインデックスの要素を取得します。読み取り専用 [IShape](../../com.aspose.slides/ishape).

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**  
[IShape](../../com.aspose.slides/ishape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public final IChart addChart(int type, float x, float y, float width, float height)
```

新しいチャートを作成し、サンプルシリーズデータと設定で初期化し、シェイプコレクションの末尾に追加します。

--------------------

> ```
> The following example shows how to create Chart in PowerPoint Presentation.
>  
>  // PPTX ファイルを表す Presentation クラスのインスタンスを作成します
>  Presentation pres = new Presentation();
>  try {
>      // 最初のスライドにアクセスします
>      ISlide sld = pres.getSlides().get_Item(0);
>      // デフォルト データでチャートを追加します
>      IChart chart = sld.getShapes().addChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
>      // チャートのタイトルを設定します
>      chart.getChartTitle().addTextFrameForOverriding("Sample Title");
>      chart.getChartTitle().getTextFrameForOverriding().getTextFrameFormat().setCenterText(NullableBool.True);
>      chart.getChartTitle().setHeight(20);
>      chart.setTitle(true);
>      // 最初のシリーズに値を表示するよう設定します
>      chart.getChartData().getSeries().get_Item(0).getLabels().getDefaultDataLabelFormat().setShowValue(true);
>      // チャート データ シートのインデックスを設定します
>      int defaultWorksheetIndex = 0;
>      // チャート データ ワークシートを取得します
>      IChartDataWorkbook fact = chart.getChartData().getChartDataWorkbook();
>      // デフォルトで生成されたシリーズとカテゴリを削除します
>      chart.getChartData().getSeries().clear();
>      chart.getChartData().getCategories().clear();
>      // 新しいシリーズを追加します
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.getType());
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.getType());
>      // 新しいカテゴリを追加します
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
>      // 最初のチャートシリーズを取得します
>      IChartSeries series = chart.getChartData().getSeries().get_Item(0);
>      // シリーズデータを設定します
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 1, 20));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 1, 50));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 1, 30));
>      // シリーズの塗りつぶし色を設定します
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.RED);
>      // 2 番目のチャートシリーズを取得します
>      series = chart.getChartData().getSeries().get_Item(1);
>      // シリーズデータを設定します
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 2, 30));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 2, 10));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 2, 60));
>      // シリーズの塗りつぶし色を設定します
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.GREEN);
>      // 最初のラベルにカテゴリ名を表示するよう設定します
>      IDataLabel lbl = series.getDataPoints().get_Item(0).getLabel();
>      lbl.getDataLabelFormat().setShowCategoryName(true);
>      lbl = series.getDataPoints().get_Item(1).getLabel();
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      // シリーズの 3 番目のラベルに値を表示するよう設定します
>      lbl = series.getDataPoints().get_Item(2).getLabel();
>      lbl.getDataLabelFormat().setShowValue(true);
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      lbl.getDataLabelFormat().setSeparator("/");
>      // PPTX ファイルをディスクに保存します
>      pres.save("AsposeChart_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| type | int | 追加するチャートの種類。 |
| x | float | 新しいチャートの X 座標（ポイント）。 |
| y | float | 新しいチャートの Y 座標（ポイント）。 |
| width | float | チャートの幅（ポイント）。 |
| height | float | チャートの高さ（ポイント）。 |

**戻り値:**  
[IChart](../../com.aspose.slides/ichart) - 新しく作成された [IChart](../../com.aspose.slides/ichart)。

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public final IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

新しいチャートを作成し、サンプルシリーズデータと設定で初期化し、シェイプコレクションの末尾に追加します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| type | int | 追加するチャートの種類。 |
| x | float | 新しいチャートの X 座標（ポイント）。 |
| y | float | 新しいチャートの Y 座標（ポイント）。 |
| width | float | チャートの幅（ポイント）。 |
| height | float | チャートの高さ（ポイント）。 |
| initWithSample | boolean | true の場合、サンプルシリーズデータと設定で初期化します。false の場合、シリーズなしで最小設定のみで作成し、作成が高速になります。 |

**戻り値:**  
[IChart](../../com.aspose.slides/ichart) - 新しく作成された [IChart](../../com.aspose.slides/ichart)。

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public final ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

SmartArt 図形を作成し、シェイプコレクションの末尾に追加します。

--------------------

> ```
> PowerPoint プレゼンテーションにスマート シェイプを追加する方法の例を示します。
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      ISmartArt smart = slide.getShapes().addSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | 図形フレームの X 座標（ポイント）。 |
| y | float | 図形フレームの Y 座標（ポイント）。 |
| width | float | 図形フレームの幅（ポイント）。 |
| height | float | 図形フレームの高さ（ポイント）。 |
| layoutType | int | SmartArt のレイアウトタイプ。 |

**戻り値:**  
[ISmartArt](../../com.aspose.slides/ismartart) - 新しく作成された [ISmartArt](../../com.aspose.slides/ismartart)。

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index)
```

新しいチャートを作成し、サンプルシリーズデータと設定で初期化し、指定インデックスに挿入します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| type | int | 作成するチャートの種類。 |
| x | float | 新しいチャートの X 座標（ポイント）。 |
| y | float | 新しいチャートの Y 座標（ポイント）。 |
| width | float | 新しいチャートの幅（ポイント）。 |
| height | float | 新しいチャートの高さ（ポイント）。 |
| index | int | ゼロベースインデックス。新しいチャートをシェイプコレクションのどこに挿入するか。 |

**戻り値:**  
[IChart](../../com.aspose.slides/ichart) - 新しく作成された [IChart](../../com.aspose.slides/ichart)。

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

新しいチャートを作成し、サンプルシリーズデータと設定で初期化し、指定インデックスに挿入します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| type | int | 作成するチャートの種類。 |
| x | float | 新しいチャートの X 座標（ポイント）。 |
| y | float | 新しいチャートの Y 座標（ポイント）。 |
| width | float | 新しいチャートの幅（ポイント）。 |
| height | float | 新しいチャートの高さ（ポイント）。 |
| index | int | ゼロベースインデックス。新しいチャートをシェイプコレクションのどこに挿入するか。 |
| initWithSample | boolean | true の場合、サンプルシリーズデータと設定で初期化します。false の場合、シリーズなしで最小設定のみで作成し、作成が高速になります。 |

**戻り値:**  
[IChart](../../com.aspose.slides/ichart) - 新しく作成された [IChart](../../com.aspose.slides/ichart)。

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

新しいズーム フレームを作成し、シェイプコレクションの末尾に追加します。

--------------------

> ```
> この例は Zoom オブジェクトをコレクションの末尾に追加する方法を示します
>  (「Presentation.pptx」プレゼンテーションに少なくとも 2 スライドがあると仮定します):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいズーム フレームの X 座標（ポイント）。 |
| y | float | 新しいズーム フレームの Y 座標（ポイント）。 |
| width | float | 新しいズーム フレームの幅（ポイント）。 |
| height | float | 新しいズーム フレームの高さ（ポイント）。 |
| slide | [ISlide](../../com.aspose.slides/islide) | ズーム フレームが参照する [ISlide](../../com.aspose.slides/islide)。このプレゼンテーションに属している必要があります。 |

**戻り値:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - 新しく作成された [IZoomFrame](../../com.aspose.slides/izoomframe)。

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

新しいズーム フレームを作成し、シェイプコレクションの末尾に追加します。

--------------------

> ```
> この例は Zoom オブジェクトをコレクションの末尾に追加する方法を示します
>  (「Presentation.pptx」プレゼンテーションに少なくとも 2 スライドがあると仮定します):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいズーム フレームの X 座標（ポイント）。 |
| y | float | 新しいズーム フレームの Y 座標（ポイント）。 |
| width | float | 新しいズーム フレームの幅（ポイント）。 |
| height | float | 新しいズーム フレームの高さ（ポイント）。 |
| slide | [ISlide](../../com.aspose.slides/islide) | ズーム フレームが参照する [ISlide](../../com.aspose.slides/islide)。このプレゼンテーションに属している必要があります。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 参照スライド [IPPImage](../../com.aspose.slides/ippimage) 用の画像。 |

**戻り値:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - 新しく作成された [IZoomFrame](../../com.aspose.slides/izoomframe)。

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

新しいズーム フレームを作成し、指定インデックスに挿入します。

--------------------

> ```
> この例はコレクションの指定インデックスに Zoom オブジェクトを作成して挿入する方法を示します
>  (「Presentation.pptx」プレゼンテーションに少なくとも 2 スライドがあると想定します):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | ゼロベースインデックス。ズーム フレームを挿入する位置。 |
| x | float | 新しいズーム フレームの X 座標（ポイント）。 |
| y | float | 新しいズーム フレームの Y 座標（ポイント）。 |
| width | float | ズーム フレームの幅（ポイント）。 |
| height | float | ズーム フレームの高さ（ポイント）。 |
| slide | [ISlide](../../com.aspose.slides/islide) | ズーム フレームが参照する [ISlide](../../com.aspose.slides/islide)。 |

**戻り値:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - 新しく作成された [IZoomFrame](../../com.aspose.slides/izoomframe)。

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

事前に定義された画像を持つ新しいズーム フレームを作成し、指定インデックスに挿入します。

--------------------

> ```
> この例は、コレクションの指定インデックスに Zoom オブジェクトを作成して挿入する方法を示します
>  （「Presentation.pptx」プレゼンテーションに少なくとも 2 スライドがあると想定します）:
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | ゼロベースインデックス。ズーム フレームを挿入する位置。 |
| x | float | 新しいズーム フレームの X 座標（ポイント）。 |
| y | float | 新しいズーム フレームの Y 座標（ポイント）。 |
| width | float | ズーム フレームの幅（ポイント）。 |
| height | float | ズーム フレームの高さ（ポイント）。 |
| slide | [ISlide](../../com.aspose.slides/islide) | ズーム フレームが参照する [ISlide](../../com.aspose.slides/islide)。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 参照スライド [IPPImage](../../com.aspose.slides/ippimage) 用の画像。 |

**戻り値:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - 新しく作成された [IZoomFrame](../../com.aspose.slides/izoomframe)。

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

新しいセクション ズーム フレームを作成し、コレクションの末尾に追加します。

--------------------

> ```
> この例はセクション Zoom オブジェクトをコレクションの末尾に追加する方法を示します
>  (「Presentation.pptx」プレゼンテーションに少なくとも 2 セクションがあると想定します):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいセクション ズーム フレームの X 座標（ポイント）。 |
| y | float | 新しいセクション ズーム フレームの Y 座標（ポイント）。 |
| width | float | セクション ズーム フレームの幅（ポイント）。 |
| height | float | セクション ズーム フレームの高さ（ポイント）。 |
| section | [ISection](../../com.aspose.slides/isection) | セクション ズーム フレームが参照する [ISection](../../com.aspose.slides/isection)。このプレゼンテーションに属し、少なくとも 1 つのスライドを含む必要があります。 |

**戻り値:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 新しく作成された [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)。

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

事前に定義された画像を持つ新しいセクション ズーム フレームを作成し、コレクションの末尾に追加します。

--------------------

> ```
> この例は、セクション Zoom オブジェクトをコレクションの末尾に追加する方法を示します
>  (「Presentation.pptx」プレゼンテーションに少なくとも 2 セクションがあると想定します):
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


**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいセクション ズーム フレームの X 座標（ポイント）。 |
| y | float | 新しいセクション ズーム フレームの Y 座標（ポイント）。 |
| width | float | セクション ズーム フレームの幅（ポイント）。 |
| height | float | セクション ズーム フレームの高さ（ポイント）。 |
| section | [ISection](../../com.aspose.slides/isection) | セクション ズーム フレームが参照する [ISection](../../com.aspose.slides/isection)。このプレゼンテーションに属し、少なくとも 1 つのスライドを含む必要があります。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | セクション ズーム フレーム内に表示する [IPPImage](../../com.aspose.slides/ippimage)。 |

**戻り値:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 新しく作成された [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)。

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

新しいセクション ズーム フレームを作成し、指定インデックスに挿入します。

--------------------

> ```
> この例は、コレクションの指定インデックスに Section Zoom オブジェクトを作成して挿入する方法を示します
>  （「Presentation.pptx」プレゼンテーションに少なくとも 2 セクションがあると想定します）:
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | ゼロベースインデックス。セクション ズーム フレームを挿入する位置。 |
| x | float | 新しいセクション ズーム フレームの X 座標（ポイント）。 |
| y | float | 新しいセクション ズーム フレームの Y 座標（ポイント）。 |
| width | float | セクション ズーム フレームの幅（ポイント）。 |
| height | float | セクション ズーム フレームの高さ（ポイント）。 |
| section | [ISection](../../com.aspose.slides/isection) | セクション ズーム フレームが参照する [ISection](../../com.aspose.slides/isection)。このプレゼンテーションに属し、少なくとも 1 つのスライドを含む必要があります。 |

**戻り値:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 新しく作成された [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)。

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

事前に定義された画像を持つ新しいセクション ズーム フレームを作成し、指定インデックスに挿入します。

--------------------

> ```
> この例は、コレクションの指定インデックスに Section Zoom オブジェクトを作成して挿入する方法を示します
>  （「Presentation.pptx」プレゼンテーションに少なくとも 2 セクションがあると想定します）:
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
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | ゼロベースインデックス。セクション ズーム フレームを挿入する位置。 |
| x | float | 新しいセクション ズーム フレームの X 座標（ポイント）。 |
| y | float | 新しいセクション ズーム フレームの Y 座標（ポイント）。 |
| width | float | セクション ズーム フレームの幅（ポイント）。 |
| height | float | セクション ズーム フレームの高さ（ポイント）。 |
| section | [ISection](../../com.aspose.slides/isection) | セクション ズーム フレームが参照する [ISection](../../com.aspose.slides/isection)。このプレゼンテーションに属し、少なくとも 1 つのスライドを含む必要があります。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | セクション ズーム フレーム内に表示する画像。 |

**戻り値:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 新しく作成された [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)。

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public final ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

新しいサマリー ズーム フレームを作成し、コレクションの末尾に追加します。

--------------------

> ```
> この例は、コレクションの末尾に Summary Zoom オブジェクトを追加する方法を示します
>  (「Presentation.pptx」プレゼンテーションに少なくとも 2 セクションがあると仮定します):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいサマリー ズーム フレームの X 座標（ポイント）。 |
| y | float | 新しいサマリー ズーム フレームの Y 座標（ポイント）。 |
| width | float | サマリー ズーム フレームの幅（ポイント）。 |
| height | float | サマリー ズーム フレームの高さ（ポイント）。 |

--------------------

このメソッドは新しいサマリー ズームを作成し、プレゼンテーション内のすべてのセクションのオブジェクト コレクションを格納します。

**戻り値:**  
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - 新しく作成された [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)。

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public final ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

新しいサマリー ズーム フレームを作成し、指定インデックスに挿入します。

--------------------

> ```
> この例は、コレクションの指定インデックスに Summary Zoom オブジェクトを作成して挿入する方法を示します
>  （「Presentation.pptx」プレゼンテーションに少なくとも 2 セクションがあると想定します）:
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | ゼロベースインデックス。サマリー ズーム フレームを挿入する位置。 |
| x | float | 新しいサマリー ズーム フレームの X 座標（ポイント）。 |
| y | float | 新しいサマリー ズーム フレームの Y 座標（ポイント）。 |
| width | float | サマリー ズーム フレームの幅（ポイント）。 |
| height | float | サマリー ズーム フレームの高さ（ポイント）。 |

--------------------

このメソッドはプレゼンテーション内のすべてのセクションのサマリー リンクを集約したサマリー ズーム フレームを作成します。

**戻り値:**  
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - 新しく作成された [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)。

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

新しい OLE オブジェクト フレームを作成し、シェイプコレクションの末尾に追加します。

--------------------

> ```
> 以下の例は、PowerPoint プレゼンテーションのスライドに OLE オブジェクト フレームを追加する方法を示しています。
>  
>  // PPTX を表す Presentation クラスをインスタンス化します
>  Presentation pres = new Presentation();
>  try
>  {
>      // 最初のスライドにアクセスします
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Excel ファイルをストリームにロードします
>      FileInputStream fs = new FileInputStream("book1.xlsx");
>      ByteArrayOutputStream mstream = new ByteArrayOutputStream();
>      byte[] buf = new byte[4096];
> 
>      while (true)
>      {
>          int bytesRead = fs.read(buf, 0, buf.length);
>          if (bytesRead <= 0)
>              break;
>          mstream.write(buf, 0, bytesRead);
>      }
>      // 埋め込み用データオブジェクトを作成します
>      IOleEmbeddedDataInfo dataInfo = new OleEmbeddedDataInfo(mstream.toByteArray(), "xlsx");
> 
>      // Ole オブジェクト フレーム シェイプを追加します
>      IOleObjectFrame oleObjectFrame = sld.getShapes().addOleObjectFrame(0, 0, (float)pres.getSlideSize().getSize().getWidth(),
>              (float)pres.getSlideSize().getSize().getHeight(), dataInfo);
> 
>      // PPTX をディスクに保存します
>      pres.save("OleEmbed_out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しい OLE フレームの X 座標（ポイント）。 |
| y | float | 新しい OLE フレームの Y 座標（ポイント）。 |
| width | float | 新しい OLE フレームの幅（ポイント）。 |
| height | float | 新しい OLE フレームの高さ（ポイント）。 |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | 埋め込まれた OLE データ ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)) に関する情報。 |

**戻り値:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 新しく作成された [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)。

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

新しい OLE オブジェクト フレームを作成し、シェイプコレクションの末尾に追加します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しい OLE フレームの X 座標（ポイント）。 |
| y | float | 新しい OLE フレームの Y 座標（ポイント）。 |
| width | float | 新しい OLE フレームの幅（ポイント）。 |
| height | float | 新しい OLE フレームの高さ（ポイント）。 |
| className | java.lang.String | OLE オブジェクトのクラス名。 |
| path | java.lang.String | リンクされたファイルへのパス。

このパスはプレゼンテーションに文字通り保存されます。相対パスが指定された場合、別ディレクトリからプレゼンテーションを開くとファイルにアクセスできなくなります。 |

**戻り値:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 新しく作成された [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)。

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

新しい OLE オブジェクト フレームを作成し、指定インデックスに挿入します。

--------------------

> ```
> This example demonstrates inserting an OLE object at the second index:
>  
>  byte[] fileData = ... // "test.zip"
>  IOleDataInfo dataInfo = new OleDataInfo(fileData, "zip");
>  IOleObjectFrame oleObjectFrame = slides.getShapes().addOleObjectFrame(2, 150, 20, 50, 50, dataInfo);
```

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | ゼロベースインデックス。OLE オブジェクト フレームを挿入する位置。 |
| x | float | 新しい OLE フレームの X 座標（ポイント）。 |
| y | float | 新しい OLE フレームの Y 座標（ポイント）。 |
| width | float | 新しい OLE フレームの幅（ポイント）。 |
| height | float | 新しい OLE フレームの高さ（ポイント）。 |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | 埋め込まれた OLE データ情報 ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo))。 |

**戻り値:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 新しく作成された [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)。

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

新しい OLE オブジェクト フレームを作成し、指定インデックスに挿入します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | ゼロベースインデックス。OLE オブジェクト フレームを挿入する位置。 |
| x | float | 新しい OLE フレームの X 座標（ポイント）。 |
| y | float | 新しい OLE フレームの Y 座標（ポイント）。 |
| width | float | 新しい OLE フレームの幅（ポイント）。 |
| height | float | 新しい OLE フレームの高さ（ポイント）。 |
| className | java.lang.String | OLE オブジェクトのクラス名。 |
| path | java.lang.String | リンクされたファイルへのパス。

このパスはプレゼンテーションに文字通り保存されます。相対パスが指定された場合、別ディレクトリからプレゼンテーションを開くとファイルにアクセスできなくなります。 |

**戻り値:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 新しく作成された OLE オブジェクト フレーム。

### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

新しいビデオ フレームを作成し、シェイプコレクションの末尾に追加します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいビデオ フレームの X 座標（ポイント）。 |
| y | float | 新しいビデオ フレームの Y 座標（ポイント）。 |
| width | float | ビデオ フレームの幅（ポイント）。 |
| height | float | ビデオ フレームの高さ（ポイント）。 |
| fname | java.lang.String | 埋め込むビデオ ファイルのパスまたは名前。 |

**戻り値:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - 新しく作成された [IVideoFrame](../../com.aspose.slides/ivideoframe)。

### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

新しいビデオ フレームを作成し、シェイプコレクションの末尾に追加します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいビデオ フレームの X 座標（ポイント）。 |
| y | float | 新しいビデオ フレームの Y 座標（ポイント）。 |
| width | float | ビデオ フレームの幅（ポイント）。 |
| height | float | ビデオ フレームの高さ（ポイント）。 |
| video | [IVideo](../../com.aspose.slides/ivideo) | ビデオ フレームに埋め込む [IVideo](../../com.aspose.slides/ivideo)。 |

**戻り値:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - 新しく作成された [IVideoFrame](../../com.aspose.slides/ivideoframe)。

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public final IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

新しいビデオ フレームを作成し、指定インデックスに挿入します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | ゼロベースインデックス。ビデオ フレームを挿入する位置。 |
| x | float | 新しいビデオ フレームの X 座標（ポイント）。 |
| y | float | 新しいビデオ フレームの Y 座標（ポイント）。 |
| width | float | ビデオ フレームの幅（ポイント）。 |
| height | float | ビデオ フレームの高さ（ポイント）。 |
| fname | java.lang.String | 埋め込むビデオ ファイルのパスまたは名前。 |

**戻り値:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - 新しく作成された [IVideoFrame](../../com.aspose.slides/ivideoframe)。

### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public final IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

CD トラックにリンクした新しいオーディオ フレームを作成し、シェイプコレクションの末尾に追加します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいオーディオ フレームの X 座標（ポイント）。 |
| y | float | 新しいオーディオ フレームの Y 座標（ポイント）。 |
| width | float | オーディオ フレームの幅（ポイント）。 |
| height | float | オーディオ フレームの高さ（ポイント）。 |

**戻り値:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新しく作成された [IAudioFrame](../../com.aspose.slides/iaudioframe)。

### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public final IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

CD トラックにリンクした新しいオーディオ フレームを作成し、指定インデックスに挿入します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | ゼロベースインデックス。オーディオ フレームを挿入する位置。 |
| x | float | 新しいオーディオ フレームの X 座標（ポイント）。 |
| y | float | 新しいオーディオ フレームの Y 座標（ポイント）。 |
| width | float | オーディオ フレームの幅（ポイント）。 |
| height | float | オーディオ フレームの高さ（ポイント）。 |

**戻り値:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新しく作成された [IAudioFrame](../../com.aspose.slides/iaudioframe)。

### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public final IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

外部オーディオ ファイルにリンクした新しいオーディオ フレームを作成し、シェイプコレクションの末尾に追加します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいオーディオ フレームの X 座標（ポイント）。 |
| y | float | 新しいオーディオ フレームの Y 座標（ポイント）。 |
| width | float | オーディオ フレームの幅（ポイント）。 |
| height | float | オーディオ フレームの高さ（ポイント）。 |
| fname | java.lang.String | リンクする外部オーディオ ファイルのパスまたは名前。 |

**戻り値:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新しく作成された [IAudioFrame](../../com.aspose.slides/iaudioframe)。

### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public final IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

外部オーディオ ファイルにリンクした新しいオーディオ フレームを作成し、指定インデックスに挿入します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | ゼロベースインデックス。オーディオ フレームを挿入する位置。 |
| x | float | 新しいオーディオ フレームの X 座標（ポイント）。 |
| y | float | 新しいオーディオ フレームの Y 座標（ポイント）。 |
| width | float | オーディオ フレームの幅（ポイント）。 |
| height | float | オーディオ フレームの高さ（ポイント）。 |
| fname | java.lang.String | リンクする外部オーディオ ファイルのパスまたは名前。 |

**戻り値:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新しく作成された [IAudioFrame](../../com.aspose.slides/iaudioframe)。

### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

埋め込み WAV ファイルを持つ新しいオーディオ フレームを作成し、シェイプコレクションの末尾に追加します。埋め込みオーディオは Presentation.Audios コレクションに追加されます。

--------------------

> ```
> 以下の例はオーディオ フレームの作成方法を示しています。
>  
>  // プレゼンテーション ファイルを表す Presentation クラスのインスタンスを作成します
>  Presentation pres = new Presentation();
>  try {
>      // 最初のスライドを取得します
>      ISlide sld = pres.getSlides().get_Item(0);
>      // wav サウンド ファイルをストリームにロードします
>      FileInputStream fstr = new FileInputStream("sampleaudio.wav");
>      try {
>          // オーディオ フレームを追加します
>          IAudioFrame audioFrame = sld.getShapes().addAudioFrameEmbedded(50, 150, 100, 100, fstr);
>          // オーディオの再生モードとボリュームを設定します
>          audioFrame.setPlayMode(AudioPlayModePreset.Auto);
>          audioFrame.setVolume(AudioVolumeMode.Loud);
>      } finally {
>          if (fstr != null) fstr.close();
>      }
>      // PowerPoint ファイルをディスクに書き込みます
>      pres.save("AudioFrameEmbed_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいオーディオ フレームの X 座標（ポイント）。 |
| y | float | 新しいオーディオ フレームの Y 座標（ポイント）。 |
| width | float | オーディオ フレームの幅（ポイント）。 |
| height | float | オーディオ フレームの高さ（ポイント）。 |
| audio_stream | java.io.InputStream | 埋め込む WAV データを含む入力ストリーム。 |

**戻り値:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新しく作成された [IAudioFrame](../../com.aspose.slides/iaudioframe)。

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public             public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```


埋め込み WAV ファイルを持つ新しいオーディオ フレームを作成し、指定インデックスに挿入します。埋め込みオーディオは Presentation.Audios コレクションに追加されます。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | ゼロベースインデックス。オーディオ フレームを挿入する位置。 |
| x | float | 新しいオーディオ フレームの X 座標（ポイント）。 |
| y | float | 新しいオーディオ フレームの Y 座標（ポイント）。 |
| width | float | オーディオ フレームの幅（ポイント）。 |
| height | float | オーディオ フレームの高さ（ポイント）。 |
| audio_stream | java.io.InputStream | 埋め込む WAV データを含む入力ストリーム。 |

**戻り値:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新しく作成された [IAudioFrame](../../com.aspose.slides/iaudioframe)。

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

既存の Presentation.Audios リストからオーディオ オブジェクトを使用して、新しいオーディオ フレームを作成し、シェイプコレクションの末尾に追加します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | 新しいオーディオ フレームの X 座標（ポイント）。 |
| y | float | 新しいオーディオ フレームの Y 座標（ポイント）。 |
| width | float | オーディオ フレームの幅（ポイント）。 |
| height | float | オーディオ フレームの高さ（ポイント）。 |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Presentation.Audios コレクションからの [IAudio](../../com.aspose.slides/iaudio) インスタンス。 |

**戻り値:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新しく作成された [IAudioFrame](../../com.aspose.slides/iaudioframe)。

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

既存の Presentation.Audios リストからオーディオ オブジェクトを使用して、新しいオーディオ フレームを作成し、指定インデックスに挿入します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | ゼロベースインデックス。オーディオ フレームを挿入する位置。 |
| x | float | 新しいオーディオ フレームの X 座標（ポイント）。 |
| y | float | 新しいオーディオ フレームの Y 座標（ポイント）。 |
| width | float | オーディオ フレームの幅（ポイント）。 |
| height | float | オーディオ フレームの高さ（ポイント）。 |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Presentation.Audios コレクションから埋め込む [IAudio](../../com.aspose.slides/iaudio) インスタンス。 |

**戻り値:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新しく作成された [IAudioFrame](../../com.aspose.slides/iaudioframe)。

### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public final int indexOf(IShape shape)
```

コレクション内で指定されたシェイプが最初に出現するゼロベースインデックスを返します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | コレクション内で検索するシェイプ。 |

**戻り値:**  
int - シェイプが見つかった場合はそのゼロベースインデックス、見つからない場合は -1。

### toArray() {#toArray--}
```
public final IShape[] toArray()
```

すべてのシェイプを含む配列を作成して返します。

**戻り値:**  
com.aspose.slides.IShape[] - [IShape](../../com.aspose.slides/ishape) オブジェクトの配列。

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IShape[] toArray(int startIndex, int count)
```

指定した範囲のすべてのシェイプを含む配列を作成して返します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| startIndex | int | 返す最初のシェイプのインデックス。 |
| count | int | 返すシェイプの数。 |

**戻り値:**  
com.aspose.slides.IShape[] - [IShape](../../com.aspose.slides/ishape) オブジェクトの配列。

### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public final void reorder(int index, IShape shape)
```

指定したシェイプをコレクション内の新しい位置に移動します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | シェイプを配置するゼロベースのターゲットインデックス。 |
| shape | [IShape](../../com.aspose.slides/ishape) | コレクション内で移動する [IShape](../../com.aspose.slides/ishape)。 |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public final void reorder(int index, IShape[] shapes)
```

指定したシェイプをコレクション内で移動し、指定インデックスから順に配置します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 最初のシェイプを配置するゼロベースのターゲットインデックス。続くシェイプは提供された順序で配置されます。 |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | 移動する 1 つ以上の [IShape](../../com.aspose.slides/ishape) インスタンス。 |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

デフォルトの書式設定で新しいオート シェイプを作成し、コレクションの末尾に追加します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shapeType | int | 追加するオート シェイプの [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | シェイプ フレームの X 座標（ポイント）。 |
| y | float | シェイプ フレームの Y 座標（ポイント）。 |
| width | float | シェイプ フレームの幅（ポイント）。 |
| height | float | シェイプ フレームの高さ（ポイント）。 |

**戻り値:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - 新しく作成された [IAutoShape](../../com.aspose.slides/iautoshape)。

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

デフォルトのテンプレート書式でオプション初期化しながら、新しいオート シェイプを作成してコレクションの末尾に追加します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shapeType | int | 追加するオート シェイプの [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | シェイプ フレームの X 座標（ポイント）。 |
| y | float | シェイプ フレームの Y 座標（ポイント）。 |
| width | float | シェイプ フレームの幅（ポイント）。 |
| height | float | シェイプ フレームの高さ（ポイント）。 |
| createFromTemplate | boolean | true の場合、デフォルトのテンプレート スタイリング（シンプル スタイル、中央揃えテキスト、名前が空でない）を新しいシェイプに適用します。false の場合、すべてのプロパティをデフォルト値に設定したシェイプを作成します。 |

**戻り値:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - 新しく作成された [IAutoShape](../../com.aspose.slides/iautoshape)。

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public final IAutoShape addMathShape(float x, float y, float width, float height)
```

数式コンテンツを保持する矩形オート シェイプを作成し、コレクションの末尾に追加します。

--------------------

> ```
> PowerPoint プレゼンテーションに数式を追加する方法の例を示します
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape mathShape = pres.getSlides().get_Item(0).getShapes().addMathShape(0, 0, 720, 150);
>      IMathParagraph mathParagraph = ((MathPortion)mathShape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>      IMathFraction fraction = new MathematicalText("x").divide("y");
>      mathParagraph.add(new MathBlock(fraction));
>      IMathBlock mathBlock = new MathematicalText("c")
>          .setSuperscript("2")
>          .join("=")
>          .join(new MathematicalText("a").setSuperscript("2"))
>          .join("+")
>          .join(new MathematicalText("b").setSuperscript("2"));
>      mathParagraph.add(mathBlock);
>      pres.save("math.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | シェイプ フレームの X 座標（ポイント）。 |
| y | float | シェイプ フレームの Y 座標（ポイント）。 |
| width | float | シェイプ フレームの幅（ポイント）。 |
| height | float | シェイプ フレームの高さ（ポイント）。 |

**戻り値:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - 新しく作成された [IAutoShape](../../com.aspose.slides/iautoshape)。

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

デフォルトのテンプレート書式を適用し、新しいオート シェイプを指定インデックスに挿入します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 挿入する新しいオート シェイプのゼロベースインデックス。 |
| shapeType | int | 挿入するオート シェイプの [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | シェイプ フレームの X 座標（ポイント）。 |
| y | float | シェイプ フレームの Y 座標（ポイント）。 |
| width | float | シェイプ フレームの幅（ポイント）。 |
| height | float | シェイプ フレームの高さ（ポイント）。 |

**戻り値:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - 新しく作成された [IAutoShape](../../com.aspose.slides/iautoshape)。

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

デフォルトのテンプレートスタイリングでオプション初期化しながら、新しいオート シェイプを指定インデックスに挿入します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 挿入するオート シェイプのゼロベースインデックス。 |
| shapeType | int | 挿入するオート シェイプの [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | シェイプ フレームの X 座標（ポイント）。 |
| y | float | シェイプ フレームの Y 座標（ポイント）。 |
| width | float | シェイプ フレームの幅（ポイント）。 |
| height | float | シェイプ フレームの高さ（ポイント）。 |
| createFromTemplate | boolean | true の場合、デフォルトのテンプレート スタイリング（名前が空でない、シンプル スタイル、中央揃えテキスト）を適用します。false の場合、すべてのプロパティをデフォルト値に設定したシェイプを作成します。 |

**戻り値:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - 新しく作成された [IAutoShape](../../com.aspose.slides/iautoshape)。

### addGroupShape() {#addGroupShape--}
```
public final IGroupShape addGroupShape()
```

空のグループ シェイプを作成し、コレクションの末尾に追加します。グループのフレームは追加されたシェイプに合わせて自動的に調整されます。

--------------------

> ```
> 以下の例は、PowerPoint プレゼンテーションのスライドにグループ シェイプを追加する方法を示します。
>  
>  // Presentation クラスのインスタンスを作成します
>  Presentation pres = new Presentation();
>  try {
>      // 最初のスライドを取得します
>      ISlide sld = pres.getSlides().get_Item(0);
>      // スライドのシェイプ コレクションにアクセスします
>      IShapeCollection slideShapes = sld.getShapes();
>      // スライドにグループ シェイプを追加します
>      IGroupShape groupShape = slideShapes.addGroupShape();
>      // 追加したグループ シェイプ内にシェイプを追加します
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 300, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 300, 100, 100);
>      // グループ シェイプのフレームを追加します
>      groupShape.setFrame(new ShapeFrame(100, 300, 500, 40, NullableBool.False, NullableBool.False, 0));
>      // PPTX ファイルをディスクに書き込みます
>      pres.save("GroupShape_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**  
[IGroupShape](../../com.aspose.slides/igroupshape) - 新しく作成された [IGroupShape](../../com.aspose.slides/igroupshape)。

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public final IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

指定された SVG 画像を個々のシェイプに変換し、結果のグループをコレクションの末尾に追加します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | シェイプに変換するベクトル コンテンツを含む [ISvgImage](../../com.aspose.slides/isvgimage)。 |
| x | float | グループ フレームの X 座標（ポイント）。 |
| y | float | グループ フレームの Y 座標（ポイント）。 |
| width | float | グループ フレームの幅（ポイント）。 |
| height | float | グループ フレームの高さ（ポイント）。 |

**戻り値:**  
[IGroupShape](../../com.aspose.slides/igroupshape) - 新しく作成された [IGroupShape](../../com.aspose.slides/igroupshape)。

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public final IGroupShape insertGroupShape(int index)
```

空のグループ シェイプを作成し、指定インデックスに挿入します。グループのフレームは追加されたシェイプに合わせて自動的に調整されます。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | グループ シェイプを挿入するゼロベースインデックス。 |

**戻り値:**  
[IGroupShape](../../com.aspose.slides/igroupshape) - 新しく作成された [IGroupShape](../../com.aspose.slides/igroupshape)。

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

デフォルトのテンプレート スタイリングで新しいコネクタ シェイプを作成し、コレクションの末尾に追加します。

--------------------

> ```
> 以下の例は、PowerPoint プレゼンテーションで 2 つのシェイプ（楕円と長方形）の間にコネクタ（曲がったコネクタ）を追加する方法を示します。
>  
>  // PPTX ファイルを表す Presentation クラスのインスタンスを作成します
>  Presentation pres = new Presentation();
>  try {
>      // 特定のスライドのシェイプ コレクションにアクセスします
>      IShapeCollection shapes = pres.getSlides().get_Item(0).getShapes();
>      // 楕円のオートシェイプを追加します
>      IAutoShape ellipse = shapes.addAutoShape(ShapeType.Ellipse, 0, 100, 100, 100);
>      // 長方形のオートシェイプを追加します
>      IAutoShape rectangle = shapes.addAutoShape(ShapeType.Rectangle, 100, 300, 100, 100);
>      // スライドのシェイプ コレクションにコネクタ シェイプを追加します
>      IConnector connector = shapes.addConnector(ShapeType.BentConnector2, 0, 0, 10, 10);
>      // コネクタを使用してシェイプを接続します
>      connector.setStartShapeConnectedTo(ellipse);
>      connector.setEndShapeConnectedTo(rectangle);
>      // シェイプ間の自動最短パスを設定する reroute を呼び出します
>      connector.reroute();
>      // プレゼンテーションを保存します
>      pres.save("Shapes-connector.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shapeType | int | 追加するコネクタ シェイプの [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | コネクタ フレームの X 座標（ポイント）。 |
| y | float | コネクタ フレームの Y 座標（ポイント）。 |
| width | float | コネクタ フレームの幅（ポイント）。 |
| height | float | コネクタ フレームの高さ（ポイント）。 |

**戻り値:**  
[IConnector](../../com.aspose.slides/iconnector) - 新しく作成された [IConnector](../../com.aspose.slides/iconnector)。

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

デフォルトのテンプレート スタイリングでオプション初期化しながら、新しいコネクタ シェイプをコレクションの末尾に追加します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shapeType | int | 作成するコネクタ シェイプの [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | コネクタ フレームの X 座標（ポイント）。 |
| y | float | コネクタ フレームの Y 座標（ポイント）。 |
| width | float | コネクタ フレームの幅（ポイント）。 |
| height | float | コネクタ フレームの高さ（ポイント）。 |
| createFromTemplate | boolean | true の場合、デフォルトのテンプレート スタイリング（名前が空でない、シンプル スタイル）を適用します。false の場合、デフォルト プロパティでコネクタを作成します。 |

**戻り値:**  
[IConnector](../../com.aspose.slides/iconnector) - 新しく作成された [IConnector](../../com.aspose.slides/iconnector)。

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

デフォルトのテンプレート スタイリングを適用し、指定インデックスに新しいコネクタ シェイプを挿入します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 挿入するコネクタ シェイプのゼロベースインデックス。 |
| shapeType | int | 挿入するコネクタ シェイプの [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | コネクタ フレームの X 座標（ポイント）。 |
| y | float | コネクタ フレームの Y 座標（ポイント）。 |
| width | float | コネクタ フレームの幅（ポイント）。 |
| height | float | コネクタ フレームの高さ（ポイント）。 |

**戻り値:**  
[IConnector](../../com.aspose.slides/iconnector) - 新しく作成された [IConnector](../../com.aspose.slides/iconnector)。

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public             public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

デフォルトのテンプレート スタイリングでオプション初期化しながら、指定インデックスに新しいコネクタ シェイプを挿入します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 挿入するコネクタ シェイプのゼロベースインデックス。 |
| shapeType | int | 挿入するコネクタ シェイプの [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | コネクタ フレームの X 座標（ポイント）。 |
| y | float | コネクタ フレームの Y 座標（ポイント）。 |
| width | float | コネクタ フレームの幅（ポイント）。 |
| height | float | コネクタ フレームの高さ（ポイント）。 |
| createFromTemplate | boolean | true の場合、デフォルトのテンプレート スタイリング（名前が空でない、シンプル スタイル）を適用します。false の場合、デフォルト プロパティでコネクタを作成します。 |

**戻り値:**  
[IConnector](../../com.aspose.slides/iconnector) - 新しく作成された [IConnector](../../com.aspose.slides/iconnector)。

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

指定された画像を含む新しいピクチャ フレームを作成し、コレクションの末尾に追加します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) に含まれるシェイプ タイプを指定します（線種は除く）。 |
| x | float | ピクチャ フレームの X 座標（ポイント）。 |
| y | float | ピクチャ フレームの Y 座標（ポイント）。 |
| width | float | ピクチャ フレームの幅（ポイント）。 |
| height | float | ピクチャ フレームの高さ（ポイント）。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | ピクチャ フレームに表示する [IPPImage](../../com.aspose.slides/ippimage)。 |

**戻り値:**  
[IPictureFrame](../../com.aspose.slides/ipictureframe) - 新しく作成された [IPictureFrame](../../com.aspose.slides/ipictureframe)。

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

指定された画像を含む新しいピクチャ フレームを作成し、指定インデックスに挿入します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | ピクチャ フレームを挿入するゼロベースインデックス。 |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) に含まれるシェイプ タイプを指定します（線種は除く）。 |
| x | float | ピクチャ フレームの X 座標（ポイント）。 |
| y | float | ピクチャ フレームの Y 座標（ポイント）。 |
| width | float | ピクチャ フレームの幅（ポイント）。 |
| height | float | ピクチャ フレームの高さ（ポイント）。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | ピクチャ フレームに表示する [IPPImage](../../com.aspose.slides/ippimage)。 |

**戻り値:**  
[IPictureFrame](../../com.aspose.slides/ipictureframe) - 新しく作成された [IPictureFrame](../../com.aspose.slides/ipictureframe)。

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public final ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

新しいテーブルを作成し、コレクションの末尾に追加します。

--------------------

> ```
> // PPTX ファイルを表す Presentation クラスのインスタンスを作成します
>  Presentation pres = new Presentation();
>  try
>  {
>      // 最初のスライドにアクセスします
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // 列の幅と行の高さを定義します
>      double[] dblCols = {50, 50, 50};
>      double[] dblRows = {50, 30, 30, 30, 30};
> 
>      // スライドにテーブル シェイプを追加します
>      ITable tbl = sld.getShapes().addTable(100, 50, dblCols, dblRows);
> 
>      // 各セルの枠線フォーマットを設定します
>      for (int row = 0; row < tbl.getRows().size(); row++)
>      {
>          for (int cell = 0; cell < tbl.getRows().get_Item(row).size(); cell++)
>          {
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().getFillFormat().setFillType((FillType.Solid));
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().setWidth(5);
>          }
>      }
>      // 行 1 のセル 1 と 2 を結合します
>      tbl.mergeCells(tbl.get_Item(0, 0), tbl.get_Item(1, 1), false);
> 
>      // 結合されたセルにテキストを追加します
>      tbl.get_Item(0, 0).getTextFrame().setText("Merged Cells");
> 
>      // PPTX をディスクに保存します
>      pres.save("table.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | テーブルの X 座標（ポイント）。 |
| y | float | テーブルの Y 座標（ポイント）。 |
| columnWidths | double[] | 各列の幅（ポイント）を表す double 配列。 |
| rowHeights | double[] | 各行の高さ（ポイント）を表す double 配列。 |

**戻り値:**  
[ITable](../../com.aspose.slides/itable) - 新しく作成された [ITable](../../com.aspose.slides/itable)。

### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public final ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

新しいテーブルを作成し、指定インデックスに挿入します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | テーブルを挿入するゼロベースインデックス。 |
| x | float | テーブルの X 座標（ポイント）。 |
| y | float | テーブルの Y 座標（ポイント）。 |
| columnWidths | double[] | 各列の幅（ポイント）を表す double 配列。 |
| rowHeights | double[] | 各行の高さ（ポイント）を表す double 配列。 |

**戻り値:**  
[ITable](../../com.aspose.slides/itable) - 新しく作成された [ITable](../../com.aspose.slides/itable)。

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

指定インデックスのシェイプをコレクションから削除します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除するシェイプのゼロベースインデックス。 |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public final void remove(IShape shape)
```

コレクションから指定シェイプの最初の出現を削除します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | 削除する [IShape](../../com.aspose.slides/ishape)。 |

### clear() {#clear--}
```
public final void clear()
```

コレクション内のすべてのシェイプを削除します。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iterator()
```

コレクションを反復処理する列挙子を返します。

**戻り値:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - コレクションを反復できる IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iteratorJava()
```

コレクション全体の Java イテレータを返します。

**戻り値:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - コレクション全体の java.util.Iterator。

### getParentGroup() {#getParentGroup--}
```
public             public final IGroupShape getParentGroup()
```

シェイプ コレクションの親グループ シェイプ オブジェクトを取得します。読み取り専用 [IGroupShape](../../com.aspose.slides/igroupshape)。

**戻り値:**  
[IGroupShape](../../com.aspose.slides/igroupshape)

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

指定されたシェイプのコピーを作成し、コレクションの末尾に追加します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | クローン対象のシェイプ。 |
| x | float | 新しいシェイプのフレームの X 座標（ポイント）。 |
| y | float | 新しいシェイプのフレームの Y 座標（ポイント）。 |
| width | float | 新しいシェイプのフレームの幅（ポイント）。 |
| height | float | 新しいシェイプのフレームの高さ（ポイント）。 |

**戻り値:**  
[IShape](../../com.aspose.slides/ishape) - 新しく作成された [IShape](../../com.aspose.slides/ishape)。

### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y)
```

指定されたシェイプのコピーを作成し、コレクションの末尾に追加します。新しいシェイプは sourceShape の幅と高さを保持します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | クローン対象のシェイプ。 |
| x | float | 新しいシェイプのフレームの X 座標（ポイント）。 |
| y | float | 新しいシェイプのフレームの Y 座標（ポイント）。 |

**戻り値:**  
[IShape](../../com.aspose.slides/ishape) - 新しく作成された [IShape](../../com.aspose.slides/ishape)。

### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public final IShape addClone(IShape sourceShape)
```

指定されたシェイプのコピーを作成し、コレクションの末尾に追加します。クローンされたシェイプは元の位置とサイズを保持します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | クローン対象の [IShape](../../com.aspose.slides/ishape)。 |

**戻り値:**  
[IShape](../../com.aspose.slides/ishape) - 新しく作成された [IShape](../../com.aspose.slides/ishape)。

### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

指定されたシェイプのコピーを作成し、指定インデックスに挿入します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | クローンしたシェイプを挿入するゼロベースインデックス。 |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | クローン対象の [IShape](../../com.aspose.slides/ishape)。 |
| x | float | クローンしたシェイプのフレームの X 座標（ポイント）。 |
| y | float | クローンしたシェイプのフレームの Y 座標（ポイント）。 |
| width | float | クローンしたシェイプのフレームの幅（ポイント）。 |
| height | float | クローンしたシェイプのフレームの高さ（ポイント）。 |

**戻り値:**  
[IShape](../../com.aspose.slides/ishape) - 新しく作成された [IShape](../../com.aspose.slides/ishape)。

### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y)
```

指定されたシェイプのコピーを作成し、指定インデックスに挿入します。新しいシェイプは sourceShape の幅と高さを保持します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | クローンしたシェイプを挿入するゼロベースインデックス。 |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | クローン対象の [IShape](../../com.aspose.slides/ishape)。 |
| x | float | クローンしたシェイプのフレームの X 座標（ポイント）。 |
| y | float | クローンしたシェイプのフレームの Y 座標（ポイント）。 |

**戻り値:**  
[IShape](../../com.aspose.slides/ishape) - 新しく作成された [IShape](../../com.aspose.slides/ishape)。

### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public final IShape insertClone(int index, IShape sourceShape)
```

指定されたシェイプのコピーを作成し、指定インデックスに挿入します。クローンされたシェイプは元の位置とサイズを保持します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | クローンしたシェイプを挿入するゼロベースインデックス。 |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | クローン対象の [IShape](../../com.aspose.slides/ishape)。 |

**戻り値:**  
[IShape](../../com.aspose.slides/ishape) - 新しく作成された [IShape](../../com.aspose.slides/ishape)。

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

コレクションのすべての要素を指定配列にコピーします。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標配列。 |
| index | int | 目標配列の開始インデックス。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

コレクションへのアクセスが同期化されているか（スレッドセーフか）を示す値を返します。読み取り専用 boolean 。

**戻り値:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public             public final Object getSyncRoot()
```

同期ルートを返します。読み取り専用 Object 。

**戻り値:**  
java.lang.Object