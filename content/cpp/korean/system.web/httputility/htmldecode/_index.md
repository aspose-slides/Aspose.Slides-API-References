---
title: HtmlDecode()
second_title: Aspose.Slides for C++ API 참조
description: Html 조각을 디코드합니다.
type: docs
weight: 27
url: /ko/system.web/httputility/htmldecode/
---
## HttpUtility::HtmlDecode(const String\&) 메서드


디코드된 Html 조각을 반환합니다.

```cpp
static String System::Web::HttpUtility::HtmlDecode(const String &str)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 디코드할 Html 조각. |

### 반환값

디코드된 Html 조각.

## HttpUtility::HtmlDecode(const String\&, const SharedPtr\<IO::TextWriter\>\&) 메서드


디코드된 Html 조각을 반환합니다.

```cpp
static void System::Web::HttpUtility::HtmlDecode(const String &str, const SharedPtr<IO::TextWriter> &output)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 디코드할 Html 조각. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 출력을 위한 TextWriter 객체. |

## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [HttpUtility](../)
* 클래스 [TextWriter](../../../system.io/textwriter/)
* 네임스페이스 [System::Web](../../)
* 라이브러리 [Aspose.Slides](../../../)