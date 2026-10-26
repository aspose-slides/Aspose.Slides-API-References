---
title: ObjectExt
second_title: Aspose.Slides for C++ API 參考文件
description: 提供靜態方法，模擬針對非 Object 的 C++ 類型（字串、數字等）所呼叫的 C# Object 方法。這是一個靜態類型，沒有實例服務。絕不應以任何方式建立其實例。
type: docs
weight: 1145
url: /zh-hant/system/objectext/
---
## ObjectExt 類別

提供靜態方法，模擬 C# [Object](../object/) 方法，針對非 Object 的 C++ 類型（字串、數字等）呼叫。此為靜態類型，沒有實例服務。絕不應以任何方式建立其實例。

```cpp
class ObjectExt : public System::ObjectType
```

## 方法

| 方法 | 說明 |
| --- | --- |
| static std::enable_if<(std::is_fundamental\<To\>::value), std::array\<To, sizeof...(From)>\>::type [ArrayInitializerCast](./arrayinitializercast/)(From ...) | 將陣列的基礎值轉換（C# 會隱式執行，但 C++ 顯然不會）。 |
| static std::enable_if\<std::is_enum\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | 將值類型裝箱以轉換為 [Object](../object/)。用於列舉類型的實作。 |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | 將值類型裝箱以轉換為 [Object](../object/)。用於非列舉類型的實作。 |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | 將 [Nullable](../nullable/) 類型裝箱以轉換為 [Object](../object/)。 |
| static [SmartPtr](../smartptr/)\<[Object](../object/)\> [Box](./box/)(const [String](../string/)\&) | 將字串值裝箱。 |
| static [SmartPtr](../smartptr/)\<[System::BoxedValueBase](../boxedvaluebase/)\> [BoxEnum](./boxenum/)(T) | 將列舉類型裝箱，以便作為 [Object](../object/) 傳遞。 |
| static [SmartPtr](../smartptr/)\<[System::Collections::IList](../../system.collections/ilist/)\> [CastToIList](./casttoilist/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) |  |
| static auto [Coalesce](./coalesce/)(T0, T1) | 實作非可為 null 類型的 '??' 運算子翻譯。 |
| static T0 [Coalesce](./coalesce/)([System::Nullable](../nullable/)\<T0\>, T1) | 實作可為 null 類型的 '??' 運算子翻譯。 |
| static auto [CoalesceAssign](./coalesceassign/)(T0\&, T1) | 實作 '??=' 運算子翻譯。 |
| static std::conditional\<std::is_convertible\<RT2, RT1\>::value, RT1, RT2\>::type [CoalesceInternal](./coalesceinternal/)(RT1, F) | 實作非可為 null 類型的 '??' 運算子翻譯。若 RT2 可轉換為 RT1 的情況之重載。 |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) |  |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | 替代 C# [Object.Equals](../object/equals/) 呼叫，適用於 C++ 中的任何類型。針對智慧指標類型的重載。 |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(T, const T2\&) | 替代 C# [Object.Equals](../object/equals/) 呼叫，適用於 C++ 中的任何類型。針對結構類型的重載。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | 替代 C# [Object.Equals](../object/equals/) 呼叫，適用於 C++ 中的任何類型。針對標量類型的重載。 |
| static **bool** [Equals](./equals/)(const char_t(&), [String](../string/)) | 替代 C# [Object.Equals](../object/equals/) 呼叫，適用於 C++ 中的任何類型。針對字串常量的字串比較重載。 |
| static **bool** [Equals](./equals/)(const **float**\&, const **float**\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 與任何值（包括 NaN）皆不相等。 |
| static **bool** [Equals](./equals/)(const **double**\&, const **double**\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 與任何值（包括 NaN）皆不相等。 |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static std::enable_if\<[System::IsSmartPtr](../issmartptr/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static int [GetHashCode](./gethashcode/)(const T\&) | 實作 [GetHashCode()](./gethashcode/) 呼叫；可在 [Object](../object/) 子類別以及不相關的類型上使用。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | 實作 typeof() 翻譯。針對智慧指標的重載。 |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | 實作 typeof() 翻譯。針對結構的重載。 |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | 實作 typeof() 翻譯。針對例外的重載。 |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | 實作 typeof() 翻譯。針對原始類型的重載。 |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | 實作 typeof() 翻譯。針對 [Nullable](../nullable/) 類型的重載。 |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | 實作 typeof() 翻譯。針對原始類型的重載。 |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | 實作 typeof() 翻譯。針對列舉類型的重載。 |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | 實作 typeof() 翻譯。針對結構與指標的重載。 |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | 實作 typeof() 翻譯。針對 [Nullable](../nullable/) 的重載。 |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | 實作 typeof() 翻譯。針對 MulticastDelegate 的重載。 |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | 實作 typeof() 翻譯。針對結構與指標的重載。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)(const [String](../string/)\&) | 實作 typeof() 翻譯。針對字串類型的重載。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | 實作 typeof() 翻譯。針對 **uint8_t** 的重載。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | 實作 typeof() 翻譯。針對 **uint8_t** 的重載。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | 實作 typeof() 翻譯。針對 **uint8_t** 的重載。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | 實作 typeof() 翻譯。針對 **uint8_t** 的重載。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | 實作 typeof() 翻譯。針對 **uint8_t** 的重載。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | 實作 typeof() 翻譯。針對 **uint8_t** 的重載。 |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, **bool**\>::type [Is](./is/)(const T\&) | 實作 'is' 運算子翻譯。針對可裝箱（值）類型的特化，正因它們屬於此類型。 |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | 實作 'is' 運算子翻譯。針對指標類型的特化，為 'final' 類別優化。 |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&\!std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | 實作 'is' 運算子翻譯。針對指標類型的特化。 |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | 實作 'is' 運算子翻譯。針對值類型的特化。 |
| static std::enable_if<\!std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | 實作 'is' 運算子翻譯。針對不可轉換的類型的特化。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | 實作 'is' 運算子翻譯。針對指標類型的特化。 |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Is](./is/)(const [ExceptionWrapper](../exceptionwrapper/)\<U\>\&) | 實作 'is' 運算子翻譯。針對例外包裝類型的特化。 |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 實作 'is' 運算子翻譯。針對可為 null 的類型的特化。 |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 實作 'is' 運算子翻譯。針對已定義 == 運算子的可裝箱類型的特化。 |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 實作 'is' 運算子翻譯。針對未定義 == 運算子的可裝箱類型的特化。 |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!std::is_same\<V, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<V\>\&) | 實作 'is' 運算子翻譯。針對值類型裝箱成介面的特化。 |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | 實作 'is' 運算子翻譯。針對列舉類型的特化。 |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [WeakPtr](../weakptr/)\<U\>\&) | 實作 'is' 運算子翻譯。針對列舉類型相對於弱指標的特化。 |
| static **bool** [Is](./is/)(const [Nullable](../nullable/)\<U\>\&) | 實作 'is' 運算子翻譯。針對 [Nullable](../nullable/) 類型的特化。 |
| static **bool** [Is](./is/)(const char16_t *) | 實作 'is' 運算子翻譯。針對字串常量的特化。 |
| static **bool** [Is](./is/)(**int32_t**) | 實作 'is' 運算子翻譯。針對整數常量的特化。 |
| static **bool** [IsBoxedValue](./isboxedvalue/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 檢查物件是否為裝箱值。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | 將 [Object](../object/) 轉換為未知類型，同時處理智慧指標類型與已裝箱值的情況。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | 將 [Object](../object/) 轉換為未知類型，同時處理智慧指標類型與已裝箱值的情況。 |
| static [String](../string/) [ToString](./tostring/)(const char_t *) | 替代 C# ToString 方法，使其可於任何 C++ 類型上使用。 |
| static [String](../string/) [ToString](./tostring/)(const [Nullable](../nullable/)\<T\>\&) | 替代 C# ToString 方法，使其可於任何 C++ 類型上使用。 |
| static std::enable_if\<std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | 替代 C# ToString 方法，使其可於任何 C++ 類型上使用。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | 替代 C# ToString 方法，使其可於任何 C++ 類型上使用。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value||std::is_pointer\<T\>::value||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | 替代 C# ToString 方法，使其可於任何 C++ 類型上使用。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | 替代 C# ToString 方法，使其可於任何 C++ 類型上使用。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | 替代 C# ToString 方法，使其可於任何 C++ 類型上使用。 |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | 替代 C# ToString 方法，使其可於任何 C++ 類型上使用。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | 替代 C# ToString 方法，使其可於任何 C++ 類型上使用。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_reference\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | 替代 C# ToString 方法，使其可於任何 C++ 類型上使用。 |
| static std::enable_if\<std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 在將 [Object](../object/) 轉換後解除列舉類型的裝箱。用於列舉類型的實作。 |
| static std::enable_if<\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 在將 [Object](../object/) 轉換後解除非列舉且可為 null 類型的裝箱。用於非列舉且不可為 null 類型的實作。 |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 在將 [Object](../object/) 轉換後解除非列舉且可為 null 類型的裝箱。用於非列舉且不可為 null 類型的實作。 |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::numeric_limits\<T\>::is_integer, T\>::type [Unbox](./unbox/)(E) | 將列舉類型解除裝箱為整數。 |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(E) | 轉換列舉類型。 |
| static [String](../string/) [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 解除字串值的裝箱。 |
| static [String](../string/) [UnboxStringSafe](./unboxstringsafe/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 從裝箱值中解除字串。 |
| static [Nullable](../nullable/)\<T\> [UnboxToNullable](./unboxtonullable/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | 解除物件為可為 null 類型。 |
| static std::enable_if<\!std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | 檢查未知類型物件是否為 nullptr。非標量類型的重載。 |
| static std::enable_if\<std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | 檢查未知類型物件是否為 nullptr。標量類型的重載。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(T) | 將未知類型轉換為 [Object](../object/)，同時處理智慧指標類型與值類型的情況。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(const T\&) | 將未知類型轉換為 [Object](../object/)，同時處理智慧指標類型與值類型的情況。 |

## 另請參閱

* 類別 [ObjectType](../objecttype/)
* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)