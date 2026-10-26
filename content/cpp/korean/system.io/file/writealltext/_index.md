---
title: WriteAllText()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 인코딩을 사용하여 지정된 문자열의 내용을 파일에 쓰면서 새 텍스트 파일을 생성하거나 기존 파일을 덮어씁니다.
type: docs
weight: 469
url: /ko/system.io/file/writealltext/
---
## File::WriteAllText(const String\&, const String\&, const EncodingPtr\&) 메서드

새 텍스트 파일을 생성하거나 기존 파일을 덮어쓰고, 지정된 인코딩을 사용하여 지정된 문자열의 내용을 파일에 씁니다.

```cpp
static void System::IO::File::WriteAllText(const String &path, const String &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 생성하거나 덮어쓸 파일 |
| contents | const [String](../../../system/string/)\& | 문자열 배열 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 사용할 문자 인코딩 |

## 참고

* Typedef [EncodingPtr](../../../system/encodingptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [File](../)
* 네임스페이스 [System::IO](../../)
* Library [Aspose.Slides](../../../)