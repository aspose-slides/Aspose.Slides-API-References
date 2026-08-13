---
title: OpenText()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 기존 파일을 공유 없이 UTF-8 인코딩을 사용하여 텍스트를 읽기 위해 엽니다.
type: docs
weight: 261
url: /ko/system.io/file/opentext/
---
## File::OpenText(const String\&, const EncodingPtr\&) 메서드

지정된 기존 파일을 공유 없이 UTF-8 인코딩을 사용하여 텍스트를 읽기 위해 엽니다.

```cpp
static StreamReaderPtr System::IO::File::OpenText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 열려는 파일의 경로 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 사용할 문자 인코딩 |

### 반환 값

열린 파일과 연결된 [StreamWriter](../../streamwriter/) 객체에 대한 공유 포인터

## 참조

* 타입 정의 [StreamReaderPtr](../../../system/streamreaderptr/)
* 타입 정의 [EncodingPtr](../../../system/encodingptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [File](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)