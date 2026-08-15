---
title: ColorMatrix
second_title: Aspose.Slides for C++ API 參考文件
description: "表示一個 5x5 矩陣，包含 RGBAW 色彩空間的座標。此類別的物件應僅使用 System::MakeObject() 函式配置。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別封裝在 System::SmartPtr 指標中，並使用該指標將其作為參數傳遞給函式。"
type: docs
weight: 27
url: /zh-hant/system.drawing.imaging/colormatrix/
---
## ColorMatrix 類別

表示一個 5x5 矩陣，包含 RGBAW 色彩空間的座標。此類別的物件應僅使用 [System::MakeObject()](../../system/makeobject/) 函式配置。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別封裝在 [System::SmartPtr](../../system/smartptr/) 指標中，並使用該指標將其作為參數傳遞給函式。

```cpp
class ColorMatrix : public System::Object
```

## 方法

| 方法 | 說明 |
| --- | --- |
|  [ColorMatrix](./colormatrix/)() | 建構新的 [ColorMatrix](./) 類別實例，並以單位矩陣的值進行初始化。 |
|  [ColorMatrix](./colormatrix/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::ArrayPtr](../../system/arrayptr/)\<**float**\>\>\&) | 建構新的 [ColorMatrix](./) 類別實例，並以指定的值進行初始化。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模仿 C# 風格的浮點比較，將兩個 NaN 視為相等，即使依 IEC 60559:1989 規範 NaN 不等於任何值（包括 NaN）。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模仿 C# 風格的浮點比較，將兩個 NaN 視為相等，即使依 IEC 60559:1989 規範 NaN 不等於任何值（包括 NaN）。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| **float** [get_Matrix00](./get_matrix00/)() const | 取得第 0 列第 0 欄的值。 |
| **float** [get_Matrix01](./get_matrix01/)() const | 取得第 0 列第 1 欄的值。 |
| **float** [get_Matrix02](./get_matrix02/)() const | 取得第 0 列第 2 欄的值。 |
| **float** [get_Matrix03](./get_matrix03/)() const | 取得第 0 列第 3 欄的值。 |
| **float** [get_Matrix04](./get_matrix04/)() const | 取得第 0 列第 4 欄的值。 |
| **float** [get_Matrix10](./get_matrix10/)() const | 取得第 1 列第 0 欄的值。 |
| **float** [get_Matrix11](./get_matrix11/)() const | 取得第 1 列第 1 欄的值。 |
| **float** [get_Matrix12](./get_matrix12/)() const | 取得第 1 列第 2 欄的值。 |
| **float** [get_Matrix13](./get_matrix13/)() const | 取得第 1 列第 3 欄的值。 |
| **float** [get_Matrix14](./get_matrix14/)() const | 取得第 1 列第 4 欄的值。 |
| **float** [get_Matrix20](./get_matrix20/)() const | 取得第 2 列第 0 欄的值。 |
| **float** [get_Matrix21](./get_matrix21/)() const | 取得第 2 列第 1 欄的值。 |
| **float** [get_Matrix22](./get_matrix22/)() const | 取得第 2 列第 2 欄的值。 |
| **float** [get_Matrix23](./get_matrix23/)() const | 取得第 2 列第 3 欄的值。 |
| **float** [get_Matrix24](./get_matrix24/)() const | 取得第 2 列第 4 欄的值。 |
| **float** [get_Matrix30](./get_matrix30/)() const | 取得第 3 列第 0 欄的值。 |
| **float** [get_Matrix31](./get_matrix31/)() const | 取得第 3 列第 1 欄的值。 |
| **float** [get_Matrix32](./get_matrix32/)() const | 取得第 3 列第 2 欄的值。 |
| **float** [get_Matrix33](./get_matrix33/)() const | 取得第 3 列第 3 欄的值。 |
| **float** [get_Matrix34](./get_matrix34/)() const | 取得第 3 列第 4 欄的值。 |
| **float** [get_Matrix40](./get_matrix40/)() const | 取得第 4 列第 0 欄的值。 |
| **float** [get_Matrix41](./get_matrix41/)() const | 取得第 4 列第 1 欄的值。 |
| **float** [get_Matrix42](./get_matrix42/)() const | 取得第 4 列第 2 欄的值。 |
| **float** [get_Matrix43](./get_matrix43/)() const | 取得第 4 列第 3 欄的值。 |
| **float** [get_Matrix44](./get_matrix44/)() const | 取得第 4 列第 4 欄的值。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的類似實作。支援自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| **float** [idx_get](./idx_get/)(int, int) | 於指定的列與欄取得值。 |
| **float** [idx_set](./idx_set/)(int, int, **float**) | 在矩陣的指定位置設定指定值。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為目標類型的實例。相當於 C# 的 `is` 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定行為。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監護物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的類似實作。支援自訂類型的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 以指定值減少共享參考計數。 |
| void [set_Matrix00](./set_matrix00/)(**float**) | 設定第 0 列第 0 欄的值。 |
| void [set_Matrix01](./set_matrix01/)(**float**) | 設定第 0 列第 1 欄的值。 |
| void [set_Matrix02](./set_matrix02/)(**float**) | 設定第 0 列第 2 欄的值。 |
| void [set_Matrix03](./set_matrix03/)(**float**) | 設定第 0 列第 3 欄的值。 |
| void [set_Matrix04](./set_matrix04/)(**float**) | 設定第 0 列第 4 欄的值。 |
| void [set_Matrix10](./set_matrix10/)(**float**) | 設定第 1 列第 0 欄的值。 |
| void [set_Matrix11](./set_matrix11/)(**float**) | 設定第 1 列第 1 欄的值。 |
| void [set_Matrix12](./set_matrix12/)(**float**) | 設定第 1 列第 2 欄的值。 |
| void [set_Matrix13](./set_matrix13/)(**float**) | 設定第 1 列第 3 欄的值。 |
| void [set_Matrix14](./set_matrix14/)(**float**) | 設定第 1 列第 4 欄的值。 |
| void [set_Matrix20](./set_matrix20/)(**float**) | 設定第 2 列第 0 欄的值。 |
| void [set_Matrix21](./set_matrix21/)(**float**) | 設定第 2 列第 1 欄的值。 |
| void [set_Matrix22](./set_matrix22/)(**float**) | 設定第 2 列第 2 欄的值。 |
| void [set_Matrix23](./set_matrix23/)(**float**) | 設定第 2 列第 3 欄的值。 |
| void [set_Matrix24](./set_matrix24/)(**float**) | 設定第 2 列第 4 欄的值。 |
| void [set_Matrix30](./set_matrix30/)(**float**) | 設定第 3 列第 0 欄的值。 |
| void [set_Matrix31](./set_matrix31/)(**float**) | 設定第 3 列第 1 欄的值。 |
| void [set_Matrix32](./set_matrix32/)(**float**) | 設定第 3 列第 2 欄的值。 |
| void [set_Matrix33](./set_matrix33/)(**float**) | 設定第 3 列第 3 欄的值。 |
| void [set_Matrix34](./set_matrix34/)(**float**) | 設定第 3 列第 4 欄的值。 |
| void [set_Matrix40](./set_matrix40/)(**float**) | 設定第 4 列第 0 欄的值。 |
| void [set_Matrix41](./set_matrix41/)(**float**) | 設定第 4 列第 1 欄的值。 |
| void [set_Matrix42](./set_matrix42/)(**float**) | 設定第 4 列第 2 欄的值。 |
| void [set_Matrix43](./set_matrix43/)(**float**) | 設定第 4 列第 3 欄的值。 |
| void [set_Matrix44](./set_matrix44/)(**float**) | 設定第 4 列第 4 欄的值。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享指標）。允許在容器中將指標切換至弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得當前的共享參考計數值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 減少並返回共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的類似實作。支援將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖行為。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監護物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 減少弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另請參閱

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.Slides](../../)