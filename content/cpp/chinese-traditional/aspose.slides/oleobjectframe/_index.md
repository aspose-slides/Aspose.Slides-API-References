---
title: OleObjectFrame
second_title: Aspose.Slides for C++ API 參考
description: 代表投影片上的 OLE 物件。
type: docs
weight: 4603
url: /zh-hant/aspose.slides/oleobjectframe/
---
## OleObjectFrame 類別

Represents an OLE object on a slide.

```cpp
class OleObjectFrame : public Aspose::Slides::GraphicalObject,
                       public Aspose::Slides::IOleObjectFrame
```

## 方法

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | 如果不存在則新增佔位元，並將佔位元屬性設定為指定的佔位元。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使依 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使依 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | 傳回與圖形關聯的替代文字。請參閱 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | 傳回與圖形關聯的替代文字標題。請參閱 [System::String](../../system/string/)。 |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | 屬性指定圖形在黑白顯示模式下的呈現方式。請參閱 [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | 傳回圖形的連接點數量。唯讀 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | 傳回圖形的自訂資料。唯讀 [ICustomData](../icustomdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | 傳回包含套用於圖形的像素效果的 [EffectFormat](../effectformat/) 物件。註：對於沒有效果屬性的某些圖形類型，可能會傳回 null。唯讀 [IEffectFormat](../ieffectformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\> [get_EmbeddedData](./get_embeddeddata/)() override | 取得 OLE 嵌入資料的資訊。請參閱 [IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)。 |
| [System::String](../../system/string/) [get_EmbeddedFileLabel](./get_embeddedfilelabel/)() override | 傳回嵌入式 OLE 物件的檔案名稱 |
| [System::String](../../system/string/) [get_EmbeddedFileName](./get_embeddedfilename/)() override | 傳回嵌入式 OLE 物件的路徑 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | 傳回包含圖形填色格式屬性的 [FillFormat](../fillformat/) 物件。註：對於沒有填色屬性的某些圖形類型，可能會傳回 null。唯讀 [IFillFormat](../ifillformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | 傳回圖形框架的屬性。請參閱 [IShapeFrame](../ishapeframe/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | 傳回圖形的鎖定設定。唯讀 [IGraphicalObjectLock](../igraphicalobjectlock/)。 |
| **float** [get_Height](../shape/get_height/)() override | 取得圖形的高度（以點為單位）。請參閱 **float**。 |
| **bool** [get_Hidden](../shape/get_hidden/)() override | 判斷圖形是否為隱藏狀態。請參閱 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | 傳回滑鼠點擊時定義的超連結。請參閱 [IHyperlink](../ihyperlink/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | 傳回超連結管理器。唯讀 [IHyperlinkManager](../ihyperlinkmanager/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | 傳回滑鼠移過時定義的超連結。請參閱 [IHyperlink](../ihyperlink/)。 |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | 取得「標記為裝飾」選項的讀寫 **bool**。 |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | 判斷圖形是否為群組。唯讀 **bool**。 |
| **bool** [get_IsObjectIcon](./get_isobjecticon/)() override | 判斷物件是否以圖示方式顯示。請參閱 **bool**。 |
| **bool** [get_IsObjectLink](./get_isobjectlink/)() override | 判斷物件是否連結至外部檔案。唯讀 **bool**。 |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | 判斷圖形是否為 TextHolder_PPT。唯讀 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | 傳回包含圖形線條格式屬性的 [LineFormat](../lineformat/) 物件。註：對於沒有線條屬性的某些圖形類型，可能會傳回 null。唯讀 [ILineFormat](../ilineformat/)。 |
| [System::String](../../system/string/) [get_LinkFileName](./get_linkfilename/)() override | 傳回連結檔案的完整路徑。將使用短檔名。唯讀 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() override | 傳回連結檔案的完整路徑。將使用長檔名。請參閱 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_LinkPathRelative](./get_linkpathrelative/)() override | 若存在則傳回連結檔案的相對路徑，否則傳回空字串。唯讀 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | 傳回圖形的名稱。不得為 null。必要時使用空字串。請參閱 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_ObjectName](./get_objectname/)() override | 傳回物件的名稱。請參閱 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_ObjectProgId](./get_objectprogid/)() override | 傳回物件的 ProgID。唯讀 [System::String](../../system/string/)。 |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | 傳回在投影片範圍內唯一的識別碼，於圖形生命週期內保持不變，讓 PowerPoint 或互通程式碼能從文件任何位置可靠地參照該圖形。唯讀 **uint32_t**。另請參閱 [Shape::get_UniqueId](../shape/get_uniqueid/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | 若圖形為群組，傳回父層 [GroupShape](../groupshape/) 物件；否則傳回 null。唯讀 [IGroupShape](../igroupshape/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | 傳回圖形的佔位元。若圖形沒有佔位元則傳回 null。唯讀 [IPlaceholder](../iplaceholder/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | 傳回投影片的父層簡報。唯讀 [IPresentation](../ipresentation/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | 傳回原始圖形框架的屬性。請參閱 [IShapeFrame](../ishapeframe/)。 |
| **float** [get_Rotation](../shape/get_rotation/)() override | 傳回指定圖形繞 z 軸旋轉的角度（度），正值表示順時針旋轉，負值表示逆時針旋轉。請參閱 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | 傳回圖形的鎖定設定。唯讀 [IBaseShapeLock](../ibaseshapelock/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | 傳回圖形的父層投影片。唯讀 [IBaseSlide](../ibaseslide/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_SubstitutePictureFormat](./get_substitutepictureformat/)() override | 傳回 OleObject 圖像填色屬性物件。唯讀 [IPictureFillFormat](../ipicturefillformat/)。 |
| [System::String](../../system/string/) [get_SubstitutePictureTitle](./get_substitutepicturetitle/)() override | 傳回 OleObject 圖示的標題。請參閱 [System::String](../../system/string/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | 傳回包含圖形 3D 效果屬性的 [ThreeDFormat](../threedformat/) 物件。註：對於沒有 3D 屬性的某些圖形類型，可能會傳回 null。唯讀 [IThreeDFormat](../ithreedformat/)。 |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | 傳回內部的、簡報範圍的識別碼，供外掛或其他程式碼使用。由於此值可能被使用者或程式重新指派，故不應視為永久唯一鍵。唯讀 **uint32_t**。另請參閱 [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)。 |
| **bool** [get_UpdateAutomatic](./get_updateautomatic/)() override | 判斷在開啟或列印簡報時，連結的嵌入式物件是否自動更新。請參閱 **bool**。 |
| **float** [get_Width](../shape/get_width/)() override | 取得圖形的寬度（以點為單位）。請參閱 **float**。 |
| **float** [get_X](../shape/get_x/)() override | 取得圖形左上角的 X 座標（以點為單位）。請參閱 **float**。 |
| **float** [get_Y](../shape/get_y/)() override | 取得圖形左上角的 Y 座標（以點為單位）。請參閱 **float**。 |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | 傳回圖形在 Z 軸順序中的位置。Shapes[0] 為 Z 軸最底層的圖形，Shapes[Shapes.Count - 1] 為最前端的圖形。唯讀 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | 傳回基本佔位元圖形（來自版面配置或母片投影片，供目前圖形繼承的圖形）。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參照計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊功能。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | 傳回圖形縮圖。預設使用 [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) 圖形縮圖範圍類型。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | 傳回圖形縮圖。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | 取得根據圖形渲染內容計算的視覺範圍。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述型別的實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視器物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的克隆。 |
| [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參照方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參照方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 將值型別物件與 nullptr 以參照方式比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 針對字串與 nullptr 情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化版本。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 針對字串情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化版本。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參照計數減少指定的值。 |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | 定義此圖形不是佔位元。 |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | 設定與圖形關聯的替代文字。寫入 [System::String](../../system/string/)。 |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | 設定與圖形關聯的替代文字標題。寫入 [System::String](../../system/string/)。 |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | 屬性指定圖形在黑白顯示模式下的呈現方式。寫入 [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | 設定圖形框架的屬性。寫入 [IShapeFrame](../ishapeframe/)。 |
| void [set_Height](../shape/set_height/)(**float**) override | 設定圖形的高度（以點為單位）。寫入 **float**。 |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | 設定圖形是否為隱藏狀態。寫入 **bool**。 |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | 設定滑鼠點擊時的超連結。寫入 [IHyperlink](../ihyperlink/)。 |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | 設定滑鼠移過時的超連結。寫入 [IHyperlink](../ihyperlink/)。 |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | 設定「標記為裝飾」選項。寫入 **bool**。 |
| void [set_IsObjectIcon](./set_isobjecticon/)(**bool**) override | 設定物件是否以圖示方式顯示。寫入 **bool**。 |
| void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) override | 設定使用長檔名的連結檔案完整路徑。寫入 [System::String](../../system/string/)。 |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | 設定圖形的名稱。不得為 null。必要時使用空字串。寫入 [System::String](../../system/string/)。 |
| void [set_ObjectName](./set_objectname/)([System::String](../../system/string/)) override | 設定物件的名稱。寫入 [System::String](../../system/string/)。 |
| void [set_ObjectProgId](./set_objectprogid/)([System::String](../../system/string/)) override | 傳回物件的 ProgID。唯讀 [System::String](../../system/string/)。 |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | 設定原始圖形框架的屬性。寫入 [IShapeFrame](../ishapeframe/)。 |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | 設定指定圖形繞 z 軸旋轉的角度（度）。正值表示順時針旋轉，負值表示逆時針旋轉。寫入 **float**。 |
| void [set_SubstitutePictureTitle](./set_substitutepicturetitle/)([System::String](../../system/string/)) override | 設定 OleObject 圖示的標題。寫入 [System::String](../../system/string/)。 |
| void [set_UpdateAutomatic](./set_updateautomatic/)(**bool**) override | 設定在開啟或列印簡報時，連結的嵌入式物件是否自動更新。寫入 **bool**。 |
| void [set_Width](../shape/set_width/)(**float**) override | 設定圖形的寬度（以點為單位）。寫入 **float**。 |
| void [set_X](../shape/set_x/)(**float**) override | 設定圖形左上角的 X 座標（以點為單位）。寫入 **float**。 |
| void [set_Y](../shape/set_y/)(**float**) override | 設定圖形左上角的 Y 座標（以點為單位）。寫入 **float**。 |
| void [SetEmbeddedData](./setembeddeddata/)([System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\>) override | 設定 OLE 嵌入資料的資訊。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享指標）。允許在容器中切換指標至弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參照計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 將共享參照計數遞增。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 將共享參照計數遞減並返回。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視器物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 將弱參照計數遞增。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 將弱參照計數遞減。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | 將 [Shape](../shape/) 的內容儲存為 SVG 檔案。 |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | 將 [Shape](../shape/) 的內容儲存為 SVG 檔案。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 備註

以下範例說明如何存取 OLE 物件框架。
```cpp
// 載入 PPTX 至簡報物件
auto pres = System::MakeObject<Presentation>(u"AccessingOLEObjectFrame.pptx");

// 取得第一張投影片
auto slide = pres->get_Slides()->idx_get(0);
// 將形狀轉型為 OleObjectFrame
System::SharedPtr<OleObjectFrame> oleObjectFrame = System::AsCast<OleObjectFrame>(slide->get_Shapes()->idx_get(0));
// 讀取 OLE 物件並寫入磁碟
if (oleObjectFrame != nullptr)
{
    // 取得嵌入檔案資料
    System::ArrayPtr<uint8_t> data = oleObjectFrame->get_EmbeddedData()->get_EmbeddedFileData();
    // 取得嵌入檔案副檔名
    System::String fileExtention = oleObjectFrame->get_EmbeddedData()->get_EmbeddedFileExtension();
    // 建立保存提取檔案的路徑
    System::String extractedPath = System::String(u"excelFromOLE_out") + fileExtention;
    // 保存提取的資料
    auto stream = System::MakeObject<System::IO::FileStream>(extractedPath,
                                                             System::IO::FileMode::Create,
                                                             System::IO::FileAccess::Write);
    stream->Write(data, 0, data->get_Length());
}
```

## 另請參閱

* 類別 [GraphicalObject](../graphicalobject/)
* 類別 [IOleObjectFrame](../ioleobjectframe/)
* 命名空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)