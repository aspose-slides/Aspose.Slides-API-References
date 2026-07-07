---
title: SmartArtShape
second_title: Aspose.Sildes for .NET API 參考
description: 代表 SmartArt 形狀
type: docs
weight: 10660
url: /zh-hant/aspose.slides.smartart/smartartshape/
---
## SmartArtShape 類別

代表 SmartArt 形狀

```csharp
public class SmartArtShape : GeometryShape, ISmartArtShape
```

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | 傳回形狀的調整值集合。唯讀 [`IAdjustValueCollection`](../../aspose.slides/iadjustvaluecollection)。 |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 取得或設定與形狀關聯的替代文字。可讀寫 String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 取得或設定與形狀關聯的替代文字標題。可讀寫 String。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 此屬性指定形狀在黑白顯示模式下的呈現方式。可讀寫 [`BlackWhiteMode`](../../aspose.slides/blackwhitemode)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 傳回形狀的連接點數量。唯讀 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 傳回形狀的自訂資料。唯讀 [`ICustomData`](../../aspose.slides/icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 傳回包含套用於形狀之像素效果的 EffectFormat 物件。註：對於某些沒有效果屬性的形狀可能傳回 null。唯讀 [`IEffectFormat`](../../aspose.slides/ieffectformat)。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 傳回包含形狀填充格式屬性的 FillFormat 物件。註：對於某些沒有填充屬性的形狀可能傳回 null。唯讀 [`IFillFormat`](../../aspose.slides/ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 取得或設定形狀框架的屬性。可讀寫 [`IShapeFrame`](../../aspose.slides/ishapeframe)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 取得或設定形狀的高度（以點為單位）。可讀寫 Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 判斷形狀是否隱藏。可讀寫 Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 取得或設定滑鼠點擊時的超連結。可讀寫 [`IHyperlink`](../../aspose.slides/ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 傳回超連結管理員。唯讀 [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 取得或設定滑鼠懸停時的超連結。可讀寫 [`IHyperlink`](../../aspose.slides/ihyperlink)。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 取得或設定「標記為裝飾」選項。可讀寫 Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 判斷形狀是否已群組。唯讀 Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 判斷形狀是否為 TextHolder_PPT。唯讀 Boolean。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 傳回包含形狀線條格式屬性的 LineFormat 物件。註：對於某些沒有線條屬性的形狀可能傳回 null。唯讀 [`ILineFormat`](../../aspose.slides/ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 取得或設定形狀的名稱。必須非 null。如有需要可使用空字串。可讀寫 String。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 傳回在投影片範圍內唯一且在形狀生命週期內保持不變的識別碼，讓 PowerPoint 或 interop 程式碼能可靠地從文件任何位置參照該形狀。唯讀 UInt32。另請參閱 [`UniqueId`](../../aspose.slides/shape/uniqueid)。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 如果形狀已群組，傳回其父層 GroupShape 物件；否則傳回 null。唯讀 [`IGroupShape`](../../aspose.slides/igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 傳回形狀的佔位符。若形狀沒有佔位符則傳回 null。唯讀 [`IPlaceholder`](../../aspose.slides/iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 傳回投影片的父層簡報。唯讀 [`IPresentation`](../../aspose.slides/ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 取得或設定原始形狀框架的屬性。可讀寫 [`IShapeFrame`](../../aspose.slides/ishapeframe)。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 取得或設定指定形狀繞 Z 軸旋轉的角度（度數）。正值表示順時針旋轉；負值表示逆時針旋轉。可讀寫 Single。 |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | 傳回形狀的鎖定設定。唯讀 [`IBaseShapeLock`](../../aspose.slides/ibaseshapelock)。 |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | 傳回形狀的樣式物件。唯讀 [`IShapeStyle`](../../aspose.slides/ishapestyle)。 |
| override [ShapeType](../../aspose.slides.smartart/smartartshape/shapetype) { get; set; } | 取得或設定幾何預設類型。註：值變更時所有調整值將重置為預設值。可讀寫 [`ShapeType`](../../aspose.slides/shapetype)。 |
| [Slide](../../aspose.slides/shape/slide) { get; } | 傳回形狀的父投影片。唯讀 [`IBaseSlide`](../../aspose.slides/ibaseslide)。 |
| [TextFrame](../../aspose.slides.smartart/smartartshape/textframe) { get; } | 傳回 SmartArt 形狀的文字。唯讀 [`ITextFrame`](../../aspose.slides/itextframe)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 傳回包含形狀 3D 效果屬性的 ThreeDFormat 物件。註：對於某些沒有 3D 屬性的形狀可能傳回 null。唯讀 [`IThreeDFormat`](../../aspose.slides/ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 傳回供外掛或其他程式使用的內部、簡報範圍識別碼。因為此值可被使用者或程式重新指派，不能視為永久唯一鍵。唯讀 UInt32。另請參閱 [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid)。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 取得或設定形狀的寬度（以點為單位）。可讀寫 Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 取得或設定形狀左上角的 X 座標（以點為單位）。可讀寫 Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 取得或設定形狀左上角的 Y 座標（以點為單位）。可讀寫 Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 傳回形狀在 Z 次序中的位置。Shapes[0] 代表 Z 次序最底層的形狀，Shapes[Shapes.Count - 1] 代表最上層的形狀。唯讀 Int32。 |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 如果不存在，新增一個佔位符並將佔位符屬性設定為指定的項目。 |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | 建立並傳回形狀元素的陣列。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 傳回基本佔位符形狀（從版面配置或母片投影片繼承而來的形狀）。若目前形狀未繼承則傳回 null。 |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | 傳回幾何形狀路徑的副本。座標相對於形狀的左上角。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 傳回形狀縮圖。預設使用 ShapeThumbnailBounds.Shape 形狀縮圖邊界類型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 傳回形狀縮圖。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 取得根據形狀已渲染內容計算出的視覺邊界。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定義此形狀不是佔位符。 |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | 根據 [`IGeometryPath`](../../aspose.slides/igeometrypath) 物件更新形狀幾何。座標必須相對於形狀的左上角。將形狀類型（[`ShapeType`](../../aspose.slides/geometryshape/shapetype)）變更為 Custom。 |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | 根據 [`IGeometryPath`](../../aspose.slides/igeometrypath) 陣列更新形狀幾何。座標必須相對於形狀的左上角。將形狀類型（[`ShapeType`](../../aspose.slides/geometryshape/shapetype)）變更為 Custom。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 將形狀內容儲存為 SVG 檔案。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 將形狀內容儲存為 SVG 檔案。 |

### 另請參閱

* 類別 [GeometryShape](../../aspose.slides/geometryshape)
* 介面 [ISmartArtShape](../ismartartshape)
* 命名空間 [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->