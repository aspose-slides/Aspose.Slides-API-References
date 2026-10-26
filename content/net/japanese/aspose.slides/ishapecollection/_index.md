---
title: IShapeCollection
second_title: Aspose.Sildes for .NET API リファレンス
description: シェイプのコレクションを表します。
type: docs
weight: 6980
url: /ja/aspose.slides/ishapecollection/
---
## IShapeCollection インターフェイス

シェイプのコレクションを表します。

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | 指定されたインデックスの要素を取得します。読み取り専用 [`IShape`](../ishape)。 |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | シェイプ コレクションの親グループ シェイプ オブジェクトを取得します。読み取り専用 [`IGroupShape`](../igroupshape)。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | CD トラックにリンクされた新しいオーディオ フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Presentation.Audios リストの既存のオーディオ オブジェクトを使用して、新しいオーディオ フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | 埋め込み WAV ファイルを持つ新しいオーディオ フレームを作成し、シェイプ コレクションの末尾に追加します。埋め込みオーディオは Presentation.Audios コレクションに追加されます。 |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | 外部オーディオ ファイルにリンクされた新しいオーディオ フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | デフォルトの書式設定で新しいオート シェイプを作成し、シェイプ コレクションの末尾に追加します。 |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | 新しいオート シェイプを作成し、シェイプ コレクションの末尾に追加します。オプションでデフォルトのテンプレート書式設定で初期化できます。 |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | 新しいチャートを作成し、サンプル系列データと設定で初期化し、シェイプ コレクションの末尾に追加します。 |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | 新しいチャートを作成し、サンプル系列データと設定で初期化し、シェイプ コレクションの末尾に追加します。 |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | 指定されたシェイプのコピーを作成し、シェイプ コレクションの末尾に追加します。クローンされたシェイプは元の位置とサイズを保持します。 |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | 指定されたシェイプのコピーを作成し、シェイプ コレクションの末尾に追加します。新しいシェイプは *sourceShape* の幅と高さを保持します。 |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | 指定されたシェイプのコピーを作成し、シェイプ コレクションの末尾に追加します。 |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | デフォルトのテンプレート スタイルで新しいコネクタ シェイプを作成し、シェイプ コレクションの末尾に追加します。 |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | 新しいコネクタ シェイプを作成し、シェイプ コレクションの末尾に追加します。オプションでデフォルトのテンプレート スタイルを適用できます。 |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | 空のグループ シェイプを新規作成し、シェイプ コレクションの末尾に追加します。グループのフレームは追加されたシェイプに合わせて自動的に調整されます。 |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | 新しいグループ シェイプを作成し、指定された SVG 画像を個々のシェイプに変換し、結果のグループをシェイプ コレクションの末尾に追加します。 |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | 数式コンテンツを配置するための新しい矩形オート シェイプを作成し、シェイプ コレクションの末尾に追加します。 |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | 新しい OLE オブジェクト フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | 新しい OLE オブジェクト フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | 指定された画像を含む新しい画像フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | 新しいセクション ズーム フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | 事前定義された画像とともに新しいセクション ズーム フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | SmartArt ダイアグラムを作成し、シェイプ コレクションの末尾に追加します。 |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | 新しいサマリー ズーム フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | 新しいテーブルを作成し、シェイプ コレクションの末尾に追加します。 |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | 新しいビデオ フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | 新しいビデオ フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | 新しいズーム フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | 新しいズーム フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [Clear](../../aspose.slides/ishapecollection/clear)() | シェイプ コレクションからすべてのシェイプを削除します。 |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | コレクション内で指定されたシェイプが最初に出現するインデックス（0 ベース）を返します。 |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | CD トラックにリンクされた新しいオーディオ フレームを作成し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Presentation.Audios リストの既存のオーディオ オブジェクトを使用して、新しいオーディオ フレームを作成し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | 埋め込み WAV ファイルを持つ新しいオーディオ フレームを作成し、指定されたインデックスにシェイプ コレクションに挿入します。埋め込みオーディオは Presentation.Audios コレクションに追加されます。 |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | 外部オーディオ ファイルにリンクされた新しいオーディオ フレームを作成し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | デフォルトのテンプレート書式設定で新しいオート シェイプを作成し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | 新しいオート シェイプを作成し、指定されたインデックスにシェイプ コレクションに挿入します。オプションでデフォルトのテンプレート スタイルで初期化できます。 |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | 新しいチャートを作成し、サンプル系列データと設定で初期化し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | 新しいチャートを作成し、サンプル系列データと設定で初期化し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | 指定されたシェイプのコピーを作成し、指定されたインデックスにシェイプ コレクションに挿入します。クローンされたシェイプは元の位置とサイズを保持します。 |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | 指定されたシェイプのコピーを作成し、指定されたインデックスにシェイプ コレクションに挿入します。新しいシェイプは *sourceShape* の幅と高さを保持します。 |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | 指定されたシェイプのコピーを作成し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | デフォルトのテンプレート スタイルで新しいコネクタ シェイプを作成し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | 新しいコネクタ シェイプを作成し、指定されたインデックスにシェイプ コレクションに挿入します。オプションでデフォルトのテンプレート スタイルを適用できます。 |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | 空のグループ シェイプを作成し、指定されたインデックスにシェイプ コレクションに挿入します。グループのフレームは追加されたシェイプに合わせて自動的に調整されます。 |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | 新しい OLE オブジェクト フレームを作成し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | 新しい OLE オブジェクト フレームを作成し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | 指定された画像を含む新しい画像フレームを作成し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | 新しいセクション ズーム フレームを作成し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | 事前定義された画像とともに新しいセクション ズーム フレームを作成し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | 新しいサマリー ズーム フレームを作成し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | 新しいテーブルを作成し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | 新しいビデオ フレームを作成し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | 新しいズーム フレームを作成し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | 事前定義された画像とともに新しいズーム フレームを作成し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | 指定されたシェイプの最初の出現をシェイプ コレクションから削除します。 |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | 指定されたインデックスのシェイプをシェイプ コレクションから削除します。 |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | 指定されたシェイプをシェイプ コレクション内の新しい位置に移動します。 |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | 指定されたシェイプをシェイプ コレクション内で移動し、指定されたインデックスから順に配置します。 |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | すべてのシェイプを含む配列を作成して返します。 |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | 指定された範囲内のシェイプを含む配列を作成して返します。 |

### 参照

* インターフェイス [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* インターフェイス [IShape](../ishape)
* 名前空間 [Aspose.Slides](../../aspose.slides)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->