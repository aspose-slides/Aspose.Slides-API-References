---
title: ReadAllLines()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 문자 인코딩을 사용하여 지정된 텍스트 파일의 내용을 한 줄씩 문자열 배열에 읽어들입니다.
type: docs
weight: 300
url: /ko/system.io/file/readalllines/
---
## File::ReadAllLines(const String\&, const EncodingPtr\&) 메서드


지정된 텍스트 파일의 내용을 지정된 문자 인코딩을 사용하여 한 줄씩 문자열 배열에 읽어들입니다.

```cpp
static ArrayPtr<String> System::IO::File::ReadAllLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 읽을 파일의 경로 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 사용할 문자 인코딩 |

### 반환 값

각 요소가 지정된 파일의 한 줄을 나타내는 문자열 배열입니다.

## 참조

* 타입 정의 [ArrayPtr](../../../system/arrayptr/)
* 타입 정의 [EncodingPtr](../../../system/encodingptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [File](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)