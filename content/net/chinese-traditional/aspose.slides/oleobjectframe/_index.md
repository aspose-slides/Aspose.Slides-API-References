---
title: OleObjectFrame
second_title: Aspose.Sildes for .NET API 參考
description: 表示投影片上的 OLE 物件。
type: docs
weight: 9230
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
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 取得或設定與圖形關聯的替代文字。可讀寫 String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 取得或設定與圖形關聯的替代文字標題。可讀寫 String。 |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | 允許取得基礎 IGraphicalObject 介面。唯讀 [`IGraphicalObject`](../igraphicalobject)。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 屬性指定圖形在黑白顯示模式下的呈現方式。可讀寫 [`BlackWhiteMode`](../blackwhitemode)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 取得圖形的連接點數量。唯讀 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 取得圖形的自訂資料。唯讀 [`ICustomData`](../icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 取得包含套用於圖形之像素效果的 EffectFormat 物件。註：對於某些沒有效果屬性的圖形類型，可能會傳回 null。唯讀 [`IEffectFormat`](../ieffectformat)。 |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | 取得或設定有關 OLE 嵌入資料的資訊。可讀寫 [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo)。 |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | 取得嵌入 OLE 物件的檔案名稱 |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | 取得嵌入 OLE 物件的路徑 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 取得包含圖形填色格式屬性的 FillFormat 物件。註：對於某些沒有填色屬性的圖形類型，可能會傳回 null。唯讀 [`IFillFormat`](../ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 取得或設定圖形框架的屬性。可讀寫 [`IShapeFrame`](../ishapeframe)。 |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | 取得圖形的鎖定設定。唯讀 [`IGraphicalObjectLock`](../igraphicalobjectlock)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 取得或設定圖形的高度，單位為點。可讀寫 Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 判斷圖形是否隱藏。可讀寫 Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 取得或設定滑鼠點擊時的超連結。可讀寫 [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 取得超連結管理器。唯讀 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 取得或設定滑鼠移過時的超連結。可讀寫 [`IHyperlink`](../ihyperlink)。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 取得或設定「標記為裝飾」選項。可讀寫 Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 判斷圖形是否已群組。唯讀 Boolean。 |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | 判斷物件是否以圖示顯示。可讀寫 Boolean。 |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | 判斷物件是否連結到外部檔案。唯讀 Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 判斷圖形是否為 TextHolder_PPT。唯讀 Boolean。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 取得包含圖形線條格式屬性的 LineFormat 物件。註：對於某些沒有線條屬性的圖形類型，可能會傳回 null。唯讀 [`ILineFormat`](../ilineformat)。 |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | 取得連結檔案的完整路徑，將使用短檔名。唯讀 String。 |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | 取得連結檔案的完整路徑，將使用長檔名。可讀寫 String。 |
| [LinkPathRelative](../../aspose.slides/oleobjectframe/linkpathrelative) { get; } | 取得連結檔案的相對路徑（若存在），否則回傳空字串。唯讀 String。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 取得或設定圖形的名稱。不得為 null。如有需要，可使用空字串。可讀寫 String。 |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | 取得或設定物件的名稱。可讀寫 String。 |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | 取得物件的 ProgID。唯讀 String。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 取得在投影片範圍內唯一的識別碼，於圖形生命週期內保持不變，讓 PowerPoint 或 interop 程式碼可在文件任意位置可靠地參照該圖形。唯讀 UInt32。另請參閱 [`UniqueId`](../shape/uniqueid)。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 若圖形已群組，則取得父層 GroupShape 物件；否則回傳 null。唯讀 [`IGroupShape`](../igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 取得圖形的佔位元。若圖形沒有佔位元，則回傳 null。唯讀 [`IPlaceholder`](../iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 取得投影片的父層簡報。唯讀 [`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 取得或設定原始圖形框架的屬性。可讀寫 [`IShapeFrame`](../ishapeframe)。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 取得或設定指定圖形繞 Z 軸旋轉的角度（度數）。正值表示順時針旋轉；負值表示逆時針旋轉。可讀寫 Single。 |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | 取得圖形的鎖定設定。唯讀 [`IGraphicalObjectLock`](../igraphicalobjectlock)。（2 個屬性） |
| [Slide](../../aspose.slides/shape/slide) { get; } | 取得圖形的父層投影片。唯讀 [`IBaseSlide`](../ibaseslide)。 |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | 取得 OleObject 圖像填充屬性物件。唯讀 [`IPictureFillFormat`](../ipicturefillformat)。 |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | 取得或設定 OleObject 圖示的標題。可讀寫 String。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 取得圖形的 ThreeDFormat 物件，包含 3D 效果屬性。註：對於某些沒有 3D 屬性的圖形類型，可能會傳回 null。唯讀 [`IThreeDFormat`](../ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 取得內部、簡報範圍的識別碼，供外掛程式或其他程式碼使用。由於此值可能被使用者或程式重新指派，不能視為永久唯一鍵。唯讀 UInt32。另請參閱 [`OfficeInteropShapeId`](../shape/officeinteropshapeid)。 |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | 判斷在開啟或列印簡報時，連結的嵌入物件是否自動更新。可讀寫 Boolean。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 取得或設定圖形的寬度，單位為點。可讀寫 Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 取得或設定圖形左上角的 X 座標，單位為點。可讀寫 Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 取得或設定圖形左上角的 Y 座標，單位為點。可讀寫 Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 取得圖形在 Z 軸順序中的位置。Shapes[0] 代表 Z 軸順序最靠後的圖形，Shapes[Shapes.Count - 1] 代表最前面的圖形。唯讀 Int32。 |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 新增一個佔位元（如果不存在），並將佔位元屬性設定為指定的佔位元。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 取得基本佔位元形狀（從版面配置和/或母片取得，為目前圖形所繼承的形狀）。如果目前圖形未繼承，則回傳 null。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 取得圖形縮圖。預設使用 ShapeThumbnailBounds.Shape 作為縮圖邊界類型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 取得圖形縮圖。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 取得依據圖形已渲染內容計算出的可視邊界。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定義此圖形不是佔位元。 |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | 設定 OLE 嵌入資料的資訊。此方法會變更物件屬性以符合新資料，並將 IsObjectLink 標誌設為 false，表示 OLE 物件為嵌入狀態。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 將圖形內容儲存為 SVG 檔案。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 將圖形內容儲存為 SVG 檔案。 |

### 範例

以下範例說明如何存取 OLE 物件框架。

```csharp
[C#]
// 載入 PPTX 至簡報物件
using (Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx"))
{
    // 取得第一張投影片
    ISlide sld = pres.Slides[0];
    // 將圖形轉型為 OleObjectFrame
    OleObjectFrame oleObjectFrame = sld.Shapes[0] as OleObjectFrame;
    // 讀取 OLE 物件並寫入磁碟
    if (oleObjectFrame != null)
    {
        // 取得嵌入檔案資料
        byte[] data = oleObjectFrame.EmbeddedData.EmbeddedFileData;
        // 取得嵌入檔案副檔名
        string fileExtention = oleObjectFrame.EmbeddedData.EmbeddedFileExtension;
        // 建立儲存抽取檔案的路徑
        string extractedPath = "excelFromOLE_out" + fileExtention;
        // 儲存抽取的資料
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
* 程式集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->