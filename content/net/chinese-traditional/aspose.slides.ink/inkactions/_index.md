---
title: InkActions
second_title: Aspose.Sildes for .NET API 參考文件
description: 表示墨跡動作的根節點。
type: docs
weight: 7580
url: /zh-hant/aspose.slides.ink/inkactions/
---
## InkActions 類別

表示墨跡動作的根節點。

```csharp
public class InkActions : GraphicalObject, IInkActions
```

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 傳回或設定與形狀相關聯的替代文字。Read/write String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 傳回或設定與形狀相關聯的替代文字標題。Read/write String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 屬性指定形狀在黑白顯示模式下的渲染方式。Read/write [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 傳回形狀的連接點數量。Read-only Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 傳回形狀的自訂資料。Read-only [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 傳回包含套用於形狀之像素效果的 EffectFormat 物件。注意：對於某些不具有效果屬性的形狀可能返回 null。Read-only [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 傳回包含形狀填充格式屬性的 FillFormat 物件。注意：對於某些不具有填充屬性的形狀可能返回 null。Read-only [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 傳回或設定形狀框架的屬性。Read/write [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | 傳回形狀的鎖定設定。Read-only [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | 取得或設定形狀的高度，以點為單位。Read/write Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 判斷形狀是否隱藏。Read/write Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 傳回或設定點擊滑鼠時的超連結。Read/write [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 傳回超連結管理員。Read-only [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 傳回或設定滑鼠懸停時的超連結。Read/write [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 取得或設定「標記為裝飾」選項 Reed/write Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 判斷形狀是否已群組。Read-only Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 判斷形狀是否為 TextHolder_PPT。Read-only Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 傳回包含形狀線條格式屬性的 LineFormat 物件。注意：對於某些不具有線條屬性的形狀可能返回 null。Read-only [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | 傳回或設定形狀的名稱。不得為 null。如有需要請使用空字串。Read/write String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 傳回在投影片範圍內唯一且在形狀生命週期內保持不變的識別碼，可讓 PowerPoint 或互通程式碼從文件任何位置可靠地參照形狀。Read-only UInt32. 另請參閱 [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 若形狀已群組則傳回父級 GroupShape 物件，否則返回 null。Read-only [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 傳回形狀的佔位符。若形狀沒有佔位符則返回 null。Read-only [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 傳回投影片的父級簡報。Read-only [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 傳回或設定原始形狀框架的屬性。Read/write [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 傳回或設定指定形狀繞 Z 軸旋轉的角度（度數）。正值表示順時針旋轉，負值表示逆時針旋轉。Read/write Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | 傳回形狀的鎖定設定。Read-only [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 個屬性) |
| [Slide](../../aspose.slides/shape/slide) { get; } | 傳回形狀所在投影片的父級投影片。Read-only [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 傳回包含形狀 3D 效果屬性的 ThreeDFormat 物件。注意：對於某些不具有 3D 屬性的形狀可能返回 null。Read-only [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 傳回內部、簡報範圍內的識別碼，供外掛程式或其他程式碼使用。由於此值可能被使用者或程式重新指派，不能視為永久唯一的鍵。Read-only UInt32. 另請參閱 [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | 取得或設定形狀的寬度，以點為單位。Read/write Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | 取得或設定形狀左上角的 X 座標，以點為單位。Read/write Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | 取得或設定形狀左上角的 Y 座標，以點為單位。Read/write Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 傳回形狀在 Z 順序中的位置。Shapes[0] 代表 Z 順序最背面的形狀，Shapes[Shapes.Count - 1] 代表最前面的形狀。Read-only Int32. |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 若不存在則新增佔位符，並將佔位符屬性設定為指定的佔位符。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 傳回基本佔位符形狀（從版面配置或母投影片繼承而來的形狀）。若當前形狀未繼承則返回 null。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 傳回形狀縮圖。預設使用 ShapeThumbnailBounds.Shape 形狀縮圖邊界類型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 傳回形狀縮圖。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 取得根據形狀已呈現內容計算出的視覺邊界。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定義此形狀不是佔位符。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 將 Shape 內容儲存為 SVG 檔案。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 將 Shape 內容儲存為 SVG 檔案。 |

### 另請參閱

* 類別 [GraphicalObject](../../aspose.slides/graphicalobject)
* 介面 [IInkActions](../iinkactions)
* 命名空間 [Aspose.Slides.Ink](../../aspose.slides.ink)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->