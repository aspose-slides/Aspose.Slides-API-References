---
title: Shape
second_title: Aspose.Slides for C++ API 參考文件
description: 表示投影片上的形狀。
type: docs
weight: 5084
url: /zh-hant/aspose.slides/shape/
---
## Shape 類別


表示投影片上的形狀。

```cpp
class Shape : public virtual Aspose::Slides::IShape,
              public Aspose::Slides::IDOMObject
```

## 方法

| 方法 | 說明 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](./addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | 如果沒有則新增佔位元，並將佔位元屬性設定為指定的佔位元。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 與任何值（包括 NaN）皆不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 與任何值（包括 NaN）皆不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [System::String](../../system/string/) [get_AlternativeText](./get_alternativetext/)() override | 傳回與形狀相關聯的替代文字。請參閱 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_AlternativeTextTitle](./get_alternativetexttitle/)() override | 傳回與形狀相關聯的替代文字標題。請參閱 [System::String](../../system/string/)。 |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](./get_blackwhitemode/)() override | 屬性指定形狀在黑白顯示模式下的呈現方式。請參閱 [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| **int32_t** [get_ConnectionSiteCount](./get_connectionsitecount/)() override | 傳回形狀的連接點數量。唯讀 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](./get_customdata/)() override | 傳回形狀的自訂資料。唯讀 [ICustomData](../icustomdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() override | 傳回包含套用於形狀的像素效果之 [EffectFormat](../effectformat/) 物件。注意：對於沒有效果屬性的某些形狀類型，可能傳回 null。唯讀 [IEffectFormat](../ieffectformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() override | 傳回包含形狀填充格式屬性的 [FillFormat](../fillformat/) 物件。注意：對於沒有填充屬性的某些形狀類型，可能傳回 null。唯讀 [IFillFormat](../ifillformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](./get_frame/)() override | 傳回形狀框架的屬性。請參閱 [IShapeFrame](../ishapeframe/)。 |
| **float** [get_Height](./get_height/)() override | 取得形狀的高度，單位為點 (points)。唯讀 **float**。 |
| **bool** [get_Hidden](./get_hidden/)() override | 判斷形狀是否為隱藏。唯讀 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](./get_hyperlinkclick/)() override | 傳回滑鼠點擊時定義的超連結。請參閱 [IHyperlink](../ihyperlink/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](./get_hyperlinkmanager/)() override | 傳回超連結管理員。唯讀 [IHyperlinkManager](../ihyperlinkmanager/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](./get_hyperlinkmouseover/)() override | 傳回滑鼠懸停時定義的超連結。請參閱 [IHyperlink](../ihyperlink/)。 |
| **bool** [get_IsDecorative](./get_isdecorative/)() override | 取得「標記為裝飾」選項。讀寫 **bool**。 |
| **bool** [get_IsGrouped](./get_isgrouped/)() override | 判斷形狀是否已分組。唯讀 **bool**。 |
| **bool** [get_IsTextHolder](./get_istextholder/)() override | 判斷形狀是否為 TextHolder_PPT。唯讀 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() override | 傳回包含形狀線條格式屬性的 [LineFormat](../lineformat/) 物件。注意：對於沒有線條屬性的某些形狀類型，可能傳回 null。唯讀 [ILineFormat](../ilineformat/)。 |
| [System::String](../../system/string/) [get_Name](./get_name/)() override | 傳回形狀的名稱。不可為 null。如有需要可使用空字串。請參閱 [System::String](../../system/string/)。 |
| **uint32_t** [get_OfficeInteropShapeId](./get_officeinteropshapeid/)() override | 傳回在投影片範圍內唯一的識別碼，於形狀生命週期內保持不變，讓 PowerPoint 或互操作程式能從文件任何位置可靠地參照該形狀。唯讀 **uint32_t**。另請參閱 [Shape::get_UniqueId](./get_uniqueid/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](./get_parentgroup/)() override | 若形狀已分組，傳回父層 [GroupShape](../groupshape/) 物件；否則傳回 null。唯讀 [IGroupShape](../igroupshape/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](./get_placeholder/)() override | 傳回形狀的佔位元。若形狀沒有佔位元，則傳回 null。唯讀 [IPlaceholder](../iplaceholder/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](./get_presentation/)() override | 傳回投影片的父簡報。唯讀 [IPresentation](../ipresentation/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](./get_rawframe/)() override | 傳回原始形狀框架的屬性。請參閱 [IShapeFrame](../ishapeframe/)。 |
| **float** [get_Rotation](./get_rotation/)() override | 傳回指定形狀繞 Z 軸旋轉的角度（度數）。正值表示順時針旋轉，負值表示逆時針旋轉。唯讀 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](./get_shapelock/)() override | 傳回形狀的鎖定狀態。唯讀 [IBaseShapeLock](../ibaseshapelock/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](./get_slide/)() override | 傳回形狀的父投影片。唯讀 [IBaseSlide](../ibaseslide/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() override | 傳回包含形狀 3D 效果屬性的 [ThreeDFormat](../threedformat/) 物件。注意：對於沒有 3D 屬性的某些形狀類型，可能傳回 null。唯讀 [IThreeDFormat](../ithreedformat/)。 |
| **uint32_t** [get_UniqueId](./get_uniqueid/)() override | 傳回供外掛程式或其他程式碼使用的內部、簡報範圍識別碼。由於此值可能被使用者或程式重新指派，不能視為永久唯一鍵。唯讀 **uint32_t**。另請參閱 [Shape::get_OfficeInteropShapeId](./get_officeinteropshapeid/)。 |
| **float** [get_Width](./get_width/)() override | 取得形狀的寬度，單位為點。唯讀 **float**。 |
| **float** [get_X](./get_x/)() override | 取得形狀左上角的 X 座標，單位為點。唯讀 **float**。 |
| **float** [get_Y](./get_y/)() override | 取得形狀左上角的 Y 座標，單位為點。唯讀 **float**。 |
| **int32_t** [get_ZOrderPosition](./get_zorderposition/)() override | 傳回形狀在 Z 序中的位置。Shapes[0] 為 Z 序最底層的形狀，Shapes[Shapes.Count - 1] 為最前面的形狀。唯讀 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](./getbaseplaceholder/)() override | 傳回基本佔位形狀（從版面配置或母投影片繼承而來的形狀）。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)() override | 傳回形狀縮圖。[ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) 形狀縮圖邊界類型預設使用。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | 傳回形狀縮圖。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](./getvisualbounds/)() | 取得根據渲染內容計算的形狀視覺邊界。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷貝建構函式。實際上不會複製任何內容，只是初始化新物件，並允許子類別進行拷貝建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件，並允許子類別進行拷貝建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化版本，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化版本，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| void [RemovePlaceholder](./removeplaceholder/)() override | 定義此形狀不是佔位元。 |
| void [set_AlternativeText](./set_alternativetext/)([System::String](../../system/string/)) override | 設定與形狀相關聯的替代文字。寫入 [System::String](../../system/string/)。 |
| void [set_AlternativeTextTitle](./set_alternativetexttitle/)([System::String](../../system/string/)) override | 設定與形狀相關聯的替代文字標題。寫入 [System::String](../../system/string/)。 |
| void [set_BlackWhiteMode](./set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | 屬性指定形狀在黑白顯示模式下的呈現方式。寫入 [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| void [set_Frame](./set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | 設定形狀框架的屬性。寫入 [IShapeFrame](../ishapeframe/)。 |
| void [set_Height](./set_height/)(**float**) override | 設定形狀的高度，單位為點。寫入 **float**。 |
| void [set_Hidden](./set_hidden/)(**bool**) override | 設定形狀是否為隱藏。寫入 **bool**。 |
| void [set_HyperlinkClick](./set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | 設定滑鼠點擊時的超連結。寫入 [IHyperlink](../ihyperlink/)。 |
| void [set_HyperlinkMouseOver](./set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | 設定滑鼠懸停時的超連結。寫入 [IHyperlink](../ihyperlink/)。 |
| void [set_IsDecorative](./set_isdecorative/)(**bool**) override | 設定「標記為裝飾」選項。讀寫 **bool**。 |
| void [set_Name](./set_name/)([System::String](../../system/string/)) override | 設定形狀的名稱。不可為 null。必要時使用空字串。寫入 [System::String](../../system/string/)。 |
| void [set_RawFrame](./set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | 設定原始形狀框架的屬性。寫入 [IShapeFrame](../ishapeframe/)。 |
| void [set_Rotation](./set_rotation/)(**float**) override | 設定指定形狀繞 Z 軸旋轉的角度（度數）。正值表示順時針旋轉，負值表示逆時針旋轉。寫入 **float**。 |
| void [set_Width](./set_width/)(**float**) override | 設定形狀的寬度，單位為點。寫入 **float**。 |
| void [set_X](./set_x/)(**float**) override | 設定形狀左上角的 X 座標，單位為點。寫入 **float**。 |
| void [set_Y](./set_y/)(**float**) override | 設定形狀左上角的 Y 座標，單位為點。寫入 **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享指標）。允許在容器中切換指標為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WriteAsSvg](./writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | 將 [Shape](./) 的內容儲存為 SVG 檔案。 |
| void [WriteAsSvg](./writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | 將 [Shape](./) 的內容儲存為 SVG 檔案。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另請參閱

* 類別 [IShape](../ishape/)
* 類別 [IDOMObject](../idomobject/)
* 命名空間 [Aspose::Slides](../)
* 程式庫 [Aspose.Slides](../../)