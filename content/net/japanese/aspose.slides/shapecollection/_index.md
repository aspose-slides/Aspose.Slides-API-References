---
title: ShapeCollection
second_title: Aspose.Sildes for .NET API リファレンス
description: 図形のコレクションを表します。
type: docs
weight: 9860
url: /ja/aspose.slides/shapecollection/
---
## ShapeCollection クラス

図形のコレクションを表します。

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | コレクションに実際に含まれる要素の数を取得します。読み取り専用 Int32。 |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | コレクションへのアクセスが同期化されているか（スレッドセーフ）を示す値を返します。読み取り専用 Boolean。 |
| [Item](../../aspose.slides/shapecollection/item) { get; } | 指定したインデックスの要素を取得します。読み取り専用 [`IShape`](../ishape)。 |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | シェイプ コレクションの親グループ シェイプ オブジェクトを取得します。読み取り専用 [`IGroupShape`](../igroupshape)。 |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | 同期ルートを返します。読み取り専用 Object。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | CD トラックにリンクされた新しいオーディオフレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Presentation.Audios リストの既存のオーディオオブジェクトを使用して、新しいオーディオフレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | 埋め込み WAV ファイルを持つ新しいオーディオフレームを作成し、シェイプ コレクションの末尾に追加します。埋め込みオーディオは Presentation.Audios コレクションに追加されます。 |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | 外部オーディオファイルにリンクされた新しいオーディオフレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | デフォルトの書式設定で新しいオートシェイプを作成し、シェイプ コレクションの末尾に追加します。 |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | 新しいオートシェイプを作成し、シェイプ コレクションの末尾に追加します。オプションでデフォルトテンプレートの書式設定で初期化できます。 |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | 新しいチャートを作成し、サンプル系列データと設定で初期化し、シェイプ コレクションの末尾に追加します。 |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | 新しいチャートを作成し、サンプル系列データと設定で初期化し、シェイプ コレクションの末尾に追加します。 |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | 指定されたシェイプのコピーを作成し、シェイプ コレクションの末尾に追加します。クローンされたシェイプは元の位置とサイズを保持します。 |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | 指定されたシェイプのコピーを作成し、シェイプ コレクションの末尾に追加します。新しいシェイプは *sourceShape* の幅と高さを保持します。 |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | 指定されたシェイプのコピーを作成し、シェイプ コレクションの末尾に追加します。 |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | デフォルトテンプレートのスタイリングで新しいコネクタ シェイプを作成し、シェイプ コレクションの末尾に追加します。 |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | 新しいコネクタ シェイプを作成し、シェイプ コレクションの末尾に追加します。オプションでデフォルトテンプレートのスタイリングを適用できます。 |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | 新しい空のグループ シェイプを作成し、シェイプ コレクションの末尾に追加します。グループのフレームは追加されたシェイプに合わせて自動的に調整されます。 |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | 新しいグループ シェイプを作成し、指定された SVG 画像を個々のシェイプに変換し、生成されたグループをシェイプ コレクションの末尾に追加します。 |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | 数式コンテンツをホストする新しい矩形オートシェイプを作成し、シェイプ コレクションの末尾に追加します。 |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | 新しい OLE オブジェクト フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | 新しい OLE オブジェクト フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | 指定された画像を含む新しい画像フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | 新しい Section Zoom フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | 事前定義された画像を使用した新しい Section Zoom フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | SmartArt ダイアグラムを作成し、シェイプ コレクションの末尾に追加します。 |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | 新しい Summary Zoom フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | 新しいテーブルを作成し、シェイプ コレクションの末尾に追加します。 |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | 新しいビデオフレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | 新しいビデオフレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | 新しい Zoom フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | 新しい Zoom フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [Clear](../../aspose.slides/shapecollection/clear)() | シェイプ コレクションからすべてのシェイプを削除します。 |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | コレクションのすべての要素を指定された配列にコピーします。 |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | コレクションを反復処理する列挙子を返します。 |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | コレクション内で指定されたシェイプが最初に出現するゼロベースのインデックスを返します。 |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | CD トラックにリンクされた新しいオーディオフレームを作成し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Presentation.Audios リストの既存オーディオオブジェクトを使用して、新しいオーディオフレームを作成し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | 埋め込み WAV ファイルを持つ新しいオーディオフレームを作成し、指定されたインデックスにシェイプ コレクションに挿入します。埋め込みオーディオは Presentation.Audios コレクションに追加されます。 |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | 外部オーディオファイルにリンクされた新しいオーディオフレームを作成し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | 新しいオートシェイプを作成し、指定されたインデックスにシェイプ コレクションに挿入します。デフォルトテンプレートの書式設定を適用します。 |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | 新しいオートシェイプを作成し、指定されたインデックスにシェイプ コレクションに挿入します。オプションでデフォルトテンプレートのスタイリングで初期化できます。 |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | 新しいチャートを作成し、サンプル系列データと設定で初期化し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | 新しいチャートを作成し、サンプル系列データと設定で初期化し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | 指定されたシェイプのコピーを作成し、指定されたインデックスにシェイプ コレクションに挿入します。クローンされたシェイプは元の位置とサイズを保持します。 |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | 指定されたシェイプのコピーを作成し、指定されたインデックスにシェイプ コレクションに挿入します。新しいシェイプは *sourceShape* の幅と高さを保持します。 |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | 指定されたシェイプのコピーを作成し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | 新しいコネクタ シェイプを作成し、指定されたインデックスにシェイプ コレクションに挿入します。デフォルトテンプレートのスタイリングを適用します。 |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | 新しいコネクタ シェイプを作成し、指定されたインデックスにシェイプ コレクションに挿入します。オプションでデフォルトテンプレートのスタイリングを適用できます。 |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | 新しい空のグループ シェイプを作成し、指定されたインデックスにシェイプ コレクションに挿入します。グループのフレームは追加されたシェイプに合わせて自動的に調整されます。 |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | 新しい OLE オブジェクト フレームを作成し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | 新しい OLE オブジェクト フレームを作成し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | 指定された画像を含む新しい画像フレームを作成し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | 新しい Section Zoom フレームを作成し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | 事前定義された画像を使用した新しい Section Zoom フレームを作成し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | 新しい Summary Zoom フレームを作成し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | 新しいテーブルを作成し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | 新しいビデオフレームを作成し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | 新しい Zoom フレームを作成し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | 事前定義された画像を使用した新しい Zoom フレームを作成し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | シェイプ コレクションから指定されたシェイプの最初の出現を削除します。 |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | シェイプ コレクションから指定されたインデックスのシェイプを削除します。 |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | シェイプ コレクション内で指定されたシェイプを新しい位置に移動します。 |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | シェイプ コレクション内で指定されたシェイプを移動し、指定されたインデックスから配置します。 |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | すべてのシェイプを含む配列を作成して返します。 |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | 指定された範囲内のすべてのシェイプを含む配列を作成して返します。 |

### 参照

* クラス [DomObject&lt;TParent&gt;](../domobject-1)
* クラス [GroupShape](../groupshape)
* インターフェース [IShapeCollection](../ishapecollection)
* 名前空間 [Aspose.Slides](../../aspose.slides)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->