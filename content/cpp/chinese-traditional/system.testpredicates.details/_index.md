---
title: "System::TestPredicates::Details"
second_title: Aspose.Slides for C++ API 參考文件
description: 
type: docs
weight: 937
url: /zh-hant/system.testpredicates.details/
---
## 函式

| 函式 | 說明 |
| --- | --- |
| std::enable_if_t<\![TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\> [PrintToString](./printtostring/)(const T\&) | 藉由選擇適當的序列化函式，將物件印出為字串。 |
| std::enable_if_t\<[TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\> [PrintToString](./printtostring/)(const T\&) | 將 ICollection 風格的容器透過印出其元素（不超過 32 個）轉換為字串。 |
| std::string [PrintToString](./printtostring/)(std::nullptr_t) | 將 nullptr 轉換為字串。 |
| std::string [PrintToString](./printtostring/)(const [Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<**bool**\>\&) | 將 [IEnumerable<bool>](../system.collections.generic/ienumerable/) 集合透過印出其元素（不超過 32 個）轉換為字串。 |
| std::enable_if\<System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, long long) | 使用 ToString() 方法將 [System::Object](../system/object/) 子類別轉換為字串。 |
| std::enable_if\<System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const [WeakPtr](../system/weakptr/)\<T\>\&, long long) | 使用 ToString() 方法將 [System::Object](../system/object/) 子類別轉換為字串。 |
| std::enable_if<\![TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | 使用 ToString() 方法將物件轉換為字串。 |
| std::enable_if\<[TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&\![TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | 使用 PrintTo 方法將物件轉換為字串。 |
| std::enable_if\<[TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&[TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | 使用 PrintTo 方法將物件轉換為字串。 |
| std::string [PrintToStringImpl](./printtostringimpl/)(const std::pair\<T1, T2\>\&, long long) | 將 pair 轉換為字串。 |
| std::string [PrintToStringImpl](./printtostringimpl/)(const [Collections::Generic::KeyValuePair](../system.collections.generic/keyvaluepair/)\<T1, T2\>\&, long long) | 將 pair 轉換為字串。 |
| std::enable_if\<[TypeTraits::IsCppContainer](../system.testpredicates.typetraits/iscppcontainer/)\<T\>::value\&&\!std::is_base_of\<[Object](../system/object/), T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | 將 STL 風格的容器透過印出其元素（不超過 32 個）轉換為字串。 |
| std::string [PrintToStringImpl](./printtostringimpl/)(const T\&, int) | 使用 gtest 提供的函式將其他類型轉換為字串。 |
| testing::AssertionResult [EqFailure](./eqfailure/)(const char *, const char *, T1\&, T2\&) | 格式化 == 斷言失敗以供輸出。 |
| testing::AssertionResult [NotEqFailure](./noteqfailure/)(const char *, const char *, T1\&, T2\&) | 格式化 != 斷言失敗以供輸出。 |
| testing::AssertionResult [SameFailure](./samefailure/)(const char *, const char *, T1\&, T2\&) | 格式化 'same' 斷言失敗以供輸出。 |
| testing::AssertionResult [NotSameFailure](./notsamefailure/)(const char *, const char *, T1\&, T2\&) | 格式化 'not same' 斷言失敗以供輸出。 |