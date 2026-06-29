---
title: OleObjectFrame
second_title: Aspose.Sildes for .NET API リファレンス
description: スライド上の OLE オブジェクトを表します。
type: docs
weight: 9210
url: /ja/aspose.slides/oleobjectframe/
---
## OleObjectFrame クラス

スライド上の OLE オブジェクトを表します。

```csharp
public class OleObjectFrame : GraphicalObject, IOleObjectFrame
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | シェイプに関連付けられた代替テキストを取得または設定します。 読み書き可能な String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | シェイプに関連付けられた代替テキストのタイトルを取得または設定します。 読み書き可能な String。 |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | ベースの IGraphicalObject インターフェイスを取得できます。 読み取り専用 [`IGraphicalObject`](../igraphicalobject)。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | プロパティはシェイプが白黒表示モードでどのように描画されるかを指定します。 読み書き可能な [`BlackWhiteMode`](../blackwhitemode)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | シェイプ上の接続ポイントの数を返します。 読み取り専用 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | シェイプのカスタム データを返します。 読み取り専用 [`ICustomData`](../icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | シェイプに適用されたピクセル効果を含む EffectFormat オブジェクトを返します。 注: 効果プロパティを持たない特定のタイプのシェイプでは null を返すことがあります。 読み取り専用 [`IEffectFormat`](../ieffectformat)。 |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | OLE 埋め込みデータに関する情報を取得または設定します。 読み書き可能な [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo)。 |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | 埋め込み OLE オブジェクトのファイル名を返します |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | 埋め込み OLE オブジェクトのパスを返します |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | シェイプの塗りつぶし書式プロパティを含む FillFormat オブジェクトを返します。 注: 塗りつぶしプロパティを持たない特定のタイプのシェイプでは null を返すことがあります。 読み取り専用 [`IFillFormat`](../ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | シェイプフレームのプロパティを取得または設定します。 読み書き可能な [`IShapeFrame`](../ishapeframe)。 |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | シェイプのロック情報を返します。 読み取り専用 [`IGraphicalObjectLock`](../igraphicalobjectlock)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | シェイプの高さ（ポイント単位）を取得または設定します。 読み書き可能な Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | シェイプが非表示かどうかを決定します。 読み書き可能な Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | マウスクリック用に定義されたハイパーリンクを取得または設定します。 読み書き可能な [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | ハイパーリンクマネージャーを返します。 読み取り専用 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | マウスオーバー用に定義されたハイパーリンクを取得または設定します。 読み書き可能な [`IHyperlink`](../ihyperlink)。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 装飾としてマークするオプションを取得または設定します。 読み書き可能な Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | シェイプがグループ化されているかどうかを決定します。 読み取り専用 Boolean。 |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | オブジェクトがアイコンとして表示されるかどうかを決定します。 読み書き可能な Boolean。 |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | オブジェクトが外部ファイルにリンクされているかどうかを決定します。 読み取り専用 Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | シェイプが TextHolder_PPT かどうかを決定します。 読み取り専用 Boolean。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | シェイプの線書式プロパティを含む LineFormat オブジェクトを返します。 注: 線プロパティを持たない特定のタイプのシェイプでは null を返すことがあります。 読み取り専用 [`ILineFormat`](../ilineformat)。 |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | リンクされたファイルへのフルパスを返します。 短いファイル名が使用されます。 読み取り専用 String。 |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | リンクされたファイルへのフルパスを返します。 長いファイル名が使用されます。 読み書き可能な String。 |
| [LinkPathRelative](../../aspose.slides/oleobjectframe/linkpathrelative) { get; } | 存在する場合はリンクされたファイルへの相対パスを返し、存在しない場合は空文字列を返します。 読み取り専用 String。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | シェイプの名前を取得または設定します。 null であってはなりません。 必要に応じて空文字列を使用してください。 読み書き可能な String。 |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | オブジェクトの名前を取得または設定します。 読み書き可能な String。 |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | オブジェクトの ProgID を返します。 読み取り専用 String。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | スライド単位の一意識別子を返します。この識別子はシェイプの存続期間中一定で、PowerPoint または interop コードがドキュメント内の任意の場所からシェイプを確実に参照できるようにします。 読み取り専用 UInt32。 参照: [`UniqueId`](../shape/uniqueid)。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | シェイプがグループ化されている場合は親 GroupShape オブジェクトを返します。 それ以外の場合は null を返します。 読み取り専用 [`IGroupShape`](../igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | シェイプのプレースホルダーを返します。 シェイプにプレースホルダーがない場合は null を返します。 読み取り専用 [`IPlaceholder`](../iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | スライドの親プレゼンテーションを返します。 読み取り専用 [`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 生のシェイプフレームのプロパティを取得または設定します。 読み書き可能な [`IShapeFrame`](../ishapeframe)。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 指定されたシェイプが z 軸周りに回転する角度（度数）を取得または設定します。 正の値は時計回りの回転を示し、負の値は反時計回りの回転を示します。 読み書き可能な Single。 |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | シェイプのロック情報を返します。 読み取り専用 [`IGraphicalObjectLock`](../igraphicalobjectlock)。 (2 プロパティ) |
| [Slide](../../aspose.slides/shape/slide) { get; } | シェイプの親スライドを返します。 読み取り専用 [`IBaseSlide`](../ibaseslide)。 |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | OleObject の画像塗りつぶしプロパティオブジェクトを返します。 読み取り専用 [`IPictureFillFormat`](../ipicturefillformat)。 |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | OleObject アイコンのタイトルを取得または設定します。 読み書き可能な String。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | シェイプの 3D 効果プロパティを含む ThreeDFormat オブジェクトを返します。 注: 3D プロパティを持たない特定のタイプのシェイプでは null を返すことがあります。 読み取り専用 [`IThreeDFormat`](../ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | アドインやその他のコードで使用することを目的とした、内部のプレゼンテーション単位の識別子を返します。この値はユーザーまたはプログラムによって再割り当て可能なため、永続的な一意キーとして扱ってはなりません。 読み取り専用 UInt32。 参照: [`OfficeInteropShapeId`](../shape/officeinteropshapeid)。 |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | プレゼンテーションが開かれたときや印刷されたときに、リンクされた埋め込みオブジェクトが自動的に更新されるかどうかを決定します。 読み書き可能な Boolean。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | シェイプの幅（ポイント単位）を取得または設定します。 読み書き可能な Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | シェイプの左上隅の x 座標（ポイント単位）を取得または設定します。 読み書き可能な Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | シェイプの左上隅の y 座標（ポイント単位）を取得または設定します。 読み書き可能な Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | シェイプの Z 順序における位置を返します。 Shapes[0] は Z 順序の最背面にあるシェイプを返し、Shapes[Shapes.Count - 1] は最前面にあるシェイプを返します。 読み取り専用 Int32。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、指定されたプレースホルダーのプロパティを設定します。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 基本的なプレースホルダーシェイプを返します（現在のシェイプが継承元であるレイアウトやマスタースライドからのシェイプ）。 現在のシェイプが継承されていない場合は null を返します。 |
| [GetImage](../../aspose.slides/shape/getimage)() | シェイプのサムネイルを返します。 デフォルトでは ShapeThumbnailBounds.Shape のサムネイル境界タイプが使用されます。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | シェイプのサムネイルを返します。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | レンダリングされたコンテンツから計算されたシェイプの視覚的境界を取得します。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | このシェイプがプレースホルダーではないことを定義します。 |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | OLE 埋め込みデータに関する情報を設定します。このメソッドはオブジェクトのプロパティを新しいデータに合わせて変更し、IsObjectLink フラグを false に設定して OLE オブジェクトが埋め込みであることを示します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | シェイプの内容を SVG ファイルとして保存します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | シェイプの内容を SVG ファイルとして保存します。 |

### 例

以下の例は OLE オブジェクト フレームへのアクセス方法を示しています。

```csharp
[C#]
// PPTX をプレゼンテーションオブジェクトに読み込みます
using (Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx"))
{
    // 最初のスライドにアクセスします
    ISlide sld = pres.Slides[0];
    // シェイプを OleObjectFrame にキャストします
    OleObjectFrame oleObjectFrame = sld.Shapes[0] as OleObjectFrame;
    // OLE オブジェクトを読み取り、ディスクに書き込みます
    if (oleObjectFrame != null)
    {
        // 埋め込みファイルデータを取得します
        byte[] data = oleObjectFrame.EmbeddedData.EmbeddedFileData;
        // 埋め込みファイルの拡張子を取得します
        string fileExtention = oleObjectFrame.EmbeddedData.EmbeddedFileExtension;
        // 抽出したファイルを保存するパスを作成します
        string extractedPath = "excelFromOLE_out" + fileExtention;
        // 抽出したデータを保存します
        using (FileStream fstr = new FileStream(extractedPath, FileMode.Create, FileAccess.Write))
        {
            fstr.Write(data, 0, data.Length);
        }
    }
}
```

### 参照

* クラス [GraphicalObject](../graphicalobject)
* インターフェイス [IOleObjectFrame](../ioleobjectframe)
* 名前空間 [Aspose.Slides](../../aspose.slides)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->