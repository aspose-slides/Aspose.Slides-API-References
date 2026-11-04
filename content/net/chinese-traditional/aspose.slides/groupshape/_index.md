---
title: GroupShape
second_title: Aspose.Sildes for .NET API 參考
description: 表示投影片上形狀的群組。
type: docs
weight: 5110
url: /zh-hant/aspose.slides/groupshape/
---
## GroupShape 類別

表示投影片上形狀的群組。

```csharp
public class GroupShape : Shape, IGroupShape
```

## 屬性

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 取得或設定與形狀相關聯的替代文字。Read/write String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 取得或設定與形狀相關聯的替代文字標題。Read/write String. |
| [AsIShape](../../aspose.slides/groupshape/asishape) { get; } | 允許取得基礎 IShape 介面。Read-only [`IShape`](../ishape). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 屬性指定形狀在黑白顯示模式下的呈現方式.. Read/write [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 取得形狀的連接點數量。Read-only Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 取得形狀的自訂資料。Read-only [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 取得包含套用於形狀的像素效果的 EffectFormat 物件。注意：對於某些沒有效果屬性的形狀類型，可能會傳回 null。Read-only [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 取得包含形狀填充格式屬性的 FillFormat 物件。注意：對於某些沒有填充屬性的形狀類型，可能會傳回 null。Read-only [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 取得或設定形狀框架的屬性。Read/write [`IShapeFrame`](../ishapeframe). |
| [GroupShapeLock](../../aspose.slides/groupshape/groupshapelock) { get; } | 取得形狀的鎖定設定。Read-only [`IGroupShapeLock`](../igroupshapelock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | 取得或設定形狀的高度，以點為單位。Read/write Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 判斷形狀是否為隱藏。Read/write Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 取得或設定滑鼠點擊時的超連結。Read/write [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 取得超連結管理員。Read-only [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 取得或設定滑鼠懸停時的超連結。Read/write [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 取得或設定「標記為裝飾」選項 Reed/write Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 判斷形狀是否已群組。Read-only Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 判斷形狀是否為 TextHolder_PPT。Read-only Boolean. |
| override [LineFormat](../../aspose.slides/groupshape/lineformat) { get; } | 取得包含形狀線條格式屬性的 LineFormat 物件。注意：對於 GroupShape 物件，因為它們沒有線條屬性，會傳回 null。Read-only [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | 取得或設定形狀的名稱。不可為 null。如有需要請使用空字串。Read/write String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 取得在投影片範圍內唯一的識別碼，於形狀生命週期內保持不變，讓 PowerPoint 或 Interop 程式碼能從文件任何位置可靠地參照此形狀。Read-only UInt32。另請參閱 [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 如果形狀已群組，則取得父級 GroupShape 物件。否則傳回 null。Read-only [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 取得形狀的佔位符。若形狀無佔位符，則傳回 null。Read-only [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 取得投影片的父級簡報。Read-only [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 取得或設定原始形狀框架的屬性。Read/write [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 取得或設定指定形狀繞 Z 軸旋轉的角度（度數）。正值表示順時針旋轉，負值表示逆時針旋轉。Read/write Single. |
| [ShapeLock](../../aspose.slides/groupshape/shapelock) { get; } | 取得形狀的鎖定設定。Read-only [`IGroupShapeLock`](../igroupshapelock)。（2 個屬性） |
| [Shapes](../../aspose.slides/groupshape/shapes) { get; } | 取得群組內的形狀集合。Read-only [`IShapeCollection`](../ishapecollection). |
| [Slide](../../aspose.slides/shape/slide) { get; } | 取得形狀的父級投影片。Read-only [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 取得形狀的 ThreeDFormat 物件，以取得 3D 效果屬性。注意：對於某些沒有 3D 屬性的形狀類型，可能會傳回 null。Read-only [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 取得用於外掛程式或其他程式碼的內部、簡報範圍識別碼。由於此值可能被使用者或程式重新指派，不能視為持久唯一鍵。Read-only UInt32。另請參閱 [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | 取得或設定形狀的寬度，以點為單位。Read/write Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | 取得或設定形狀左上角的 X 座標，以點為單位。Read/write Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | 取得或設定形狀左上角的 Y 座標，以點為單位。Read/write Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 取得形狀在 Z 軸順序中的位置。Shapes[0] 會傳回位於 Z 軸最底層的形狀，Shapes[Shapes.Count - 1] 會傳回位於最前端的形狀。Read-only Int32. |

## 方法

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 如果不存在則新增佔位符，並將佔位符屬性設定為指定的佔位符。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 傳回基本佔位符形狀（來自版面配置和/或母片，且目前形狀繼承自該形狀的形狀）。如果目前形狀未繼承，則傳回 null。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 傳回形狀縮圖。預設使用 ShapeThumbnailBounds.Shape 形狀縮圖界限型別。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 傳回形狀縮圖。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 取得根據渲染內容計算出的形狀可視界限。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定義此形狀不是佔位符。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 將形狀內容儲存為 SVG 檔案。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 將形狀內容儲存為 SVG 檔案。 |

### 另見

* 類別 [Shape](../shape)
* 介面 [IGroupShape](../igroupshape)
* 名稱空間 [Aspose.Slides](../../aspose.slides)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->