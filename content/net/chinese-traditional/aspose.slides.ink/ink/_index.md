---
title: Ink
second_title: Aspose.Sildes 的 .NET API 參考
description: 表示投影片上的墨水物件。
type: docs
weight: 7570
url: /zh-hant/aspose.slides.ink/ink/
---
## Ink 類別

Represents an ink object on a slide.

```csharp
public class Ink : GraphicalObject, IInk
```

## 屬性

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 取得或設定與形狀相關聯的替代文字。可讀寫 String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 取得或設定與形狀相關聯的替代文字標題。可讀寫 String。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 屬性指定形狀在黑白顯示模式下的呈現方式。可讀寫 [`BlackWhiteMode`](../../aspose.slides/blackwhitemode)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 取得形狀的連接點數量。唯讀 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 取得形狀的自訂資料。唯讀 [`ICustomData`](../../aspose.slides/icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 取得包含套用於形狀的像素效果的 EffectFormat 物件。註：對於沒有效果屬性的某些形狀類型，可能會傳回 null。唯讀 [`IEffectFormat`](../../aspose.slides/ieffectformat)。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 取得包含形狀填色格式屬性的 FillFormat 物件。註：對於沒有填色屬性的某些形狀類型，可能會傳回 null。唯讀 [`IFillFormat`](../../aspose.slides/ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 取得或設定形狀框架的屬性。可讀寫 [`IShapeFrame`](../../aspose.slides/ishapeframe)。 |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | 取得形狀的鎖定。唯讀 [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 取得或設定形狀的高度（以點為單位）。可讀寫 Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 決定形狀是否隱藏。可讀寫 Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 取得或設定滑鼠點擊時的超連結。可讀寫 [`IHyperlink`](../../aspose.slides/ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 取得超連結管理員。唯讀 [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 取得或設定滑鼠懸停時的超連結。可讀寫 [`IHyperlink`](../../aspose.slides/ihyperlink)。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 取得或設定「標記為裝飾」選項。可讀寫 Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 決定形狀是否已群組。唯讀 Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 決定形狀是否為 TextHolder_PPT。唯讀 Boolean。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 取得包含形狀線條格式屬性的 LineFormat 物件。註：對於沒有線條屬性的某些形狀類型，可能會傳回 null。唯讀 [`ILineFormat`](../../aspose.slides/ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 取得或設定形狀的名稱。不得為 null。必要時使用空字串值。可讀寫 String。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 取得在投影片範圍內唯一且在形狀生命週期內保持不變的識別碼，讓 PowerPoint 或互操作程式碼能可靠地從文件中的任何位置參照此形狀。唯讀 UInt32。另請參閱 [`UniqueId`](../../aspose.slides/shape/uniqueid)。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 如果形狀已群組，取得其父 GroupShape 物件；否則傳回 null。唯讀 [`IGroupShape`](../../aspose.slides/igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 取得形狀的佔位符。如果形狀沒有佔位符，則傳回 null。唯讀 [`IPlaceholder`](../../aspose.slides/iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 取得投影片的父簡報。唯讀 [`IPresentation`](../../aspose.slides/ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 取得或設定原始形狀框架的屬性。可讀寫 [`IShapeFrame`](../../aspose.slides/ishapeframe)。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 取得或設定指定形狀繞 z 軸旋轉的角度（度數）。正值表示順時針旋轉，負值表示逆時針旋轉。可讀寫 Single。 |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | 取得形狀的鎖定。唯讀 [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock)。（2 個屬性） |
| [Slide](../../aspose.slides/shape/slide) { get; } | 取得形狀的父投影片。唯讀 [`IBaseSlide`](../../aspose.slides/ibaseslide)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 取得包含形狀 3D 效果屬性的 ThreeDFormat 物件。註：對於沒有 3D 屬性的某些形狀類型，可能會傳回 null。唯讀 [`IThreeDFormat`](../../aspose.slides/ithreedformat)。 |
| [Traces](../../aspose.slides.ink/ink/traces) { get; } | 取得 IInk 元素 [`IInkTrace`](../iinktrace) 中包含的所有痕跡。唯讀。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 取得供外掛程式或其他程式碼使用的內部、簡報範圍內識別碼。由於此值可能被使用者或程式重新指派，不能視為永久唯一鍵。唯讀 UInt32。另請參閱 [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid)。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 取得或設定形狀的寬度（以點為單位）。可讀寫 Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 取得或設定形狀左上角的 x 座標（以點為單位）。可讀寫 Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 取得或設定形狀左上角的 y 座標（以點為單位）。可讀寫 Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 取得形狀在 Z 軸順序中的位置。Shapes[0] 會返回位於 Z 軸順序最底層的形狀，Shapes[Shapes.Count - 1] 會返回位於最前面的形狀。唯讀 Int32。 |
| static [InkEffectImages](../../aspose.slides.ink/ink/inkeffectimages) { get; } | 取得用於模擬墨水筆刷視覺效果的自訂影像集合。當使用特定 [`InkEffectType`](../inkeffecttype) 值（如 Galaxy、Rainbow 等）渲染墨水時，會使用這些影像。提供自訂影像即可控制每種墨水效果的顯示方式。 |

## 方法

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 如果不存在，新增一個佔位符，並將佔位符屬性設定為指定的佔位符。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 傳回基本的佔位符形狀（從版面配置或母片投影片繼承而來的形狀）。如果目前形狀未繼承，則傳回 null。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 傳回形狀縮圖。預設使用 ShapeThumbnailBounds.Shape 的縮圖邊界類型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 傳回形狀縮圖。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 取得由渲染內容計算出的形狀視覺邊界。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定義此形狀不是佔位符。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 將形狀內容儲存為 SVG 檔案。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 將形狀內容儲存為 SVG 檔案。 |

### 另請參閱

* 類別 [GraphicalObject](../../aspose.slides/graphicalobject)
* 介面 [IInk](../iink)
* 命名空間 [Aspose.Slides.Ink](../../aspose.slides.ink)
* 程式集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->