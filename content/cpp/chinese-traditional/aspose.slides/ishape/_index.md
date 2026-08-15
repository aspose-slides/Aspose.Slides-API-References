---
title: IShape
second_title: Aspose.Slides C++ API 參考
description: 表示投影片上的形狀。
type: docs
weight: 3641
url: /zh-hant/aspose.slides/ishape/
---
## IShape 類別


表示投影片上的形狀。

```cpp
class IShape : public virtual Aspose::Slides::ISlideComponent,
               public Aspose::Slides::IHyperlinkContainer
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](./addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | 如果不存在則新增佔位符，並將佔位符屬性設置為指定的佔位符。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 方式比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 方式比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual [System::String](../../system/string/) [get_AlternativeText](./get_alternativetext/)() | 傳回與形狀相關聯的替代文字。閱讀 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](./get_alternativetexttitle/)() | 傳回與形狀相關聯的替代文字標題。閱讀 [System::String](../../system/string/)。 |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](./get_blackwhitemode/)() | 屬性指定形狀在黑白顯示模式下的呈現方式。閱讀 [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| virtual **int32_t** [get_ConnectionSiteCount](./get_connectionsitecount/)() | 傳回形狀的連接點數量。唯讀 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](./get_customdata/)() | 傳回形狀的自訂資料。唯讀 [ICustomData](../icustomdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() | 傳回包含套用於形狀的像素效果的 [EffectFormat](../effectformat/) 物件。唯讀 [IEffectFormat](../ieffectformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() | 傳回包含形狀填充格式屬性的 [FillFormat](../fillformat/) 物件。唯讀 [IFillFormat](../ifillformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](./get_frame/)() | 傳回形狀框架的屬性。閱讀 [IShapeFrame](../ishapeframe/)。 |
| virtual **float** [get_Height](./get_height/)() | 取得形狀的高度（以點為單位）。唯讀 **float**。 |
| virtual **bool** [get_Hidden](./get_hidden/)() | 判斷形狀是否隱藏。唯讀 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | 傳回在滑鼠點擊時定義的超連結。閱讀 [IHyperlink](../ihyperlink/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | 超連結管理器 唯讀 [IHyperlinkManager](../ihyperlinkmanager/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | 傳回在滑鼠懸停時定義的超連結。閱讀 [IHyperlink](../ihyperlink/)。 |
| virtual **bool** [get_IsDecorative](./get_isdecorative/)() | 取得「標記為裝飾性」選項 讀寫 **bool**。 |
| virtual **bool** [get_IsGrouped](./get_isgrouped/)() | 判斷形狀是否已群組。唯讀 **bool**。 |
| virtual **bool** [get_IsTextHolder](./get_istextholder/)() | 判斷形狀是否為 TextHolder。唯讀 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() | 傳回包含形狀線條格式屬性的 [LineFormat](../lineformat/) 物件。唯讀 [ILineFormat](../ilineformat/)。 |
| virtual [System::String](../../system/string/) [get_Name](./get_name/)() | 傳回形狀的名稱。閱讀 [System::String](../../system/string/)。 |
| virtual **uint32_t** [get_OfficeInteropShapeId](./get_officeinteropshapeid/)() | 傳回在投影片範圍內唯一的識別碼，於形狀生命週期內保持不變，讓 PowerPoint 或互通程式碼能可靠地從文件任何位置引用該形狀。唯讀 **uint32_t**。另請參閱 [IShape::get_UniqueId](./get_uniqueid/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](./get_parentgroup/)() | 如果形狀已群組，傳回父層 [GroupShape](../groupshape/) 物件。否則傳回 null。唯讀 [IGroupShape](../igroupshape/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](./get_placeholder/)() | 傳回形狀的佔位符。唯讀 [IPlaceholder](../iplaceholder/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | 傳回簡報。唯讀 [IPresentation](../ipresentation/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](./get_rawframe/)() | 傳回原始形狀框架的屬性。閱讀 [IShapeFrame](../ishapeframe/)。 |
| virtual **float** [get_Rotation](./get_rotation/)() | 傳回指定形狀繞 z 軸旋轉的角度（度）。正值表示順時針旋轉；負值表示逆時針旋轉。唯讀 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](./get_shapelock/)() | 傳回形狀的鎖定設定。唯讀 [IBaseShapeLock](../ibaseshapelock/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | 傳回基礎投影片。唯讀 [IBaseSlide](../ibaseslide/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() | 傳回包含形狀線條格式屬性的 [ThreeDFormat](../threedformat/) 物件。唯讀 [IThreeDFormat](../ithreedformat/)。 |
| virtual **uint32_t** [get_UniqueId](./get_uniqueid/)() | 傳回內部、簡報範圍的識別碼，供外掛或其他程式碼使用。由於此值可能被使用者或程式重新指派，不能視為持續唯一的鍵。唯讀 **uint32_t**。另請參閱 [IShape::get_OfficeInteropShapeId](./get_officeinteropshapeid/)。 |
| virtual **float** [get_Width](./get_width/)() | 取得形狀的寬度（以點為單位）。唯讀 **float**。 |
| virtual **float** [get_X](./get_x/)() | 取得形狀左上角的 X 座標（以點為單位）。唯讀 **float**。 |
| virtual **float** [get_Y](./get_y/)() | 取得形狀左上角的 Y 座標（以點為單位）。唯讀 **float**。 |
| virtual **int32_t** [get_ZOrderPosition](./get_zorderposition/)() | 傳回形狀在 Z 序中的位置。Shapes[0] 傳回 Z 序最背後的形狀，Shapes[Shapes.Count - 1] 傳回最前面的形狀。唯讀 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](./)\> [GetBasePlaceholder](./getbaseplaceholder/)() | 傳回基本佔位符形狀（來自版面配置和/或母版投影片，供目前形狀繼承的形狀）。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)() | 傳回形狀縮圖。[ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) 形狀縮圖邊界類型預設使用。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | 傳回形狀縮圖。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷貝建構子。實際上不會拷貝任何內容，只是初始化新物件並允許子類別的拷貝建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不會拷貝任何內容，只是初始化新物件並允許子類別的拷貝建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特殊化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特殊化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的數值。 |
| virtual void [RemovePlaceholder](./removeplaceholder/)() | 定義此形狀不是佔位符。 |
| virtual void [set_AlternativeText](./set_alternativetext/)([System::String](../../system/string/)) | 設定與形狀相關聯的替代文字。寫入 [System::String](../../system/string/)。 |
| virtual void [set_AlternativeTextTitle](./set_alternativetexttitle/)([System::String](../../system/string/)) | 設定與形狀相關聯的替代文字標題。寫入 [System::String](../../system/string/)。 |
| virtual void [set_BlackWhiteMode](./set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | 屬性指定形狀在黑白顯示模式下的呈現方式。寫入 [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| virtual void [set_Frame](./set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | 設定形狀框架的屬性。寫入 [IShapeFrame](../ishapeframe/)。 |
| virtual void [set_Height](./set_height/)(**float**) | 設定形狀的高度（以點為單位）。寫入 **float**。 |
| virtual void [set_Hidden](./set_hidden/)(**bool**) | 設定形狀是否隱藏。寫入 **bool**。 |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | 設定滑鼠點擊時的超連結。寫入 [IHyperlink](../ihyperlink/)。 |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | 設定滑鼠懸停時的超連結。寫入 [IHyperlink](../ihyperlink/)。 |
| virtual void [set_IsDecorative](./set_isdecorative/)(**bool**) | 設定「標記為裝飾性」選項。讀寫 **bool**。 |
| virtual void [set_Name](./set_name/)([System::String](../../system/string/)) | 設定形狀的名稱。寫入 [System::String](../../system/string/)。 |
| virtual void [set_RawFrame](./set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | 設定原始形狀框架的屬性。寫入 [IShapeFrame](../ishapeframe/)。 |
| virtual void [set_Rotation](./set_rotation/)(**float**) | 設定指定形狀繞 z 軸旋轉的角度（度）。正值表示順時針，負值表示逆時針。寫入 **float**。 |
| virtual void [set_Width](./set_width/)(**float**) | 設定形狀的寬度（以點為單位）。寫入 **float**。 |
| virtual void [set_X](./set_x/)(**float**) | 設定形狀左上角的 X 座標（以點為單位）。寫入 **float**。 |
| virtual void [set_Y](./set_y/)(**float**) | 設定形狀左上角的 Y 座標（以點為單位）。寫入 **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享指標）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual void [WriteAsSvg](./writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | 將 [Shape](../shape/) 的內容儲存為 SVG 檔案。 |
| virtual void [WriteAsSvg](./writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | 將 [Shape](../shape/) 的內容儲存為 SVG 檔案。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另請參閱

* 類別 [ISlideComponent](../islidecomponent/)
* 類別 [IHyperlinkContainer](../ihyperlinkcontainer/)
* 命名空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)