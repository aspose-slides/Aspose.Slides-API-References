---
title: UrlEncodeToBytes()
second_title: Aspose.Slides for C++ API 레퍼런스
description: URI 조각을 인코딩합니다.
type: docs
weight: 66
url: /ko/system.web/httputility/urlencodetobytes/
---
## HttpUtility::UrlEncodeToBytes(const String\&) 메서드


URI 조각을 인코딩합니다.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str)
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 인코딩할 URI 조각. |

### 반환값

인코딩된 URI 조각.

## HttpUtility::UrlEncodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) 메서드


URI 조각을 인코딩합니다.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 인코딩할 URI 조각. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | 사용할 인코딩. |

### 반환값

인코딩된 URI 조각.

## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&) 메서드


URI 조각을 인코딩합니다.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 인코딩할 URI 조각. |

### 반환값

인코딩된 URI 조각.

## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 메서드


URI 조각을 인코딩합니다.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 인코딩할 URI 조각. |
| offset | **int32_t** | 주어진 바이트 배열에서의 오프셋. |
| count | **int32_t** | 읽을 바이트 수. |

### 반환값

인코딩된 URI 조각.

## 참조

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [HttpUtility](../)
* 클래스 [Encoding](../../../system.text/encoding/)
* 네임스페이스 [System::Web](../../)
* Library [Aspose.Slides](../../../)