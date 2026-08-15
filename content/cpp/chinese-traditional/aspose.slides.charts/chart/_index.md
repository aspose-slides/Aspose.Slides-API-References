---
title: Chart
second_title: Aspose.Slides for C++ API 參考
description: 代表投影片上的圖形圖表。
type: docs
weight: 53
url: /zh-hant/aspose.slides.charts/chart/
---
## Chart 類別

Represents an graphic chart on a slide.

```cpp
class Chart : public Aspose::Slides::GraphicalObject,
              public Aspose::Slides::Charts::IChart
```

## 方法

| 方法 | 說明 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) override | 如果不存在則新增佔位符，並將佔位符屬性設定為指定的。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Theme::IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](./createthemeeffective/)() override | 傳回此圖表的有效佈景主題。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/shape/get_alternativetext/)() override | 傳回與形狀相關聯的替代文字。閱讀 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/shape/get_alternativetexttitle/)() override | 傳回與形狀相關聯的替代文字標題。閱讀 [System::String](../../system/string/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAxesManager](../iaxesmanager/)\> [get_Axes](./get_axes/)() override | 提供對圖表坐標軸的存取。唯讀 [IAxesManager](../iaxesmanager/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_BackWall](./get_backwall/)() override | 傳回允許變更 3D 圖表後牆格式的物件。唯讀 [IChartWall](../ichartwall/)。 |
| [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/shape/get_blackwhitemode/)() override | 屬性指定形狀在黑白顯示模式下的呈現方式。閱讀 [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartData](../ichartdata/)\> [get_ChartData](./get_chartdata/)() override | 傳回與圖表相關聯的連結或嵌入資料資訊。唯讀 [IChartData](../ichartdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataTable](../idatatable/)\> [get_ChartDataTable](./get_chartdatatable/)() override | 傳回圖表的資料表。唯讀 [IDataTable](../idatatable/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_ChartTitle](./get_charttitle/)() override | 傳回圖表標題。唯讀 [IChartTitle](../icharttitle/)。 |
| **int32_t** [get_ConnectionSiteCount](../../aspose.slides/shape/get_connectionsitecount/)() override | 傳回形狀的連接點數量。唯讀 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/shape/get_customdata/)() override | 傳回形狀的自訂資料。唯讀 [ICustomData](../../aspose.slides/icustomdata/)。 |
| [DisplayBlanksAsType](../displayblanksastype/) [get_DisplayBlanksAs](./get_displayblanksas/)() override | 傳回圖表中空白儲存格的繪製方式。閱讀 [DisplayBlanksAsType](../displayblanksastype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/shape/get_effectformat/)() override | 傳回包含套用於形狀之像素效果的 [EffectFormat](../../aspose.slides/effectformat/) 物件。註：對於沒有效果屬性的某些形狀類型，可能會傳回 null。唯讀 [IEffectFormat](../../aspose.slides/ieffectformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/shape/get_fillformat/)() override | 傳回包含形狀填充格式屬性的 [FillFormat](../../aspose.slides/fillformat/) 物件。註：對於沒有填充屬性的某些形狀類型，可能會傳回 null。唯讀 [IFillFormat](../../aspose.slides/ifillformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_Floor](./get_floor/)() override | 傳回允許變更 3D 圖表底部格式的物件。唯讀 [IChartWall](../ichartwall/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/shape/get_frame/)() override | 傳回形狀框架的屬性。閱讀 [IShapeFrame](../../aspose.slides/ishapeframe/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/graphicalobject/get_graphicalobjectlock/)() override | 傳回形狀的鎖定設定。唯讀 [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)。 |
| **bool** [get_HasDataTable](./get_hasdatatable/)() override | 判斷圖表是否具有資料表。閱讀 **bool**。 |
| **bool** [get_HasLegend](./get_haslegend/)() override | 判斷圖表是否具有圖例。閱讀 **bool**。 |
| **bool** [get_HasRoundedCorners](./get_hasroundedcorners/)() override | 指定圖表區域應具有圓角。閱讀 **bool**。 |
| **bool** [get_HasTitle](./get_hastitle/)() override | 判斷圖表是否具有可見標題。閱讀 **bool**。 |
| **float** [get_Height](../../aspose.slides/shape/get_height/)() override | 取得形狀的高度（以點為單位）。閱讀 **float**。 |
| **bool** [get_Hidden](../../aspose.slides/shape/get_hidden/)() override | 判斷形狀是否隱藏。閱讀 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/shape/get_hyperlinkclick/)() override | 傳回滑鼠點擊時的超連結。閱讀 [IHyperlink](../../aspose.slides/ihyperlink/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/shape/get_hyperlinkmanager/)() override | 傳回超連結管理器。唯讀 [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/shape/get_hyperlinkmouseover/)() override | 傳回滑鼠懸停時的超連結。閱讀 [IHyperlink](../../aspose.slides/ihyperlink/)。 |
| **bool** [get_IsDecorative](../../aspose.slides/shape/get_isdecorative/)() override | 取得「標記為裝飾」選項讀寫 **bool**。 |
| **bool** [get_IsGrouped](../../aspose.slides/shape/get_isgrouped/)() override | 判斷形狀是否已群組。唯讀 **bool**。 |
| **bool** [get_IsTextHolder](../../aspose.slides/shape/get_istextholder/)() override | 判斷形狀是否為 TextHolder_PPT。唯讀 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegend](../ilegend/)\> [get_Legend](./get_legend/)() override | 傳回圖表的圖例。唯讀 [ILegend](../ilegend/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/shape/get_lineformat/)() override | 傳回包含形狀線條格式屬性的 [LineFormat](../../aspose.slides/lineformat/) 物件。註：對於沒有線條屬性的某些形狀類型，可能會傳回 null。唯讀 [ILineFormat](../../aspose.slides/ilineformat/)。 |
| [System::String](../../system/string/) [get_Name](../../aspose.slides/shape/get_name/)() override | 傳回形狀的名稱。必須非 null。如有需要可使用空字串。閱讀 [System::String](../../system/string/)。 |
| **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/)() override | 傳回在投影片範圍內唯一且在形狀生命週期內保持不變的識別碼，讓 PowerPoint 或互操作程式碼能從文件任何位置可靠地參照形狀。唯讀 **uint32_t**。另請參閱 [Shape::get_UniqueId](../../aspose.slides/shape/get_uniqueid/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/shape/get_parentgroup/)() override | 如果形狀已群組，傳回父層 [GroupShape](../../aspose.slides/groupshape/) 物件；否則傳回 null。唯讀 [IGroupShape](../../aspose.slides/igroupshape/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/shape/get_placeholder/)() override | 傳回形狀的佔位符。若形狀沒有佔位符則傳回 null。唯讀 [IPlaceholder](../../aspose.slides/iplaceholder/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartPlotArea](../ichartplotarea/)\> [get_PlotArea](./get_plotarea/)() override | 代表圖表的繪圖區域。唯讀 [IChartPlotArea](../ichartplotarea/)。 |
| **bool** [get_PlotVisibleCellsOnly](./get_plotvisiblecellsonly/)() override | 判斷是否僅繪製可見儲存格。若為 false，則同時繪製可見與隱藏儲存格。閱讀 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/shape/get_presentation/)() override | 傳回投影片的父層簡報。唯讀 [IPresentation](../../aspose.slides/ipresentation/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/shape/get_rawframe/)() override | 傳回原始形狀框架的屬性。閱讀 [IShapeFrame](../../aspose.slides/ishapeframe/)。 |
| **float** [get_Rotation](../../aspose.slides/shape/get_rotation/)() override | 傳回指定形狀繞 Z 軸旋轉的角度（以度為單位）。正值表示順時針旋轉；負值表示逆時針旋轉。閱讀 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IRotation3D](../irotation3d/)\> [get_Rotation3D](./get_rotation3d/)() override | 傳回圖表的 3D 旋轉。唯讀 [IRotation3D](../irotation3d/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/shape/get_shapelock/)() override | 傳回形狀的鎖定設定。唯讀 [IBaseShapeLock](../../aspose.slides/ibaseshapelock/)。 |
| **bool** [get_ShowDataLabelsOverMaximum](./get_showdatalabelsovermaximum/)() override | 指定是否顯示圖表最大值之上的資料標籤。閱讀 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_SideWall](./get_sidewall/)() override | 傳回允許變更 3D 圖表側牆格式的物件。唯讀 [IChartWall](../ichartwall/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/shape/get_slide/)() override | 傳回形狀的父層投影片。唯讀 [IBaseSlide](../../aspose.slides/ibaseslide/)。 |
| [StyleType](../styletype/) [get_Style](./get_style/)() override | 傳回圖表樣式。閱讀 [StyleType](../styletype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | 傳回圖表文字格式。此屬性不適用於以下類型：[ChartType::Treemap](../charttype/)、[ChartType::Sunburst](../charttype/)、[ChartType::Waterfall](../charttype/)、[ChartType::Histogram](../charttype/)、[ChartType::Funnel](../charttype/)、[ChartType::BoxAndWhisker](../charttype/)。唯讀 [IChartTextFormat](../icharttextformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Theme::IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)\> [get_ThemeManager](./get_thememanager/)() override | 傳回佈景主題管理員。唯讀 [Aspose::Slides::Theme::IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/shape/get_threedformat/)() override | 傳回包含形狀 3D 效果屬性的 [ThreeDFormat](../../aspose.slides/threedformat/) 物件。註：對於沒有 3D 屬性的某些形狀類型，可能會傳回 null。唯讀 [IThreeDFormat](../../aspose.slides/ithreedformat/)。 |
| [ChartType](../charttype/) [get_Type](./get_type/)() override | 傳回圖表類型。閱讀 [ChartType](../charttype/)。 |
| **uint32_t** [get_UniqueId](../../aspose.slides/shape/get_uniqueid/)() override | 傳回供外掛程式或其他程式碼使用的內部簡報範圍識別碼。由於此值可被使用者或程式重新指派，不能視為持久唯一鍵。唯讀 **uint32_t**。另請參閱 [Shape::get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_UserShapes](./get_usershapes/)() override | 指定繪製於圖表之上的形狀。唯讀 [IGroupShape](../../aspose.slides/igroupshape/)。 |
| **float** [get_Width](../../aspose.slides/shape/get_width/)() override | 取得形狀的寬度（以點為單位）。閱讀 **float**。 |
| **float** [get_X](../../aspose.slides/shape/get_x/)() override | 取得形狀左上角的 x 座標（以點為單位）。閱讀 **float**。 |
| **float** [get_Y](../../aspose.slides/shape/get_y/)() override | 取得形狀左上角的 y 座標（以點為單位）。閱讀 **float**。 |
| **int32_t** [get_ZOrderPosition](../../aspose.slides/shape/get_zorderposition/)() override | 傳回形狀在 Z 序中的位置。Shapes[0] 代表 Z 序最底層的形狀，Shapes[Shapes.Count - 1] 代表最前面的形狀。唯讀 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder/)() override | 傳回基本佔位符形狀（來自版面配置和/或母片，且目前形狀繼承自該形狀）。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關的引用計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 等同於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)() override | 傳回形狀縮圖。預設使用 [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) 形狀縮圖邊界類型。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) override | 傳回形狀縮圖。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。等同於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../../aspose.slides/shape/getvisualbounds/)() | 取得根據渲染內容計算出的形狀視覺邊界。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述的類型實例。等同於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 敘述的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視器物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 等同於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不會複製任何東西，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何東西，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以引用方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以引用方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以引用方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 針對字串與 nullptr 情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 針對字串情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享引用計數減少指定的數值。 |
| void [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder/)() override | 定義此形狀不是佔位符。 |
| void [set_AlternativeText](../../aspose.slides/shape/set_alternativetext/)([System::String](../../system/string/)) override | 設定與形狀相關聯的替代文字。寫入 [System::String](../../system/string/)。 |
| void [set_AlternativeTextTitle](../../aspose.slides/shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | 設定與形狀相關聯的替代文字標題。寫入 [System::String](../../system/string/)。 |
| void [set_BlackWhiteMode](../../aspose.slides/shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) override | 屬性指定形狀在黑白顯示模式下的呈現方式。寫入 [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)。 |
| void [set_DisplayBlanksAs](./set_displayblanksas/)([DisplayBlanksAsType](../displayblanksastype/)) override | 設定圖表中空白儲存格的繪製方式。寫入 [DisplayBlanksAsType](../displayblanksastype/)。 |
| void [set_Frame](../../aspose.slides/shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | 設定形狀框架的屬性。寫入 [IShapeFrame](../../aspose.slides/ishapeframe/)。 |
| void [set_HasDataTable](./set_hasdatatable/)(**bool**) override | 設定圖表是否具有資料表。寫入 **bool**。 |
| void [set_HasLegend](./set_haslegend/)(**bool**) override | 設定圖表是否具有圖例。寫入 **bool**。 |
| void [set_HasRoundedCorners](./set_hasroundedcorners/)(**bool**) override | 設定圖表區域應具有圓角。寫入 **bool**。 |
| void [set_HasTitle](./set_hastitle/)(**bool**) override | 設定圖表是否具有可見標題。寫入 **bool**。 |
| void [set_Height](../../aspose.slides/shape/set_height/)(**float**) override | 設定形狀的高度（以點為單位）。寫入 **float**。 |
| void [set_Hidden](../../aspose.slides/shape/set_hidden/)(**bool**) override | 設定形狀是否隱藏。寫入 **bool**。 |
| void [set_HyperlinkClick](../../aspose.slides/shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | 設定滑鼠點擊時的超連結。寫入 [IHyperlink](../../aspose.slides/ihyperlink/)。 |
| void [set_HyperlinkMouseOver](../../aspose.slides/shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | 設定滑鼠懸停時的超連結。寫入 [IHyperlink](../../aspose.slides/ihyperlink/)。 |
| void [set_IsDecorative](../../aspose.slides/shape/set_isdecorative/)(**bool**) override | 設定「標記為裝飾」選項。寫入 **bool**。 |
| void [set_Name](../../aspose.slides/shape/set_name/)([System::String](../../system/string/)) override | 設定形狀的名稱。必須非 null。如有需要可使用空字串。寫入 [System::String](../../system/string/)。 |
| void [set_PlotVisibleCellsOnly](./set_plotvisiblecellsonly/)(**bool**) override | 設定是否僅繪製可見儲存格。若為 false，則同時繪製可見與隱藏儲存格。寫入 **bool**。 |
| void [set_RawFrame](../../aspose.slides/shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | 設定原始形狀框架的屬性。寫入 [IShapeFrame](../../aspose.slides/ishapeframe/)。 |
| void [set_Rotation](../../aspose.slides/shape/set_rotation/)(**float**) override | 設定指定形狀繞 Z 軸旋轉的角度（以度為單位）。正值表示順時針旋轉；負值表示逆時針旋轉。寫入 **float**。 |
| void [set_ShowDataLabelsOverMaximum](./set_showdatalabelsovermaximum/)(**bool**) override | 設定是否顯示圖表最大值之上的資料標籤。寫入 **bool**。 |
| void [set_Style](./set_style/)([StyleType](../styletype/)) override | 設定圖表樣式。寫入 [StyleType](../styletype/)。 |
| void [set_Type](./set_type/)([ChartType](../charttype/)) override | 設定圖表類型。寫入 [ChartType](../charttype/)。 |
| void [set_Width](../../aspose.slides/shape/set_width/)(**float**) override | 設定形狀的寬度（以點為單位）。寫入 **float**。 |
| void [set_X](../../aspose.slides/shape/set_x/)(**float**) override | 設定形狀左上角的 x 座標（以點為單位）。寫入 **float**。 |
| void [set_Y](../../aspose.slides/shape/set_y/)(**float**) override | 設定形狀左上角的 y 座標（以點為單位）。寫入 **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享引用計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享引用計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並返回共享引用計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 等同於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 敘述的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視器物件。 |
| void [ValidateChartLayout](./validatechartlayout/)() override | 計算圖表元素的實際值。實際值包括實作 [IActualLayout](../iactuallayout/) 介面的元素位置（[IActualLayout::get_ActualX](../iactuallayout/get_actualx/)、[IActualLayout::get_ActualY](../iactuallayout/get_actualy/)、[IActualLayout::get_ActualWidth](../iactuallayout/get_actualwidth/)、[IActualLayout::get_ActualHeight](../iactuallayout/get_actualheight/)）以及實際坐標軸值（[IAxis::get_ActualMaxValue](../iaxis/get_actualmaxvalue/)、[IAxis::get_ActualMinValue](../iaxis/get_actualminvalue/)、[IAxis::get_ActualMajorUnit](../iaxis/get_actualmajorunit/)、[IAxis::get_ActualMinorUnit](../iaxis/get_actualminorunit/)、[IAxis::get_ActualMajorUnitScale](../iaxis/get_actualmajorunitscale/)、[IAxis::get_ActualMinorUnitScale](../iaxis/get_actualminorunitscale/)）。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱引用計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱引用計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | 將 [Shape](../../aspose.slides/shape/) 的內容儲存為 SVG 檔案。 |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | 將 [Shape](../../aspose.slides/shape/) 的內容儲存為 SVG 檔案。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 參見

* 類別 [GraphicalObject](../../aspose.slides/graphicalobject/)
* 類別 [IChart](../ichart/)
* 命名空間 [Aspose::Slides::Charts](../)
* 函式庫 [Aspose.Slides](../../)