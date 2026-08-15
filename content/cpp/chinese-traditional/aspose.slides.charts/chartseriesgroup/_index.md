---
title: ChartSeriesGroup
second_title: Aspose.Slides for C++ API 參考
description: 表示系列的群組。
type: docs
weight: 300
url: /zh-hant/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup 類別

表示系列的群組。

```cpp
class ChartSeriesGroup : public Aspose::Slides::Charts::IChartSeriesGroup,
                         public Aspose::Slides::IDOMObject
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
| [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() override | 指定氣泡圖上氣泡大小值的表示方式。閱讀 [BubbleSizeRepresentationType](../bubblesizerepresentationtype/)。 |
| **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() override | 指定氣泡圖的縮放係數（可在預設大小的 0% 到 300% 之間）。閱讀 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | 返回父圖表。唯讀 [IChart](../ichart/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) override | 返回群組中指定索引的圖表系列。 |
| **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() override | 指定環形圖中洞的大小（可在繪圖區大小的 0% 到 90% 之間）。閱讀 **uint8_t**。 |
| **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() override | 取得第一個餅圖或環形圖切片的角度，單位為度（由上方順時針，0 到 360 度）。閱讀 **uint16_t**。 |
| **uint16_t** [get_GapDepth](./get_gapdepth/)() override | 返回 3D 圖表中資料系列之間的距離，作為標記寬度的百分比。閱讀 **uint16_t**。 |
| **uint16_t** [get_GapWidth](./get_gapwidth/)() override | 指定條形或柱狀叢集之間的間距，作為條形或柱狀寬度的百分比。閱讀 **uint16_t**。 |
| **bool** [get_HasSeriesLines](./get_hasserieslines/)() override | 若圖表具有系列線則為 true。適用於堆疊條形圖和 OfPie 圖表。閱讀 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() override | 指定 HiLowLines 格式。HiLowLines 適用於 HiLowClose、OpenHiLowClose、VolumeHiLowClose 和 VolumeOpenHiLowClose 圖表類型。 |
| **bool** [get_IsColorVaried](./get_iscolorvaried/)() override | 指定系列中的每個資料標記具有不同的顏色。閱讀 **bool**。 |
| **int8_t** [get_Overlap](./get_overlap/)() override | 指定條形和柱狀在 2D 圖表上的重疊程度，作為百分比（從 -100% 到 100%）。 |
| [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() override | 指定如何判斷哪個資料點位於 pie-of-pie 或 bar-of-pie 圖表的第二個餅或條。閱讀 [PieSplitType](../piesplittype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) override | 自訂分割資訊，用於具有自訂分割的 pie-of-pie 或 bar-of-pie 圖表。根據索引返回應繪製於第二個餅或條的資料點。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() override | 自訂分割資訊，用於具有自訂分割的 pie-of-pie 或 bar-of-pie 圖表。包含應繪製於第二個餅或條的資料點。唯讀 [PieSplitCustomPointCollection](../piesplitcustompointcollection/)。 |
| **double** [get_PieSplitPosition](./get_piesplitposition/)() override | 指定用於判斷哪個資料點位於 pie-of-pie 或 bar-of-pie 圖表第二個餅或條的值。與 PieSplitBy 屬性一起使用。閱讀 **double**。 |
| **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() override | 指示此群組的系列是否繪製於次要軸上。唯讀 **bool**。 |
| **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() override | 指定 pie-of-pie 或 bar-of-pie 圖表第二個餅或條的大小，作為第一個餅大小的百分比（可在 5% 到 200% 之間）。閱讀 **uint16_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() override | 返回系列的集合。唯讀 [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)。 |
| [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() override | 返回此系列群組的類型。唯讀 [CombinableSeriesTypesGroup](../combinableseriestypesgroup/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() override | 提供對折線圖或股價圖的上/下條的存取。唯讀 [IUpDownBarsManager](../iupdownbarsmanager/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數器資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) override | 取得指定索引處的元素。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否代表 targetType 所描述的型別實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷貝建構函式。實際上不會拷貝任何東西，只是初始化新物件並允許子類別的拷貝建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會拷貝任何東西，只是初始化新物件並允許子類別的拷貝建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化版本，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化版本，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) override | 指定氣泡圖上氣泡大小值的表示方式。寫入 [BubbleSizeRepresentationType](../bubblesizerepresentationtype/)。 |
| void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) override | 指定氣泡圖的縮放係數（可在預設大小的 0% 到 300% 之間）。寫入 **int32_t**。 |
| void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) override | 指定環形圖中洞的大小（可在繪圖區大小的 0% 到 90% 之間）。寫入 **uint8_t**。 |
| void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) override | 設定第一個餅圖或環形圖切片的角度，單位為度（由上方順時針，0 到 360 度）。寫入 **uint16_t**。 |
| void [set_GapDepth](./set_gapdepth/)(**uint16_t**) override | 設定 3D 圖表中資料系列之間的距離，作為標記寬度的百分比。寫入 **uint16_t**。 |
| void [set_GapWidth](./set_gapwidth/)(**uint16_t**) override | 指定條形或柱狀叢集之間的間距，作為條形或柱狀寬度的百分比。寫入 **uint16_t**。 |
| void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) override | 若圖表具有系列線則為 true。適用於堆疊條形圖和 OfPie 圖表。寫入 **bool**。 |
| void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) override | 指定系列中的每個資料標記具有不同的顏色。寫入 **bool**。 |
| void [set_Overlap](./set_overlap/)(**int8_t**) override | 指定條形和柱狀在 2-D 圖表上的重疊程度，作為百分比（從 -100% 到 100%）。 |
| void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) override | 指定如何判斷哪個資料點位於 pie-of-pie 或 bar-of-pie 圖表的第二個餅或條。寫入 [PieSplitType](../piesplittype/)。 |
| void [set_PieSplitPosition](./set_piesplitposition/)(**double**) override | 指定用於判斷哪個資料點位於 pie-of-pie 或 bar-of-pie 圖表第二個餅或條的值。與 PieSplitBy 屬性一起使用。寫入 **double**。 |
| void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) override | 指定 pie-of-pie 或 bar-of-pie 圖表第二個餅或條的大小，作為第一個餅大小的百分比（可在 5% 到 200% 之間）。寫入 **uint16_t**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數器的當前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並返回共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 備註

1) 請參閱 ChartSeriesGroupCollection 類別和 CombinableSeriesTypesGroup 列舉的摘要與備註。  
2) 系列群組包含一些對群組中每個系列共通的系列屬性（「series group properties」）。[ChartSeriesGroup](./) 類別中的「Series group properties」為可讀寫。每個「Series group properties」在 [ChartSeries](../chartseries/) 類別中可以有唯讀的投影。

## 另見

* 類別 [IChartSeriesGroup](../ichartseriesgroup/)
* 類別 [IDOMObject](../../aspose.slides/idomobject/)
* 命名空間 [Aspose::Slides::Charts](../)
* 程式庫 [Aspose.Slides](../../)