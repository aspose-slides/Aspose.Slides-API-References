---
title: HttpHeaderValueCollection()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새 인스턴스를 생성합니다.
type: docs
weight: 40
url: /ko/system.net.http.headers/httpheadervaluecollection/httpheadervaluecollection/
---
## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>) constructor

새 인스턴스를 생성합니다.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | 헤더 이름. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | HTTP 헤더의 컬렉션. |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) constructor

새 인스턴스를 생성합니다.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | 헤더 이름. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | HTTP 헤더의 컬렉션. |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | 추가된 항목을 검증하는 데 사용되는 대리자. |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T) constructor

새 인스턴스를 생성합니다.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | 헤더 이름. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | HTTP 헤더의 컬렉션. |
| specialValue | T | "특별 값". |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) constructor

새 인스턴스를 생성합니다.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | 헤더 이름. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | HTTP 헤더의 컬렉션. |
| specialValue | T | "특별 값". |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | 추가된 항목을 검증하는 데 사용되는 대리자. |

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Action](../../../system/action/)
* 클래스 [String](../../../system/string/)
* 클래스 [HttpHeaders](../../httpheaders/)
* 클래스 [HttpHeaderValueCollection](../)
* 네임스페이스 [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)