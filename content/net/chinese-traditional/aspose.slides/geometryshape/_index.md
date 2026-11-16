---
title: GeometryShape
second_title: Aspose.Sildes for .NET API 參考
description: 表示所有幾何圖形的父類別。
type: docs
weight: 4990
url: /zh-hant/aspose.slides/geometryshape/
---
## GeometryShape 類別

表示所有幾何圖形的父類別。

```csharp
public abstract class GeometryShape : Shape, IGeometryShape
```

## 屬性

| Name | Description |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | 返回形狀的調整值集合。只讀 [`IAdjustValueCollection`](../iadjustvaluecollection)。 |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 返回或設定與形狀相關聯的替代文字。可讀寫 String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 返回或設定與形狀相關聯的替代文字的標題。可讀寫 String。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 屬性指定形狀在黑白顯示模式下的呈現方式。可讀寫 [`BlackWhiteMode`](../blackwhitemode)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 返回形狀的連接點數量。只讀 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 返回形狀的自訂資料。只讀 [`ICustomData`](../icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 返回包含套用於形狀的像素效果的 EffectFormat 物件。註：對於沒有效果屬性的某些形狀類型可能返回 null。只讀 [`IEffectFormat`](../ieffectformat)。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 返回包含形狀填充格式屬性的 FillFormat 物件。註：對於沒有填充屬性的某些形狀類型可能返回 null。只讀 [`IFillFormat`](../ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 返回或設定形狀框架的屬性。可讀寫 [`IShapeFrame`](../ishapeframe)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 取得或設定形狀的高度，以點為單位。可讀寫 Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 確定形狀是否被隱藏。可讀寫 Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 返回或設定滑鼠點擊時的超連結。可讀寫 [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 返回超連結管理器。只讀 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 返回或設定滑鼠暈過時的超連結。可讀寫 [`IHyperlink`](../ihyperlink)。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 取得或設定「標記為裝飾」選項。可讀寫 Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 確定形狀是否已分組。只讀 Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 確定形狀是否為 TextHolder_PPT。只讀 Boolean。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 返回包含形狀線條格式屬性的 LineFormat 物件。註：對於沒有線條屬性的某些形狀類型可能返回 null。只讀 [`ILineFormat`](../ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 返回或設定形狀的名稱。不可為 null。如有需要請使用空字串。可讀寫 String。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 返回在投影片範圍內唯一且在形狀生命期內保持不變的識別碼，使 PowerPoint 或 interop 程式碼能從文件任何位置可靠地參照該形狀。只讀 UInt32。另請參閱 [`UniqueId`](../shape/uniqueid)。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 如果形狀已分組，返回其父 GroupShape 物件；否則返回 null。只讀 [`IGroupShape`](../igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 返回形狀的佔位符。如果形狀沒有佔位符，返回 null。只讀 [`IPlaceholder`](../iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 返回投影片的父簡報。只讀 [`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 返回或設定原始形狀框架的屬性。可讀寫 [`IShapeFrame`](../ishapeframe)。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 返回或設定指定形狀繞 z 軸旋轉的角度（以度為單位）。正值表示順時針旋轉；負值表示逆時針旋轉。可讀寫 Single。 |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | 返回形狀的鎖定設定。只讀 [`IBaseShapeLock`](../ibaseshapelock)。 |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | 返回形狀的樣式物件。只讀 [`IShapeStyle`](../ishapestyle)。 |
| virtual [ShapeType](../../aspose.slides/geometryshape/shapetype) { get; set; } | 返回或設定幾何預設類型。註：當值變更時，所有調整值將重設為預設值。可讀寫 [`ShapeType`](../shapetype)。 |
| [Slide](../../aspose.slides/shape/slide) { get; } | 返回形狀的父投影片。只讀 [`IBaseSlide`](../ibaseslide)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 返回形狀的 ThreeDFormat 物件，其中包含 3D 效果屬性。註：對於沒有 3D 屬性的某些形狀類型可能返回 null。只讀 [`IThreeDFormat`](../ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 返回供外掛程式或其他程式碼使用的內部、簡報範圍識別碼。由於此值可能被使用者或程式重新指派，不能視為永久唯一鍵。只讀 UInt32。另請參閱 [`OfficeInteropShapeId`](../shape/officeinteropshapeid)。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 取得或設定形狀的寬度，以點為單位。可讀寫 Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 取得或設定形狀左上角的 X 座標，以點為單位。可讀寫 Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 取得或設定形狀左上角的 Y 座標，以點為單位。可讀寫 Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 返回形狀在 Z 軸排序中的位置。Shapes[0] 代表 Z 軸排序最背面的形狀，Shapes[Shapes.Count - 1] 代表最前面的形狀。只讀 Int32。 |

## 方法

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 如果不存在，則新增佔位符並將佔位符屬性設定為指定的佔位符。 |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | 建立並返回形狀元素的陣列。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 返回基本佔位符形狀（即目前形狀繼承自的版面配置或母片投影片中的形狀）。若目前形狀未繼承，則返回 null。 |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | 返回幾何形狀路徑的副本。座標相對於形狀的左上角。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 返回形狀縮圖。預設使用 ShapeThumbnailBounds.Shape 形狀縮圖邊界類型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 返回形狀縮圖。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 取得根據渲染內容計算出的形狀視覺邊界。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定義此形狀不是佔位符。 |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | 根據 [`IGeometryPath`](../igeometrypath) 物件更新形狀幾何。座標必須相對於形狀的左上角。將形狀類型 ([`ShapeType`](./shapetype)) 變更為自訂。 |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | 根據 [`IGeometryPath`](../igeometrypath) 陣列更新形狀幾何。座標必須相對於形狀的左上角。將形狀類型 ([`ShapeType`](./shapetype)) 變更為自訂。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 將 Shape 的內容儲存為 SVG 檔案。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 將 Shape 的內容儲存為 SVG 檔案。 |

### 另請參閱

* 類別 [Shape](../shape)
* 介面 [IGeometryShape](../igeometryshape)
* 命名空間 [Aspose.Slides](../../aspose.slides)
* 程式集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->