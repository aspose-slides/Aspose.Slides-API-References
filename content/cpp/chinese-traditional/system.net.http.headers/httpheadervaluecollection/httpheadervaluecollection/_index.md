---
title: HttpHeaderValueCollection()
second_title: Aspose.Slides for C++ API 參考
description: 建立一個新實例。
type: docs
weight: 40
url: /zh-hant/system.net.http.headers/httpheadervaluecollection/httpheadervaluecollection/
---
## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>) 建構函式

建立一個新實例。

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | 標頭名稱。 |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | HTTP 標頭的集合。 |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) 建構函式

建立一個新實例。

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | 標頭名稱。 |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | HTTP 標頭的集合。 |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | 用於驗證新增項目的委派。 |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T) 建構函式

建立一個新實例。

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | 標頭名稱。 |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | HTTP 標頭的集合。 |
| specialValue | T | \"特殊值\"。 |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) 建構函式

建立一個新實例。

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | 標頭名稱。 |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | HTTP 標頭的集合。 |
| specialValue | T | \"特殊值\"。 |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | 用於驗證新增項目的委派。 |

## 另見

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類型定義 [Action](../../../system/action/)
* 類別 [String](../../../system/string/)
* 類別 [HttpHeaders](../../httpheaders/)
* 類別 [HttpHeaderValueCollection](../)
* 命名空間 [System::Net::Http::Headers](../../)
* 函式庫 [Aspose.Slides](../../../)