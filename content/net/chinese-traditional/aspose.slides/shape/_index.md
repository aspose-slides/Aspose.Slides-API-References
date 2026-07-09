---
title: Shape
second_title: Aspose.Slides for .NET API 參考文件
description: 表示投影片上的形狀。
type: docs
weight: 9830
url: /zh-hant/aspose.slides/shape/
---
## Shape 類別

表示投影片上的形狀。

```csharp
public class Shape : IShape
```

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 返回或設定與形狀關聯的替代文字。Read/write String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 返回或設定與形狀關聯的替代文字標題。Read/write String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 指定形狀在黑白顯示模式下的呈現方式。Read/write [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 返回形狀的連接點數量。Read-only Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 返回形狀的自訂資料。Read-only [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 返回包含套用於形狀之像素效果的 EffectFormat 物件。注意：對於某些沒有效果屬性的形狀，可能會返回 null。Read-only [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 返回包含形狀填充格式屬性的 FillFormat 物件。注意：對於某些沒有填充屬性的形狀，可能會返回 null。Read-only [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 返回或設定形狀框架的屬性。Read/write [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | 取得或設定形狀的高度（以點為單位）。Read/write Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 決定形狀是否隱藏。Read/write Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 返回或設定滑鼠點擊時的超連結。Read/write [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 返回超連結管理器。Read-only [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 返回或設定滑鼠懸停時的超連結。Read/write [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 取得或設定「Mark as decorative」選項。Reed/write Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 判斷形狀是否已群組。Read-only Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 判斷形狀是否為 TextHolder_PPT。Read-only Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 返回包含形狀線條格式屬性的 LineFormat 物件。注意：對於某些沒有線條屬性的形狀，可能會返回 null。Read-only [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | 返回或設定形狀的名稱。不得為 null，必要時使用空字串。Read/write String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 返回在投影片範圍內唯一且在形狀生命期內保持不變的識別碼，供 PowerPoint 或互操作程式可靠地從文件任何位置參照形狀。Read-only UInt32. 另請參閱 [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 若形狀已群組，返回其父 GroupShape 物件；否則返回 null。Read-only [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 返回形狀的佔位符；若形狀沒有佔位符則返回 null。Read-only [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 返回投影片的父簡報。Read-only [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 返回或設定原始形狀框架的屬性。Read/write [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 返回或設定指定形狀繞 z 軸旋轉的角度（以度為單位）。正值表示順時針旋轉，負值表示逆時針旋轉。Read/write Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | 返回形狀的鎖定設定。Read-only [`IBaseShapeLock`](../ibaseshapelock). |
| [Slide](../../aspose.slides/shape/slide) { get; } | 返回形狀的父投影片。Read-only [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 返回提供形狀三維效果屬性的 ThreeDFormat 物件。注意：對於某些沒有 3D 屬性的形狀，可能會返回 null。Read-only [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 返回供外掛或其他程式使用的內部、簡報範圍識別碼。因為此值可能被使用者或程式重新指派，不能視為永久唯一鍵。Read-only UInt32. 另請參閱 [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | 取得或設定形狀的寬度（以點為單位）。Read/write Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | 取得或設定形狀左上角的 X 座標（以點為單位）。Read/write Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | 取得或設定形狀左上角的 Y 座標（以點為單位）。Read/write Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 返回形狀在 Z 順序中的位置。Shapes[0] 返回位於 Z 順序最底層的形狀，Shapes[Shapes.Count - 1] 返回位於最前面的形狀。Read-only Int32. |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 若不存在，則新增佔位符並將佔位符屬性設定為指定的佔位符。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 返回基本佔位符形狀（來自版面配置或母片投影片的形狀，且當前形狀繼承自該形狀）。若當前形狀未繼承則返回 null。 |
| [GetImage](../../aspose.slides/shape/getimage#getimage)() | 返回形狀縮圖。預設使用 ShapeThumbnailBounds.Shape 形狀縮圖邊界類型。 |
| [GetImage](../../aspose.slides/shape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | 返回形狀縮圖。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 取得根據渲染內容計算出的形狀視覺邊界。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定義此形狀不是佔位符。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg#writeassvg)(Stream) | 將 Shape 的內容另存為 SVG 檔案。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | 將 Shape 的內容另存為 SVG 檔案。 |

### 另請參閱

* interface [IShape](../ishape)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->