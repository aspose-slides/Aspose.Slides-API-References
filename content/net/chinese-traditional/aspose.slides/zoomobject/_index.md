---
title: ZoomObject
second_title: Aspose.Sildes for .NET API 參考
description: 表示投影片中的 Zoom 物件。
type: docs
weight: 11890
url: /zh-hant/aspose.slides/zoomobject/
---
## ZoomObject 類別

表示投影片中的 Zoom 物件。

```csharp
public class ZoomObject : GraphicalObject, IZoomObject
```

## 屬性

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 取得或設定與形狀相關聯的替代文字。可讀寫 String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 取得或設定與形狀相關聯的替代文字標題。可讀寫 String。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 屬性指定形狀在黑白顯示模式下的呈現方式。可讀寫 [`BlackWhiteMode`](../blackwhitemode)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 取得形狀的連接點數量。唯讀 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 取得形狀的自訂資料。唯讀 [`ICustomData`](../icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 取得包含套用於形狀之像素效果的 EffectFormat 物件。注意：對於沒有效果屬性的某些形狀類型，可能會傳回 null。唯讀 [`IEffectFormat`](../ieffectformat)。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 取得包含形狀填色格式屬性的 FillFormat 物件。注意：對於沒有填色屬性的某些形狀類型，可能會傳回 null。唯讀 [`IFillFormat`](../ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 取得或設定形狀框架的屬性。可讀寫 [`IShapeFrame`](../ishapeframe)。 |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | 取得形狀的鎖定。唯讀 [`IGraphicalObjectLock`](../igraphicalobjectlock)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 取得或設定形狀的高度，以點為單位。可讀寫 Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 判斷形狀是否被隱藏。可讀寫 Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 取得或設定滑鼠點擊時定義的超連結。可讀寫 [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 取得超連結管理器。唯讀 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 取得或設定滑鼠懸停時定義的超連結。可讀寫 [`IHyperlink`](../ihyperlink)。 |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | 取得或設定 Zoom 物件的影像類型。可讀寫 [`ZoomImageType`](../zoomimagetype)。預設值：Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 取得或設定「標記為裝飾」選項。可讀寫 Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 判斷形狀是否已群組。唯讀 Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 判斷形狀是否為 TextHolder_PPT。唯讀 Boolean。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 取得包含形狀線條格式屬性的 LineFormat 物件。注意：對於沒有線條屬性的某些形狀類型，可能會傳回 null。唯讀 [`ILineFormat`](../ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 取得或設定形狀的名稱。不得為 null。如有需要可使用空字串。可讀寫 String。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 取得在投影片範圍內唯一的識別碼，於形狀生命週期內保持不變，讓 PowerPoint 或 interop 程式碼能可靠地在文件任何位置參照該形狀。唯讀 UInt32。另請參閱 [`UniqueId`](../shape/uniqueid)。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 若形狀已群組，取得其父層 GroupShape 物件；否則傳回 null。唯讀 [`IGroupShape`](../igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 取得形狀的佔位符。若形狀沒有佔位符則傳回 null。唯讀 [`IPlaceholder`](../iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 取得投影片的父投影片簡報。唯讀 [`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 取得或設定原始形狀框架的屬性。可讀寫 [`IShapeFrame`](../ishapeframe)。 |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | 取得或設定投影片放映時的導覽行為。可讀寫 Boolean。預設值：false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 取得或設定指定形狀繞 Z 軸旋轉的角度（度數）。正值表示順時針旋轉，負值表示逆時針旋轉。可讀寫 Single。 |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | 取得形狀的鎖定。唯讀 [`IGraphicalObjectLock`](../igraphicalobjectlock)。（2 個屬性） |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | 取得或設定 Zoom 是否使用目的投影片的背景。可讀寫 Boolean。預設值：true |
| [Slide](../../aspose.slides/shape/slide) { get; } | 取得形狀的父投影片。唯讀 [`IBaseSlide`](../ibaseslide)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 取得包含形狀 3D 效果屬性的 ThreeDFormat 物件。注意：對於沒有 3D 屬性的某些形狀類型，可能會傳回 null。唯讀 [`IThreeDFormat`](../ithreedformat)。 |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | 取得或設定 Zoom 與投影片之間轉場的持續時間。可讀寫 Single。預設值：1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 取得供外掛或其他程式使用的內部、簡報範圍內的識別碼。由於此值可能被使用者或程式重新指派，不能視為永久唯一鍵。唯讀 UInt32。另請參閱 [`OfficeInteropShapeId`](../shape/officeinteropshapeid)。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 取得或設定形狀的寬度，以點為單位。可讀寫 Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 取得或設定形狀左上角的 X 座標，以點為單位。可讀寫 Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 取得或設定形狀左上角的 Y 座標，以點為單位。可讀寫 Single。 |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | 取得或設定 Zoom 物件的影像。可讀寫 [`IPPImage`](../ippimage)。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 取得形狀在 Z 序中的位置。Shapes[0] 代表最底層形狀，Shapes[Shapes.Count - 1] 代表最前層形狀。唯讀 Int32。 |

## 方法

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 若不存在則新增佔位符，並將佔位符屬性設定為指定的佔位符。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 取得基本的佔位符形狀（從版面配置或母片取得之形狀，供目前形狀繼承）。若目前形狀未繼承則傳回 null。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 取得形狀縮圖。預設使用 ShapeThumbnailBounds.Shape 作為縮圖界限類型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 取得形狀縮圖。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 取得以已呈現內容計算出的形狀可視範圍。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定義此形狀不是佔位符。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 將形狀內容另存為 SVG 檔案。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 將形狀內容另存為 SVG 檔案。 |

### 另請參閱

* 類別 [GraphicalObject](../graphicalobject)
* 介面 [IZoomObject](../izoomobject)
* 命名空間 [Aspose.Slides](../../aspose.slides)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->