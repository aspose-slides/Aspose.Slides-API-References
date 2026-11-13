---
title: OleObjectFrame
second_title: Aspose.Sildes for .NET API 參考
description: 表示投影片上的 OLE 物件。
type: docs
weight: 9250
url: /zh-hant/aspose.slides/oleobjectframe/
---
## OleObjectFrame 類別

表示投影片上的 OLE 物件。

```csharp
public class OleObjectFrame : GraphicalObject, IOleObjectFrame
```

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 傳回或設定與形狀相關聯的替代文字。可讀寫 String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 傳回或設定與形狀相關聯的替代文字標題。可讀寫 String。 |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | 允許取得基礎 IGraphicalObject 介面。唯讀 [`IGraphicalObject`](../igraphicalobject)。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 屬性指定形狀在黑白顯示模式下的呈現方式。可讀寫 [`BlackWhiteMode`](../blackwhitemode)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 傳回形狀的連接點數量。唯讀 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 傳回形狀的自訂資料。唯讀 [`ICustomData`](../icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 傳回包含套用於形狀的像素效果的 EffectFormat 物件。註：對於某些沒有效果屬性的形狀，可能會傳回 null。唯讀 [`IEffectFormat`](../ieffectformat)。 |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | 取得或設定 OLE 嵌入資料的資訊。可讀寫 [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo)。 |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | 傳回已嵌入 OLE 物件的檔案名稱 |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | 傳回已嵌入 OLE 物件的路徑 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 傳回包含形狀填充格式屬性的 FillFormat 物件。註：對於某些沒有填充屬性的形狀，可能會傳回 null。唯讀 [`IFillFormat`](../ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 傳回或設定形狀框架的屬性。可讀寫 [`IShapeFrame`](../ishapeframe)。 |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | 傳回形狀的鎖定。唯讀 [`IGraphicalObjectLock`](../igraphicalobjectlock)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 取得或設定形狀的高度（以點為單位）。可讀寫 Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 判斷形狀是否隱藏。可讀寫 Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 傳回或設定滑鼠點擊時的超連結。可讀寫 [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 傳回超連結管理員。唯讀 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 傳回或設定滑鼠移過時的超連結。可讀寫 [`IHyperlink`](../ihyperlink)。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 取得或設定「標示為裝飾」選項。可讀寫 Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 判斷形狀是否已群組。唯讀 Boolean。 |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | 判斷物件是否以圖示形式顯示。可讀寫 Boolean。 |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | 判斷物件是否已連結至外部檔案。唯讀 Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 判斷形狀是否為 TextHolder_PPT。唯讀 Boolean。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 傳回包含形狀線條格式屬性的 LineFormat 物件。註：對於某些沒有線條屬性的形狀，可能會傳回 null。唯讀 [`ILineFormat`](../ilineformat)。 |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | 傳回連結檔案的完整路徑。將使用短檔名。唯讀 String。 |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | 傳回連結檔案的完整路徑。將使用長檔名。可讀寫 String。 |
| [LinkPathRelative](../../aspose.slides/oleobjectframe/linkpathrelative) { get; } | 如果存在則傳回連結檔案的相對路徑，否則傳回空字串。唯讀 String。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 傳回或設定形狀的名稱。不能為 null。如有需要請使用空字串。可讀寫 String。 |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | 傳回或設定物件的名稱。可讀寫 String。 |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | 傳回物件的 ProgID。唯讀 String。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 傳回在投影片範圍內唯一且在形狀生命週期內保持不變的識別碼，讓 PowerPoint 或 interop 程式碼能在文件任何位置可靠地參照此形狀。唯讀 UInt32。另請參閱 [`UniqueId`](../shape/uniqueid)。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 如果形狀已群組，傳回父 GroupShape 物件；否則傳回 null。唯讀 [`IGroupShape`](../igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 傳回形狀的佔位符。若形狀沒有佔位符則傳回 null。唯讀 [`IPlaceholder`](../iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 傳回投影片的父簡報。唯讀 [`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 傳回或設定原始形狀框架的屬性。可讀寫 [`IShapeFrame`](../ishapeframe)。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 傳回或設定指定形狀繞 Z 軸旋轉的角度（以度為單位）。正值表示順時針旋轉，負值表示逆時針旋轉。可讀寫 Single。 |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | 傳回形狀的鎖定。（2 個屬性）唯讀 [`IGraphicalObjectLock`](../igraphicalobjectlock)。 |
| [Slide](../../aspose.slides/shape/slide) { get; } | 傳回形狀的父投影片。唯讀 [`IBaseSlide`](../ibaseslide)。 |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | 傳回 OleObject 圖像填充屬性物件。唯讀 [`IPictureFillFormat`](../ipicturefillformat)。 |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | 傳回或設定 OleObject 圖示的標題。可讀寫 String。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 傳回形狀的 ThreeDFormat 物件，其中包含 3D 效果屬性。註：對於某些沒有 3D 屬性的形狀，可能會傳回 null。唯讀 [`IThreeDFormat`](../ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 傳回內部、簡報範圍的識別碼，供外掛或其他程式碼使用。因為此值可能被使用者或程式重新指派，不能視為永久唯一鍵。唯讀 UInt32。另請參閱 [`OfficeInteropShapeId`](../shape/officeinteropshapeid)。 |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | 判斷在開啟或列印簡報時是否自動更新已連結的嵌入物件。可讀寫 Boolean。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 取得或設定形狀的寬度（以點為單位）。可讀寫 Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 取得或設定形狀左上角的 X 座標（以點為單位）。可讀寫 Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 取得或設定形狀左上角的 Y 座標（以點為單位）。可讀寫 Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 傳回形狀在 Z 序中的位置。Shapes[0] 代表最底層，Shapes[Shapes.Count - 1] 代表最前層。唯讀 Int32。 |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 如果沒有則新增佔位符，並將佔位符屬性設定為指定的佔位符。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 傳回基本佔位符形狀（從版面配置或母片投影片繼承的形狀）。如果目前形狀未繼承則傳回 null。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 傳回形狀縮圖。預設使用 ShapeThumbnailBounds.Shape 形狀縮圖邊界類型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 傳回形狀縮圖。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 取得根據已呈現內容計算出的形狀視覺邊界。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 將此形狀定義為非佔位符。 |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | 設定 OLE 嵌入資料的資訊。此方法會變更物件的屬性以符合新資料，並將 IsObjectLink 旗標設為 false，表示 OLE 物件已嵌入。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 將形狀內容儲存為 SVG 檔案。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 將形狀內容儲存為 SVG 檔案。 |

### 範例

以下範例說明如何存取 OLE 物件框架。

```csharp
[C#]
// 載入 PPTX 為簡報物件
using (Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx"))
{
    // 存取第一張投影片
    ISlide sld = pres.Slides[0];
    // 將形狀轉型為 OleObjectFrame
    OleObjectFrame oleObjectFrame = sld.Shapes[0] as OleObjectFrame;
    // 讀取 OLE 物件並寫入磁碟
    if (oleObjectFrame != null)
    {
        // 取得嵌入檔案資料
        byte[] data = oleObjectFrame.EmbeddedData.EmbeddedFileData;
        // 取得嵌入檔案副檔名
        string fileExtention = oleObjectFrame.EmbeddedData.EmbeddedFileExtension;
        // 建立儲存擷取檔案的路徑
        string extractedPath = "excelFromOLE_out" + fileExtention;
        // 儲存擷取的資料
        using (FileStream fstr = new FileStream(extractedPath, FileMode.Create, FileAccess.Write))
        {
            fstr.Write(data, 0, data.Length);
        }
    }
}
```

### 另請參閱

* 類別 [GraphicalObject](../graphicalobject)
* 介面 [IOleObjectFrame](../ioleobjectframe)
* 命名空間 [Aspose.Slides](../../aspose.slides)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->