---
title: HttpHeaderValueCollection()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a new instance.
type: docs
weight: 40
url: /system.net.http.headers/httpheadervaluecollection/httpheadervaluecollection/
---
## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>) constructor


Constructs a new instance.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | The header name. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | The collection of the HTTP headers. |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) constructor


Constructs a new instance.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | The header name. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | The collection of the HTTP headers. |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | The delegate that is used to validate added items. |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T) constructor


Constructs a new instance.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | The header name. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | The collection of the HTTP headers. |
| specialValue | T | A \"special value\". |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) constructor


Constructs a new instance.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | The header name. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | The collection of the HTTP headers. |
| specialValue | T | A \"special value\". |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | The delegate that is used to validate added items. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Action](../../../system/action/)
* Class [String](../../../system/string/)
* Class [HttpHeaders](../../httpheaders/)
* Class [HttpHeaderValueCollection](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)