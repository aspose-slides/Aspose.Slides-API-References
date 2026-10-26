---
title: IChartSeriesGroup
second_title: Aspose.Slides 用於 C++ 的 API 參考
description: 表示系列的群組。
type: docs
weight: 846
url: /zh-hant/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup 類別


表示系列的群組。

```cpp
class IChartSeriesGroup : public Aspose::Slides::Charts::IChartComponent
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 比較物件時使用 C# [Object.Equals](../../system/object/equals/) 語意。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點數比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點數比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() | 指定泡泡圖上泡泡大小值的表示方式。讀取 [BubbleSizeRepresentationType](../bubblesizerepresentationtype/)。 |
| virtual **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() | 指定泡泡圖的比例因子（可在預設大小的 0% 到 300% 之間）。讀取 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | 傳回圖表。唯讀 [IChart](../ichart/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) | 傳回群組中指定索引的圖表系列。 |
| virtual **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() | 指定甜甜圈圖中孔的大小（可在繪圖區域大小的 10% 到 90% 之間）。讀取 **uint8_t**。 |
| virtual **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() | 取得第一個餅或甜甜圈圖切片的角度（以度為單位，從上方順時針，0 到 360 度）。讀取 **uint16_t**。 |
| virtual **uint16_t** [get_GapDepth](./get_gapdepth/)() | 傳回 3D 圖表中資料系列之間的距離，以標記寬度的百分比表示。讀取 **uint16_t**。 |
| virtual **uint16_t** [get_GapWidth](./get_gapwidth/)() | 指定條形或柱狀叢集之間的間距，以條形或柱狀寬度的百分比表示。讀取 **uint16_t**。 |
| virtual **bool** [get_HasSeriesLines](./get_hasserieslines/)() | 如果圖表具有系列線則為 true。適用於堆疊條形圖和 OfPie 圖表。讀取 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() | 指定 HiLowLines 格式。HiLowLines 應用於 HiLowClose、OpenHiLowClose、VolumeHiLowClose 以及 VolumeOpenHiLowClose 圖表類型。 |
| virtual **bool** [get_IsColorVaried](./get_iscolorvaried/)() | 指定系列中的每個資料標記具有不同的顏色。讀取 **bool**。 |
| virtual **int8_t** [get_Overlap](./get_overlap/)() | 指定條形和柱狀在 2-D 圖表上的重疊程度，以百分比表示（從 -100% 到 100%）。 |
| virtual [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() | 指定如何決定在 pie-of-pie 或 bar-of-pie 圖表中哪些資料點屬於第二個餅或條。讀取 [PieSplitType](../piesplittype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) | 針對具有自訂分割的 pie-of-pie 或 bar-of-pie 圖表的自訂分割資訊。依索引傳回應在第二個餅或條中繪製的資料點。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() | 針對具有自訂分割的 pie-of-pie 或 bar-of-pie 圖表的自訂分割資訊。包含應在第二個餅或條中繪製的資料點。唯讀 [IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)。 |
| virtual **double** [get_PieSplitPosition](./get_piesplitposition/)() | 指定用於決定在 pie-of-pie 或 bar-of-pie 圖表中哪些資料點屬於第二個餅或條的值。與 PieSplitBy 屬性一起使用。讀取 **double**。 |
| virtual **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() | 指示此群組的系列是否繪製於次坐標軸。唯讀 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | 傳回簡報。唯讀 [IPresentation](../../aspose.slides/ipresentation/)。 |
| virtual **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() | 指定 pie-of-pie 或 bar-of-pie 圖表中第二個餅或條的大小，以第一個餅的大小百分比表示（可在 5% 到 200% 之間）。讀取 **uint16_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() | 傳回圖表系列的唯讀集合。唯讀 [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | 傳回基礎投影片。唯讀 [IBaseSlide](../../aspose.slides/ibaseslide/)。 |
| virtual [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() | 傳回此系列群組的類型。唯讀 [CombinableSeriesTypesGroup](../combinableseriestypesgroup/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() | 提供存取折線圖或股票圖的上/下條。唯讀 [IUpDownBarsManager](../iupdownbarsmanager/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) | 取得指定索引處的元素。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷貝建構函式。實際上不會複製任何內容，只是初始化新物件並允許子類別的拷貝建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的拷貝建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，適用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，適用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共用參考計數減少指定的值。 |
| virtual void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) | 指定泡泡圖上泡泡大小值的表示方式。寫入 [BubbleSizeRepresentationType](../bubblesizerepresentationtype/)。 |
| virtual void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) | 指定泡泡圖的比例因子（可在預設大小的 0% 到 300% 之間）。寫入 **int32_t**。 |
| virtual void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) | 指定甜甜圈圖中孔的大小（可在繪圖區域大小的 10% 到 90% 之間）。寫入 **uint8_t**。 |
| virtual void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) | 設定第一個餅或甜甜圈圖切片的角度（以度為單位，從上方順時針，0 到 360 度）。寫入 **uint16_t**。 |
| virtual void [set_GapDepth](./set_gapdepth/)(**uint16_t**) | 設定 3D 圖表中資料系列之間的距離，以標記寬度的百分比表示。寫入 **uint16_t**。 |
| virtual void [set_GapWidth](./set_gapwidth/)(**uint16_t**) | 指定條形或柱狀叢集之間的間距，以條形或柱狀寬度的百分比表示。寫入 **uint16_t**。 |
| virtual void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) | 如果圖表具有系列線則為 true。適用於堆疊條形圖和 OfPie 圖表。寫入 **bool**。 |
| virtual void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) | 指定系列中的每個資料標記具有不同的顏色。寫入 **bool**。 |
| virtual void [set_Overlap](./set_overlap/)(**int8_t**) | 指定條形和柱狀在 2-D 圖表上的重疊程度，以百分比表示（從 -100% 到 100%）。 |
| virtual void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) | 指定如何決定在 pie-of-pie 或 bar-of-pie 圖表中哪些資料點屬於第二個餅或條。寫入 [PieSplitType](../piesplittype/)。 |
| virtual void [set_PieSplitPosition](./set_piesplitposition/)(**double**) | 指定用於決定在 pie-of-pie 或 bar-of-pie 圖表中哪些資料點屬於第二個餅或條的值。與 PieSplitBy 屬性一起使用。寫入 **double**。 |
| virtual void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) | 指定 pie-of-pie 或 bar-of-pie 圖表中第二個餅或條的大小，以第一個餅的大小百分比表示（可在 5% 到 200% 之間）。寫入 **uint16_t**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共用參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共用參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共用參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 備註


1) 請參閱 ChartSeriesGroupCollection 類別與 CombinableSeriesTypesGroup 列舉的摘要與備註。2) 系列群組包含一些對群組中每個系列皆通用的系列屬性（「系列群組屬性」）。[ChartSeriesGroup](../chartseriesgroup/) 類別中的「系列群組屬性」是讀寫的。每個「系列群組屬性」在 [ChartSeries](../chartseries/) 類別中可以有唯讀的投影。 

## 另請參閱

* 類別 [IChartComponent](../ichartcomponent/)
* 命名空間 [Aspose::Slides::Charts](../)
* 函式庫 [Aspose.Slides](../../)