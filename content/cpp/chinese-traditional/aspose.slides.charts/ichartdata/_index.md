---
title: IChartData
second_title: Aspose.Slides for C++ API 參考
description: 代表用於圖表繪製的資料。
type: docs
weight: 651
url: /zh-hant/aspose.slides.charts/ichartdata/
---
## IChartData 類別

代表用於圖表繪製的資料。

```cpp
class IChartData : public virtual System::Object
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 並不等於任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 並不等於任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_Categories](./get_categories/)() | 取得主要類別（如果 [IChartData::set_UseSecondaryCategories](./set_usesecondarycategories/) 設為 false，則取得主要與次要類別）。唯讀 [IChartCategoryCollection](../ichartcategorycollection/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_Category](./get_category/)(**int32_t**) | 在指定的索引處返回主要類別。若 [get_UseSecondaryCategories](./get_usesecondarycategories/) 為 false，則在所有類別中取得。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataWorkbook](../ichartdataworkbook/)\> [get_ChartDataWorkbook](./get_chartdataworkbook/)() | 取得用於建立圖表系列或類別之儲存格的工廠。唯讀 [IChartDataWorkbook](../ichartdataworkbook/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) | 在指定的索引處返回系列。 |
| virtual [ChartDataSourceType](../chartdatasourcetype/) [get_DataSourceType](./get_datasourcetype/)() | 代表圖表的資料來源 |
| virtual [WorkbookType](../workbooktype/) [get_EmbeddedWorkbookType](./get_embeddedworkbooktype/)() | 取得嵌入式活頁簿的類型。如果 [IChartData::get_DataSourceType](./get_datasourcetype/) 為 [ChartDataSourceType::ExternalWorkbook](../chartdatasourcetype/)，則返回 [WorkbookType::NotDefined](../workbooktype/)。唯讀 [WorkbookType](../workbooktype/)。 |
| virtual [System::String](../../system/string/) [get_ExternalWorkbookPath](./get_externalworkbookpath/)() | 如果資料來源是外部則代表外部活頁簿路徑（如果資料來源是外部），否則為 null |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_SecondaryCategories](./get_secondarycategories/)() | 如果 [IChartData::get_UseSecondaryCategories](./get_usesecondarycategories/) 為 true，取得次要類別。唯讀 [IChartCategoryCollection](../ichartcategorycollection/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_SecondaryCategory](./get_secondarycategory/)(**int32_t**) | 在指定的索引處返回次要類別。若 [get_UseSecondaryCategories](./get_usesecondarycategories/) 為 false，則 [IChartData::get_SecondaryCategories](./get_secondarycategories/) 為 null。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesCollection](../ichartseriescollection/)\> [get_Series](./get_series/)() | 取得系列。唯讀 [IChartSeriesCollection](../ichartseriescollection/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)([System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\>) |  |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)(**int32_t**) | 在指定的索引處返回系列群組。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroupCollection](../ichartseriesgroupcollection/)\> [get_SeriesGroups](./get_seriesgroups/)() | 取得系列的群組。唯讀 [IChartSeriesGroupCollection](../ichartseriesgroupcollection/)。 |
| virtual **bool** [get_UseSecondaryCategories](./get_usesecondarycategories/)() | 若設定為 false，則 [IChartData::get_SecondaryCategories](./get_secondarycategories/) 返回 null，且 [IChartData::get_Categories](./get_categories/) 中的資料同時用於主要與次要系列。若設定為 true，則 [IChartData::get_SecondaryCategories](./get_secondarycategories/) 中的資料用於次要系列，而 [IChartData::get_Categories](./get_categories/) 中的資料用於主要系列。讀取 **bool**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數器資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的類比。啟用自訂物件的雜湊。 |
| virtual [System::String](../../system/string/) [GetRange](./getrange/)() | 取得圖表資料範圍。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。C# [System.Object.GetType()](../../system/object/gettype/) 呼叫的類比。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。C# 'is' 運算子的類比。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的類比。啟用自訂型別的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構式。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\> [ReadWorkbookStream](./readworkbookstream/)() | 將內部包含的 [Excel](../../aspose.slides.excel/) 活頁簿寫入記憶體中串流。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 針對字串與 nullptr 情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 針對字串情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共用參考計數減少指定的數值。 |
| virtual void [set_UseSecondaryCategories](./set_usesecondarycategories/)(**bool**) | 若設定為 false，則 [IChartData::get_SecondaryCategories](./get_secondarycategories/) 返回 null，且 [IChartData::get_Categories](./get_categories/) 中的資料同時用於主要與次要系列。若設定為 true，則 [IChartData::get_SecondaryCategories](./get_secondarycategories/) 中的資料用於次要系列，而 [IChartData::get_Categories](./get_categories/) 中的資料用於主要系列。寫入 **bool**。 |
| virtual void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/)) | 將外部活頁簿設定為圖表的資料來源。[Chart](../chart/) 資料將從目標活頁簿更新。 |
| virtual void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/), **bool**) | 將外部活頁簿設定為圖表的資料來源。 |
| virtual void [SetRange](./setrange/)([System::String](../../system/string/)) | 設定圖表資料範圍。系列與類別將根據新資料範圍更新。若資料範圍中的系列數量大於圖表資料中的系列數量，則會在集合的末端新增與最後一個系列相同類型的額外系列。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共用指標）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共用參考計數器的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共用參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並返回共用參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual void [SwitchRowColumn](./switchrowcolumn/)() | 交換軸向資料。原本在 X 軸繪製的資料將移至 Y 軸，反之亦然。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的類比。啟用自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual void [WriteWorkbookStream](./writeworkbookstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\>) | 以使用者指定的值初始化內部包含的 [Excel](../../aspose.slides.excel/) 活頁簿。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另請參閱

* 類別 [Object](../../system/object/)
* 命名空間 [Aspose::Slides::Charts](../)
* 程式庫 [Aspose.Slides](../../)