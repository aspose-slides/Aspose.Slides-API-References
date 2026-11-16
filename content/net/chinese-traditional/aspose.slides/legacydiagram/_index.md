---
title: LegacyDiagram
second_title: Aspose.Sildes .NET API 參考
description: 表示舊版圖表物件。
type: docs
weight: 7690
url: /zh-hant/aspose.slides/legacydiagram/
---
## LegacyDiagram 類別

表示舊版圖表物件。

```csharp
public class LegacyDiagram : GraphicalObject, ILegacyDiagram
```

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 返回或設定與形狀相關聯的替代文字。 讀寫 String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 返回或設定與形狀相關聯的替代文字標題。 讀寫 String。 |
| [AsIGraphicalObject](../../aspose.slides/legacydiagram/asigraphicalobject) { get; } | 允許取得基礎 IGraphicalObject 介面。 唯讀 [`IGraphicalObject`](../igraphicalobject)。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 屬性指定形狀在黑白顯示模式下的呈現方式。 讀寫 [`BlackWhiteMode`](../blackwhitemode)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 返回形狀的連接點數量。 唯讀 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 返回形狀的自訂資料。 唯讀 [`ICustomData`](../icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 返回包含套用在形狀上的像素效果的 EffectFormat 物件。 注意：對於某些沒有效果屬性的形狀可能返回 null。 唯讀 [`IEffectFormat`](../ieffectformat)。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 返回包含形狀填充格式屬性的 FillFormat 物件。 注意：對於某些沒有填充屬性的形狀可能返回 null。 唯讀 [`IFillFormat`](../ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 返回或設定形狀框架的屬性。 讀寫 [`IShapeFrame`](../ishapeframe)。 |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | 返回形狀的鎖定資訊。 唯讀 [`IGraphicalObjectLock`](../igraphicalobjectlock)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 取得或設定形狀的高度，單位為點。 讀寫 Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 判斷形狀是否為隱藏。 讀寫 Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 返回或設定滑鼠點擊時的超連結。 讀寫 [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 返回超連結管理員。 唯讀 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 返回或設定滑鼠懸停時的超連結。 讀寫 [`IHyperlink`](../ihyperlink)。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 取得或設定「標記為裝飾」選項。 讀寫 Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 判斷形狀是否已分組。 唯讀 Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 判斷形狀是否為 TextHolder_PPT。 唯讀 Boolean。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 返回包含形狀線條格式屬性的 LineFormat 物件。 注意：對於某些沒有線條屬性的形狀可能返回 null。 唯讀 [`ILineFormat`](../ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 返回或設定形狀的名稱。 必須非 null，必要時使用空字串。 讀寫 String。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 返回在投影片範圍內唯一的識別碼，該識別碼在形狀生命週期內保持不變，讓 PowerPoint 或 interop 程式碼能可靠地從文件任何位置參照此形狀。 唯讀 UInt32。另請參閱 [`UniqueId`](../shape/uniqueid)。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 若形狀已分組，返回父層 GroupShape 物件；否則返回 null。 唯讀 [`IGroupShape`](../igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 返回形狀的占位符。若形狀沒有占位符則返回 null。 唯讀 [`IPlaceholder`](../iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 返回投影片的父級簡報。 唯讀 [`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 返回或設定原始形狀框架的屬性。 讀寫 [`IShapeFrame`](../ishapeframe)。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 返回或設定指定形狀繞 Z 軸旋轉的角度（度）。正值表示順時針旋轉，負值表示逆時針旋轉。 讀寫 Single。 |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | 返回形狀的鎖定資訊。 唯讀 [`IGraphicalObjectLock`](../igraphicalobjectlock)。 (2 個屬性) |
| [Slide](../../aspose.slides/shape/slide) { get; } | 返回形狀的父投影片。 唯讀 [`IBaseSlide`](../ibaseslide)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 返回包含形狀 3D 效果屬性的 ThreeDFormat 物件。 注意：對於某些沒有 3D 屬性的形狀可能返回 null。 唯讀 [`IThreeDFormat`](../ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 返回供外掛或其他程式使用的內部、簡報範圍識別碼。由於此值可能被使用者或程式重新指派，不能視為永久唯一鍵。 唯讀 UInt32。另請參閱 [`OfficeInteropShapeId`](../shape/officeinteropshapeid)。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 取得或設定形狀的寬度，單位為點。 讀寫 Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 取得或設定形狀左上角的 X 座標，單位為點。 讀寫 Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 取得或設定形狀左上角的 Y 座標，單位為點。 讀寫 Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 返回形狀在 Z 序中的位置。Shapes[0] 代表最底層，Shapes[Shapes.Count - 1] 代表最上層。 唯讀 Int32。 |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 若不存在則新增占位符，並將占位符屬性設定為指定的占位符。 |
| [ConvertToGroupShape](../../aspose.slides/legacydiagram/converttogroupshape)() | 將舊版圖表轉換為可編輯的群組形狀。已建立的 GroupShape 物件會在相同位置加入父群組形狀。 |
| [ConvertToSmartArt](../../aspose.slides/legacydiagram/converttosmartart)() | 將舊版圖表轉換為可編輯的 SmartArt 物件。已建立的 SmartArt 物件會在相同位置加入父群組形狀。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 返回基本占位符形狀（從版面配置或母版投影片繼承的形狀）。若目前形狀未繼承則返回 null。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 返回形狀縮圖。預設使用 ShapeThumbnailBounds.Shape 形狀縮圖邊界類型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 返回形狀縮圖。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 取得根據已呈現內容計算出的形狀視覺邊界。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定義此形狀不是占位符。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 將 Shape 內容儲存為 SVG 檔案。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 將 Shape 內容儲存為 SVG 檔案。 |

### 另見

* 類別 [GraphicalObject](../graphicalobject)
* 介面 [ILegacyDiagram](../ilegacydiagram)
* 命名空間 [Aspose.Slides](../../aspose.slides)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->