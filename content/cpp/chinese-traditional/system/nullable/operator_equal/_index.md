---
title: operator=()
second_title: Aspose.Slides for C++ API 參考
description: 將 null 指派給目前的物件。
type: docs
weight: 14
url: /zh-hant/system/nullable/operator_equal/
---
## Nullable::operator=(std::nullptr_t) method


將 null 指派給目前的物件。

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator=(std::nullptr_t)
```


### Return Value

一個代表 null 值的 [Nullable](../) 物件。

## Nullable::operator=(const T1\&) method


將物件目前所代表的值替換為指定的值。

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value &&!std::is_null_pointer<T1>::value, Nullable<T> &>::type System::Nullable<T>::operator=(const T1 &x)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| The | type of the new value to be represented by the current object |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | const T1\& | The new value to be represented by the current object |

### Return Value

指向本身的參考

## Nullable::operator=(const Nullable\<T1\>\&) method


將物件目前所代表的值替換為指定的值。

```cpp
template<typename T1> Nullable<T> & System::Nullable<T>::operator=(const Nullable<T1> &x)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| The | type of the new value to be represented by the current object |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | const [Nullable](../)\<T1\>\& | The new value to be represented by the current object |

### Return Value

指向本身的參考

## See Also

* Class [Nullable](../)
* Struct [IsNullable](../../isnullable/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)