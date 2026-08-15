---
title: AutoShape
second_title: Aspose.Slides for C++ API 參考
description: 表示一個 AutoShape。
type: docs
weight: 66
url: /zh-hant/aspose.slides/autoshape/
---
## AutoShape 類別

表示一個 [AutoShape](./)。

```cpp
class AutoShape : public Aspose::Slides::GeometryShape,
                  public Aspose::Slides::IAutoShape
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | 如果沒有則新增佔位符，並將佔位符屬性設定為指定的。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [AddTextFrame](./addtextframe/)([System::String](../../system/string/)) override | 為形狀新增一個 [TextFrame](../textframe/)。如果形狀已經有 [TextFrame](../textframe/)，則僅變更其文字。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | 建立並傳回形狀元素的陣列。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使依據 IEC 60559:1989 NaN 與任何值（包括 NaN）皆不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使依據 IEC 60559:1989 NaN 與任何值（包括 NaN）皆不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | 傳回指定索引處的形狀調整值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | 傳回形狀調整值的集合。唯讀 [IAdjustValueCollection](../iadjustvaluecollection/)。 |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | 傳回與形狀關聯的替代文字。讀取 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | 傳回與形狀關聯的替代文字標題。讀取 [System::String](../../system/string/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShapeLock](../iautoshapelock/)\> [get_AutoShapeLock](./get_autoshapelock/)() override | 傳回自動圖形的鎖定。唯讀 [IAutoShapeLock](../iautoshapelock/)。 |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | 屬性指定形狀在黑白顯示模式下的呈現方式。讀取 [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | 傳回形狀的連接點數量。唯讀 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | 傳回形狀的自訂資料。唯讀 [ICustomData](../icustomdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | 傳回包含套用於形狀之像素效果的 [EffectFormat](../effectformat/) 物件。註：對於某些沒有效果屬性的形狀，可能傳回 null。唯讀 [IEffectFormat](../ieffectformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | 傳回包含形狀填充格式屬性的 [FillFormat](../fillformat/) 物件。註：對於某些沒有填充屬性的形狀，可能傳回 null。唯讀 [IFillFormat](../ifillformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | 傳回形狀框架的屬性。讀取 [IShapeFrame](../ishapeframe/)。 |
| **float** [get_Height](../shape/get_height/)() override | 取得形狀的高度（以點為單位）。讀取 **float**。 |
| **bool** [get_Hidden](../shape/get_hidden/)() override | 判斷形狀是否隱藏。讀取 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | 傳回為滑鼠點擊所定義的超連結。讀取 [IHyperlink](../ihyperlink/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | 傳回超連結管理員。唯讀 [IHyperlinkManager](../ihyperlinkmanager/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | 傳回為滑鼠懸停所定義的超連結。讀取 [IHyperlink](../ihyperlink/)。 |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | 取得 'Mark as decorative' 選項 讀寫 **bool**。 |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | 判斷形狀是否已群組。唯讀 **bool**。 |
| **bool** [get_IsTextBox](./get_istextbox/)() override | 指定形狀是否為文字方塊。 |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | 判斷形狀是否為 TextHolder_PPT。唯讀 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | 傳回包含形狀線條格式屬性的 [LineFormat](../lineformat/) 物件。註：對於某些沒有線條屬性的形狀，可能傳回 null。唯讀 [ILineFormat](../ilineformat/)。 |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | 傳回形狀的名稱。不能為 null。如有需要，使用空字串值。讀取 [System::String](../../system/string/)。 |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | 傳回在投影片範圍內唯一的識別碼，於形狀生命週期內保持不變，讓 PowerPoint 或互操作程式碼能在文件任何位置可靠地參照形狀。唯讀 **uint32_t**。另請參閱 [Shape::get_UniqueId](../shape/get_uniqueid/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | 如果形狀已群組，傳回父 [GroupShape](../groupshape/) 物件。否則傳回 null。唯讀 [IGroupShape](../igroupshape/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | 傳回形狀的占位符。如果形狀沒有占位符，傳回 null。唯讀 [IPlaceholder](../iplaceholder/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | 傳回投影片的父簡報。唯讀 [IPresentation](../ipresentation/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | 傳回原始形狀框架的屬性。讀取 [IShapeFrame](../ishapeframe/)。 |
| **float** [get_Rotation](../shape/get_rotation/)() override | 傳回指定形狀繞 Z 軸旋轉的角度（度）。正值表示順時鐘旋轉，負值表示逆時鐘旋轉。讀取 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | 傳回形狀的鎖定。唯讀 [IBaseShapeLock](../ibaseshapelock/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | 傳回形狀的樣式物件。唯讀 [IShapeStyle](../ishapestyle/)。 |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../geometryshape/get_shapetype/)() override | 傳回幾何預設類型。註：值變更時，所有調整值將重設為預設值。讀取 [Slides::ShapeType](../shapetype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | 傳回形狀的父投影片。唯讀 [IBaseSlide](../ibaseslide/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() override | 傳回 [TextFrame](../textframe/) 物件給 [AutoShape](./)。唯讀 [ITextFrame](../itextframe/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | 傳回形狀的 [ThreeDFormat](../threedformat/) 物件，其包含 3D 效果屬性。註：對於某些沒有 3D 屬性的形狀，可能傳回 null。唯讀 [IThreeDFormat](../ithreedformat/)。 |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | 傳回內部、簡報範圍的識別碼，供外掛或其他程式碼使用。由於此值可能被使用者或程式重新指派，不能視為永久的唯一鍵。唯讀 **uint32_t**。另請參閱 [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)。 |
| **bool** [get_UseBackgroundFill](./get_usebackgroundfill/)() override | 判斷此自動圖形是否應以投影片背景填充，而非由樣式或填充格式指定。讀取 **bool**。 |
| **float** [get_Width](../shape/get_width/)() override | 取得形狀的寬度（以點為單位）。讀取 **float**。 |
| **float** [get_X](../shape/get_x/)() override | 取得形狀左上角的 x 座標（以點為單位）。讀取 **float**。 |
| **float** [get_Y](../shape/get_y/)() override | 取得形狀左上角的 y 座標（以點為單位）。讀取 **float**。 |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | 傳回形狀在 Z 順序中的位置。Shapes[0] 代表 Z 順序最後面的形狀，Shapes[Shapes.Count - 1] 代表最前面的形狀。唯讀 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | 傳回基本的占位符形狀（來自版面配置和/或母片投影片，且目前形狀繼承自該形狀）。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參照計數資料結構。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | 傳回幾何形狀路徑的複本。座標相對於形狀的左上角。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。支援自訂物件的雜湊。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | 傳回形狀縮圖。預設使用 [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) 形狀縮圖邊界類型。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | 傳回形狀縮圖。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | 取得根據已呈現內容計算出的形狀視覺邊界。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 描述的類型實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守護物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。支援自訂類型的複製。 |
| [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件，並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件，並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參照比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參照比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參照比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特殊化，適用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特殊化，適用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 依指定值減少共享參照計數。 |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | 定義此形狀不是占位符。 |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | 設定與形狀關聯的替代文字。寫入 [System::String](../../system/string/)。 |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | 設定與形狀關聯的替代文字標題。寫入 [System::String](../../system/string/)。 |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | 屬性指定形狀在黑白顯示模式下的呈現方式。寫入 [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | 設定形狀框架的屬性。寫入 [IShapeFrame](../ishapeframe/)。 |
| void [set_Height](../shape/set_height/)(**float**) override | 設定形狀的高度（以點為單位）。寫入 **float**。 |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | 設定形狀是否隱藏。寫入 **bool**。 |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | 設定為滑鼠點擊所定義的超連結。寫入 [IHyperlink](../ihyperlink/)。 |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | 設定為滑鼠懸停所定義的超連結。寫入 [IHyperlink](../ihyperlink/)。 |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | 設定「Mark as decorative」選項 讀寫 **bool**。 |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | 設定形狀的名稱。不可為 null。如有需要，使用空字串。寫入 [System::String](../../system/string/)。 |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | 設定原始形狀框架的屬性。寫入 [IShapeFrame](../ishapeframe/)。 |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | 設定指定形狀繞 Z 軸旋轉的角度（度）。正值表示順時鐘旋轉，負值表示逆時鐘旋轉。寫入 **float**。 |
| void [set_ShapeType](../geometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override | 設定幾何預設類型。註：值變更時，所有調整值將重設為預設值。寫入 [Slides::ShapeType](../shapetype/)。 |
| void [set_UseBackgroundFill](./set_usebackgroundfill/)(**bool**) override | 設定此自動圖形是否應以投影片背景填充，而非由樣式或填充格式指定。寫入 **bool**。 |
| void [set_Width](../shape/set_width/)(**float**) override | 設定形狀的寬度（以點為單位）。寫入 **float**。 |
| void [set_X](../shape/set_x/)(**float**) override | 設定形狀左上角的 x 座標（以點為單位）。寫入 **float**。 |
| void [set_Y](../shape/set_y/)(**float**) override | 設定形狀左上角的 y 座標（以點為單位）。寫入 **float**。 |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | 從 [IGeometryPath](../igeometrypath/) 物件更新形狀幾何。座標必須相對於形狀的左上角。將形狀類型 ([ShapeType](../shapetype/)) 更改為 [ShapeType::Custom](../shapetype/)。 |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | 從 [IGeometryPath](../igeometrypath/) 陣列更新形狀幾何。座標必須相對於形狀的左上角。將形狀類型 ([ShapeType](../shapetype/)) 更改為 [ShapeType::Custom](../shapetype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中切換指標為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參照計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參照計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並傳回共享參照計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。支援將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守護物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參照計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參照計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | 將 [Shape](../shape/) 內容儲存為 SVG 檔案。 |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | 將 [Shape](../shape/) 內容儲存為 SVG 檔案。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另請參閱

* 類別 [GeometryShape](../geometryshape/)
* 類別 [IAutoShape](../iautoshape/)
* 命名空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)