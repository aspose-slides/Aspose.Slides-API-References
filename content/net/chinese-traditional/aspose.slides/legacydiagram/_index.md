---
title: LegacyDiagram
second_title: Aspose.Sildes for .NET API 參考文件
description: 代表傳統圖表物件。
type: docs
weight: 7670
url: /zh-hant/aspose.slides/legacydiagram/
---
## LegacyDiagram 類別

代表一個傳統圖表物件。

```csharp
public class LegacyDiagram : GraphicalObject, ILegacyDiagram
```

## Properties

| 名稱 | 描述 |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 取得或設定與圖形相關聯的替代文字。 讀寫 String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 取得或設定與圖形相關聯的替代文字標題。 讀寫 String. |
| [AsIGraphicalObject](../../aspose.slides/legacydiagram/asigraphicalobject) { get; } | 允許取得基礎 IGraphicalObject 介面。 唯讀 [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 屬性指定圖形在黑白顯示模式下的呈現方式。 讀寫 [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 取得圖形的連接點數量。 唯讀 Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 取得圖形的自訂資料。 唯讀 [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 取得包含套用於圖形之像素效果的 EffectFormat 物件。 註：對於沒有效果屬性的某些圖形類型，可能會傳回 null。 唯讀 [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 取得包含圖形填充格式屬性的 FillFormat 物件。 註：對於沒有填充屬性的某些圖形類型，可能會傳回 null。 唯讀 [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 取得或設定圖形框架的屬性。 讀寫 [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | 取得圖形的鎖定。 唯讀 [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | 取得或設定圖形的高度（以點為單位）。 讀寫 Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 判斷圖形是否被隱藏。 讀寫 Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 取得或設定滑鼠點擊時的超連結。 讀寫 [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 取得超連結管理員。 唯讀 [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 取得或設定滑鼠懸停時的超連結。 讀寫 [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 取得或設定「標記為裝飾」選項。 讀寫 Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 判斷圖形是否已分組。 唯讀 Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 判斷圖形是否為 TextHolder_PPT。 唯讀 Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 取得包含圖形線條格式屬性的 LineFormat 物件。 註：對於沒有線條屬性的某些圖形類型，可能會傳回 null。 唯讀 [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | 取得或設定圖形的名稱。 必須非 null。如有需要可使用空字串。 讀寫 String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 取得在投影片範圍內的唯一識別碼，此識別碼在圖形生命週期內保持不變，讓 PowerPoint 或互操作程式碼能可靠地從文件任何位置參照圖形。 唯讀 UInt32。 另請參閱 [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 若圖形已分組，取得其父層 GroupShape 物件。否則傳回 null。 唯讀 [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 取得圖形的占位符。若圖形沒有占位符，則傳回 null。 唯讀 [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 取得投影片的父簡報。 唯讀 [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 取得或設定原始圖形框架的屬性。 讀寫 [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 取得或設定指定圖形繞 Z 軸旋轉的度數。正值表示順時針旋轉，負值表示逆時針旋轉。 讀寫 Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | 取得圖形的鎖定。 唯讀 [`IGraphicalObjectLock`](../igraphicalobjectlock)。（2 個屬性） |
| [Slide](../../aspose.slides/shape/slide) { get; } | 取得圖形的父投影片。 唯讀 [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 取得圖形的 ThreeDFormat 物件，其包含 3D 效果屬性。 註：對於沒有 3D 屬性的某些圖形類型，可能會傳回 null。 唯讀 [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 取得內部、簡報範圍的識別碼，供外掛程式或其他程式碼使用。由於此值可能被使用者或程式重新指派，不能視為永久唯一鍵。 唯讀 UInt32。 另請參閱 [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | 取得或設定圖形的寬度（以點為單位）。 讀寫 Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | 取得或設定圖形左上角的 x 座標（以點為單位）。 讀寫 Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | 取得或設定圖形左上角的 y 座標（以點為單位）。 讀寫 Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 取得圖形在 Z 軸排序中的位置。Shapes[0] 會回傳位於 Z 軸最底層的圖形，Shapes[Shapes.Count - 1] 會回傳位於最前面的圖形。 唯讀 Int32. |

## Methods

| 名稱 | 描述 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 如果不存在則新增佔位符，並將佔位符屬性設定為指定的佔位符。 |
| [ConvertToGroupShape](../../aspose.slides/legacydiagram/converttogroupshape)() | 將傳統圖表轉換為可編輯的群組圖形。建立的 GroupShape 物件會在相同位置加入至父群組圖形。 |
| [ConvertToSmartArt](../../aspose.slides/legacydiagram/converttosmartart)() | 將傳統圖表轉換為可編輯的 SmartArt 物件。建立的 SmartArt 物件會在相同位置加入至父群組圖形。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 取得基本的佔位符形狀（即從版面配置或母版投影片繼承的形狀）。如果目前的形狀未繼承，則傳回 null。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 取得圖形縮圖。預設使用 ShapeThumbnailBounds.Shape 圖形縮圖邊界類型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 取得圖形縮圖。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 取得根據圖形已渲染內容計算的視覺邊界。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定義此圖形不是佔位符。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 將圖形內容儲存為 SVG 檔案。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 將圖形內容儲存為 SVG 檔案。 |

### 另請參閱

* 類別 [GraphicalObject](../graphicalobject)
* 介面 [ILegacyDiagram](../ilegacydiagram)
* 命名空間 [Aspose.Slides](../../aspose.slides)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->