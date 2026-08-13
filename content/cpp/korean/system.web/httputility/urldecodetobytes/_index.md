---
title: UrlDecodeToBytes()
second_title: Aspose.Slides for C++ API 참조
description: 바이트 배열에서 URI 조각을 디코딩합니다.
type: docs
weight: 14
url: /ko/system.web/httputility/urldecodetobytes/
---
## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&) method


바이트 배열에서 URI 조각을 디코딩합니다.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 인코딩된 URI 조각. |

### 반환값

디코딩된 URI 조각.

## HttpUtility::UrlDecodeToBytes(const String\&) method


바이트 문자열에서 URI 조각을 디코딩합니다.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 인코딩된 URI 조각. |

### 반환값

디코딩된 URI 조각.

## HttpUtility::UrlDecodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) method


문자열에서 URI 조각을 디코딩합니다.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 인코딩된 URI 조각. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | 사용할 인코딩. |

### 반환값

디코딩된 URI 조각.

## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


바이트 배열에서 URI 조각을 디코딩합니다.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 인코딩된 URI 조각. |
| offset | **int32_t** | 주어진 바이트 배열에서의 오프셋. |
| count | **int32_t** | 읽을 바이트 수. |

### 반환값

디코딩된 URI 조각.

## 또 보기

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpUtility](../)
* Class [String](../../../system/string/)
* Class [Encoding](../../../system.text/encoding/)
* Namespace [System::Web](../../)
* Library [Aspose.Slides](../../../)