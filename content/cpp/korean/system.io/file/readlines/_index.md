---
title: ReadLines()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 문자 인코딩을 사용하여 지정된 텍스트 파일의 내용을 한 줄씩 읽고, 파일 내용의 각 줄을 나타내는 문자열의 열거 가능한 컬렉션을 반환합니다.
type: docs
weight: 326
url: /ko/system.io/file/readlines/
---
## File::ReadLines(const String\&, const EncodingPtr\&) 메서드


지정된 텍스트 파일의 내용을 지정된 문자 인코딩을 사용하여 한 줄씩 읽고, 파일 내용의 각 줄을 나타내는 문자열 컬렉션을 반환합니다.

```cpp
static SharedPtr<Collections::Generic::IEnumerable<String>> System::IO::File::ReadLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```


### 매개변수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 읽을 파일의 경로 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 사용할 문자 인코딩 |

### 반환 값

지정된 파일의 내용을 나타내는 문자열의 열거 가능한 컬렉션

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* 클래스 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 클래스 [String](../../../system/string/)
* 클래스 [File](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)