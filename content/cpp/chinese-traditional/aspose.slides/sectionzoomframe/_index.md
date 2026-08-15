---
title: SectionZoomFrame
second_title: Aspose.Slides for C++ API 參考
description: 表示投影片中的 Section Zoom 物件。
type: docs
weight: 5045
url: /zh-hant/aspose.slides/sectionzoomframe/
---
## SectionZoomFrame 類別

表示投影片中的 [Section](../section/) Zoom 物件。

```cpp
class SectionZoomFrame : public Aspose::Slides::ZoomObject,
                         public virtual Aspose::Slides::ISectionZoomFrame
```

## 方法

| 方法 | 說明 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | 如果不存在則新增佔位元件，並將佔位元件屬性設定為指定的那一個。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，儘管根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，儘管根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | 傳回與圖形相關聯的替代文字。閱讀 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | 傳回與圖形相關聯的替代文字標題。閱讀 [System::String](../../system/string/)。 |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | 屬性指定圖形在黑白顯示模式下的呈現方式。閱讀 [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | 傳回圖形的連接點數量。唯讀 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | 傳回圖形的自訂資料。唯讀 [ICustomData](../icustomdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | 傳回包含套用於圖形之像素效果的 [EffectFormat](../effectformat/) 物件。註：對於某些沒有效果屬性的圖形類型，可能會傳回 null。唯讀 [IEffectFormat](../ieffectformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | 傳回包含圖形填充格式屬性的 [FillFormat](../fillformat/) 物件。註：對於某些沒有填充屬性的圖形類型，可能會傳回 null。唯讀 [IFillFormat](../ifillformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | 傳回圖形框架的屬性。閱讀 [IShapeFrame](../ishapeframe/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | 傳回圖形的鎖定設定。唯讀 [IGraphicalObjectLock](../igraphicalobjectlock/)。 |
| **float** [get_Height](../shape/get_height/)() override | 取得圖形的高度，以點為單位。唯讀 **float**。 |
| **bool** [get_Hidden](../shape/get_hidden/)() override | 判斷圖形是否隱藏。唯讀 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | 傳回滑鼠點擊時定義的超連結。閱讀 [IHyperlink](../ihyperlink/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | 傳回超連結管理器。唯讀 [IHyperlinkManager](../ihyperlinkmanager/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | 傳回滑鼠懸停時定義的超連結。閱讀 [IHyperlink](../ihyperlink/)。 |
| [ZoomImageType](../zoomimagetype/) [get_ImageType](../zoomobject/get_imagetype/)() override | 取得 Zoom 物件的影像類型。閱讀 [ZoomImageType](../zoomimagetype/)。預設值：Preview |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | 取得「標記為裝飾」選項。讀/寫 **bool**。 |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | 判斷圖形是否已分組。唯讀 **bool**。 |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | 判斷圖形是否為 TextHolder_PPT。唯讀 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | 傳回包含圖形線條格式屬性的 [LineFormat](../lineformat/) 物件。註：對於某些沒有線條屬性的圖形類型，可能會傳回 null。唯讀 [ILineFormat](../ilineformat/)。 |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | 傳回圖形的名稱。不得為 null。如有需要請使用空字串。閱讀 [System::String](../../system/string/)。 |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | 傳回在投影片範圍內唯一的識別碼，於圖形生命週期內保持不變，讓 PowerPoint 或互操作程式碼能在文件的任意位置可靠地參照該圖形。唯讀 **uint32_t**。另請參閱 [Shape::get_UniqueId](../shape/get_uniqueid/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | 如果圖形已分組，傳回父層 [GroupShape](../groupshape/) 物件。否則傳回 null。唯讀 [IGroupShape](../igroupshape/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | 傳回圖形的佔位元件。若圖形沒有佔位元件則傳回 null。唯讀 [IPlaceholder](../iplaceholder/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | 傳回投影片的父層簡報。唯讀 [IPresentation](../ipresentation/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | 傳回未處理的圖形框架屬性。閱讀 [IShapeFrame](../ishapeframe/)。 |
| **bool** [get_ReturnToParent](../zoomobject/get_returntoparent/)() override | 取得投影片放映時的導覽行為。唯讀 **bool**。預設值：false |
| **float** [get_Rotation](../shape/get_rotation/)() override | 傳回指定圖形繞 Z 軸旋轉的角度（度）。正值表示順時針旋轉，負值表示逆時針旋轉。唯讀 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | 傳回圖形的鎖定設定。唯讀 [IBaseShapeLock](../ibaseshapelock/)。 |
| **bool** [get_ShowBackground](../zoomobject/get_showbackground/)() override | 取得指定 Zoom 是否使用目的投影片的背景之值。唯讀 **bool**。預設值：true |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | 傳回圖形的父層投影片。唯讀 [IBaseSlide](../ibaseslide/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\> [get_TargetSection](./get_targetsection/)() override | 取得 [Section](../section/) Zoom 物件所連結的節(section)物件。閱讀 [ISection](../isection/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | 傳回圖形的 3D 效果屬性 [ThreeDFormat](../threedformat/) 物件。註：對於某些沒有 3D 屬性的圖形類型，可能會傳回 null。唯讀 [IThreeDFormat](../ithreedformat/)。 |
| **float** [get_TransitionDuration](../zoomobject/get_transitionduration/)() override | 取得 Zoom 與投影片之間過渡的持續時間。唯讀 **float**。預設值：1.0f |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | 傳回內部的、簡報範圍內的識別碼，供外掛程式或其他程式碼使用。因為此值可能被使用者或程式重新指派，不能視為永續的唯一鍵。唯讀 **uint32_t**。另請參閱 [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)。 |
| **float** [get_Width](../shape/get_width/)() override | 取得圖形的寬度，以點為單位。唯讀 **float**。 |
| **float** [get_X](../shape/get_x/)() override | 取得圖形左上角的 x 座標，以點為單位。唯讀 **float**。 |
| **float** [get_Y](../shape/get_y/)() override | 取得圖形左上角的 y 座標，以點為單位。唯讀 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](../zoomobject/get_zoomimage/)() override | 取得 Zoom 物件的影像。閱讀 [IPPImage](../ippimage/)。 |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | 傳回圖形在 Z 次序中的位置。Shapes[0] 代表 Z 次序最靠後的圖形，Shapes[Shapes.Count - 1] 代表最前面的圖形。唯讀 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | 傳回基本的佔位圖形（從版面配置和/或母片中繼承而來的圖形）。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | 傳回圖形的縮圖。預設使用 [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) 圖形縮圖邊界類型。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | 傳回圖形的縮圖。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | 取得根據圖形渲染內容計算出的視覺邊界。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定功能。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守護物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的克隆。 |
| [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式將值型別物件與 nullptr 比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數降低指定的數值。 |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | 定義此圖形不是佔位元件。 |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | 設定與圖形相關聯的替代文字。寫入 [System::String](../../system/string/)。 |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | 設定與圖形相關聯的替代文字標題。寫入 [System::String](../../system/string/)。 |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | 屬性指定圖形在黑白顯示模式下的呈現方式。寫入 [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | 設定圖形框架的屬性。寫入 [IShapeFrame](../ishapeframe/)。 |
| void [set_Height](../shape/set_height/)(**float**) override | 設定圖形的高度，以點為單位。寫入 **float**。 |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | 設定圖形是否隱藏。寫入 **bool**。 |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | 設定滑鼠點擊時的超連結。寫入 [IHyperlink](../ihyperlink/)。 |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | 設定滑鼠懸停時的超連結。寫入 [IHyperlink](../ihyperlink/)。 |
| void [set_ImageType](../zoomobject/set_imagetype/)([ZoomImageType](../zoomimagetype/)) override | 設定 Zoom 物件的影像類型。寫入 [ZoomImageType](../zoomimagetype/)。預設值：Preview |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | 設定「標記為裝飾」選項。讀/寫 **bool**。 |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | 設定圖形的名稱。不得為 null。如有需要請使用空字串。寫入 [System::String](../../system/string/)。 |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | 設定未處理的圖形框架屬性。寫入 [IShapeFrame](../ishapeframe/)。 |
| void [set_ReturnToParent](../zoomobject/set_returntoparent/)(**bool**) override | 設定投影片放映時的導覽行為。寫入 **bool**。預設值：false |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | 設定指定圖形繞 Z 軸旋轉的角度（度）。正值表示順時針旋轉，負值表示逆時針旋轉。寫入 **float**。 |
| void [set_ShowBackground](../zoomobject/set_showbackground/)(**bool**) override | 設定指定 Zoom 是否使用目的投影片的背景之值。寫入 **bool**。預設值：true |
| void [set_TargetSection](./set_targetsection/)([System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\>) override | 設定 [Section](../section/) Zoom 物件所連結的節(section)物件。寫入 [ISection](../isection/)。 |
| void [set_TransitionDuration](../zoomobject/set_transitionduration/)(**float**) override | 設定 Zoom 與投影片之間過渡的持續時間。寫入 **float**。預設值：1.0f |
| void [set_Width](../shape/set_width/)(**float**) override | 設定圖形的寬度，以點為單位。寫入 **float**。 |
| void [set_X](../shape/set_x/)(**float**) override | 設定圖形左上角的 x 座標，以點為單位。寫入 **float**。 |
| void [set_Y](../shape/set_y/)(**float**) override | 設定圖形左上角的 y 座標，以點為單位。寫入 **float**。 |
| void [set_ZoomImage](../zoomobject/set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) override | 設定 Zoom 物件的影像。寫入 [IPPImage](../ippimage/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中切換指標為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫，請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並傳回共享參考計數。不應直接呼叫，請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 结构。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖功能。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守護物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫，請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫，請改用智慧指標或 ThisProtector。 |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | 將 [Shape](../shape/) 的內容儲存為 SVG 檔案。 |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | 將 [Shape](../shape/) 的內容儲存為 SVG 檔案。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另請參閱

* 類別 [ZoomObject](../zoomobject/)
* 類別 [ISectionZoomFrame](../isectionzoomframe/)
* 命名空間 [Aspose::Slides](../)
* 程式庫 [Aspose.Slides](../../)