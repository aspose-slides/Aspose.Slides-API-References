---
title: SmartArt
second_title: Aspose.Sildes .NET API 參考
description: 表示一個 SmartArt 圖表
type: docs
weight: 10620
url: /zh-hant/aspose.slides.smartart/smartart/
---
## SmartArt 類別

表示 SmartArt 圖表

```csharp
public class SmartArt : GraphicalObject, ISmartArt
```

## 屬性

| Name | Description |
| --- | --- |
| [AllNodes](../../aspose.slides.smartart/smartart/allnodes) { get; } | 傳回 SmartArt 物件中所有節點的集合。唯讀 [`ISmartArtNodeCollection`](../ismartartnodecollection)。 |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 傳回或設定與圖形關聯的替代文字。讀寫 String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 傳回或設定與圖形關聯的替代文字標題。讀寫 String。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 屬性指定圖形在黑白顯示模式下的呈現方式。讀寫 [`BlackWhiteMode`](../../aspose.slides/blackwhitemode)。 |
| [ColorStyle](../../aspose.slides.smartart/smartart/colorstyle) { get; set; } | 傳回或設定 SmartArt 物件的顏色樣式。讀寫 [`SmartArtColorType`](../smartartcolortype)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 傳回圖形的連線點數量。唯讀 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 傳回圖形的自訂資料。唯讀 [`ICustomData`](../../aspose.slides/icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 傳回包含套用於圖形的像素效果的 EffectFormat 物件。注意：對於某些不具備效果屬性的圖形類型，可能傳回 null。唯讀 [`IEffectFormat`](../../aspose.slides/ieffectformat)。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 傳回包含圖形填充格式屬性的 FillFormat 物件。注意：對於某些不具備填充屬性的圖形類型，可能傳回 null。唯讀 [`IFillFormat`](../../aspose.slides/ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 傳回或設定圖形框架的屬性。讀寫 [`IShapeFrame`](../../aspose.slides/ishapeframe)。 |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | 傳回圖形的鎖定資訊。唯讀 [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 取得或設定圖形的高度，單位為點。讀寫 Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 判斷圖形是否隱藏。讀寫 Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 傳回或設定滑鼠點擊時的超連結。讀寫 [`IHyperlink`](../../aspose.slides/ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 傳回超連結管理員。唯讀 [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 傳回或設定滑鼠移過時的超連結。讀寫 [`IHyperlink`](../../aspose.slides/ihyperlink)。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 取得或設定「標記為裝飾」選項。讀寫 Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 判斷圖形是否已群組。唯讀 Boolean。 |
| [IsReversed](../../aspose.slides.smartart/smartart/isreversed) { get; set; } | 傳回或設定 SmartArt 圖表的方向狀態，以左至右 (LTR) 或右至左 (RTL) 為準，前提是圖表支援方向反轉。讀寫 Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 判斷圖形是否為 TextHolder_PPT。唯讀 Boolean。 |
| [Layout](../../aspose.slides.smartart/smartart/layout) { get; set; } | 傳回或設定 SmartArt 物件的版面配置。讀寫 [`SmartArtLayoutType`](../smartartlayouttype)。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 傳回包含圖形線條格式屬性的 LineFormat 物件。注意：對於某些不具備線條屬性的圖形類型，可能傳回 null。唯讀 [`ILineFormat`](../../aspose.slides/ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 傳回或設定圖形的名稱。不得為 null。若需要，請使用空字串。讀寫 String。 |
| [Nodes](../../aspose.slides.smartart/smartart/nodes) { get; } | 傳回 SmartArt 物件中根節點的集合。唯讀 [`ISmartArtNodeCollection`](../ismartartnodecollection)。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 傳回唯一且僅在投影片範圍內的識別碼，該識別碼在圖形生命週期內保持不變，讓 PowerPoint 或 interop 程式碼能從文件任何位置可靠地參照該圖形。唯讀 UInt32。另請參閱 [`UniqueId`](../../aspose.slides/shape/uniqueid)。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 若圖形已群組，傳回父層 GroupShape 物件，否則傳回 null。唯讀 [`IGroupShape`](../../aspose.slides/igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 傳回圖形的佔位元件。若圖形沒有佔位元件，則傳回 null。唯讀 [`IPlaceholder`](../../aspose.slides/iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 傳回投影片的父簡報。唯讀 [`IPresentation`](../../aspose.slides/ipresentation)。 |
| [QuickStyle](../../aspose.slides.smartart/smartart/quickstyle) { get; set; } | 傳回或設定 SmartArt 物件的快速樣式。讀寫 [`SmartArtQuickStyleType`](../smartartquickstyletype)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 傳回或設定圖形框架的原始屬性。讀寫 [`IShapeFrame`](../../aspose.slides/ishapeframe)。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 傳回或設定指定圖形繞 z 軸旋轉的角度（度數）。正值表示順時鐘旋轉，負值表示逆時鐘旋轉。讀寫 Single。 |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | 傳回圖形的鎖定資訊。唯讀 [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock)。 (2 個屬性) |
| [Slide](../../aspose.slides/shape/slide) { get; } | 傳回圖形的父投影片。唯讀 [`IBaseSlide`](../../aspose.slides/ibaseslide)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 傳回包含圖形 3D 效果屬性的 ThreeDFormat 物件。注意：對於某些不具備 3D 屬性的圖形類型，可能傳回 null。唯讀 [`IThreeDFormat`](../../aspose.slides/ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 傳回供外掛或其他程式碼使用的內部、僅限簡報範圍的識別碼。由於此值可能被使用者或程式重新指派，不能視為永久唯一鍵。唯讀 UInt32。另請參閱 [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid)。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 取得或設定圖形的寬度，單位為點。讀寫 Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 取得或設定圖形左上角的 X 座標，單位為點。讀寫 Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 取得或設定圖形左上角的 Y 座標，單位為點。讀寫 Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 傳回圖形在 Z 順序中的位置。Shapes[0] 代表 Z 順序最背後的圖形，Shapes[Shapes.Count - 1] 代表最前面的圖形。唯讀 Int32。 |

## 方法

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 如果不存在佔位元件，則新增一個，並將其屬性設定為指定的佔位元件。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 傳回基本佔位元件形狀（來自版面配置和/或母片投影片、目前圖形所繼承的形狀）。若目前圖形未繼承則傳回 null。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 傳回圖形縮圖。預設使用 ShapeThumbnailBounds.Shape 圖形縮圖範圍類型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 傳回圖形縮圖。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 取得根據已呈現內容計算出的圖形可視範圍。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定義此圖形不是佔位元件。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 將圖形內容儲存為 SVG 檔案。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 將圖形內容儲存為 SVG 檔案。 |

### 另請參閱

* 類別 [GraphicalObject](../../aspose.slides/graphicalobject)
* 介面 [ISmartArt](../ismartart)
* 命名空間 [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* 程式集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->