---
title: Table
second_title: Aspose.Slides for C++ API 參考
description: 表示投影片上的表格。
type: docs
weight: 5409
url: /zh-hant/aspose.slides/table/
---
## Table 類別

Represents a table on a slide.

```cpp
class Table : public Aspose::Slides::GraphicalObject,
              public Aspose::Slides::ITable
```

## 方法

| 方法 | 說明 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | 如果不存在，新增一個占位符並將占位符屬性設定為指定的占位符。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別的物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別的物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點數比較，即使根據 IEC 60559:1989，NaN 不等於任何值（包括 NaN），兩個 NaN 仍被視為相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點數比較，即使根據 IEC 60559:1989，NaN 不等於任何值（包括 NaN），兩個 NaN 仍被視為相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | 傳回與形狀關聯的替代文字。請參閱 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | 傳回與形狀關聯的替代文字之標題。請參閱 [System::String](../../system/string/)。 |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | 屬性指定形狀在黑白顯示模式下的呈現方式。請參閱 [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_Column](./get_column/)(**int32_t**) override | 傳回指定索引處的欄。唯讀 [Aspose::Slides::IColumn](../icolumn/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumnCollection](../icolumncollection/)\> [get_Columns](./get_columns/)() override | 傳回欄的集合。唯讀 [IColumnCollection](../icolumncollection/)。 |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | 傳回形狀的連接點數量。唯讀 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | 傳回形狀的自訂資料。唯讀 [ICustomData](../icustomdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | 傳回包含套用於形狀的像素效果的 [EffectFormat](../effectformat/) 物件。注意：對於某些沒有效果屬性的形狀，可能會傳回 null。唯讀 [IEffectFormat](../ieffectformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() override | 傳回包含 [Table](./) 填充格式的 [TableFormat::get_FillFormat](../tableformat/get_fillformat/) 物件。唯讀 [IFillFormat](../ifillformat/)。 |
| **bool** [get_FirstCol](./get_firstcol/)() override | 判斷表格的第一欄是否需要以特殊格式繪製。讀取 **bool**。 |
| **bool** [get_FirstRow](./get_firstrow/)() override | 判斷表格的第一列是否需要以特殊格式繪製。讀取 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | 傳回形狀框架的屬性。請參閱 [IShapeFrame](../ishapeframe/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | 傳回形狀的鎖定。唯讀 [IGraphicalObjectLock](../igraphicalobjectlock/)。 |
| **float** [get_Height](../shape/get_height/)() override | 取得形狀的高度，以點為單位。讀取 **float**。 |
| **bool** [get_Hidden](../shape/get_hidden/)() override | 判斷形狀是否隱藏。讀取 **bool**。 |
| **bool** [get_HorizontalBanding](./get_horizontalbanding/)() override | 判斷偶數列是否需要以不同的格式繪製。讀取 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | 傳回滑鼠點擊時定義的超連結。請參閱 [IHyperlink](../ihyperlink/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | 傳回超連結管理器。唯讀 [IHyperlinkManager](../ihyperlinkmanager/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | 傳回滑鼠懸停時定義的超連結。請參閱 [IHyperlink](../ihyperlink/)。 |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | 取得「標記為裝飾」選項，讀寫 **bool**。 |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | 判斷形狀是否已群組。唯讀 **bool**。 |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | 判斷形狀是否為 TextHolder_PPT。唯讀 **bool**。 |
| **bool** [get_LastCol](./get_lastcol/)() override | 判斷表格的最後一欄是否需要以特殊格式繪製。讀取 **bool**。 |
| **bool** [get_LastRow](./get_lastrow/)() override | 判斷表格的最後一列是否需要以特殊格式繪製。讀取 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | 傳回包含形狀線條格式屬性的 [LineFormat](../lineformat/) 物件。注意：對於某些沒有線條屬性的形狀，可能會傳回 null。唯讀 [ILineFormat](../ilineformat/)。 |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | 傳回形狀的名稱。必須非 null。如有需要可使用空字串。請參閱 [System::String](../../system/string/)。 |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | 傳回在投影片範圍內唯一的辨識碼，於形狀的生命週期內保持不變，讓 PowerPoint 或互操作程式能在文件任意位置可靠地參照該形狀。唯讀 **uint32_t**。另請參閱 [Shape::get_UniqueId](../shape/get_uniqueid/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | 如果形狀已群組，傳回父層 [GroupShape](../groupshape/) 物件。否則傳回 null。唯讀 [IGroupShape](../igroupshape/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | 傳回形狀的占位符。若形狀沒有占位符，則傳回 null。唯讀 [IPlaceholder](../iplaceholder/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | 傳回投影片的父簡報。唯讀 [IPresentation](../ipresentation/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | 傳回原始形狀框架的屬性。請參閱 [IShapeFrame](../ishapeframe/)。 |
| **bool** [get_RightToLeft](./get_righttoleft/)() override | 判斷表格是否採用由右至左的閱讀順序。讀取 **bool**。 |
| **float** [get_Rotation](../shape/get_rotation/)() override | 傳回指定形狀繞 Z 軸旋轉的角度（單位：度）。正值表示順時針旋轉，負值表示逆時針旋轉。讀取 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_Row](./get_row/)(**int32_t**) override | 傳回指定索引處的列。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IRowCollection](../irowcollection/)\> [get_Rows](./get_rows/)() override | 傳回列的集合。唯讀 [IRowCollection](../irowcollection/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | 傳回形狀的鎖定。唯讀 [IBaseShapeLock](../ibaseshapelock/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | 傳回形狀的父投影片。唯讀 [IBaseSlide](../ibaseslide/)。 |
| [TableStylePreset](../tablestylepreset/) [get_StylePreset](./get_stylepreset/)() override | 取得內建的表格樣式。請參閱 [TableStylePreset](../tablestylepreset/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITableFormat](../itableformat/)\> [get_TableFormat](./get_tableformat/)() override | 傳回包含此表格格式屬性的 [TableFormat](../tableformat/) 物件。唯讀 [ITableFormat](../itableformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | 傳回包含形狀 3D 效果屬性的 [ThreeDFormat](../threedformat/) 物件。注意：對於某些沒有 3D 屬性的形狀，可能會傳回 null。唯讀 [IThreeDFormat](../ithreedformat/)。 |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | 傳回供外掛程式或其他程式碼使用的內部、簡報範圍識別碼。由於此值可能被使用者或程式重新指派，不能視為永續的唯一鍵。唯讀 **uint32_t**。另請參閱 [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)。 |
| **bool** [get_VerticalBanding](./get_verticalbanding/)() override | 判斷偶數欄是否需要以不同的格式繪製。讀取 **bool**。 |
| **float** [get_Width](../shape/get_width/)() override | 取得形狀的寬度，以點為單位。讀取 **float**。 |
| **float** [get_X](../shape/get_x/)() override | 取得形狀左上角的 X 座標，以點為單位。讀取 **float**。 |
| **float** [get_Y](../shape/get_y/)() override | 取得形狀左上角的 Y 座標，以點為單位。讀取 **float**。 |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | 傳回形狀在 Z 順序中的位置。Shapes[0] 傳回 Z 順序最背面的形狀，Shapes[Shapes.Count - 1] 傳回 Z 順序最前面的形狀。唯讀 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | 傳回基本的占位符形狀（來自版面配置或母片且目前形狀繼承自該形狀的形狀）。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | 傳回形狀縮圖。預設使用 [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) 形狀縮圖邊界類型。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | 傳回形狀縮圖。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | 取得根據形狀渲染內容計算出的視覺邊界。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [idx_get](./idx_get/)(**int32_t**, **int32_t**) override | 傳回指定欄與列索引處的儲存格。唯讀 [Cell](../cell/)。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的克隆。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [MergeCells](./mergecells/)([System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\>, **bool**) override | 合併相鄰的儲存格。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構式。實際上不會複製任何內容，只是初始化新物件，並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件，並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參照方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參照方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參照方式將值型別物件與 nullptr 比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共用參考計數減少指定的值。 |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | 定義此形狀不是占位符。 |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | 設定與形狀關聯的替代文字。寫入 [System::String](../../system/string/)。 |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | 設定與形狀關聯的替代文字之標題。寫入 [System::String](../../system/string/)。 |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | 屬性指定形狀在黑白顯示模式下的呈現方式。寫入 [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| void [set_FirstCol](./set_firstcol/)(**bool**) override | 判斷表格的第一欄是否需要以特殊格式繪製。寫入 **bool**。 |
| void [set_FirstRow](./set_firstrow/)(**bool**) override | 判斷表格的第一列是否需要以特殊格式繪製。寫入 **bool**。 |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | 設定形狀框架的屬性。寫入 [IShapeFrame](../ishapeframe/)。 |
| void [set_Height](../shape/set_height/)(**float**) override | 設定形狀的高度（以點為單位）。寫入 **float**。 |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | 判斷形狀是否隱藏。寫入 **bool**。 |
| void [set_HorizontalBanding](./set_horizontalbanding/)(**bool**) override | 判斷偶數列是否需要以不同的格式繪製。寫入 **bool**。 |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | 設定滑鼠點擊時定義的超連結。寫入 [IHyperlink](../ihyperlink/)。 |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | 設定滑鼠懸停時定義的超連結。寫入 [IHyperlink](../ihyperlink/)。 |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | 設定「標記為裝飾」選項，讀寫 **bool**。 |
| void [set_LastCol](./set_lastcol/)(**bool**) override | 判斷表格的最後一欄是否需要以特殊格式繪製。寫入 **bool**。 |
| void [set_LastRow](./set_lastrow/)(**bool**) override | 判斷表格的最後一列是否需要以特殊格式繪製。寫入 **bool**。 |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | 設定形狀的名稱。必須非 null。如有需要可使用空字串。寫入 [System::String](../../system/string/)。 |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | 設定原始形狀框架的屬性。寫入 [IShapeFrame](../ishapeframe/)。 |
| void [set_RightToLeft](./set_righttoleft/)(**bool**) override | 判斷表格是否採用由右至左的閱讀順序。寫入 **bool**。 |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | 設定指定形狀繞 Z 軸旋轉的角度（單位：度）。正值表示順時針旋轉，負值表示逆時針旋轉。寫入 **float**。 |
| void [set_StylePreset](./set_stylepreset/)([TableStylePreset](../tablestylepreset/)) override | 設定內建的表格樣式。寫入 [TableStylePreset](../tablestylepreset/)。 |
| void [set_VerticalBanding](./set_verticalbanding/)(**bool**) override | 判斷偶數欄是否需要以不同的格式繪製。寫入 **bool**。 |
| void [set_Width](../shape/set_width/)(**float**) override | 設定形狀的寬度（以點為單位）。寫入 **float**。 |
| void [set_X](../shape/set_x/)(**float**) override | 設定形狀左上角的 X 座標（以點為單位）。寫入 **float**。 |
| void [set_Y](../shape/set_y/)(**float**) override | 設定形狀左上角的 Y 座標（以點為單位）。寫入 **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共用指標）。允許在容器中切換指標至弱模式。 |
| void [SetTextFormat](./settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\>) override | 設定所有表格儲存格片段的已定義部分格式屬性。 |
| void [SetTextFormat](./settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormat](../iparagraphformat/)\>) override | 設定所有表格儲存格段落的已定義段落格式屬性。 |
| void [SetTextFormat](./settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormat](../itextframeformat/)\>) override | 設定所有表格儲存格文字框的已定義文字框格式屬性。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共用參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 將共用參考計數遞增。不要直接呼叫，請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 將共用參考計數遞減並傳回。不要直接呼叫，請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 將弱參考計數遞增。不要直接呼叫，請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 將弱參考計數遞減。不要直接呼叫，請改用智慧指標或 ThisProtector。 |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | 將 [Shape](../shape/) 的內容儲存為 SVG 檔案。 |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | 將 [Shape](../shape/) 的內容儲存為 SVG 檔案。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另請參閱

* 類別 [GraphicalObject](../graphicalobject/)
* 類別 [ITable](../itable/)
* 命名空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)