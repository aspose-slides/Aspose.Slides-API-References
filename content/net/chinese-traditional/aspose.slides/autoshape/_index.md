---
title: AutoShape
second_title: Aspose.Sildes .NET API 參考
description: 代表一個 AutoShape。
type: docs
weight: 900
url: /zh-hant/aspose.slides/autoshape/
---
## AutoShape 類別

表示一個 AutoShape。

```csharp
public sealed class AutoShape : GeometryShape, IAutoShape
```

## 屬性

| 名稱 | 描述 |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | 傳回形狀調整值的集合。唯讀 [`IAdjustValueCollection`](../iadjustvaluecollection)。 |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 傳回或設定與形狀關聯的替代文字。可讀寫 String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 傳回或設定與形狀關聯的替代文字的標題。可讀寫 String。 |
| [AutoShapeLock](../../aspose.slides/autoshape/autoshapelock) { get; } | 傳回 AutoShape 的鎖定設定。唯讀 [`IAutoShapeLock`](../iautoshapelock)。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 屬性指定形狀在黑白顯示模式下的呈現方式。可讀寫 [`BlackWhiteMode`](../blackwhitemode)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 傳回形狀上的連接點數量。唯讀 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 傳回形狀的自訂資料。唯讀 [`ICustomData`](../icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 傳回包含套用於形狀的像素效果的 EffectFormat 物件。註：對於某些沒有效果屬性的形狀，可能返回 null。唯讀 [`IEffectFormat`](../ieffectformat)。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 傳回包含形狀填充格式屬性的 FillFormat 物件。註：對於某些沒有填充屬性的形狀，可能返回 null。唯讀 [`IFillFormat`](../ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 傳回或設定形狀框架的屬性。可讀寫 [`IShapeFrame`](../ishapeframe)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 取得或設定形狀的高度（以點為單位）。可讀寫 Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 判斷形狀是否隱藏。可讀寫 Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 傳回或設定滑鼠點擊時的超連結。可讀寫 [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 傳回超連結管理員。唯讀 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 傳回或設定滑鼠懸停時的超連結。可讀寫 [`IHyperlink`](../ihyperlink)。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 取得或設定「標記為裝飾」選項。可讀寫 Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 判斷形狀是否已群組。唯讀 Boolean。 |
| [IsTextBox](../../aspose.slides/autoshape/istextbox) { get; } | 指定形狀是否為文字方塊。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 判斷形狀是否為 TextHolder_PPT。唯讀 Boolean。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 傳回包含形狀線條格式屬性的 LineFormat 物件。註：對於某些沒有線條屬性的形狀，可能返回 null。唯讀 [`ILineFormat`](../ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 傳回或設定形狀的名稱。不得為 null。如有需要可使用空字串。可讀寫 String。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 傳回在投影片範圍內唯一且在形狀生命週期內保持不變的識別碼，讓 PowerPoint 或互操作程式碼能可靠地從文件任何位置參考該形狀。唯讀 UInt32。另請參閱 [`UniqueId`](../shape/uniqueid)。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 若形狀已群組則傳回其父 GroupShape 物件。否則返回 null。唯讀 [`IGroupShape`](../igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 傳回形狀的佔位符。若形狀沒有佔位符則返回 null。唯讀 [`IPlaceholder`](../iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 傳回投影片的父簡報。唯讀 [`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 傳回或設定原始形狀框架的屬性。可讀寫 [`IShapeFrame`](../ishapeframe)。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 傳回或設定指定形狀繞 Z 軸旋轉的角度（度數）。正值表示順時鐘方向旋轉，負值表示逆時鐘方向旋轉。可讀寫 Single。 |
| [ShapeLock](../../aspose.slides/autoshape/shapelock) { get; } | 傳回形狀的鎖定設定。唯讀 [`IAutoShapeLock`](../iautoshapelock)。（2 個屬性） |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | 傳回形狀的樣式物件。唯讀 [`IShapeStyle`](../ishapestyle)。 |
| virtual [ShapeType](../../aspose.slides/geometryshape/shapetype) { get; set; } | 傳回或設定幾何預設類型。註：值變更時所有調整值將重置為預設值。可讀寫 [`ShapeType`](../shapetype)。 |
| [Slide](../../aspose.slides/shape/slide) { get; } | 傳回形狀的父投影片。唯讀 [`IBaseSlide`](../ibaseslide)。 |
| [TextFrame](../../aspose.slides/autoshape/textframe) { get; } | 傳回 AutoShape 的 TextFrame 物件。唯讀 [`ITextFrame`](../itextframe)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 傳回形狀之 3D 效果屬性的 ThreeDFormat 物件。註：對於某些沒有 3D 屬性的形狀，可能返回 null。唯讀 [`IThreeDFormat`](../ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 傳回供外掛或其他程式碼使用的內部、簡報範圍識別碼。由於此值可能被使用者或程式重新指派，不能視為持久唯一鍵。唯讀 UInt32。另請參閱 [`OfficeInteropShapeId`](../shape/officeinteropshapeid)。 |
| [UseBackgroundFill](../../aspose.slides/autoshape/usebackgroundfill) { get; set; } | 判斷此 AutoShape 是否應以投影片的背景填充，而非由樣式或填充格式指定。可讀寫 Boolean。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 取得或設定形狀的寬度（以點為單位）。可讀寫 Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 取得或設定形狀左上角的 X 坐標（以點為單位）。可讀寫 Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 取得或設定形狀左上角的 Y 坐標（以點為單位）。可讀寫 Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 傳回形狀在 Z 次序中的位置。Shapes[0] 代表 Z 次序最底層的形狀，Shapes[Shapes.Count - 1] 代表最前面的形狀。唯讀 Int32。 |

## 方法

| 名稱 | 描述 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 若不存在佔位符，則新增一個佔位符並將其屬性設定為指定的佔位符。 |
| [AddTextFrame](../../aspose.slides/autoshape/addtextframe)(string) | 為形狀新增 TextFrame。若形狀已經有 TextFrame，則僅修改其文字。 |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | 建立並傳回形狀元素的陣列。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 傳回基本的佔位符形狀（從版面配置或母片投影片繼承的形狀）。若目前形狀未繼承則返回 null。 |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | 傳回幾何形狀路徑的副本。座標相對於形狀的左上角。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 傳回形狀縮圖。預設使用 ShapeThumbnailBounds.Shape 作為縮圖邊界類型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 傳回形狀縮圖。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 取得根據形狀已呈現內容計算出的視覺邊界。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定義此形狀不是佔位符。 |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | 從 [`IGeometryPath`](../igeometrypath) 物件更新形狀幾何。座標須相對於形狀左上角。將形狀類型（[`ShapeType`](../geometryshape/shapetype)）變更為 Custom。 |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | 從 [`IGeometryPath`](../igeometrypath) 陣列更新形狀幾何。座標須相對於形狀左上角。將形狀類型（[`ShapeType`](../geometryshape/shapetype)）變更為 Custom。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 將 Shape 的內容儲存為 SVG 檔案。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 將 Shape 的內容儲存為 SVG 檔案。 |

### 另請參閱

* 類別 [GeometryShape](../geometryshape)
* 介面 [IAutoShape](../iautoshape)
* 命名空間 [Aspose.Slides](../../aspose.slides)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->