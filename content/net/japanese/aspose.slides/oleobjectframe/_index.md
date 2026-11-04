---
title: OleObjectFrame
second_title: Aspose.Sildes for .NET API リファレンス
description: スライド上のOLEオブジェクトを表します。
type: docs
weight: 9250
url: /ja/aspose.slides/oleobjectframe/
---
## OleObjectFrame クラス

スライド上のOLEオブジェクトを表します。

```csharp
public class OleObjectFrame : GraphicalObject, IOleObjectFrame
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | シェイプに関連付けられた代替テキストを取得または設定します。Read/write String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | シェイプに関連付けられた代替テキストのタイトルを取得または設定します。Read/write String. |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | ベースのIGraphicalObjectインターフェイスを取得できます。Read-only [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | シェイプが白黒表示モードでどのように描画されるかを指定するプロパティです。Read/write [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | シェイプ上の接続ポイントの数を取得します。Read-only Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | シェイプのカスタムデータを取得します。Read-only [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | シェイプに適用されたピクセルエフェクトを含むEffectFormatオブジェクトを取得します。注: エフェクトプロパティを持たない特定のタイプのシェイプではnullが返される場合があります。Read-only [`IEffectFormat`](../ieffectformat). |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | OLE埋め込みデータに関する情報を取得または設定します。Read/write [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo). |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | 埋め込みOLEオブジェクトのファイル名を取得します |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | 埋め込みOLEオブジェクトのパスを取得します |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | シェイプの塗りつぶし書式プロパティを含むFillFormatオブジェクトを取得します。注: 塗りつぶしプロパティを持たない特定のタイプのシェイプではnullが返される場合があります。Read-only [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | シェイプフレームのプロパティを取得または設定します。Read/write [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | シェイプのロックを取得します。Read-only [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | シェイプの高さ（ポイント単位）を取得または設定します。Read/write Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | シェイプが非表示かどうかを判定します。Read/write Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | マウスクリック用に定義されたハイパーリンクを取得または設定します。Read/write [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | ハイパーリンクマネージャーを取得します。Read-only [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | マウスオーバー用に定義されたハイパーリンクを取得または設定します。Read/write [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 「装飾としてマーク」オプションを取得または設定します。Read/write Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | シェイプがグループ化されているかどうかを判定します。Read-only Boolean. |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | オブジェクトがアイコンとして表示されるかどうかを判定します。Read/write Boolean. |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | オブジェクトが外部ファイルにリンクされているかどうかを判定します。Read-only Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | シェイプが TextHolder_PPT かどうかを判定します。Read-only Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | シェイプの線書式プロパティを含むLineFormatオブジェクトを取得します。注: 線プロパティを持たない特定のタイプのシェイプではnullが返される場合があります。Read-only [`ILineFormat`](../ilineformat). |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | リンクされたファイルへのフルパスを取得します。短いファイル名が使用されます。Read-only String. |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | リンクされたファイルへのフルパスを取得します。長いファイル名が使用されます。Read/write String. |
| [LinkPathRelative](../../aspose.slides/oleobjectframe/linkpathrelative) { get; } | 存在すればリンクされたファイルへの相対パスを取得し、存在しなければ空文字列を返します。Readonly String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | シェイプの名前を取得または設定します。nullであってはなりません。必要に応じて空文字列を使用してください。Read/write String. |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | オブジェクトの名前を取得または設定します。Read/write String. |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | オブジェクトのProgIDを取得します。Read only String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | シェイプのライフタイム全体で一定であり、PowerPointやインターロップコードがドキュメント内の任意の場所からシェイプを確実に参照できるスライドスコープの一意識別子を取得します。Read-only UInt32。[`UniqueId`](../shape/uniqueid)も参照してください。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | シェイプがグループ化されている場合は親のGroupShapeオブジェクトを取得します。そうでない場合はnullを返します。Read-only [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | シェイプのプレースホルダーを取得します。プレースホルダーがない場合はnullを返します。Read-only [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | スライドの親プレゼンテーションを取得します。Read-only [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 生のシェイプフレームのプロパティを取得または設定します。Read/write [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 指定されたシェイプがz軸周りに回転する角度（度数）を取得または設定します。正の値は時計回りの回転、負の値は反時計回りの回転を示します。Read/write Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | シェイプのロックを取得します。Read-only [`IGraphicalObjectLock`](../igraphicalobjectlock)。 (2 プロパティ) |
| [Slide](../../aspose.slides/shape/slide) { get; } | シェイプの親スライドを取得します。Read-only [`IBaseSlide`](../ibaseslide). |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | OleObjectの画像塗りつぶしプロパティオブジェクトを取得します。Read-only [`IPictureFillFormat`](../ipicturefillformat). |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | OleObjectアイコンのタイトルを取得または設定します。Read/write String. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | シェイプの3Dエフェクトプロパティを含むThreeDFormatオブジェクトを取得します。注: 3Dプロパティを持たない特定のタイプのシェイプではnullが返される場合があります。Read-only [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | アドインやその他のコードが使用することを想定した、プレゼンテーションスコープの内部識別子を取得します。この値はユーザーやプログラムによって再割り当て可能なため、永続的なユニークキーとして扱うべきではありません。Read-only UInt32。[`OfficeInteropShapeId`](../shape/officeinteropshapeid)も参照してください。 |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | プレゼンテーションが開かれた時または印刷された時に、リンクされた埋め込みオブジェクトが自動的に更新されるかどうかを判定します。Read/write Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | シェイプの幅（ポイント単位）を取得または設定します。Read/write Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | シェイプの左上隅のX座標（ポイント単位）を取得または設定します。Read/write Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | シェイプの左上隅のY座標（ポイント単位）を取得または設定します。Read/write Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | zオーダー内でのシェイプの位置を取得します。Shapes[0] はzオーダーの背面にあるシェイプを返し、Shapes[Shapes.Count - 1] は前面にあるシェイプを返します。Read-only Int32. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 新しいプレースホルダーが存在しない場合に追加し、指定されたプレースホルダーのプロパティを設定します。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 基本的なプレースホルダーシェイプを返します（現在のシェイプが継承元となっているレイアウトまたはマスタースライドからのシェイプ）。現在のシェイプが継承されていない場合はnullが返されます。 |
| [GetImage](../../aspose.slides/shape/getimage)() | シェイプのサムネイルを返します。デフォルトで ShapeThumbnailBounds.Shape のサムネイル境界タイプが使用されます。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | シェイプのサムネイルを返します。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | レンダリングされたコンテンツから計算されたシェイプの視覚的境界を取得します。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | このシェイプがプレースホルダーではないことを定義します。 |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | OLE埋め込みデータに関する情報を設定します。このメソッドはオブジェクトのプロパティを新しいデータに合わせて変更し、IsObjectLink フラグを false に設定して、OLE オブジェクトが埋め込まれていることを示します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | シェイプの内容を SVG ファイルとして保存します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | シェイプの内容を SVG ファイルとして保存します。 |

### 例

次の例は OLE オブジェクトフレームへのアクセス方法を示しています。

```csharp
[C#]
// PPTX をプレゼンテーションオブジェクトにロードします
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

### 関連項目

* クラス [GraphicalObject](../graphicalobject)
* インターフェイス [IOleObjectFrame](../ioleobjectframe)
* 名前空間 [Aspose.Slides](../../aspose.slides)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->