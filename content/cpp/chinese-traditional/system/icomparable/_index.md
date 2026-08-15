---
title: IComparable
second_title: Aspose.Slides for C++ API 參考
description: "定義一個比較兩個物件的方法。此類別的物件只能透過 System::MakeObject() 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤與/或斷言失敗。請始終將此類別包裝成 System::SmartPtr 指標，並使用該指標作為參數傳遞給函式。"
type: docs
weight: 924
url: /zh-hant/system/icomparable/
---
## IComparable 類別


Defines a method that compares two objects. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename T>class IComparable : public virtual System::Object
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | The type of the objects with which the current object gets compared |
## 方法

| 方法 | 說明 |
| --- | --- |
| virtual int [CompareTo](./compareto/)(T) | 比較目前物件與指定的物件。 |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | 使用 C# [Object.Equals](../object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | 取得與物件關聯的引用計數資料結構。 |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../object/gettype/) 呼叫。 |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../lockcontext/) 監視物件。 |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../object/memberwiseclone/) 方法。啟用自訂型別的克隆。 |
|  [Object](../object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../object/object/)([Object](../object/) const\&) | 拷貝建構子。實際上不會拷貝任何東西，只會初始化新物件並允許子類別的拷貝建構。 |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | 指定運算子。實際上不會拷貝任何東西，只會初始化新物件並允許子類別的拷貝建構。 |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/) 在字串與 nullptr 情況下的特化。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/) 在字串情況下的特化。 |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | 將共享參考計數減少指定的數值。 |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | 将第 n 個模板參數設為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../object/sharedcount/)() const | 取得共享參考計數器的目前值。 |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | 遞減並返回共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../string/) [ToString](../object/tostring/)() const | 相當於 C# [Object.ToString()](../object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | 實作 C# typeof([System.Object](../object/)) 結構。 |
| void [Unlock](../object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另見

* 類別 [Object](../object/)
* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)