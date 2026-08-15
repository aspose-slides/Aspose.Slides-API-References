---
title: "System::TestPredicates::TypeTraits"
second_title: Aspose.Slides for C++ API 參考
description: 
type: docs
weight: 963
url: /zh-hant/system.testpredicates.typetraits/
---
## 結構

| 結構 | 說明 |
| --- | --- |
| [has_data_method](./has_data_method/) | 檢查類型是否具有 data() 方法。如果有，繼承 std::true_type，否則繼承 std::false_type。 |
| [has_data_method< System::Collections::BitArray, void >](./has_data_method_tmpl_system_collections_bitarray__void__end_tmpl/) | 對 BitArray 類型的特化，提供在此不可存取的 boost 類型。 |
| [has_print_to_method](./has_print_to_method/) | 檢查 PrintTo 函式是否有接受給定類型作為第一個參數的重載。如果存在重載，繼承 std::true_type，否則繼承 std::false_type。 |
| [IsCppContainer](./iscppcontainer/) | 檢查特定類型是否為 STL 風格的容器。為此，檢查 iterator 與 const_iterator 成員類型的存在性。如果兩者皆存在，繼承 std::true_type，否則繼承 std::false_type。 |
| [IsEnumerable](./isenumerable/) | 檢查類型是否具有 [System::Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/) 特化作為基礎類型。如果是，value 成員被設為 true，否則設為 false。 |
| [LargestFPType](./largestfptype/) | 提供所提供的最長浮點型別的別名。會忽略非浮點型別。 |

## 型別別名

| 型別別名 | 說明 |
| --- | --- |
| [AreFPandArithmetic](./arefpandarithmetic/) | 檢查 **T1** 為算術型別且 **T2** 為浮點型別，或相反。若符合，將 value 成員設為 true，否則為 false。 |
| [AnyOfDecimal](./anyofdecimal/) | 檢查至少有一個型別參數是 [System::Decimal](../system/decimal/)。若是，將 value 成員設為 true，否則為 false。 |
| [IsArray](./isarray/) | 檢查類型是否為 [System::Array](../system/array/) 的特化。如果是，value 成員被設為 true，否則設為 false。 |
| [IsList](./islist/) | 檢查類型是否為 [System::Collections::Generic::List](../system.collections.generic/list/) 的特化。如果是，value 成員被設為 true，否則設為 false。 |
| [BothArrayOrList](./botharrayorlist/) | 檢查兩個型別參數是否皆為陣列或列表。若是，value 成員被設為 true，否則設為 false。 |
| [BothEnumerable](./bothenumerable/) | 檢查兩個型別參數是否皆為 IEnumerable。若是，value 成員被設為 true，否則設為 false。 |