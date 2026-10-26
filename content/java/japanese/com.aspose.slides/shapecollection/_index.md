---
title: ShapeCollection
second_title: Aspose.Slides for Java API リファレンス
description: 形状のコレクションを表します。
type: docs
url: /ja/com.aspose.slides/shapecollection/
---
**継承:**  
java.lang.Object, com.aspose.slides.DomObject

**実装されたすべてのインターフェイス:**  
[com.aspose.slides.IShapeCollection](../../com.aspose.slides/ishapecollection)  
```
public final class ShapeCollection extends DomObject<GroupShape> implements IShapeCollection
```

シェイプのコレクションを表します。  
## メソッド

| メソッド | 説明 |
| --- | --- |
| [size()](#size--) | コレクションに実際に含まれる要素数を取得します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | 新しいチャートを作成し、サンプルシリーズデータと設定で初期化し、シェイプコレクションの末尾に追加します。 |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | 新しいチャートを作成し、サンプルシリーズデータと設定で初期化し、シェイプコレクションの末尾に追加します。 |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | SmartArt ダイアグラムを作成し、シェイプコレクションの末尾に追加します。 |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | 新しいチャートを作成し、サンプルシリーズデータと設定で初期化し、指定されたインデックスにシェイプコレクションへ挿入します。 |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | 新しいチャートを作成し、サンプルシリーズデータと設定で初期化し、指定されたインデックスにシェイプコレクションへ挿入します。 |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | 新しいズーム フレームを作成し、シェイプコレクションの末尾に追加します。 |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | 新しいズーム フレームを作成し、シェイプコレクションの末尾に追加します。 |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | 新しいズーム フレームを作成し、指定されたインデックスにシェイプコレクションへ挿入します。 |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | 事前定義された画像を持つ新しいズーム フレームを作成し、指定されたインデックスにシェイプコレクションへ挿入します。 |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | 新しいセクション ズーム フレームを作成し、シェイプコレクションの末尾に追加します。 |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | 事前定義された画像を持つ新しいセクション ズーム フレームを作成し、シェイプコレクションの末尾に追加します。 |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | 新しいセクション ズーム フレームを作成し、指定されたインデックスにシェイプコレクションへ挿入します。 |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | 事前定義された画像を持つ新しいセクション ズーム フレームを作成し、指定されたインデックスにシェイプコレクションへ挿入します。 |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | 新しいサマリー ズーム フレームを作成し、シェイプコレクションの末尾に追加します。 |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | 新しいサマリー ズーム フレームを作成し、指定されたインデックスにシェイプコレクションへ挿入します。 |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | 新しい OLE オブジェクト フレームを作成し、シェイプコレクションの末尾に追加します。 |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | 新しい OLE オブジェクト フレームを作成し、シェイプコレクションの末尾に追加します。 |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | 新しい OLE オブジェクト フレームを作成し、指定されたインデックスにシェイプコレクションへ挿入します。 |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | 新しい OLE オブジェクト フレームを作成し、指定されたインデックスにシェイプコレクションへ挿入します。 |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | 新しいビデオ フレームを作成し、シェイプコレクションの末尾に追加します。 |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | 新しいビデオ フレームを作成し、シェイプコレクションの末尾に追加します。 |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | 新しいビデオ フレームを作成し、指定されたインデックスにシェイプコレクションへ挿入します。 |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | CD トラックにリンクされた新しいオーディオ フレームを作成し、シェイプコレクションの末尾に追加します。 |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | CD トラックにリンクされた新しいオーディオ フレームを作成し、指定されたインデックスにシェイプコレクションへ挿入します。 |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | 外部オーディオ ファイルにリンクされた新しいオーディオ フレームを作成し、シェイプコレクションの末尾に追加します。 |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | 外部オーディオ ファイルにリンクされた新しいオーディオ フレームを作成し、指定されたインデックスにシェイプコレクションへ挿入します。 |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | 埋め込み WAV ファイルを持つ新しいオーディオ フレームを作成し、シェイプコレクションの末尾に追加します。 |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | 埋め込み WAV ファイルを持つ新しいオーディオ フレームを作成し、指定されたインデックスにシェイプコレクションへ挿入します。 |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Presentation.Audios リストの既存オーディオ オブジェクトを使用して新しいオーディオ フレームを作成し、シェイプコレクションの末尾に追加します。 |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Presentation.Audios リストの既存オーディオ オブジェクトを使用して新しいオーディオ フレームを作成し、指定されたインデックスにシェイプコレクションへ挿入します。 |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | コレクション内で指定されたシェイプが最初に出現するゼロベースのインデックスを返します。 |
| [toArray()](#toArray--) | すべてのシェイプを含む配列を作成し、返します。 |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 指定された範囲のすべてのシェイプを含む配列を作成し、返します。 |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | 指定されたシェイプをシェイプコレクション内の新しい位置に移動します。 |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | 指定されたシェイプをシェイプコレクション内で移動し、指定されたインデックスから配置します。 |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | デフォルトの書式設定で新しいオートシェイプを作成し、シェイプコレクションの末尾に追加します。 |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | 新しいオートシェイプを作成し、シェイプコレクションの末尾に追加します。オプションでデフォルトのテンプレート書式設定で初期化できます。 |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | 数式コンテンツをホストする新しい矩形オートシェイプを作成し、シェイプコレクションの末尾に追加します。 |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | 新しいオートシェイプを作成し、指定されたインデックスにシェイプコレクションへ挿入し、デフォルトのテンプレート書式設定を適用します。 |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | 新しいオートシェイプを作成し、指定されたインデックスにシェイプコレクションへ挿入し、オプションでデフォルトのテンプレートスタイリングで初期化できます。 |
| [addGroupShape()](#addGroupShape--) | 空のグループシェイプを新規作成し、シェイプコレクションの末尾に追加します。 |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | 新しいグループシェイプを作成し、指定された SVG 画像を個々のシェイプに変換し、結果のグループをシェイプコレクションの末尾に追加します。 |
| [insertGroupShape(int index)](#insertGroupShape-int-) | 空のグループシェイプを新規作成し、指定されたインデックスにシェイプコレクションへ挿入します。 |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | デフォルトのテンプレートスタイリングで新しいコネクタシェイプを作成し、シェイプコレクションの末尾に追加します。 |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | 新しいコネクタシェイプを作成し、シェイプコレクションの末尾に追加します。オプションでデフォルトのテンプレートスタイリングを適用できます。 |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | 新しいコネクタシェイプを作成し、指定されたインデックスにシェイプコレクションへ挿入し、デフォルトのテンプレートスタイリングを適用します。 |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | 新しいコネクタシェイプを作成し、指定されたインデックスにシェイプコレクションへ挿入し、オプションでデフォルトのテンプレートスタイリングを適用できます。 |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | 指定された画像を含む新しい画像フレームを作成し、シェイプコレクションの末尾に追加します。 |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | 指定された画像を含む新しい画像フレームを作成し、指定されたインデックスにシェイプコレクションへ挿入します。 |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | 新しいテーブルを作成し、シェイプコレクションの末尾に追加します。 |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | 新しいテーブルを作成し、指定されたインデックスにシェイプコレクションへ挿入します。 |
| [removeAt(int index)](#removeAt-int-) | 指定されたインデックスのシェイプをシェイプコレクションから削除します。 |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | 指定されたシェイプの最初の出現をシェイプコレクションから削除します。 |
| [clear()](#clear--) | シェイプコレクションからすべてのシェイプを削除します。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
| [getParentGroup()](#getParentGroup--) | シェイプコレクションの親グループシェイプオブジェクトを取得します。 |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | 指定されたシェイプのコピーを作成し、シェイプコレクションの末尾に追加します。 |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | 指定されたシェイプのコピーを作成し、シェイプコレクションの末尾に追加します。 |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | 指定されたシェイプのコピーを作成し、シェイプコレクションの末尾に追加します。 |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | 指定されたシェイプのコピーを作成し、指定されたインデックスにシェイプコレクションへ挿入します。 |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | 指定されたシェイプのコピーを作成し、指定されたインデックスにシェイプコレクションへ挿入します。 |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | 指定されたシェイプのコピーを作成し、指定されたインデックスにシェイプコレクションへ挿入します。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | コレクションのすべての要素を指定された配列にコピーします。 |
| [isSynchronized()](#isSynchronized--) | コレクションへのアクセスが同期化されているか（スレッドセーフか）を示す値を返します。 |
| [getSyncRoot()](#getSyncRoot--) | 同期ルートを返します。 |

### size() {#size--}
```
public final int size()
```

コレクションに実際に含まれる要素数を取得します。 読み取り専用  int .

**戻り値:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IShape get_Item(int index)
```

指定されたインデックスの要素を取得します。 読み取り専用 [IShape](../../com.aspose.slides/ishape).

**パラメータ:**
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
>  // PPTX ファイルを表す Presentation クラスのインスタンスを生成します
>  Presentation pres = new Presentation();
>  try {
>      // 最初のスライドにアクセスします
>      ISlide sld = pres.getSlides().get_Item(0);
>      // デフォルトデータでチャートを追加します
>      IChart chart = sld.getShapes().addChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
>      // チャートのタイトルを設定します
>      chart.getChartTitle().addTextFrameForOverriding("Sample Title");
>      chart.getChartTitle().getTextFrameForOverriding().getTextFrameFormat().setCenterText(NullableBool.True);
>      chart.getChartTitle().setHeight(20);
>      chart.setTitle(true);
>      // 最初の系列に値を表示するよう設定します
>      chart.getChartData().getSeries().get_Item(0).getLabels().getDefaultDataLabelFormat().setShowValue(true);
>      // チャートデータシートのインデックスを設定します
>      int defaultWorksheetIndex = 0;
>      // チャートデータのワークシートを取得します
>      IChartDataWorkbook fact = chart.getChartData().getChartDataWorkbook();
>      // デフォルトで生成された系列とカテゴリを削除します
>      chart.getChartData().getSeries().clear();
>      chart.getChartData().getCategories().clear();
>      // 新しい系列を追加します
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.getType());
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.getType());
>      // 新しいカテゴリを追加します
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
>      // 最初のチャート系列を取得します
>      IChartSeries series = chart.getChartData().getSeries().get_Item(0);
>      // 系列データを入力します
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 1, 20));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 1, 50));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 1, 30));
>      // 系列の塗りつぶし色を設定します
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.RED);
>      // 2番目のチャート系列を取得します
>      series = chart.getChartData().getSeries().get_Item(1);
>      // 系列データを入力します
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 2, 30));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 2, 10));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 2, 60));
>      // 系列の塗りつぶし色を設定します
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.GREEN);
>      // 最初のラベルにカテゴリ名を表示するよう設定します
>      IDataLabel lbl = series.getDataPoints().get_Item(0).getLabel();
>      lbl.getDataLabelFormat().setShowCategoryName(true);
>      lbl = series.getDataPoints().get_Item(1).getLabel();
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      // 3番目のラベルに値を表示するよう系列を設定します
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


**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| type | int | 追加するチャートのタイプ。 |
| x | float | 新しいチャートの x 座標（ポイント単位）。 |
| y | float | 新しいチャートの y 座標（ポイント単位）。 |
| width | float | チャートの幅（ポイント単位）。 |
| height | float | チャートの高さ（ポイント単位）。 |

**戻り値:**
[IChart](../../com.aspose.slides/ichart) - 新しく作成された [IChart](../../com.aspose.slides/ichart).

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public final IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

新しいチャートを作成し、サンプルシリーズデータと設定で初期化し、シェイプコレクションの末尾に追加します。

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| type | int | 追加するチャートのタイプ。 |
| x | float | 新しいチャートの x 座標（ポイント単位）。 |
| y | float | 新しいチャートの y 座標（ポイント単位）。 |
| width | float | チャートの幅（ポイント単位）。 |
| height | float | チャートの高さ（ポイント単位）。 |
| initWithSample | boolean | true の場合、新しいチャートをサンプルシリーズデータと設定で初期化します。false の場合、シリーズなしで最小限の設定のみでチャートを作成し、作成が速くなります。 |

**戻り値:**
[IChart](../../com.aspose.slides/ichart) - 新しく作成された [IChart](../../com.aspose.slides/ichart).

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public final ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

SmartArt ダイアグラムを作成し、シェイプコレクションの末尾に追加します。

--------------------

> ```
> The following example shows how to add smart shape in PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      ISmartArt smart = slide.getShapes().addSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | ダイアグラムフレームの x 座標（ポイント単位）。 |
| y | float | ダイアグラムフレームの y 座標（ポイント単位）。 |
| width | float | ダイアグラムフレームの幅（ポイント単位）。 |
| height | float | ダイアグラムフレームの高さ（ポイント単位）。 |
| layoutType | int | SmartArt のレイアウトタイプ。 |

**戻り値:**
[ISmartArt](../../com.aspose.slides/ismartart) - 新しく作成された [ISmartArt](../../com.aspose.slides/ismartart).

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index)
```

新しいチャートを作成し、サンプルシリーズデータと設定で初期化し、指定されたインデックスにシェイプコレクションへ挿入します。

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| type | int | 作成するチャートのタイプ。 |
| x | float | 新しいチャートの x 座標（ポイント単位）。 |
| y | float | 新しいチャートの y 座標（ポイント単位）。 |
| width | float | 新しいチャートの幅（ポイント単位）。 |
| height | float | 新しいチャートの高さ（ポイント単位）。 |
| index | int | シェイプコレクションに新しいチャートを挿入するゼロベースのインデックス。 |

**戻り値:**
[IChart](../../com.aspose.slides/ichart) - 新しく作成された [IChart](../../com.aspose.slides/ichart).

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

新しいチャートを作成し、サンプルシリーズデータと設定で初期化し、指定されたインデックスにシェイプコレクションへ挿入します。

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| type | int | 作成するチャートのタイプ。 |
| x | float | 新しいチャートの x 座標（ポイント単位）。 |
| y | float | 新しいチャートの y 座標（ポイント単位）。 |
| width | float | 新しいチャートの幅（ポイント単位）。 |
| height | float | 新しいチャートの高さ（ポイント単位）。 |
| index | int | シェイプコレクションに新しいチャートを挿入するゼロベースのインデックス。 |
| initWithSample | boolean | true の場合、新しいチャートをサンプルシリーズデータと設定で初期化します。false の場合、シリーズなしで最小限の設定のみでチャートを作成し、作成が速くなります。 |
| x | float | 新しいチャートの x 座標（ポイント単位）。 |
| y | float | 新しいチャートの y 座標（ポイント単位）。 |
| width | float | 新しいチャートの幅（ポイント単位）。 |
| height | float | 新しいチャートの高さ（ポイント単位）。 |
| index | int | シェイプコレクションに新しいチャートを挿入する 0 ベースのインデックス。 |
| initWithSample | boolean | サンプルシリーズ データと設定で新しいチャートを初期化する場合は True、シリーズなしで最小設定のみで作成し、作成を高速化する場合は false。 |

**戻り値:**
[IChart](../../com.aspose.slides/ichart) - 新しく作成された [IChart](../../com.aspose.slides/ichart)。

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

新しいズーム フレームを作成し、シェイプコレクションの末尾に追加します。

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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | 新しいズーム フレームの x 座標（ポイント単位）。 |
| y | float | 新しいズーム フレームの y 座標（ポイント単位）。 |
| width | float | 新しいズーム フレームの幅（ポイント単位）。 |
| height | float | 新しいズーム フレームの高さ（ポイント単位）。 |
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
> This example demonstrates adding a Zoom object to the end of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | 新しいズーム フレームの x 座標（ポイント単位）。 |
| y | float | 新しいズーム フレームの y 座標（ポイント単位）。 |
| width | float | 新しいズーム フレームの幅（ポイント単位）。 |
| height | float | 新しいズーム フレームの高さ（ポイント単位）。 |
| slide | [ISlide](../../com.aspose.slides/islide) | ズーム フレームが参照する [ISlide](../../com.aspose.slides/islide)。このプレゼンテーションに属している必要があります。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 参照スライド [IPPImage](../../com.aspose.slides/ippimage) 用の画像。 |

**戻り値:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - 新しく作成された [IZoomFrame](../../com.aspose.slides/izoomframe)。

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

新しいズーム フレームを作成し、指定したインデックスにシェイプコレクションへ挿入します。

--------------------

> ```
> この例は、コレクションの指定インデックスに Zoom オブジェクトを作成して挿入する方法を示しています
>  （「Presentation.pptx」プレゼンテーションにスライドが少なくとも2枚あると仮定します）:
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ズーム フレームを挿入する 0 ベースのインデックス。 |
| x | float | 新しいズーム フレームの x 座標（ポイント単位）。 |
| y | float | 新しいズーム フレームの y 座標（ポイント単位）。 |
| width | float | 新しいズーム フレームの幅（ポイント単位）。 |
| height | float | 新しいズーム フレームの高さ（ポイント単位）。 |
| slide | [ISlide](../../com.aspose.slides/islide) | ズーム フレームが参照する [ISlide](../../com.aspose.slides/islide)。 |

**戻り値:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - 新しく作成された [IZoomFrame](../../com.aspose.slides/izoomframe)。

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

事前に定義された画像を使用して新しいズーム フレームを作成し、指定したインデックスにシェイプコレクションへ挿入します。

--------------------

> ```
> この例は、コレクションの指定インデックスに Zoom オブジェクトを作成して挿入する方法を示しています
>  （「Presentation.pptx」プレゼンテーションにスライドが少なくとも2枚あると仮定します）:
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ズーム フレームを挿入する 0 ベースのインデックス。 |
| x | float | 新しいズーム フレームの x 座標（ポイント単位）。 |
| y | float | 新しいズーム フレームの y 座標（ポイント単位）。 |
| width | float | 新しいズーム フレームの幅（ポイント単位）。 |
| height | float | 新しいズーム フレームの高さ（ポイント単位）。 |
| slide | [ISlide](../../com.aspose.slides/islide) | ズーム フレームが参照する [ISlide](../../com.aspose.slides/islide)。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 参照スライド [IPPImage](../../com.aspose.slides/ippimage) 用の画像。 |

**戻り値:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - 新しく作成された [IZoomFrame](../../com.aspose.slides/izoomframe)。

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

新しいセクション ズーム フレームを作成し、シェイプコレクションの末尾に追加します。

--------------------

> ```
> この例は、コレクションの末尾に Section Zoom オブジェクトを追加する方法を示しています
>  （「Presentation.pptx」プレゼンテーションにセクションが少なくとも2つあると仮定します）:
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | 新しいセクション ズーム フレームの x 座標（ポイント単位）。 |
| y | float | 新しいセクション ズーム フレームの y 座標（ポイント単位）。 |
| width | float | 新しいセクション ズーム フレームの幅（ポイント単位）。 |
| height | float | 新しいセクション ズーム フレームの高さ（ポイント単位）。 |
| section | [ISection](../../com.aspose.slides/isection) | セクション ズーム フレームが参照する [ISection](../../com.aspose.slides/isection)。このプレゼンテーションに属し、少なくとも 1 枚のスライドを含んでいる必要があります。 |

**戻り値:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 新しく作成された [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)。

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

事前に定義された画像を使用して新しいセクション ズーム フレームを作成し、シェイプコレクションの末尾に追加します。

--------------------

> ```
> この例は、コレクションの末尾に Section Zoom オブジェクトを追加する方法を示しています
>  （「Presentation.pptx」プレゼンテーションにセクションが少なくとも2つあると仮定します）:
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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | 新しいセクション ズーム フレームの x 座標（ポイント単位）。 |
| y | float | 新しいセクション ズーム フレームの y 座標（ポイント単位）。 |
| width | float | 新しいセクション ズーム フレームの幅（ポイント単位）。 |
| height | float | 新しいセクション ズーム フレームの高さ（ポイント単位）。 |
| section | [ISection](../../com.aspose.slides/isection) | セクション ズーム フレームが参照する [ISection](../../com.aspose.slides/isection)。このプレゼンテーションに属し、少なくとも 1 枚のスライドを含んでいる必要があります。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | セクション ズーム フレーム内に表示する [IPPImage](../../com.aspose.slides/ippimage)。 |

**戻り値:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 新しく作成された [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)。

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

新しいセクション ズーム フレームを作成し、指定したインデックスにシェイプコレクションへ挿入します。

--------------------

> ```
> この例は、コレクションの指定インデックスに Section Zoom オブジェクトを作成して挿入する方法を示しています
>  (「Presentation.pptx」プレゼンテーションにセクションが少なくとも2つあると仮定します):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | セクション ズーム フレームを挿入する 0 ベースのインデックス。 |
| x | float | 新しいセクション ズーム フレームの x 座標（ポイント単位）。 |
| y | float | 新しいセクション ズーム フレームの y 座標（ポイント単位）。 |
| width | float | 新しいセクション ズーム フレームの幅（ポイント単位）。 |
| height | float | 新しいセクション ズーム フレームの高さ（ポイント単位）。 |
| section | [ISection](../../com.aspose.slides/isection) | セクション ズーム フレームが参照する [ISection](../../com.aspose.slides/isection)。このプレゼンテーションに属し、少なくとも 1 枚のスライドを含んでいる必要があります。 |

**戻り値:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 新しく作成された [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)。

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

事前に定義された画像を使用して新しいセクション ズーム フレームを作成し、指定したインデックスにシェイプコレクションへ挿入します。

--------------------

> ```
> この例は、コレクションの指定インデックスに Section Zoom オブジェクトを作成して挿入する方法を示しています
>  （「Presentation.pptx」プレゼンテーションにセクションが少なくとも2つあると仮定します）:
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | セクション ズーム フレームを挿入する 0 ベースのインデックス。 |
| x | float | 新しいセクション ズーム フレームの x 座標（ポイント単位）。 |
| y | float | 新しいセクション ズーム フレームの y 座標（ポイント単位）。 |
| width | float | 新しいセクション ズーム フレームの幅（ポイント単位）。 |
| height | float | 新しいセクション ズーム フレームの高さ（ポイント単位）。 |
| section | [ISection](../../com.aspose.slides/isection) | セクション ズーム フレームが参照する [ISection](../../com.aspose.slides/isection)。このプレゼンテーションに属し、少なくとも 1 枚のスライドを含んでいる必要があります。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | セクション ズーム フレーム内に表示する画像。 |

**戻り値:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 新しく作成された [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)。

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public final ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

新しいサマリー ズーム フレームを作成し、シェイプコレクションの末尾に追加します。

--------------------

> ```
> この例は、コレクションの末尾に Summary Zoom オブジェクトを追加する方法を示しています
>  （「Presentation.pptx」プレゼンテーションにセクションが少なくとも2つあると仮定します）:
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | 新しいサマリー ズーム フレームの x 座標（ポイント単位）。 |
| y | float | 新しいサマリー ズーム フレームの y 座標（ポイント単位）。 |
| width | float | 新しいサマリー ズーム フレームの幅（ポイント単位）。 |
| height | float | 新しいサマリー ズーム フレームの高さ（ポイント単位）。 |

このメソッドは新しいサマリー ズームを作成し、プレゼンテーション内のすべてのセクションに対してオブジェクトのコレクションを配置します。

**戻り値:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - 新しく作成された [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)。

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public final ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

新しいサマリー ズーム フレームを作成し、指定したインデックスにシェイプコレクションへ挿入します。

--------------------

> ```
> この例は、コレクションの指定インデックスに Summary Zoom オブジェクトを作成して挿入する方法を示しています
>  （「Presentation.pptx」プレゼンテーションにセクションが少なくとも2つあると仮定します）:
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | サマリー ズーム フレームを挿入する 0 ベースのインデックス。 |
| x | float | 新しいサマリー ズーム フレームの x 座標（ポイント単位）。 |
| y | float | 新しいサマリー ズーム フレームの y 座標（ポイント単位）。 |
| width | float | 新しいサマリー ズーム フレームの幅（ポイント単位）。 |
| height | float | 新しいサマリー ズーム フレームの高さ（ポイント単位）。 |

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
> The following examples shows how to adding OLE Object Frames to Slides of PowerPoint Presentation.
>  
>  // PPTX を表す Presentation クラスのインスタンスを生成します
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
>      // 埋め込み用のデータオブジェクトを作成します
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


**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | 新しい OLE フレームの x 座標（ポイント単位）。 |
| y | float | 新しい OLE フレームの y 座標（ポイント単位）。 |
| width | float | 新しい OLE フレームの幅（ポイント単位）。 |
| height | float | 新しい OLE フレームの高さ（ポイント単位）。 |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | 埋め込み OLE データに関する情報（[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)）。 |

**戻り値:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 新しく作成された [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)。

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

新しい OLE オブジェクト フレームを作成し、シェイプコレクションの末尾に追加します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | 新しい OLE フレームの x 座標（ポイント単位）。 |
| y | float | 新しい OLE フレームの y 座標（ポイント単位）。 |
| width | float | 新しい OLE フレームの幅（ポイント単位）。 |
| height | float | 新しい OLE フレームの高さ（ポイント単位）。 |
| className | java.lang.String | OLE オブジェクトのクラス名。 |
| path | java.lang.String | リンクされたファイルへのパス。 このパスはプレゼンテーションに文字通り保存されます。相対パスを指定した場合、別ディレクトリからプレゼンテーションを開く際にファイルへアクセスできなくなります。 |

**戻り値:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 新しく作成された [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)。

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

新しい OLE オブジェクト フレームを作成し、指定したインデックスにシェイプコレクションへ挿入します。

--------------------

> ```
> この例は、2 番目のインデックスに OLE オブジェクトを挿入する方法を示しています:
>  
>  byte[] fileData = Files.readAllBytes(Paths.get("test.zip"));
>  IOleDataInfo dataInfo = new OleDataInfo(fileData, "zip");
>  IOleObjectFrame oleObjectFrame = slides.getShapes().addOleObjectFrame(2, 150, 20, 50, 50, dataInfo);
> ```

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | OLE オブジェクト フレームを挿入する 0 ベースのインデックス。 |
| x | float | 新しい OLE フレームの x 座標（ポイント単位）。 |
| y | float | 新しい OLE フレームの y 座標（ポイント単位）。 |
| width | float | 新しい OLE フレームの幅（ポイント単位）。 |
| height | float | 新しい OLE フレームの高さ（ポイント単位）。 |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | 埋め込み OLE データ情報（[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)）。 |

**戻り値:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 新しく作成された [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

新しい OLE オブジェクト フレームを作成し、指定されたインデックスでシェイプ コレクションに挿入します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | OLE オブジェクト フレームを挿入するゼロベースのインデックス。 |
| x | float | 新しい OLE フレームの x 座標（ポイント単位）。 |
| y | float | 新しい OLE フレームの y 座標（ポイント単位）。 |
| width | float | 新しい OLE フレームの幅（ポイント単位）。 |
| height | float | 新しい OLE フレームの高さ（ポイント単位）。 |
| className | java.lang.String | OLE オブジェクトのクラス名。 |
| path | java.lang.String | リンクされたファイルへのパス。

このパスはプレゼンテーションにそのまま保存されます。相対パスが指定された場合、別のディレクトリからプレゼンテーションを開くとファイルにアクセスできなくなります。

**戻り値:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 新しく作成された OLE オブジェクト フレーム。

### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

新しいビデオ フレームを作成し、シェイプ コレクションの末尾に追加します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | 新しいビデオ フレームの x 座標（ポイント単位）。 |
| y | float | 新しいビデオ フレームの y 座標（ポイント単位）。 |
| width | float | 新しいビデオ フレームの幅（ポイント単位）。 |
| height | float | 新しいビデオ フレームの高さ（ポイント単位）。 |
| fname | java.lang.String | 埋め込むビデオ ファイルのパスまたは名前。 |

**戻り値:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - 新しく作成された [IVideoFrame](../../com.aspose.slides/ivideoframe)。

### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

新しいビデオ フレームを作成し、シェイプ コレクションの末尾に追加します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | 新しいビデオ フレームの x 座標（ポイント単位）。 |
| y | float | 新しいビデオ フレームの y 座標（ポイント単位）。 |
| width | float | 新しいビデオ フレームの幅（ポイント単位）。 |
| height | float | 新しいビデオ フレームの高さ（ポイント単位）。 |
| video | [IVideo](../../com.aspose.slides/ivideo) | ビデオ フレームに埋め込む [IVideo](../../com.aspose.slides/ivideo)。 |

**戻り値:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - 新しく作成された [IVideoFrame](../../com.aspose.slides/ivideoframe)。

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public final IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

新しいビデオ フレームを作成し、指定されたインデックスでシェイプ コレクションに挿入します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ビデオ フレームを挿入するゼロベースのインデックス。 |
| x | float | 新しいビデオ フレームの x 座標（ポイント単位）。 |
| y | float | 新しいビデオ フレームの y 座標（ポイント単位）。 |
| width | float | 新しいビデオ フレームの幅（ポイント単位）。 |
| height | float | 新しいビデオ フレームの高さ（ポイント単位）。 |
| fname | java.lang.String | 埋め込むビデオ ファイルのパスまたは名前。 |

**戻り値:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - 新しく作成された [IVideoFrame](../../com.aspose.slides/ivideoframe)。

### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public final IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

CD トラックにリンクされた新しいオーディオ フレームを作成し、シェイプ コレクションの末尾に追加します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | 新しいオーディオ フレームの x 座標（ポイント単位）。 |
| y | float | 新しいオーディオ フレームの y 座標（ポイント単位）。 |
| width | float | 新しいオーディオ フレームの幅（ポイント単位）。 |
| height | float | 新しいオーディオ フレームの高さ（ポイント単位）。 |

**戻り値:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新しく作成された [IAudioFrame](../../com.aspose.slides/iaudioframe)。

### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public final IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

CD トラックにリンクされた新しいオーディオ フレームを作成し、指定されたインデックスでシェイプ コレクションに挿入します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | CD トラックにリンクされたオーディオ フレームを挿入するゼロベースのインデックス。 |
| x | float | 新しいオーディオ フレームの x 座標（ポイント単位）。 |
| y | float | 新しいオーディオ フレームの y 座標（ポイント単位）。 |
| width | float | 新しいオーディオ フレームの幅（ポイント単位）。 |
| height | float | 新しいオーディオ フレームの高さ（ポイント単位）。 |

**戻り値:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新しく作成された [IAudioFrame](../../com.aspose.slides/iaudioframe)。

### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public final IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

外部オーディオ ファイルにリンクされた新しいオーディオ フレームを作成し、シェイプ コレクションの末尾に追加します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | 新しいオーディオ フレームの x 座標（ポイント単位）。 |
| y | float | 新しいオーディオ フレームの y 座標（ポイント単位）。 |
| width | float | 新しいオーディオ フレームの幅（ポイント単位）。 |
| height | float | 新しいオーディオ フレームの高さ（ポイント単位）。 |
| fname | java.lang.String | 外部オーディオ ファイルへのパスまたは名前。 |

**戻り値:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新しく作成された [IAudioFrame](../../com.aspose.slides/iaudioframe)。

### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public final IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

外部オーディオ ファイルにリンクされた新しいオーディオ フレームを作成し、指定されたインデックスでシェイプ コレクションに挿入します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 外部オーディオ ファイルにリンクされたオーディオ フレームを挿入するゼロベースのインデックス。 |
| x | float | 新しいオーディオ フレームの x 座標（ポイント単位）。 |
| y | float | 新しいオーディオ フレームの y 座標（ポイント単位）。 |
| width | float | 新しいオーディオ フレームの幅（ポイント単位）。 |
| height | float | 新しいオーディオ フレームの高さ（ポイント単位）。 |
| fname | java.lang.String | 外部オーディオ ファイルへのパスまたは名前。 |

**戻り値:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新しく作成された [IAudioFrame](../../com.aspose.slides/iaudioframe)。

### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

埋め込み WAV ファイルを持つ新しいオーディオ フレームを作成し、シェイプ コレクションの末尾に追加します。埋め込みオーディオは Presentation.Audios コレクションに追加されます。

--------------------

> ```
> 以下の例は、Audio Frame の作成方法を示します。
>  
>  // プレゼンテーションファイルを表す Presentation クラスのインスタンスを生成します
>  Presentation pres = new Presentation();
>  try {
>      // 最初のスライドを取得します
>      ISlide sld = pres.getSlides().get_Item(0);
>      // wav 音声ファイルをストリームにロードします
>      FileInputStream fstr = new FileInputStream("sampleaudio.wav");
>      try {
>          // Audio Frame を追加します
>          IAudioFrame audioFrame = sld.getShapes().addAudioFrameEmbedded(50, 150, 100, 100, fstr);
>          // オーディオの再生モードと音量を設定します
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


**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | 新しいオーディオ フレームの x 座標（ポイント単位）。 |
| y | float | 新しいオーディオ フレームの y 座標（ポイント単位）。 |
| width | float | 新しいオーディオ フレームの幅（ポイント単位）。 |
| height | float | 新しいオーディオ フレームの高さ（ポイント単位）。 |
| audio_stream | java.io.InputStream | WAV オーディオ データを含む入力ストリーム。 |

**戻り値:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新しく作成された [IAudioFrame](../../com.aspose.slides/iaudioframe)。

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

埋め込み WAV ファイルを持つ新しいオーディオ フレームを作成し、指定されたインデックスでシェイプ コレクションに挿入します。埋め込みオーディオは Presentation.Audios コレクションに追加されます。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 埋め込み WAV ファイルを持つオーディオ フレームを挿入するゼロベースのインデックス。 |
| x | float | 新しいオーディオ フレームの x 座標（ポイント単位）。 |
| y | float | 新しいオーディオ フレームの y 座標（ポイント単位）。 |
| width | float | 新しいオーディオ フレームの幅（ポイント単位）。 |
| height | float | 新しいオーディオ フレームの高さ（ポイント単位）。 |
| audio_stream | java.io.InputStream | WAV オーディオ データを含む入力ストリーム。 |

**戻り値:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新しく作成された [IAudioFrame](../../com.aspose.slides/iaudioframe)。

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

Presentation.Audios リストにある既存のオーディオ オブジェクトを使用して、新しいオーディオ フレームを作成し、シェイプ コレクションの末尾に追加します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | 新しいオーディオ フレームの x 座標（ポイント単位）。 |
| y | float | 新しいオーディオ フレームの y 座標（ポイント単位）。 |
| width | float | 新しいオーディオ フレームの幅（ポイント単位）。 |
| height | float | 新しいオーディオ フレームの高さ（ポイント単位）。 |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Presentation.Audios コレクションからの [IAudio](../../com.aspose.slides/iaudio) インスタンス。 |

**戻り値:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新しく作成された [IAudioFrame](../../com.aspose.slides/iaudioframe)。

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Presentation.Audios リストにある既存のオーディオ オブジェクトを使用して、新しいオーディオ フレームを作成し、指定されたインデックスでシェイプ コレクションに挿入します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 既存のオーディオ オブジェクトを使用してオーディオ フレームを挿入するゼロベースのインデックス。 |
| x | float | 新しいオーディオ フレームの x 座標（ポイント単位）。 |
| y | float | 新しいオーディオ フレームの y 座標（ポイント単位）。 |
| width | float | 新しいオーディオ フレームの幅（ポイント単位）。 |
| height | float | 新しいオーディオ フレームの高さ（ポイント単位）。 |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Presentation.Audios コレクションから埋め込む [IAudio](../../com.aspose.slides/iaudio) インスタンス。 |

**戻り値:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新しく作成された [IAudioFrame](../../com.aspose.slides/iaudioframe)。

### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public final int indexOf(IShape shape)
```

コレクション内で指定されたシェイプが最初に出現するゼロベースのインデックスを返します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | コレクション内で検索するシェイプ。 |

**戻り値:**
int - シェイプ コレクション内でシェイプが最初に出現するゼロベースのインデックス（見つかった場合）。見つからない場合は \\u20131。

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

指定された範囲内のすべてのシェイプを含む配列を作成して返します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | 返す最初のシェイプのインデックス。 |
| count | int | 返すシェイプの数。 |

**戻り値:**
com.aspose.slides.IShape[] - [IShape](../../com.aspose.slides/ishape) オブジェクトの配列。

### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public final void reorder(int index, IShape shape)
```

指定されたシェイプをシェイプ コレクション内の新しい位置に移動します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | シェイプが配置されるゼロベースの対象インデックス。 |
| shape | [IShape](../../com.aspose.slides/ishape) | コレクション内で移動する [IShape](../../com.aspose.slides/ishape)。 |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public final void reorder(int index, IShape[] shapes)
```

指定されたシェイプをシェイプ コレクション内で移動し、指定されたインデックスから順に配置します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 最初のシェイプが配置されるゼロベースの対象インデックス。以降のシェプは提供された順序で続きます。 |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | コレクション内で移動させる [IShape](../../com.aspose.slides/ishape) インスタンスが 1 つ以上です。 |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

デフォルトの書式設定で新しいオートシェイプを作成し、シェイプ コレクションの末尾に追加します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | 追加するオートシェイプの [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | シェイプのフレームの x 座標（ポイント単位）。 |
| y | float | シェイプのフレームの y 座標（ポイント単位）。 |
| width | float | シェイプのフレームの幅（ポイント単位）。 |
| height | float | シェイプのフレームの高さ（ポイント単位）。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 新しく作成された [IAutoShape](../../com.aspose.slides/iautoshape)。

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

新しいオートシェイプを作成し、シェイプ コレクションの末尾に追加します。必要に応じてデフォルトのテンプレート書式で初期化できます。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | 追加するオートシェイプの [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | シェイプのフレームの x 座標（ポイント単位）。 |
| y | float | シェイプのフレームの y 座標（ポイント単位）。 |
| width | float | シェイプのフレームの幅（ポイント単位）。 |
| height | float | シェイプのフレームの高さ（ポイント単位）。 |
| createFromTemplate | boolean | true の場合、デフォルトのテンプレート スタイル（シンプルなスタイル、中央揃えテキスト、名前が空でない）を新しいシェイプに適用します。false の場合、すべてのプロパティを既定値にしてシェイプを作成します。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 新しく作成された [IAutoShape](../../com.aspose.slides/iautoshape)。

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public final IAutoShape addMathShape(float x, float y, float width, float height)
```

数式コンテンツをホストするための新しい矩形オートシェイプを作成し、シェイプ コレクションの末尾に追加します。

--------------------

> ```
> 以下の例は、PowerPoint プレゼンテーションに数式を追加する方法を示しています。
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


**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | シェイプのフレームの x 座標（ポイント単位）。 |
| y | float | シェイプのフレームの y 座標（ポイント単位）。 |
| width | float | シェイプのフレームの幅（ポイント単位）。 |
| height | float | シェイプのフレームの高さ（ポイント単位）。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 新しく作成された [IAutoShape](../../com.aspose.slides/iautoshape)。

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

新しいオートシェイプを作成し、指定したインデックスにシェイプ コレクションへ挿入し、デフォルトのテンプレート書式を適用します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 新しいオートシェイプを挿入する zero-based インデックス。 |
| shapeType | int | 挿入するオートシェイプの [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | シェイプのフレームの x 座標（ポイント単位）。 |
| y | float | シェイプのフレームの y 座標（ポイント単位）。 |
| width | float | シェイプのフレームの幅（ポイント単位）。 |
| height | float | シェイプのフレームの高さ（ポイント単位）。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 新しく作成された [IAutoShape](../../com.aspose.slides/iautoshape)。

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

新しいオートシェイプを作成し、指定したインデックスにシェイプ コレクションへ挿入します。必要に応じてデフォルトのテンプレート スタイルで初期化できます。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | オートシェイプを挿入する zero-based インデックス。 |
| shapeType | int | 挿入するオートシェイプの [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | シェイプのフレームの x 座標（ポイント単位）。 |
| y | float | シェイプのフレームの y 座標（ポイント単位）。 |
| width | float | シェイプのフレームの幅（ポイント単位）。 |
| height | float | シェイプのフレームの高さ（ポイント単位）。 |
| createFromTemplate | boolean | true の場合、デフォルトのテンプレート スタイル（名前が空でない、シンプルなスタイル、中央揃えテキスト）を適用します。false の場合、すべてのプロパティを既定値にしてシェイプを作成します。 |

**戻り値:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 新しく作成された [IAutoShape](../../com.aspose.slides/iautoshape)。

### addGroupShape() {#addGroupShape--}
```
public final IGroupShape addGroupShape()
```

空のグループシェイプを新規作成し、シェイプ コレクションの末尾に追加します。グループのフレームは、追加されたシェイプに合わせて自動的に調整されます。

--------------------

> ```
> The following example shows how to add a group shape to a slide of PowerPoint Presentation.
>  
>  // Presentation クラスのインスタンス化
>  Presentation pres = new Presentation();
>  try {
>      // 最初のスライドを取得
>      ISlide sld = pres.getSlides().get_Item(0);
>      // スライドのシェイプコレクションにアクセス
>      IShapeCollection slideShapes = sld.getShapes();
>      // スライドにグループシェイプを追加
>      IGroupShape groupShape = slideShapes.addGroupShape();
>      // 追加したグループシェイプ内にシェイプを追加
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 300, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 300, 100, 100);
>      // グループシェイプのフレームを設定
>      groupShape.setFrame(new ShapeFrame(100, 300, 500, 40, NullableBool.False, NullableBool.False, 0));
>      // PPTX ファイルをディスクに書き込み
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

新しいグループシェイプを作成し、指定された SVG 画像を個々のシェイプに変換して、結果のグループをシェイプ コレクションの末尾に追加します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | シェイプに変換するベクトル コンテンツを含む [ISvgImage](../../com.aspose.slides/isvgimage)。 |
| x | float | グループのフレームの x 座標（ポイント単位）。 |
| y | float | グループのフレームの y 座標（ポイント単位）。 |
| width | float | グループのフレームの幅（ポイント単位）。 |
| height | float | グループのフレームの高さ（ポイント単位）。 |

**戻り値:**
[IGroupShape](../../com.aspose.slides/igroupshape) - 新しく作成された [IGroupShape](../../com.aspose.slides/igroupshape)。

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public final IGroupShape insertGroupShape(int index)
```

空のグループシェイプを新規作成し、指定したインデックスにシェイプ コレクションへ挿入します。グループのフレームは、追加されたシェイプに合わせて自動的に調整されます。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | グループシェイプを挿入する zero-based インデックス。 |

**戻り値:**
[IGroupShape](../../com.aspose.slides/igroupshape) - 新しく作成された [IGroupShape](../../com.aspose.slides/igroupshape)。

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

デフォルトのテンプレート スタイルで新しいコネクタ シェイプを作成し、シェイプ コレクションの末尾に追加します。

--------------------

> ```
> The following example shows how to add a connector (a bent connector) between two shapes (an ellipse and rectangle) in PowerPoint Presentation.
>  
>  // Instantiates a presentation class that represents a PPTX file
>  Presentation pres = new Presentation();
>  try {
>      // Accesses the shapes collection for a specific slide
>      IShapeCollection shapes = pres.getSlides().get_Item(0).getShapes();
>      // Adds an Ellipse autoshape
>      IAutoShape ellipse = shapes.addAutoShape(ShapeType.Ellipse, 0, 100, 100, 100);
>      // Adds a Rectangle autoshape
>      IAutoShape rectangle = shapes.addAutoShape(ShapeType.Rectangle, 100, 300, 100, 100);
>      // Adds a connector shape to the slide shape collection
>      IConnector connector = shapes.addConnector(ShapeType.BentConnector2, 0, 0, 10, 10);
>      // Connects the shapes using the connector
>      connector.setStartShapeConnectedTo(ellipse);
>      connector.setEndShapeConnectedTo(rectangle);
>      // Calls reroute that sets the automatic shortest path between shapes
>      connector.reroute();
>      // Saves the presentation
>      pres.save("Shapes-connector.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | 追加するコネクタ シェイプの [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | コネクタのフレームの x 座標（ポイント単位）。 |
| y | float | コネクタのフレームの y 座標（ポイント単位）。 |
| width | float | コネクタのフレームの幅（ポイント単位）。 |
| height | float | コネクタのフレームの高さ（ポイント単位）。 |

**戻り値:**
[IConnector](../../com.aspose.slides/iconnector) - 新しく作成された [IConnector](../../com.aspose.slides/iconnector)。

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

新しいコネクタ シェイプを作成し、シェイプ コレクションの末尾に追加します。必要に応じてデフォルトのテンプレート スタイルを適用できます。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | 作成するコネクタ シェイプの [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | コネクタのフレームの x 座標（ポイント単位）。 |
| y | float | コネクタのフレームの y 座標（ポイント単位）。 |
| width | float | コネクタのフレームの幅（ポイント単位）。 |
| height | float | コネクタのフレームの高さ（ポイント単位）。 |
| createFromTemplate | boolean | true の場合、デフォルトのテンプレート スタイル（名前が空でない、シンプルなスタイル）を適用します。false の場合、デフォルトのプロパティ値でコネクタを作成します。 |

**戻り値:**
[IConnector](../../com.aspose.slides/iconnector) - 新しく作成された [IConnector](../../com.aspose.slides/iconnector)。

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

新しいコネクタ シェイプを作成し、指定したインデックスにシェイプ コレクションへ挿入し、デフォルトのテンプレート スタイルを適用します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | コネクタ シェイプを挿入する zero-based インデックス。 |
| shapeType | int | 挿入するコネクタ シェイプの [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | コネクタのフレームの x 座標（ポイント単位）。 |
| y | float | コネクタのフレームの y 座標（ポイント単位）。 |
| width | float | コネクタのフレームの幅（ポイント単位）。 |
| height | float | コネクタのフレームの高さ（ポイント単位）。 |

**戻り値:**
[IConnector](../../com.aspose.slides/iconnector) - 新しく作成された [IConnector](../../com.aspose.slides/iconnector)。

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

新しいコネクタ シェイプを作成し、指定したインデックスにシェイプ コレクションへ挿入します。必要に応じてデフォルトのテンプレート スタイルを適用できます。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | コネクタ シェイプを挿入する zero-based インデックス。 |
| shapeType | int | 挿入するコネクタ シェイプの [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | コネクタのフレームの x 座標（ポイント単位）。 |
| y | float | コネクタのフレームの y 座標（ポイント単位）。 |
| width | float | コネクタのフレームの幅（ポイント単位）。 |
| height | float | コネクタのフレームの高さ（ポイント単位）。 |
| createFromTemplate | boolean | true の場合、デフォルトのテンプレート スタイル（名前が空でない、シンプルなスタイル）を適用します。false の場合、デフォルトのプロパティ値でコネクタを作成します。 |

**戻り値:**
[IConnector](../../com.aspose.slides/iconnector) - 新しく作成された [IConnector](../../com.aspose.slides/iconnector)。

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

指定された画像を含む新しいピクチャ フレームを作成し、シェイプ コレクションの末尾に追加します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) に含まれるシェイプタイプを指定します（ただしすべての線種は除く）：

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5. |
| x | float | ピクチャ フレームの x 座標（ポイント単位）。 |
| y | float | ピクチャ フレームの y 座標（ポイント単位）。 |
| width | float | ピクチャ フレームの幅（ポイント単位）。 |
| height | float | ピクチャ フレームの高さ（ポイント単位）。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | ピクチャ フレームに表示する [IPPImage](../../com.aspose.slides/ippimage)。 |

**戻り値:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - 新しく作成された [IPictureFrame](../../com.aspose.slides/ipictureframe)。

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

指定された画像を含む新しいピクチャ フレームを作成し、指定したインデックスにシェイプ コレクションへ挿入します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ピクチャ フレームを挿入する zero-based インデックス。 |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) に含まれるシェイプタイプを指定します（ただしすべての線種は除く）：

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5. |
| x | float | ピクチャ フレームの x 座標（ポイント単位）。 |
| y | float | ピクチャ フレームの y 座標（ポイント単位）。 |
| width | float | ピクチャ フレームの幅（ポイント単位）。 |
| height | float | ピクチャ フレームの高さ（ポイント単位）。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | ピクチャ フレームに表示する [IPPImage](../../com.aspose.slides/ippimage)。 |

**戻り値:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - 新しく作成された [IPictureFrame](../../com.aspose.slides/ipictureframe)。

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public final ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

新しいテーブルを作成し、シェイプ コレクションの末尾に追加します。

--------------------

> ```
> 以下の例は、PowerPoint プレゼンテーションにテーブルを追加する方法を示しています。
>  
>  // PPTX ファイルを表す Presentation クラスのインスタンスを生成します
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
>      // 各セルの罫線書式を設定します
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
>      // 結合したセルにテキストを追加します
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
| x | float | テーブルの x 座標（ポイント単位）。 |
| y | float | テーブルの y 座標（ポイント単位）。 |
| columnWidths | double[] | テーブルの列の幅をポイント単位で表す double の配列。 |
| rowHeights | double[] | テーブルの行の高さをポイント単位で表す double の配列。 |

**戻り値:**
[ITable](../../com.aspose.slides/itable) - 新しく作成された [ITable](../../com.aspose.slides/itable).
### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public final ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```


新しいテーブルを作成し、指定されたインデックスでシェイプ コレクションに挿入します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | テーブルを挿入するゼロベースのインデックス。 |
| x | float | テーブルの x 座標（ポイント単位）。 |
| y | float | テーブルの y 座標（ポイント単位）。 |
| columnWidths | double[] | テーブルの列の幅をポイント単位で表す double の配列。 |
| rowHeights | double[] | テーブルの行の高さをポイント単位で表す double の配列。 |

**戻り値:**
[ITable](../../com.aspose.slides/itable) - 新しく作成された [ITable](../../com.aspose.slides/itable).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


指定されたインデックスのシェイプをシェイプ コレクションから削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除するシェイプのゼロベース インデックス。 |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public final void remove(IShape shape)
```


指定されたシェイプの最初の出現をシェイプ コレクションから削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | 削除する [IShape](../../com.aspose.slides/ishape)。 |

### clear() {#clear--}
```
public final void clear()
```


シェイプ コレクションからすべてのシェイプを削除します。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iterator()
```


コレクションを反復処理する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - コレクションを反復処理できる IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iteratorJava()
```


コレクション全体の Java イテレーターを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - コレクション全体の java.util.Iterator。

### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```


シェイプ コレクションの親グループ シェイプ オブジェクトを取得します。 読み取り専用 [IGroupShape](../../com.aspose.slides/igroupshape)。

**戻り値:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```


指定されたシェイプのコピーを作成し、シェイプ コレクションの末尾に追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | クローン元のシェイプ。 |
| x | float | 新しいシェイプのフレームの x 座標（ポイント単位）。 |
| y | float | 新しいシェイプのフレームの y 座標（ポイント単位）。 |
| width | float | 新しいシェイプのフレームの幅（ポイント単位）。 |
| height | float | 新しいシェイプのフレームの高さ（ポイント単位）。 |

**戻り値:**
[IShape](../../com.aspose.slides/ishape) - 新しく作成された [IShape](../../com.aspose.slides/ishape)。
### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y)
```


指定されたシェイプのコピーを作成し、シェイプ コレクションの末尾に追加します。新しいシェイプは sourceShape の幅と高さを保持します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | クローン元のシェイプ。 |
| x | float | 新しいシェイプのフレームの x 座標（ポイント単位）。 |
| y | float | 新しいシェイプのフレームの y 座標（ポイント単位）。 |

**戻り値:**
[IShape](../../com.aspose.slides/ishape) - 新しく作成された [IShape](../../com.aspose.slides/ishape)。
### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public final IShape addClone(IShape sourceShape)
```


指定されたシェイプのコピーを作成し、シェイプ コレクションの末尾に追加します。クローンされたシェイプは元の位置とサイズを保持します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | クローンする [IShape](../../com.aspose.slides/ishape)。 |

**戻り値:**
[IShape](../../com.aspose.slides/ishape) - 新しく作成された [IShape](../../com.aspose.slides/ishape)。
### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```


指定されたシェイプのコピーを作成し、指定されたインデックスでシェイプ コレクションに挿入します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | クローンされたシェイプを挿入するゼロベースのインデックス。 |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | クローンする [IShape](../../com.aspose.slides/ishape)。 |
| x | float | クローンされたシェイプのフレームの x 座標（ポイント単位）。 |
| y | float | クローンされたシェイプのフレームの y 座標（ポイント単位）。 |
| width | float | クローンされたシェイプのフレームの幅（ポイント単位）。 |
| height | float | クローンされたシェイプのフレームの高さ（ポイント単位）。 |

**戻り値:**
[IShape](../../com.aspose.slides/ishape) - 新しく作成された [IShape](../../com.aspose.slides/ishape)。
### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y)
```


指定されたシェイプのコピーを作成し、指定されたインデックスでシェイプ コレクションに挿入します。新しいシェイプは sourceShape の幅と高さを保持します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | クローンされたシェイプを挿入するゼロベースのインデックス。 |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | クローンする [IShape](../../com.aspose.slides/ishape)。 |
| x | float | クローンされたシェイプのフレームの x 座標（ポイント単位）。 |
| y | float | クローンされたシェイプのフレームの y 座標（ポイント単位）。 |

**戻り値:**
[IShape](../../com.aspose.slides/ishape) - 新しく作成された [IShape](../../com.aspose.slides/ishape)。
### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public final IShape insertClone(int index, IShape sourceShape)
```


指定されたシェイプのコピーを作成し、指定されたインデックスでシェイプ コレクションに挿入します。クローンされたシェイプは元の位置とサイズを保持します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | クローンされたシェイプを挿入するゼロベースのインデックス。 |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | クローンする [IShape](../../com.aspose.slides/ishape)。 |

**戻り値:**
[IShape](../../com.aspose.slides/ishape) - 新しく作成された [IShape](../../com.aspose.slides/ishape)。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


コレクションのすべての要素を指定された配列にコピーします。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目的配列。 |
| index | int | 目的配列の開始インデックス。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


コレクションへのアクセスが同期化（スレッド セーフ）されているかどうかを示す値を返します。 読み取り専用  boolean 。

**戻り値:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


同期ルートを返します。 読み取り専用  Object 。

**戻り値:**
java.lang.Object