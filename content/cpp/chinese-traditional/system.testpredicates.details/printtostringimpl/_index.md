---
title: PrintToStringImpl()
second_title: Aspose.Slides for C++ API 參考
description: "使用 ToString() 方法將 System::Object 子類別列印為字串。"
type: docs
weight: 14
url: /zh-hant/system.testpredicates.details/printtostringimpl/
---
## System::TestPredicates::Details::PrintToStringImpl(const SharedPtr\<T\>\&, long long) function

使用 ToString() 方法將 [System::Object](../../system/object/) 子類別列印為字串。

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const SharedPtr<T> &value, long long s)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | 最終類別型別。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [SharedPtr](../../system/sharedptr/)\<T\>\& | 指向要列印之物件的指標。 |
| s | long long | 服務參數，用於根據此參數的類型選擇函式重載；此參數的值將被忽略。 |

### 返回值

[String](../../system/string/) 代表傳入的物件，若 **value** 為 null 則返回 "nullptr"。

## System::TestPredicates::Details::PrintToStringImpl(const WeakPtr\<T\>\&, long long) function

使用 ToString() 方法將 [System::Object](../../system/object/) 子類別列印為字串。

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const WeakPtr<T> &value, long long s)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | 最終類別型別。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [WeakPtr](../../system/weakptr/)\<T\>\& | 指向要列印之物件的指標。 |
| s | long long | 服務參數，用於根據此參數的類型選擇函式重載；此參數的值將被忽略。 |

### 返回值

[String](../../system/string/) 代表傳入的物件，若 **value** 為 null 則返回 "nullptr"。

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) function

使用 ToString() 方法將物件列印為字串。

```cpp
template<typename T> std::enable_if<!TypeTraits::has_print_to_method<T>::value &&System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | [Object](../../system/object/) 類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) 要列印。 |
| s | long long | 服務參數，用於根據此參數的類型選擇函式重載；此參數的值將被忽略。 |

### 返回值

[String](../../system/string/) 代表傳入的物件。

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) function

使用 PrintTo 方法將物件列印為字串。

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&!TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | [Object](../../system/object/) 類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) 要列印。 |
| s | long long | 服務參數，用於根據此參數的類型選擇函式重載；此參數的值將被忽略。 |

### 返回值

[String](../../system/string/) 代表傳入的物件。

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) function

使用 PrintTo 方法將物件列印為字串。

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | [Object](../../system/object/) 類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) 要列印。 |
| s | long long | 服務參數，用於根據此參數的類型選擇函式重載；此參數的值將被忽略。 |

### 返回值

[String](../../system/string/) 代表傳入的物件。

## System::TestPredicates::Details::PrintToStringImpl(const std::pair\<T1, T2\>\&, long long) function

將 pair 列印為字串。

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const std::pair<T1, T2> &value, long long s)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T1 | 第一個 pair 類型參數。 |
| T2 | 第二個 pair 類型參數。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const std::pair\<T1, T2\>\& | [Object](../../system/object/) 要列印。 |
| s | long long | 服務參數，用於根據此參數的類型選擇函式重載；此參數的值將被忽略。 |

### 返回值

第一與第二 pair 元件的合併字串表示。

## System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair\<T1, T2\>\&, long long) function

將 pair 列印為字串。

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair<T1, T2> &value, long long s)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T1 | 第一個 pair 類型參數。 |
| T2 | 第二個 pair 類型參數。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<T1, T2\>\& | [Object](../../system/object/) 要列印。 |
| s | long long | 服務參數，用於根據此參數的類型選擇函式重載；此參數的值將被忽略。 |

### 返回值

第一與第二 pair 元件的合併字串表示。

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) function

將 STL 風格的容器以字串形式列印，其元素不超過 32 個。

```cpp
template<typename T> std::enable_if<TypeTraits::IsCppContainer<T>::value &&!std::is_base_of<Object, T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &container, long long s)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | [Object](../../system/object/) 類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| container | const T\& | [Object](../../system/object/) 要列印。 |
| s | long long | 服務參數，用於根據此參數的類型選擇函式重載；此參數的值將被忽略。 |

### 返回值

所包含元素的合併字串表示。

## System::TestPredicates::Details::PrintToStringImpl(const T\&, int) function

使用 gtest 提供的函式將其他類型列印為字串。

```cpp
template<typename T> std::string System::TestPredicates::Details::PrintToStringImpl(const T &value, int s)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | [Object](../../system/object/) 類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) 要列印。 |
| s | int | 服務參數，用於根據此參數的類型選擇函式重載；此參數的值將被忽略。 |

### 返回值

[String](../../system/string/) 代表傳入的物件。

## See Also

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [WeakPtr](../../system/weakptr/)
* Class [KeyValuePair](../../system.collections.generic/keyvaluepair/)
* Class [Object](../../system/object/)
* Struct [has_print_to_method](../../system.testpredicates.typetraits/has_print_to_method/)
* Struct [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* Struct [IsCppContainer](../../system.testpredicates.typetraits/iscppcontainer/)
* Namespace [System::TestPredicates::Details](../)
* Library [Aspose.Slides](../../)