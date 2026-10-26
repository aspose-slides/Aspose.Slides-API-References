---
title: SmartArtShape
second_title: Aspose.Sildes for .NET API 參考
description: 表示 SmartArt 形狀
type: docs
weight: 10660
url: /zh-hant/aspose.slides.smartart/smartartshape/
---
## SmartArtShape 類別

表示 SmartArt 形狀

```csharp
public class SmartArtShape : GeometryShape, ISmartArtShape
```

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | 返回形狀的調整值集合。 唯讀 [`IAdjustValueCollection`](../../aspose.slides/iadjustvaluecollection)。 |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 返回或設定與形狀關聯的替代文字。 可讀寫 String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 返回或設定與形狀關聯的替代文字標題。 可讀寫 String。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 此屬性指定形狀在黑白顯示模式下的呈現方式。 可讀寫 [`BlackWhiteMode`](../../aspose.slides/blackwhitemode)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 返回形狀的連接點數量。 唯讀 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 返回形狀的自訂資料。 唯讀 [`ICustomData`](../../aspose.slides/icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 返回包含套用於形狀的像素效果的 EffectFormat 物件。 注意：對於某些沒有效果屬性的形狀可能返回 null。 唯讀 [`IEffectFormat`](../../aspose.slides/ieffectformat)。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 返回包含形狀填充格式屬性的 FillFormat 物件。 注意：對於某些沒有填充屬性的形狀可能返回 null。 唯讀 [`IFillFormat`](../../aspose.slides/ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 返回或設定形狀框架的屬性。 可讀寫 [`IShapeFrame`](../../aspose.slides/ishapeframe)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 取得或設定形狀的高度，以點為單位。 可讀寫 Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 判斷形狀是否隱藏。 可讀寫 Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 返回或設定點擊滑鼠時的超連結。 可讀寫 [`IHyperlink`](../../aspose.slides/ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 返回超連結管理器。 唯讀 [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 返回或設定滑鼠指向時的超連結。 可讀寫 [`IHyperlink`](../../aspose.slides/ihyperlink)。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 取得或設定「標記為裝飾性」選項。 可讀寫 Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 判斷形狀是否已群組。 唯讀 Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 判斷形狀是否為 TextHolder_PPT。 唯讀 Boolean。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 返回包含形狀線條格式屬性的 LineFormat 物件。 注意：對於某些沒有線條屬性的形狀可能返回 null。 唯讀 [`ILineFormat`](../../aspose.slides/ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 返回或設定形狀的名稱。 必須非 null。如有需要可使用空字串。 可讀寫 String。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 返回在投影片範圍內唯一的識別碼，在形狀生命週期內保持不變，讓 PowerPoint 或 interop 程式碼能可靠地在文件任何位置參照此形狀。 唯讀 UInt32。另請參閱 [`UniqueId`](../../aspose.slides/shape/uniqueid)。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 若形狀已群組，返回父級 GroupShape 物件；否則返回 null。 唯讀 [`IGroupShape`](../../aspose.slides/igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 返回形狀的佔位符。若形狀沒有佔位符則返回 null。 唯讀 [`IPlaceholder`](../../aspose.slides/iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 返回投影片的父級簡報。 唯讀 [`IPresentation`](../../aspose.slides/ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 返回或設定原始形狀框架的屬性。 可讀寫 [`IShapeFrame`](../../aspose.slides/ishapeframe)。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 返回或設定形狀繞 Z 軸旋轉的角度（度）。正值表示順時針旋轉，負值表示逆時針旋轉。 可讀寫 Single。 |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | 返回形狀的鎖定狀態。 唯讀 [`IBaseShapeLock`](../../aspose.slides/ibaseshapelock)。 |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | 返回形狀的樣式物件。 唯讀 [`IShapeStyle`](../../aspose.slides/ishapestyle)。 |
| override [ShapeType](../../aspose.slides.smartart/smartartshape/shapetype) { get; set; } | 返回或設定幾何預設類型。 注意：值變更時所有調整值將重設為預設值。 可讀寫 [`ShapeType`](../../aspose.slides/shapetype)。 |
| [Slide](../../aspose.slides/shape/slide) { get; } | 返回形狀的父投影片。 唯讀 [`IBaseSlide`](../../aspose.slides/ibaseslide)。 |
| [TextFrame](../../aspose.slides.smartart/smartartshape/textframe) { get; } | 返回 SmartArt 形狀的文字。 唯讀 [`ITextFrame`](../../aspose.slides/itextframe)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 返回包含形狀 3D 效果屬性的 ThreeDFormat 物件。 注意：對於某些沒有 3D 屬性的形狀可能返回 null。 唯讀 [`IThreeDFormat`](../../aspose.slides/ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 返回用於外掛或其他程式碼的內部、簡報範圍內的識別碼。由於此值可能被使用者或程式重新指派，不能視為持久的唯一鍵。 唯讀 UInt32。另請參閱 [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid)。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 取得或設定形狀的寬度，以點為單位。 可讀寫 Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 取得或設定形狀左上角的 X 座標，以點為單位。 可讀寫 Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 取得或設定形狀左上角的 Y 座標，以點為單位。 可讀寫 Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 返回形狀在 Z 順序中的位置。Shapes[0] 代表 Z 順序最底層的形狀，Shapes[Shapes.Count - 1] 代表最前層的形狀。 唯讀 Int32。 |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 若不存在則新增佔位符，並將佔位符屬性設定為指定的佔位符。 |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | 建立並返回形狀元素的陣列。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 返回基本佔位符形狀（來自版面配置或母片投影片且目前形狀繼承自該形狀）。若目前形狀未繼承則返回 null。 |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | 返回幾何形狀路徑的副本。座標相對於形狀左上角。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 返回形狀縮圖。預設使用 ShapeThumbnailBounds.Shape 形狀縮圖邊界類型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 返回形狀縮圖。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 取得根據已呈現內容計算的形狀視覺邊界。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定義此形狀不是佔位符。 |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | 從 [`IGeometryPath`](../../aspose.slides/igeometrypath) 物件更新形狀幾何。座標必須相對於形狀左上角。將形狀類型 ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) 變更為 Custom。 |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | 從 [`IGeometryPath`](../../aspose.slides/igeometrypath) 陣列更新形狀幾何。座標必須相對於形狀左上角。將形狀類型 ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) 變更為 Custom。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 將 Shape 內容另存為 SVG 檔案。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 將 Shape 內容另存為 SVG 檔案。 |

### 參見

* 類別 [GeometryShape](../../aspose.slides/geometryshape)
* 介面 [ISmartArtShape](../ismartartshape)
* 命名空間 [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->