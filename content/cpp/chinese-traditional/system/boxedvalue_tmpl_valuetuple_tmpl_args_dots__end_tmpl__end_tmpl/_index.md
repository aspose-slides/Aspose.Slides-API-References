---
title: BoxedValue< ValueTuple< Args... > >
second_title: Aspose.Slides for C++ API 參考
description: 值元組的裝箱版本。
type: docs
weight: 118
url: /zh-hant/system/boxedvalue_tmpl_valuetuple_tmpl_args_dots__end_tmpl__end_tmpl/
---
## BoxedValue< ValueTuple< Args... > > 類別


值元組的裝箱版本。

```cpp
template<typename...>class BoxedValue< ValueTuple< Args... > > : public System::Runtime::CompilerServices::ITuple
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| name | Args 元組元素類型。 |
## 方法

| 方法 | 說明 |
| --- | --- |
|  [BoxedValue](./boxedvalue/)(const [ValueT](../valuetuple/)\&) | 建構一個代表指定值已裝箱的 [BoxedValue](../boxedvalue/) 物件。 |
| **bool** [Equals](./equals/)([ptr](../object/ptr/)) override | 確定目前物件與指定物件所代表的已裝箱值的相等性。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989 NaN 與任何值（包括 NaN）皆不相等。 |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989 NaN 與任何值（包括 NaN）皆不相等。 |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | 取得與物件相關聯的參考計數器資料結構。 |
| int [GetHashCode](./gethashcode/)() const override | 傳回目前物件的雜湊碼。 |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | 取得物件的實際類型。 |
| virtual [SharedPtr](../sharedptr/)\<[Object](../object/)\> [idx_get](../../system.runtime.compilerservices/ituple/idx_get/)(**int32_t**) const | 傳回位於 index 位置的元素。 |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。類似 C# 的 'is' 運算子。 |
| **bool** [is](./is/)() const | 判斷目前物件所代表的已裝箱值之類型是否為 **V**。 |
| void [Lock](../object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../lockcontext/) 監視物件。 |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | 類似 C# [Object.MemberwiseClone()](../object/memberwiseclone/) 方法。啟用自訂型別的克隆。 |
|  [Object](../object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../object/object/)([Object](../object/) const\&) | 複製建構函式。實際上不會複製任何東西，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | 指派運算子。實際上不會複製任何東西，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/) 在字串與 nullptr 情況的特化。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/) 在字串情況的特化。 |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | 將共享參考計數降低指定的值。 |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../object/sharedcount/)() const | 取得共享參考計數器的目前值。 |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | 遞減並傳回共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| [String](../string/) [ToString](./tostring/)() const override | 傳回已裝箱值的字串表示形式。 |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | 實作 C# typeof([System.Object](../object/)) 結構。 |
| const [ValueT](../valuetuple/)\& [unbox](./unbox/)() const | 解除已裝箱的值。 |
| void [Unlock](../object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另見

* 類別 [ITuple](../../system.runtime.compilerservices/ituple/)
* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)