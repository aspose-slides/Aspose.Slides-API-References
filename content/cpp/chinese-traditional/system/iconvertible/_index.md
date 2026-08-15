---
title: IConvertible
second_title: Aspose.Slides for C++ API 參考
description: "定義將實作的參考型別或值型別之值轉換為具有等價值的通用語言執行時類型的方法。此類別的物件應僅使用 System::MakeObject() 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裹在 System::SmartPtr 指標中，並使用此指標將其作為參數傳遞給函式。"
type: docs
weight: 937
url: /zh-hant/system/iconvertible/
---
## IConvertible 類別

定義將實作的參考型別或值型別之值轉換為具有等價值的通用語言執行時類型的方法。此類別的物件應僅使用 [System::MakeObject()](../makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為這會導致執行時錯誤和/或斷言失敗。請始終將此類別包裹在 [System::SmartPtr](../smartptr/) 指標中，並使用此指標將其作為參數傳遞給函式。

```cpp
class IConvertible : public virtual System::Object
```

## 方法

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | 使用 C# [Object.Equals](../object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部用途。 |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | 取得與物件關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../object/gethashcode/) 方法。啟用自訂物件的雜湊功能。 |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../object/gettype/) 呼叫。 |
| virtual [System::TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() | 傳回此實例的型別代碼。 |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | 檢查物件是否為 targetType 所描述型別的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../lockcontext/) 監視器物件。 |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../object/memberwiseclone/) 方法。啟用自訂型別的克隆。 |
|  [Object](../object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../object/object/)([Object](../object/) const\&) | 複製建構函式。實際上不複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | 賦值運算子。實際上不複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | 針對字串與 nullptr 情況的 [Object::ReferenceEquals](../object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | 針對字串情況的 [Object::ReferenceEquals](../object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../object/sharedcount/)() const | 取得共享參考計數的當前值。 |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual **bool** [ToBoolean](./toboolean/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 使用指定的文化特定格式資訊，將此實例的值轉換為等價的 [Boolean](../boolean/) 值。 |
| virtual **uint8_t** [ToByte](./tobyte/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 使用指定的文化特定格式資訊，將此實例的值轉換為等價的 8 位元 uint32_teger。 |
| virtual char_t [ToChar](./tochar/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 使用指定的文化特定格式資訊，將此實例的值轉換為等價的 Unicode 字元。 |
| virtual [System::DateTime](../datetime/) [ToDateTime](./todatetime/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 使用指定的文化特定格式資訊，將此實例的值轉換為等價的 [System::DateTime](../datetime/)。 |
| virtual [System::Decimal](../decimal/) [ToDecimal](./todecimal/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 使用指定的文化特定格式資訊，將此實例的值轉換為等價的 [System::Decimal](../decimal/) 數字。 |
| virtual **double** [ToDouble](./todouble/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 使用指定的文化特定格式資訊，將此實例的值轉換為等價的雙精度浮點數。 |
| virtual **int16_t** [ToInt16](./toint16/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 使用指定的文化特定格式資訊，將此實例的值轉換為等價的 16 位元有號整數。 |
| virtual **int32_t** [ToInt32](./toint32/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 使用指定的文化特定格式資訊，將此實例的值轉換為等價的 32 位元有號整數。 |
| virtual **int64_t** [ToInt64](./toint64/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 使用指定的文化特定格式資訊，將此實例的值轉換為等價的 64 位元有號整數。 |
| virtual **int8_t** [ToSByte](./tosbyte/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 使用指定的文化特定格式資訊，將此實例的值轉換為等價的 8 位元有號整數。 |
| virtual **float** [ToSingle](./tosingle/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 使用指定的文化特定格式資訊，將此實例的值轉換為等價的單精度浮點數。 |
| virtual [System::String](../string/) [ToString](./tostring/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 使用指定的文化特定格式資訊，將此實例的值轉換為等價的 [System::String](../string/)。 |
| virtual [String](../string/) [ToString](./tostring/)() const | 相當於 C# [Object.ToString()](../object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| virtual [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\> [ToType](./totype/)(const [TypeInfo](../typeinfo/)\&, [System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 使用指定的文化特定格式資訊，將此實例的值轉換為指定 System::Type 的等價 [System::Object](../object/)。 |
| virtual **uint16_t** [ToUInt16](./touint16/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 使用指定的文化特定格式資訊，將此實例的值轉換為等價的 16 位元 uint32_teger。 |
| virtual **uint32_t** [ToUInt32](./touint32/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 使用指定的文化特定格式資訊，將此實例的值轉換為等價的 32 位元 uint32_teger。 |
| virtual **uint64_t** [ToUInt64](./touint64/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 使用指定的文化特定格式資訊，將此實例的值轉換為等價的 64 位元 uint32_teger。 |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | 實作 C# typeof([System.Object](../object/)) 構造式。 |
| void [Unlock](../object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../lockcontext/) 監視器物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 相關參考

* 類別 [Object](../object/)
* 命名空間 [System](../)
* Library [Aspose.Slides](../../)