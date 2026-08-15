---
title: ZoomObject
second_title: Aspose.Slides for C++ API 參考
description: 表示投影片中的 Zoom 物件。
type: docs
weight: 5591
url: /zh-hant/aspose.slides/zoomobject/
---
## ZoomObject 類別

Represents an Zoom object in a slide.

```cpp
class ZoomObject : public Aspose::Slides::GraphicalObject,
                   public virtual Aspose::Slides::IZoomObject
```

## 方法

| 方法 | 說明 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | 如果不存在，則新增一個占位符，並將占位符屬性設定為指定的占位符。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語義比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，儘管根據 IEC 60559:1989，NaN 與任何值（包括 NaN）皆不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，儘管根據 IEC 60559:1989，NaN 與任何值（包括 NaN）皆不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | 回傳與形狀相關聯的替代文字。請閱讀 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | 回傳與形狀相關聯的替代文字標題。請閱讀 [System::String](../../system/string/)。 |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | 屬性指定形狀在黑白顯示模式下的呈現方式。請閱讀 [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | 回傳形狀的連接點數量。唯讀 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | 回傳形狀的自訂資料。唯讀 [ICustomData](../icustomdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | 回傳包含套用於形狀之像素效果的 [EffectFormat](../effectformat/) 物件。注意：對於沒有效果屬性的某些形狀類型，可能會返回 null。唯讀 [IEffectFormat](../ieffectformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | 回傳包含形狀填充格式屬性的 [FillFormat](../fillformat/) 物件。注意：對於沒有填充屬性的某些形狀類型，可能會返回 null。唯讀 [IFillFormat](../ifillformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | 回傳形狀框架的屬性。請閱讀 [IShapeFrame](../ishapeframe/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | 回傳形狀的鎖定設定。唯讀 [IGraphicalObjectLock](../igraphicalobjectlock/)。 |
| **float** [get_Height](../shape/get_height/)() override | 取得形狀的高度，以點為單位。讀取 **float**。 |
| **bool** [get_Hidden](../shape/get_hidden/)() override | 判斷形狀是否隱藏。讀取 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | 回傳滑鼠點擊所定義的超連結。請閱讀 [IHyperlink](../ihyperlink/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | 回傳超連結管理器。唯讀 [IHyperlinkManager](../ihyperlinkmanager/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | 回傳滑鼠懸停時所定義的超連結。請閱讀 [IHyperlink](../ihyperlink/)。 |
| [ZoomImageType](../zoomimagetype/) [get_ImageType](./get_imagetype/)() override | 取得 Zoom 物件的影像類型。請閱讀 [ZoomImageType](../zoomimagetype/)。預設值：Preview |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | 取得「標記為裝飾」選項。讀寫 **bool**。 |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | 判斷形狀是否已群組。唯讀 **bool**。 |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | 判斷形狀是否為 TextHolder_PPT。唯讀 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | 回傳包含形狀線條格式屬性的 [LineFormat](../lineformat/) 物件。注意：對於沒有線條屬性的某些形狀類型，可能會返回 null。唯讀 [ILineFormat](../ilineformat/)。 |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | 回傳形狀的名稱。不得為 null。如有需要可使用空字串。請閱讀 [System::String](../../system/string/)。 |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | 回傳在投影片範圍內唯一的識別碼，於形狀生命週期內保持不變，讓 PowerPoint 或互操作程式碼能從文件任何位置可靠地參照該形狀。唯讀 **uint32_t**。另請參閱 [Shape::get_UniqueId](../shape/get_uniqueid/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | 若形狀已群組，回傳其父 [GroupShape](../groupshape/) 物件；否則返回 null。唯讀 [IGroupShape](../igroupshape/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | 回傳形狀的占位符。若形狀沒有占位符，返回 null。唯讀 [IPlaceholder](../iplaceholder/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | 回傳投影片的父簡報。唯讀 [IPresentation](../ipresentation/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | 回傳原始形狀框架的屬性。請閱讀 [IShapeFrame](../ishapeframe/)。 |
| **bool** [get_ReturnToParent](./get_returntoparent/)() override | 取得投影片放映時的導覽行為。讀取 **bool**。預設值：false |
| **float** [get_Rotation](../shape/get_rotation/)() override | 回傳指定形狀繞 Z 軸旋轉的角度（度數）。正值表示順時針旋轉，負值表示逆時針旋轉。讀取 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | 回傳形狀的鎖定設定。唯讀 [IBaseShapeLock](../ibaseshapelock/)。 |
| **bool** [get_ShowBackground](./get_showbackground/)() override | 取得指定 Zoom 是否使用目的投影片的背景之值。讀取 **bool**。預設值：true |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | 回傳形狀的父投影片。唯讀 [IBaseSlide](../ibaseslide/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | 回傳包含形狀 3D 效果屬性的 [ThreeDFormat](../threedformat/) 物件。注意：對於沒有 3D 屬性的某些形狀類型，可能會返回 null。唯讀 [IThreeDFormat](../ithreedformat/)。 |
| **float** [get_TransitionDuration](./get_transitionduration/)() override | 取得 Zoom 與投影片之間過渡的持續時間。讀取 **float**。預設值：1.0f |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | 回傳內部的、簡報範圍的識別碼，供外掛或其他程式碼使用。由於此值可能被使用者或程式重新指派，不能被視為永久唯一鍵。唯讀 **uint32_t**。另請參閱 [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)。 |
| **float** [get_Width](../shape/get_width/)() override | 取得形狀的寬度，以點為單位。讀取 **float**。 |
| **float** [get_X](../shape/get_x/)() override | 取得形狀左上角的 x 座標，以點為單位。讀取 **float**。 |
| **float** [get_Y](../shape/get_y/)() override | 取得形狀左上角的 y 座標，以點為單位。讀取 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](./get_zoomimage/)() override | 取得 Zoom 物件的圖像。請閱讀 [IPPImage](../ippimage/)。 |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | 回傳形狀在 Z 軸順序中的位置。Shapes[0] 代表 Z 軸最背面的形狀，Shapes[Shapes.Count - 1] 代表最前面的形狀。唯讀 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | 回傳基本的占位符形狀（來自版面配置或母片，且當前形狀繼承自該形狀）。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | 回傳形狀縮圖。預設使用 [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) 形狀縮圖邊界類型。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | 回傳形狀縮圖。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | 取得根據形狀渲染內容計算出的視覺邊界。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述的類型實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構式。實際上不會複製任何內容，只是初始化新物件並允許子類別進行複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別進行複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 以指定值減少共用參考計數。 |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | 定義此形狀不是占位符。 |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | 設定與形狀相關聯的替代文字。寫入 [System::String](../../system/string/)。 |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | 設定與形狀相關聯的替代文字標題。寫入 [System::String](../../system/string/)。 |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | 屬性指定形狀在黑白顯示模式下的呈現方式。寫入 [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | 設定形狀框架的屬性。寫入 [IShapeFrame](../ishapeframe/)。 |
| void [set_Height](../shape/set_height/)(**float**) override | 設定形狀的高度，以點為單位。寫入 **float**。 |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | 設定形狀是否隱藏。寫入 **bool**。 |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | 設定滑鼠點擊所定義的超連結。寫入 [IHyperlink](../ihyperlink/)。 |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | 設定滑鼠懸停所定義的超連結。寫入 [IHyperlink](../ihyperlink/)。 |
| void [set_ImageType](./set_imagetype/)([ZoomImageType](../zoomimagetype/)) override | 設定 Zoom 物件的影像類型。寫入 [ZoomImageType](../zoomimagetype/)。預設值：Preview |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | 設定「標記為裝飾」選項。讀寫 **bool**。 |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | 設定形狀的名稱。不得為 null。如有需要可使用空字串。寫入 [System::String](../../system/string/)。 |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | 設定原始形狀框架的屬性。寫入 [IShapeFrame](../ishapeframe/)。 |
| void [set_ReturnToParent](./set_returntoparent/)(**bool**) override | 設定投影片放映時的導覽行為。寫入 **bool**。預設值：false |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | 設定指定形狀繞 Z 軸旋轉的角度（度）。正值表示順時針旋轉，負值表示逆時針旋轉。寫入 **float**。 |
| void [set_ShowBackground](./set_showbackground/)(**bool**) override | 設定指定 Zoom 是否使用目的投影片的背景之值。寫入 **bool**。預設值：true |
| void [set_TransitionDuration](./set_transitionduration/)(**float**) override | 設定 Zoom 與投影片之間過渡的持續時間。寫入 **float**。預設值：1.0f |
| void [set_Width](../shape/set_width/)(**float**) override | 設定形狀的寬度，以點為單位。寫入 **float**。 |
| void [set_X](../shape/set_x/)(**float**) override | 設定形狀左上角的 x 座標，以點為單位。寫入 **float**。 |
| void [set_Y](../shape/set_y/)(**float**) override | 設定形狀左上角的 y 座標，以點為單位。寫入 **float**。 |
| void [set_ZoomImage](./set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) override | 設定 Zoom 物件的圖像。寫入 [IPPImage](../ippimage/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享）。允許在容器中切換指標為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得目前的共用參考計數值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共用參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並返回共用參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解除鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | 將 [Shape](../shape/) 的內容儲存為 SVG 檔案。 |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | 將 [Shape](../shape/) 的內容儲存為 SVG 檔案。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另請參閱

* 類別 [GraphicalObject](../graphicalobject/)
* 類別 [IZoomObject](../izoomobject/)
* 命名空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)