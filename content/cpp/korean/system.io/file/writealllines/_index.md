---
title: WriteAllLines()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 인코딩을 사용하여 새 텍스트 파일을 생성하거나 기존 파일을 덮어쓰고, 지정된 열거 가능한 문자열 컬렉션의 모든 문자열을 각 줄에 하나씩 파일에 씁니다.
type: docs
weight: 456
url: /ko/system.io/file/writealllines/
---
## File::WriteAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) 메서드

지정된 인코딩을 사용하여 새 텍스트 파일을 생성하거나 기존 파일을 덮어쓰고, 지정된 열거 가능한 문자열 컬렉션의 모든 문자열을 각 줄에 하나씩 파일에 씁니다.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 만들거나 덮어쓸 파일 |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | 문자열의 열거 가능한 컬렉션 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 사용할 문자 인코딩 |

## File::WriteAllLines(const String\&, const ArrayPtr\<String\>\&, const EncodingPtr\&) 메서드

지정된 인코딩을 사용하여 새 텍스트 파일을 생성하거나 기존 파일을 덮어쓰고, 지정된 문자열 배열의 모든 문자열을 각 줄에 하나씩 파일에 씁니다.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const ArrayPtr<String> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 만들거나 덮어쓸 파일 |
| contents | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | 문자열 배열 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 사용할 문자 인코딩 |

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 클래스 [File](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)