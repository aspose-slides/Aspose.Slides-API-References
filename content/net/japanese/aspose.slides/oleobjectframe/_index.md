---
title: OleObjectFrame
second_title: Aspose.Sildes の .NET API リファレンス
description: スライド上の OLE オブジェクトを表します。
type: docs
weight: 9230
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
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 図形に関連付けられた代替テキストを取得または設定します。 読み取り/書き込み String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 図形に関連付けられた代替テキストのタイトルを取得または設定します。 読み取り/書き込み String。 |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | ベースの IGraphicalObject インターフェイスを取得できます。 読み取り専用 [`IGraphicalObject`](../igraphicalobject)。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 図形が白黒表示モードでどのように描画されるかを指定するプロパティです。 読み取り/書き込み [`BlackWhiteMode`](../blackwhitemode)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 図形上の接続ポイント数を取得します。 読み取り専用 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 図形のカスタム データを取得します。 読み取り専用 [`ICustomData`](../icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 図形に適用されたピクセル効果を含む EffectFormat オブジェクトを取得します。 注: エフェクト プロパティがない特定の種類の図形の場合、null を返すことがあります。 読み取り専用 [`IEffectFormat`](../ieffectformat)。 |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | OLE 埋め込みデータに関する情報を取得または設定します。 読み取り/書き込み [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo)。 |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | 埋め込まれた OLE オブジェクトのファイル名を取得します。 |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | 埋め込まれた OLE オブジェクトのパスを取得します。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 図形の塗りつぶし書式プロパティを含む FillFormat オブジェクトを取得します。 注: 塗りつぶしプロパティがない特定の種類の図形の場合、null を返すことがあります。 読み取り専用 [`IFillFormat`](../ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 図形フレームのプロパティを取得または設定します。 読み取り/書き込み [`IShapeFrame`](../ishapeframe)。 |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | 図形のロック状態を取得します。 読み取り専用 [`IGraphicalObjectLock`](../igraphicalobjectlock)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 図形の高さ（ポイント単位）を取得または設定します。 読み取り/書き込み Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 図形が非表示かどうかを決定します。 読み取り/書き込み Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | マウスクリック用に定義されたハイパーリンクを取得または設定します。 読み取り/書き込み [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | ハイパーリンク マネージャーを取得します。 読み取り専用 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | マウスオーバー用に定義されたハイパーリンクを取得または設定します。 読み取り/書き込み [`IHyperlink`](../ihyperlink)。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 装飾としてマークするオプションを取得または設定します。 読み取り/書き込み Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 図形がグループ化されているかどうかを判定します。 読み取り専用 Boolean。 |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | オブジェクトがアイコンとして表示されるかどうかを判定します。 読み取り/書き込み Boolean。 |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | オブジェクトが外部ファイルにリンクされているかどうかを判定します。 読み取り専用 Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 図形が TextHolder_PPT かどうかを判定します。 読み取り専用 Boolean。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 図形の線書式プロパティを含む LineFormat オブジェクトを取得します。 注: 線プロパティがない特定の種類の図形の場合、null を返すことがあります。 読み取り専用 [`ILineFormat`](../ilineformat)。 |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | リンクされたファイルへのフルパスを取得します。 短いファイル名が使用されます。 読み取り専用 String。 |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | リンクされたファイルへのフルパスを取得します。 長いファイル名が使用されます。 読み取り/書き込み String。 |
| [LinkPathRelative](../../aspose.slides/oleobjectframe/linkpathrelative) { get; } | リンクされたファイルが存在する場合は相対パスを、存在しない場合は空文字列を取得します。 読み取り専用 String。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 図形の名前を取得または設定します。 null であってはなりません。 必要に応じて空文字列を使用してください。 読み取り/書き込み String。 |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | オブジェクトの名前を取得または設定します。 読み取り/書き込み String。 |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | オブジェクトの ProgID を取得します。 読み取り専用 String。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 図形の存続期間中は一定で、PowerPoint やインターロップ コードがドキュメント内の任意の場所から図形を確実に参照できるスライドスコープの一意識別子を取得します。 読み取り専用 UInt32。 参照 [`UniqueId`](../shape/uniqueid)。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 図形がグループ化されている場合は親の GroupShape オブジェクトを取得します。 それ以外の場合は null を返します。 読み取り専用 [`IGroupShape`](../igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 図形のプレースホルダーを取得します。 プレースホルダーがない場合は null を返します。 読み取り専用 [`IPlaceholder`](../iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | スライドの親プレゼンテーションを取得します。 読み取り専用 [`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 生の図形フレームのプロパティを取得または設定します。 読み取り/書き込み [`IShapeFrame`](../ishapeframe)。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 指定された図形が Z 軸周りに回転する角度（度）を取得または設定します。 正の値は時計回り回転、負の値は反時計回り回転を示します。 読み取り/書き込み Single。 |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | 図形のロック状態を取得します。 読み取り専用 [`IGraphicalObjectLock`](../igraphicalobjectlock)。 (2 プロパティ) |
| [Slide](../../aspose.slides/shape/slide) { get; } | 図形の親スライドを取得します。 読み取り専用 [`IBaseSlide`](../ibaseslide)。 |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | OleObject の画像塗りつぶしプロパティオブジェクトを取得します。 読み取り専用 [`IPictureFillFormat`](../ipicturefillformat)。 |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | OleObject アイコンのタイトルを取得または設定します。 読み取り/書き込み String。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 図形の 3D エフェクトプロパティを含む ThreeDFormat オブジェクトを取得します。 注: 3D プロパティがない特定の種類の図形の場合、null を返すことがあります。 読み取り専用 [`IThreeDFormat`](../ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | アドインやその他のコードが使用することを想定した、プレゼンテーションスコープの内部識別子を取得します。 この値はユーザーやプログラムによって再割り当て可能なため、永続的な一意キーとして扱うべきではありません。 読み取り専用 UInt32。 参照 [`OfficeInteropShapeId`](../shape/officeinteropshapeid)。 |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | プレゼンテーションが開かれたり印刷されたりした際に、リンクされた埋め込みオブジェクトが自動的に更新されるかどうかを判定します。 読み取り/書き込み Boolean。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 図形の幅（ポイント単位）を取得または設定します。 読み取り/書き込み Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 図形の左上隅の X 座標（ポイント単位）を取得または設定します。 読み取り/書き込み Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 図形の左上隅の Y 座標（ポイント単位）を取得または設定します。 読み取り/書き込み Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 図形の Z オーダー内での位置を取得します。 Shapes[0] は Z オーダーの最背面にある図形を返し、Shapes[Shapes.Count - 1] は最前面にある図形を返します。 読み取り専用 Int32。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、指定されたプレースホルダーのプロパティを設定します。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 基本的なプレースホルダー形状（レイアウトやマスタースライドから継承された現在の形状）を取得します。 継承されていない場合は null が返されます。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 図形のサムネイルを取得します。 デフォルトでは ShapeThumbnailBounds.Shape のサムネイル境界タイプが使用されます。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 図形のサムネイルを取得します。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | レンダリングされた内容から計算された図形の視覚的境界を取得します。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | この図形がプレースホルダーではないことを定義します。 |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | OLE 埋め込みデータに関する情報を設定します。 このメソッドはオブジェクトのプロパティを新しいデータに合わせて変更し、IsObjectLink フラグを false に設定して OLE オブジェクトが埋め込まれていることを示します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Shape の内容を SVG ファイルとして保存します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Shape の内容を SVG ファイルとして保存します。 |

### 例

以下の例は OLE オブジェクト フレームへのアクセス方法を示しています。

```csharp
[C#]
// PPTX をプレゼンテーション オブジェクトにロードします
using (Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx"))
{
    // 最初のスライドにアクセスします
    ISlide sld = pres.Slides[0];
    // 形状を OleObjectFrame にキャストします
    OleObjectFrame oleObjectFrame = sld.Shapes[0] as OleObjectFrame;
    // OLE オブジェクトを読み取り、ディスクに書き込みます
    if (oleObjectFrame != null)
    {
        // 埋め込まれたファイル データを取得します
        byte[] data = oleObjectFrame.EmbeddedData.EmbeddedFileData;
        // 埋め込まれたファイル拡張子を取得します
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