---
title: ITable
second_title: Aspose.Slides C++ API 參考
description: 表示投影片上的表格。
type: docs
weight: 4018
url: /zh-hant/aspose.slides/itable/
---
## ITable 類別

Represents a table on a slide.

```cpp
class ITable : public virtual Aspose::Slides::IGraphicalObject,
               public Aspose::Slides::IBulkTextFormattable
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | 如果不存在，則新增一個佔位符並將佔位符屬性設定為指定的佔位符。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點數比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值（包括 NaN）。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點數比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值（包括 NaN）。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | 返回與形狀關聯的替代文字。閱讀 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | 返回與形狀關聯的替代文字標題。閱讀 [System::String](../../system/string/)。 |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | 屬性指定形狀在黑白顯示模式下的渲染方式。閱讀 [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_Column](./get_column/)(**int32_t**) | 返回指定索引的欄。唯讀 [Aspose::Slides::IColumn](../icolumn/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumnCollection](../icolumncollection/)\> [get_Columns](./get_columns/)() | 返回欄的集合。唯讀 [IColumnCollection](../icolumncollection/)。 |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | 返回形狀的連接點數量。唯讀 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | 返回形狀的自訂資料。唯讀 [ICustomData](../icustomdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | 返回包含套用於形狀的像素效果的 [EffectFormat](../effectformat/) 物件。唯讀 [IEffectFormat](../ieffectformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | 返回包含形狀填充格式屬性的 [FillFormat](../fillformat/) 物件。唯讀 [IFillFormat](../ifillformat/)。 |
| virtual **bool** [get_FirstCol](./get_firstcol/)() | 判斷表格的第一欄是否需要以特殊格式繪製。返回 **bool**。 |
| virtual **bool** [get_FirstRow](./get_firstrow/)() | 判斷表格的第一列是否需要以特殊格式繪製。返回 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | 返回形狀框架的屬性。閱讀 [IShapeFrame](../ishapeframe/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../igraphicalobject/get_graphicalobjectlock/)() | 返回形狀的鎖定狀態。唯讀 [IGraphicalObjectLock](../igraphicalobjectlock/)。 |
| virtual **float** [get_Height](../ishape/get_height/)() | 取得形狀的高度（以點為單位）。返回 **float**。 |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | 判斷形狀是否隱藏。返回 **bool**。 |
| virtual **bool** [get_HorizontalBanding](./get_horizontalbanding/)() | 判斷偶數列是否需要以不同格式繪製。返回 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | 返回為滑鼠點擊定義的超連結。閱讀 [IHyperlink](../ihyperlink/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | 超連結管理器。唯讀 [IHyperlinkManager](../ihyperlinkmanager/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | 返回為滑鼠懸停定義的超連結。閱讀 [IHyperlink](../ihyperlink/)。 |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | 取得「標記為裝飾」選項。讀寫 **bool**。 |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | 判斷形狀是否已分組。唯讀 **bool**。 |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | 判斷形狀是否為 TextHolder。唯讀 **bool**。 |
| virtual **bool** [get_LastCol](./get_lastcol/)() | 判斷表格的最後一欄是否需要以特殊格式繪製。返回 **bool**。 |
| virtual **bool** [get_LastRow](./get_lastrow/)() | 判斷表格的最後一列是否需要以特殊格式繪製。返回 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | 返回包含形狀線條格式屬性的 [LineFormat](../lineformat/) 物件。唯讀 [ILineFormat](../ilineformat/)。 |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | 返回形狀的名稱。閱讀 [System::String](../../system/string/)。 |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | 返回在投影片範圍內唯一的識別碼，該識別碼在形狀生命週期內保持不變，讓 PowerPoint 或互通程式碼能從文件任意位置可靠地參照該形狀。唯讀 **uint32_t**。另請參閱 [IShape::get_UniqueId](../ishape/get_uniqueid/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | 如果形狀已分組，返回父層 [GroupShape](../groupshape/) 物件；否則返回 null。唯讀 [IGroupShape](../igroupshape/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | 返回形狀的佔位符。唯讀 [IPlaceholder](../iplaceholder/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | 返回簡報。唯讀 [IPresentation](../ipresentation/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | 返回原始形狀框架的屬性。閱讀 [IShapeFrame](../ishapeframe/)。 |
| virtual **bool** [get_RightToLeft](./get_righttoleft/)() | 判斷表格是否採用從右至左的閱讀順序。返回 **bool**。 |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | 返回指定形狀繞 Z 軸旋轉的角度（度），正值表示順時針旋轉，負值表示逆時針旋轉。返回 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_Row](./get_row/)(**int32_t**) | 返回指定索引的列。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRowCollection](../irowcollection/)\> [get_Rows](./get_rows/)() | 返回列的集合。唯讀 [IRowCollection](../irowcollection/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | 返回形狀的鎖定狀態。唯讀 [IBaseShapeLock](../ibaseshapelock/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | 返回基礎投影片。唯讀 [IBaseSlide](../ibaseslide/)。 |
| virtual [TableStylePreset](../tablestylepreset/) [get_StylePreset](./get_stylepreset/)() | 取得或設定內建表格樣式。閱讀 [TableStylePreset](../tablestylepreset/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITableFormat](../itableformat/)\> [get_TableFormat](./get_tableformat/)() | 返回包含此表格格式屬性的 [TableFormat](../tableformat/) 物件。唯讀 [ITableFormat](../itableformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | 返回包含形狀線條格式屬性的 [ThreeDFormat](../threedformat/) 物件。唯讀 [IThreeDFormat](../ithreedformat/)。 |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | 返回供外掛或其他程式碼使用的內部、簡報範圍內的識別碼。由於此值可能會被使用者或程式重新指定，不能視為永久唯一鍵。唯讀 **uint32_t**。另請參閱 [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)。 |
| virtual **bool** [get_VerticalBanding](./get_verticalbanding/)() | 判斷偶數欄是否需要以不同格式繪製。返回 **bool**。 |
| virtual **float** [get_Width](../ishape/get_width/)() | 取得形狀的寬度（以點為單位）。返回 **float**。 |
| virtual **float** [get_X](../ishape/get_x/)() | 取得形狀左上角的 x 座標（以點為單位）。返回 **float**。 |
| virtual **float** [get_Y](../ishape/get_y/)() | 取得形狀左上角的 y 座標（以點為單位）。返回 **float**。 |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | 返回形狀在 Z 序中的位置。Shapes[0] 取得 Z 序最底層的形狀，Shapes[Shapes.Count - 1] 取得最上層的形狀。唯讀 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | 返回基本佔位符形狀（從版面配置或母投影片繼承的形狀）。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參照計數器資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊功能。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | 返回形狀縮圖。預設使用 [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) 形狀縮圖邊界類型。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | 返回形狀縮圖。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [idx_get](./idx_get/)(**int32_t**, **int32_t**) | 返回指定欄與列索引的儲存格。唯讀 [ICell](../icell/)。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述型別的實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的加鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的複製。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [MergeCells](./mergecells/)([System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\>, **bool**) | 合併相鄰的儲存格。 |
| [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參照計數減少指定值。 |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | 定義此形狀不是佔位符。 |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | 設定與形狀關聯的替代文字。寫入 [System::String](../../system/string/)。 |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | 設定與形狀關聯的替代文字標題。寫入 [System::String](../../system/string/)。 |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | 屬性指定形狀在黑白顯示模式下的渲染方式。寫入 [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| virtual void [set_FirstCol](./set_firstcol/)(**bool**) | 判斷表格的第一欄是否需要以特殊格式繪製。寫入 **bool**。 |
| virtual void [set_FirstRow](./set_firstrow/)(**bool**) | 判斷表格的第一列是否需要以特殊格式繪製。寫入 **bool**。 |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | 設定形狀框架的屬性。寫入 [IShapeFrame](../ishapeframe/)。 |
| virtual void [set_Height](../ishape/set_height/)(**float**) | 設定形狀的高度（以點為單位）。寫入 **float**。 |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | 判斷形狀是否隱藏。寫入 **bool**。 |
| virtual void [set_HorizontalBanding](./set_horizontalbanding/)(**bool**) | 判斷偶數列是否需要以不同格式繪製。寫入 **bool**。 |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | 設定為滑鼠點擊定義的超連結。寫入 [IHyperlink](../ihyperlink/)。 |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | 設定為滑鼠懸停定義的超連結。寫入 [IHyperlink](../ihyperlink/)。 |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | 設定「標記為裝飾」選項。讀寫 **bool**。 |
| virtual void [set_LastCol](./set_lastcol/)(**bool**) | 判斷表格的最後一欄是否需要以特殊格式繪製。寫入 **bool**。 |
| virtual void [set_LastRow](./set_lastrow/)(**bool**) | 判斷表格的最後一列是否需要以特殊格式繪製。寫入 **bool**。 |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | 設定形狀的名稱。寫入 [System::String](../../system/string/)。 |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | 設定原始形狀框架的屬性。寫入 [IShapeFrame](../ishapeframe/)。 |
| virtual void [set_RightToLeft](./set_righttoleft/)(**bool**) | 判斷表格是否採用從右至左的閱讀順序。寫入 **bool**。 |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | 設定指定形狀繞 Z 軸旋轉的角度（度），正值表示順時針，負值表示逆時針。寫入 **float**。 |
| virtual void [set_StylePreset](./set_stylepreset/)([TableStylePreset](../tablestylepreset/)) | 取得或設定內建表格樣式。寫入 [TableStylePreset](../tablestylepreset/)。 |
| virtual void [set_VerticalBanding](./set_verticalbanding/)(**bool**) | 判斷偶數欄是否需要以不同格式繪製。寫入 **bool**。 |
| virtual void [set_Width](../ishape/set_width/)(**float**) | 設定形狀的寬度（以點為單位）。寫入 **float**。 |
| virtual void [set_X](../ishape/set_x/)(**float**) | 設定形狀左上角的 x 座標（以點為單位）。寫入 **float**。 |
| virtual void [set_Y](../ishape/set_y/)(**float**) | 設定形狀左上角的 y 座標（以點為單位）。寫入 **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| virtual void [SetTextFormat](../ibulktextformattable/settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\>) | 將定義的段落格式屬性套用至所有元素的部分。 |
| virtual void [SetTextFormat](../ibulktextformattable/settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormat](../iparagraphformat/)\>) | 將定義的段落格式屬性套用至所有元素的段落。 |
| virtual void [SetTextFormat](../ibulktextformattable/settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormat](../itextframeformat/)\>) | 將定義的文字框格式屬性套用至所有元素的文字框。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參照計數器的當前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參照計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參照計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參照計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參照計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | 將 [Shape](../shape/) 的內容保存為 SVG 檔案。 |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | 將 [Shape](../shape/) 的內容保存為 SVG 檔案。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 參見

* 類別 [IGraphicalObject](../igraphicalobject/)
* 類別 [IBulkTextFormattable](../ibulktextformattable/)
* 命名空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)