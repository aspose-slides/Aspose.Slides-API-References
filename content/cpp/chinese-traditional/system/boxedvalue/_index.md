---
title: BoxedValue
second_title: Aspose.Slides for C++ API 參考
description: "表示一個裝箱值。此類別的物件應僅使用 System::MakeObject() 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 System::SmartPtr 指標，並使用該指標作為參數傳遞給函式。"
type: docs
weight: 105
url: /zh-hant/system/boxedvalue/
---
## BoxedValue 類別

表示一個裝箱值。此類別的物件應僅透過 [System::MakeObject()](../makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 [System::SmartPtr](../smartptr/) 指標，並使用該指標作為參數傳遞給函式。

```cpp
template<class T>class BoxedValue : public System::BoxedValueBase,
                                    public std::conditional_t<BoxedValueDetail::ImplementsInterface_v<T, IComparable<T>>, BoxedValueDetail::Comparable<T, BoxedValue<T>>, BoxedValueDetail::NonComparable>
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | Type of the boxed value represented by the class |

## 方法

| 方法 | 描述 |
| --- | --- |
|  [BoxedValue](./boxedvalue/)(const T\&) | 建構一個物件，用於表示已裝箱的指定值。 |
| **bool** [Equals](./equals/)([ptr](../object/ptr/)) override | 判斷目前物件與指定物件所表示的裝箱值是否相等。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考類型物件。 |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值（包括 NaN）。 |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值（包括 NaN）。 |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | 取得與該物件相關聯的參考計數資料結構。 |
| int [GetHashCode](./gethashcode/)() const override | 傳回目前物件的雜湊碼。 |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | 取得物件的實際類型。 |
| [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() const override | 傳回代表目前物件所表示的裝箱值類型的值。 |
| **uint64_t** [GetUnsignedLongLongValue](./getunsignedlonglongvalue/)() const override | 如果可以轉型，傳回裝箱物件的數值；否則傳回零。 |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | 檢查物件是否代表 targetType 所描述的型別實例。相當於 C# 的 'is' 運算子。 |
| **bool** [is](./is/)() const | 判斷目前物件所表示的裝箱值類型是否為 **V**。 |
| **bool** [IsBoxedEnum](./isboxedenum/)() override | 判斷目前物件是否代表列舉型別的裝箱值。 |
| void [Lock](../object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../lockcontext/) 守護物件。 |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../object/memberwiseclone/) 方法。啟用自訂類型的克隆。 |
|  [Object](../object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../object/object/)([Object](../object/) const\&) | 拷貝建構子。實際上不拷貝任何內容，只是初始化新物件並允許子類別的拷貝建構。 |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | 指派運算子。實際上不拷貝任何內容，只是初始化新物件並允許子類別的拷貝建構。 |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../boxedvaluebase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | 將指定列舉中具有指定名稱的列舉常數值裝箱。一個參數指定在解讀表示列舉常數名稱的字串時是否忽略大小寫。 |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../boxedvaluebase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&) | 將指定列舉中具有指定名稱的列舉常數值裝箱。 |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型物件與 nullptr。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/) 在字串與 nullptr 情況下的特殊化。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/) 在字串情況下的特殊化。 |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../object/sharedcount/)() const | 取得共享參考計數器的目前值。 |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | 遞減並傳回共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| [String](../string/) [ToString](./tostring/)() const override | 將目前物件所表示的裝箱值轉換為字串。 |
| [System::String](../string/) [ToString](../boxedvaluebase/tostring/)(const [System::String](../string/)\&) const | 使用指定的格式字串將裝箱物件轉換為字串。 |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | 實作 C# typeof([System.Object](../object/)) 建構式。 |
| const T\& [unbox](./unbox/)() const | 解箱目前物件所表示的值。 |
| void [Unlock](../object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../lockcontext/) 守護物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另見

* 類別 [BoxedValueBase](../boxedvaluebase/)
* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)