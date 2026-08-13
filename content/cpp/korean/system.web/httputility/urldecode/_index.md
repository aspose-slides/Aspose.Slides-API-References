---
title: UrlDecode()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 문자열에서 URI 조각을 디코딩합니다.
type: docs
weight: 1
url: /ko/system.web/httputility/urldecode/
---
## HttpUtility::UrlDecode(String) 메서드


문자열에서 URI 조각을 디코딩합니다.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | [String](../../../system/string/) | 인코딩된 URI 조각. |

### 반환값

디코딩된 URI 조각.

## HttpUtility::UrlDecode(String, System::SharedPtr\<Text::Encoding\>) 메서드


문자열에서 URI 조각을 디코딩합니다.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str, System::SharedPtr<Text::Encoding> e)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | [String](../../../system/string/) | 인코딩된 URI 조각. |
| e | [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\> | 사용할 인코딩. |

### 반환값

디코딩된 URI 조각.

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, const System::SharedPtr\<Text::Encoding\>\&) 메서드


바이트 배열에서 URI 조각을 디코딩합니다.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, const System::SharedPtr<Text::Encoding> &e)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 인코딩된 URI 조각. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | 사용할 인코딩. |

### 반환값

디코딩된 URI 조각.

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const System::SharedPtr\<Text::Encoding\>\&) 메서드


바이트 배열에서 URI 조각을 디코딩합니다.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count, const System::SharedPtr<Text::Encoding> &e)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 인코딩된 URI 조각. |
| offset | **int32_t** | 지정된 바이트 배열의 오프셋. |
| count | **int32_t** | 읽을 바이트 수. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | 사용할 인코딩. |

### 반환값

디코딩된 URI 조각.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [HttpUtility](../)
* 클래스 [Encoding](../../../system.text/encoding/)
* 네임스페이스 [System::Web](../../)
* Library [Aspose.Slides](../../../)