---
title: ReadAllText()
second_title: Aspose.Slides C++ API 레퍼런스
description: 지정된 문자 인코딩을 사용하여 지정된 텍스트 파일의 내용을 단일 String 객체로 읽습니다.
type: docs
weight: 313
url: /ko/system.io/file/readalltext/
---
## File::ReadAllText(const String\&, const EncodingPtr\&) 메서드


지정된 문자 인코딩을 사용하여 지정된 텍스트 파일의 내용을 단일 [String](../../../system/string/) 객체로 읽습니다.

```cpp
static String System::IO::File::ReadAllText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 읽을 파일의 경로 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 사용할 문자 인코딩 |

### 반환 값

지정된 파일의 내용을 포함하는 문자열

## 관련 항목

* 타입정의 [EncodingPtr](../../../system/encodingptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [File](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)