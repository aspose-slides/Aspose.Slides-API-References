---
title: UrlEncode()
second_title: Aspose.Slides for C++ API 참조
description: URI 조각을 인코딩합니다.
type: docs
weight: 53
url: /ko/system.web/httputility/urlencode/
---
## HttpUtility::UrlEncode(String) 메서드

URI 조각을 인코딩합니다.

```cpp
static String System::Web::HttpUtility::UrlEncode(String str)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | [String](../../../system/string/) | 인코딩할 URI 조각. |

### 반환 값

인코딩된 URI 조각.

## HttpUtility::UrlEncode(String, const System::SharedPtr\<Text::Encoding\>\&) 메서드

URI 조각을 인코딩합니다.

```cpp
static String System::Web::HttpUtility::UrlEncode(String str, const System::SharedPtr<Text::Encoding> &e)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | [String](../../../system/string/) | 인코딩할 URI 조각. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | 사용할 인코딩. |

### 반환 값

인코딩된 URI 조각.

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&) 메서드

URI 조각을 인코딩합니다.

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 인코딩할 URI 조각. |

### 반환 값

인코딩된 URI 조각.

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 메서드

URI 조각을 인코딩합니다.

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 인코딩할 URI 조각. |
| offset | **int32_t** | 주어진 바이트 배열에서의 오프셋. |
| count | **int32_t** | 읽을 바이트 수. |

### 반환 값

인코딩된 URI 조각.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [HttpUtility](../)
* 클래스 [Encoding](../../../system.text/encoding/)
* 네임스페이스 [System::Web](../../)
* Library [Aspose.Slides](../../../)