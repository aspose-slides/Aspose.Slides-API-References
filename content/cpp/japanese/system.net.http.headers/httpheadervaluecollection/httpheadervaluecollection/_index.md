---
title: HttpHeaderValueCollection()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいインスタンスを作成します。
type: docs
weight: 40
url: /ja/system.net.http.headers/httpheadervaluecollection/httpheadervaluecollection/
---
## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>) コンストラクタ


新しいインスタンスを作成します。

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | ヘッダー名。 |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | HTTP ヘッダーのコレクション。 |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) コンストラクタ


新しいインスタンスを作成します。

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | ヘッダー名。 |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | HTTP ヘッダーのコレクション。 |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | 追加された項目を検証するデリゲート。 |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T) コンストラクタ


新しいインスタンスを作成します。

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | ヘッダー名。 |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | HTTP ヘッダーのコレクション。 |
| specialValue | T | 「特別な値」。 |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) コンストラクタ


新しいインスタンスを作成します。

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | ヘッダー名。 |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | HTTP ヘッダーのコレクション。 |
| specialValue | T | 「特別な値」。 |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | 追加された項目を検証するデリゲート。 |

## 参照

* typedef [SharedPtr](../../../system/sharedptr/)
* typedef [Action](../../../system/action/)
* class [String](../../../system/string/)
* class [HttpHeaders](../../httpheaders/)
* class [HttpHeaderValueCollection](../)
* 名前空間 [System::Net::Http::Headers](../../)
* ライブラリ [Aspose.Slides](../../../)