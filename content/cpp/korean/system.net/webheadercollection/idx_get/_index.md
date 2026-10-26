---
title: idx_get()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 요청 헤더를 사용하여 헤더 값을 가져옵니다.
type: docs
weight: 14
url: /ko/system.net/webheadercollection/idx_get/
---
## WebHeaderCollection::idx_get(HttpRequestHeader) 메서드

지정된 요청 헤더를 사용하여 헤더 값을 가져옵니다.

```cpp
String System::Net::WebHeaderCollection::idx_get(HttpRequestHeader header)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| header | [HttpRequestHeader](../../httprequestheader/) | 헤더입니다. |

### 반환 값

지정된 헤더를 사용한 헤더 값입니다.

## WebHeaderCollection::idx_get(HttpResponseHeader) 메서드

지정된 응답 헤더를 사용하여 헤더 값을 가져옵니다.

```cpp
String System::Net::WebHeaderCollection::idx_get(HttpResponseHeader header)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| header | [HttpResponseHeader](../../httpresponseheader/) | 헤더입니다. |

### 반환 값

지정된 헤더를 사용한 헤더 값입니다.

## WebHeaderCollection::idx_get(String) 메서드

지정된 헤더 이름을 사용하여 헤더 값을 가져옵니다.

```cpp
String System::Net::WebHeaderCollection::idx_get(String name)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 헤더 이름입니다. |

### 반환 값

지정된 헤더 이름을 사용한 헤더 값입니다.

## 참고

* Enum [HttpRequestHeader](../../httprequestheader/)
* Enum [HttpResponseHeader](../../httpresponseheader/)
* Class [String](../../../system/string/)
* Class [WebHeaderCollection](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)