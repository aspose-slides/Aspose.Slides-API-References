---
title: Shape
second_title: Aspose.Sildes for .NET API 參考
description: 表示投影片上的一個圖形。
type: docs
weight: 9850
url: /zh-hant/aspose.slides/shape/
---
## Shape 類別

表示投影片上的一個圖形。

```csharp
public class Shape : IShape
```

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 返回或設定與圖形關聯的替代文字。可讀寫 String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 返回或設定與圖形關聯的替代文字標題。可讀寫 String。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 屬性指定圖形在黑白顯示模式下的呈現方式。可讀寫 [`BlackWhiteMode`](../blackwhitemode)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 返回圖形的連接點數量。唯讀 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 返回圖形的自訂資料。唯讀 [`ICustomData`](../icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 返回包含套用於圖形的像素效果的 EffectFormat 物件。注意：對於某些不具備效果屬性的圖形，可能返回 null。唯讀 [`IEffectFormat`](../ieffectformat)。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 返回包含圖形填充格式屬性的 FillFormat 物件。注意：對於某些不具備填充屬性的圖形，可能返回 null。唯讀 [`IFillFormat`](../ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 返回或設定圖形框架的屬性。可讀寫 [`IShapeFrame`](../ishapeframe)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 取得或設定圖形的高度，以點為單位。可讀寫 Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 判斷圖形是否隱藏。可讀寫 Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 返回或設定滑鼠點擊時的超連結。可讀寫 [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 返回超連結管理員。唯讀 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 返回或設定滑鼠移過時的超連結。可讀寫 [`IHyperlink`](../ihyperlink)。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 取得或設定「標記為裝飾」選項。可讀寫 Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 判斷圖形是否已群組。唯讀 Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 判斷圖形是否為 TextHolder_PPT。唯讀 Boolean。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 返回包含圖形線條格式屬性的 LineFormat 物件。注意：對於某些不具備線條屬性的圖形，可能返回 null。唯讀 [`ILineFormat`](../ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 返回或設定圖形的名稱。不得為 null。如有需要請使用空字串。可讀寫 String。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 返回一個在投影片範圍內唯一的識別碼，於圖形的生命週期內保持不變，讓 PowerPoint 或 interop 程式碼能在文件任何位置可靠地參照該圖形。唯讀 UInt32。另請參閱 [`UniqueId`](./uniqueid)。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 如果圖形已群組，返回父級 GroupShape 物件。否則返回 null。唯讀 [`IGroupShape`](../igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 返回圖形的 placeholder。若圖形沒有 placeholder，則返回 null。唯讀 [`IPlaceholder`](../iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 返回投影片的父級簡報。唯讀 [`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 返回或設定原始圖形框架的屬性。可讀寫 [`IShapeFrame`](../ishapeframe)。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 返回或設定圖形繞 Z 軸旋轉的角度（單位為度）。正值表示順時針旋轉，負值表示逆時針旋轉。可讀寫 Single。 |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | 返回圖形的鎖定設定。唯讀 [`IBaseShapeLock`](../ibaseshapelock)。 |
| [Slide](../../aspose.slides/shape/slide) { get; } | 返回圖形的父投影片。唯讀 [`IBaseSlide`](../ibaseslide)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 返回包含圖形 3D 效果屬性的 ThreeDFormat 物件。注意：對於某些不具備 3D 屬性的圖形，可能返回 null。唯讀 [`IThreeDFormat`](../ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 返回內部、簡報範圍內的識別碼，供外掛或其他程式碼使用。因為此值可能被使用者或程式碼重新指派，不能視為永久唯一鍵。唯讀 UInt32。另請參閱 [`OfficeInteropShapeId`](./officeinteropshapeid)。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 取得或設定圖形的寬度，以點為單位。可讀寫 Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 取得或設定圖形左上角的 X 座標，以點為單位。可讀寫 Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 取得或設定圖形左上角的 Y 座標，以點為單位。可讀寫 Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 返回圖形在 Z 次序中的位置。Shapes[0] 取得 Z 次序最背面的圖形，Shapes[Shapes.Count - 1] 取得最前面的圖形。唯讀 Int32。 |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 若不存在則新增一個 placeholder，並將 placeholder 屬性設定為指定的項目。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 返回基本的 placeholder 圖形（從版面配置或母片取得的圖形，供目前圖形繼承）。若目前圖形未繼承則返回 null。 |
| [GetImage](../../aspose.slides/shape/getimage#getimage)() | 返回圖形縮圖。預設使用 ShapeThumbnailBounds.Shape 作為圖形縮圖邊界類型。 |
| [GetImage](../../aspose.slides/shape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | 返回圖形縮圖。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 取得根據圖形渲染內容計算的可視範圍。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定義此圖形不是 placeholder。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg#writeassvg)(Stream) | 將圖形內容另存為 SVG 檔案。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | 將圖形內容另存為 SVG 檔案。 |

### 另請參閱

* 介面 [IShape](../ishape)
* 命名空間 [Aspose.Slides](../../aspose.slides)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->