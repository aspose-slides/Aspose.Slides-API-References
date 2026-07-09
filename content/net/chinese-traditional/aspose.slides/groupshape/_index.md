---
title: GroupShape
second_title: Aspose.Sildes for .NET API 參考文件
description: 表示投影片上形狀的群組。
type: docs
weight: 5090
url: /zh-hant/aspose.slides/groupshape/
---
## GroupShape 類別

表示投影片上形狀的群組。

```csharp
public class GroupShape : Shape, IGroupShape
```

## 屬性

| 名稱 | 描述 |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 取得或設定與形狀關聯的替代文字。讀/寫 String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 取得或設定與形狀關聯的替代文字標題。讀/寫 String。 |
| [AsIShape](../../aspose.slides/groupshape/asishape) { get; } | 允許取得基礎 IShape 介面。唯讀 [`IShape`](../ishape)。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 屬性指定形狀在黑白顯示模式下的呈現方式。讀/寫 [`BlackWhiteMode`](../blackwhitemode)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 取得形狀的連接點數量。唯讀 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 取得形狀的自訂資料。唯讀 [`ICustomData`](../icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 取得包含套用於形狀的像素效果的 EffectFormat 物件。註：對於沒有效果屬性的某些形狀類型，可能回傳 null。唯讀 [`IEffectFormat`](../ieffectformat)。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 取得包含形狀填充格式屬性的 FillFormat 物件。註：對於沒有填充屬性的某些形狀類型，可能回傳 null。唯讀 [`IFillFormat`](../ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 取得或設定形狀框架的屬性。讀/寫 [`IShapeFrame`](../ishapeframe)。 |
| [GroupShapeLock](../../aspose.slides/groupshape/groupshapelock) { get; } | 取得形狀的鎖定。唯讀 [`IGroupShapeLock`](../igroupshapelock)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 取得或設定形狀的高度（以點為單位）。讀/寫 Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 判斷形狀是否隱藏。讀/寫 Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 取得或設定滑鼠點擊時定義的超連結。讀/寫 [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 取得超連結管理員。唯讀 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 取得或設定滑鼠懸停時定義的超連結。讀/寫 [`IHyperlink`](../ihyperlink)。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 取得或設定 “標記為裝飾” 選項。讀/寫 Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 判斷形狀是否已群組。唯讀 Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 判斷形狀是否為 TextHolder_PPT。唯讀 Boolean。 |
| override [LineFormat](../../aspose.slides/groupshape/lineformat) { get; } | 取得包含形狀線條格式屬性的 LineFormat 物件。註：對於 GroupShape 物件，會回傳 null，因為它們沒有線條屬性。唯讀 [`ILineFormat`](../ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 取得或設定形狀的名稱。不得為 null。必要時使用空字串。讀/寫 String。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 取得在投影片範圍內唯一且在形狀生命週期內保持不變的識別碼，讓 PowerPoint 或 interop 程式碼能從文件任何位置可靠地參照此形狀。唯讀 UInt32。另請參閱 [`UniqueId`](../shape/uniqueid)。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 如果形狀已群組，則返回其父 GroupShape 物件；否則返回 null。唯讀 [`IGroupShape`](../igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 取得形狀的佔位符。如果形狀沒有佔位符，則回傳 null。唯讀 [`IPlaceholder`](../iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 取得投影片的父簡報。唯讀 [`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 取得或設定原始形狀框架的屬性。讀/寫 [`IShapeFrame`](../ishapeframe)。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 取得或設定指定形狀繞 z 軸旋轉的角度（度）。正值表示順時針旋轉；負值表示逆時針旋轉。讀/寫 Single。 |
| [ShapeLock](../../aspose.slides/groupshape/shapelock) { get; } | 取得形狀的鎖定。唯讀 [`IGroupShapeLock`](../igroupshapelock)。（2 個屬性） |
| [Shapes](../../aspose.slides/groupshape/shapes) { get; } | 取得群組內的形狀集合。唯讀 [`IShapeCollection`](../ishapecollection)。 |
| [Slide](../../aspose.slides/shape/slide) { get; } | 取得形狀的父投影片。唯讀 [`IBaseSlide`](../ibaseslide)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 取得形狀的 ThreeDFormat 物件，包含 3D 效果屬性。註：對於沒有 3D 屬性的某些形狀類型，可能回傳 null。唯讀 [`IThreeDFormat`](../ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 取得用於外掛程式或其他程式碼的內部、簡報範圍識別碼。因為此值可能被使用者或程式重新指派，所以不應視為持久的唯一鍵。唯讀 UInt32。另請參閱 [`OfficeInteropShapeId`](../shape/officeinteropshapeid)。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 取得或設定形狀的寬度（以點為單位）。讀/寫 Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 取得或設定形狀左上角的 x 座標（以點為單位）。讀/寫 Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 取得或設定形狀左上角的 y 座標（以點為單位）。讀/寫 Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 取得形狀在 Z 軸排序中的位置。Shapes[0] 會回傳位於 Z 軸最底部的形狀，Shapes[Shapes.Count - 1] 會回傳位於 Z 軸最前端的形狀。唯讀 Int32。 |

## 方法

| 名稱 | 描述 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 如果不存在則新增一個佔位符，並將佔位符屬性設為指定的佔位符。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 回傳基本的佔位符形狀（來自版面配置和/或母片，且為目前形狀所繼承的形狀）。如果目前形狀未繼承，則回傳 null。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 回傳形狀縮圖。預設使用 ShapeThumbnailBounds.Shape 形狀縮圖邊界類型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 回傳形狀縮圖。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 取得依渲染內容計算出的形狀視覺邊界。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定義此形狀不是佔位符。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 將形狀內容儲存為 SVG 檔案。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 將形狀內容儲存為 SVG 檔案。 |

### 另請參閱

* 類別 [Shape](../shape)
* 介面 [IGroupShape](../igroupshape)
* 命名空間 [Aspose.Slides](../../aspose.slides)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->