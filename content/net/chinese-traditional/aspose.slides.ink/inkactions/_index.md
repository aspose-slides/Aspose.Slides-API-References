---
title: InkActions
second_title: Aspose.Sildes for .NET API 參考
description: 表示墨跡動作的根。
type: docs
weight: 7560
url: /zh-hant/aspose.slides.ink/inkactions/
---
## InkActions 類別

表示墨跡動作的根。

```csharp
public class InkActions : GraphicalObject, IInkActions
```

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 取得或設定與圖案關聯的替代文字。讀寫 String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 取得或設定與圖案關聯的替代文字標題。讀寫 String。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 屬性指定圖案在黑白顯示模式下的呈現方式。讀寫 [`BlackWhiteMode`](../../aspose.slides/blackwhitemode)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 取得圖案的連接點數量。唯讀 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 取得圖案的自訂資料。唯讀 [`ICustomData`](../../aspose.slides/icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 取得包含套用於圖案之像素效果的 EffectFormat 物件。註：對於某些沒有效果屬性的圖案可能傳回 null。唯讀 [`IEffectFormat`](../../aspose.slides/ieffectformat)。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 取得包含圖案填色格式屬性的 FillFormat 物件。註：對於某些沒有填色屬性的圖案可能傳回 null。唯讀 [`IFillFormat`](../../aspose.slides/ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 取得或設定圖案框架的屬性。讀寫 [`IShapeFrame`](../../aspose.slides/ishapeframe)。 |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | 取得圖案的鎖定資訊。唯讀 [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 取得或設定圖案的高度（以點為單位）。讀寫 Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 決定圖案是否隱藏。讀寫 Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 取得或設定滑鼠點擊時的超連結。讀寫 [`IHyperlink`](../../aspose.slides/ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 取得超連結管理員。唯讀 [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 取得或設定滑鼠移過時的超連結。讀寫 [`IHyperlink`](../../aspose.slides/ihyperlink)。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 取得或設定「Mark as decorative」選項 Reed/write Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 判斷圖案是否已分組。唯讀 Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 判斷圖案是否為 TextHolder_PPT。唯讀 Boolean。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 取得包含圖案線條格式屬性的 LineFormat 物件。註：對於某些沒有線條屬性的圖案可能傳回 null。唯讀 [`ILineFormat`](../../aspose.slides/ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 取得或設定圖案的名稱。不得為 null；如有需要請使用空字串。讀寫 String。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 取得在投影片範圍內唯一且在圖案生命週期內保持不變的識別碼，可讓 PowerPoint 或 interop 程式碼在文件任意位置可靠地參照圖案。唯讀 UInt32。另請參閱 [`UniqueId`](../../aspose.slides/shape/uniqueid)。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 若圖案已分組，傳回其父 GroupShape 物件；否則傳回 null。唯讀 [`IGroupShape`](../../aspose.slides/igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 取得圖案的占位符；若圖案無占位符則傳回 null。唯讀 [`IPlaceholder`](../../aspose.slides/iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 取得投影片的父簡報。唯讀 [`IPresentation`](../../aspose.slides/ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 取得或設定原始圖案框架的屬性。讀寫 [`IShapeFrame`](../../aspose.slides/ishapeframe)。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 取得或設定圖案繞 Z 軸旋轉的角度（以度為單位）。正值表示順時針旋轉；負值表示逆時針旋轉。讀寫 Single。 |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | 取得圖案的鎖定資訊。唯讀 [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock)。（2 個屬性） |
| [Slide](../../aspose.slides/shape/slide) { get; } | 取得圖案的父投影片。唯讀 [`IBaseSlide`](../../aspose.slides/ibaseslide)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 取得包含圖案 3D 效果屬性的 ThreeDFormat 物件。註：對於某些沒有 3D 屬性的圖案可能傳回 null。唯讀 [`IThreeDFormat`](../../aspose.slides/ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 取得供外掛程式或其他程式碼使用的內部、簡報範圍識別碼。因為此值可能被使用者或程式碼重新指派，故不應視為永久唯一鍵。唯讀 UInt32。另請參閱 [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid)。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 取得或設定圖案的寬度（以點為單位）。讀寫 Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 取得或設定圖案左上角的 X 座標（以點為單位）。讀寫 Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 取得或設定圖案左上角的 Y 座標（以點為單位）。讀寫 Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 取得圖案在 Z 順序中的位置。Shapes[0] 為 Z 順序最底層圖案，Shapes[Shapes.Count - 1] 為最上層圖案。唯讀 Int32。 |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 若不存在則新增占位符，並將占位符屬性設定為指定的占位符。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 取得基礎占位符圖案（來自版面配置或母投影片且目前圖案繼承自該圖案）。若目前圖案未繼承則傳回 null。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 取得圖案縮圖。預設使用 ShapeThumbnailBounds.Shape 圖案縮圖邊界類型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 取得圖案縮圖。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 取得根據已呈現內容計算出的圖案視覺邊界。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定義此圖案不是占位符。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 將圖案內容儲存為 SVG 檔案。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 將圖案內容儲存為 SVG 檔案。 |

### 另請參閱

* 類別 [GraphicalObject](../../aspose.slides/graphicalobject)
* 介面 [IInkActions](../iinkactions)
* 命名空間 [Aspose.Slides.Ink](../../aspose.slides.ink)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->