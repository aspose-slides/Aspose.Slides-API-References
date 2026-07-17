---
title: HttpHeaderValueCollection()
second_title: Aspose.Slides C++ API 参考
description: 构造一个新实例。
type: docs
weight: 40
url: /zh/system.net.http.headers/httpheadervaluecollection/httpheadervaluecollection/
---
## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>) 构造函数


构造一个新实例。

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store)
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | 标头名称。 |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | HTTP 标头的集合。 |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) 构造函数


构造一个新实例。

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | 标头名称。 |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | HTTP 标头的集合。 |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | 用于验证添加项的委托。 |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T) 构造函数


构造一个新实例。

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue)
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | 标头名称。 |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | HTTP 标头的集合。 |
| specialValue | T | \"特殊值\"。 |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) 构造函数


构造一个新实例。

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | 标头名称。 |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | HTTP 标头的集合。 |
| specialValue | T | \"特殊值\"。 |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | 用于验证添加项的委托。 |

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Action](../../../system/action/)
* Class [String](../../../system/string/)
* Class [HttpHeaders](../../httpheaders/)
* Class [HttpHeaderValueCollection](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)