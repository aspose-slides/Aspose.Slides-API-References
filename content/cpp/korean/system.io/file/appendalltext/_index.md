---
title: AppendAllText()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 인코딩을 사용하여 지정된 파일에 지정된 문자열을 추가합니다.
type: docs
weight: 14
url: /ko/system.io/file/appendalltext/
---
## File::AppendAllText(const String\&, const String\&, const EncodingPtr\&) 메서드


지정된 인코딩을 사용하여 지정된 파일에 지정된 문자열을 추가합니다.

```cpp
static void System::IO::File::AppendAllText(const String &path, const String &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 문자열을 추가할 파일의 경로 |
| contents | const [String](../../../system/string/)\& | 파일에 쓸 문자열 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 사용할 문자 인코딩 |

## 관련 내용

* Typedef [EncodingPtr](../../../system/encodingptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [File](../)
* 네임스페이스 [System::IO](../../)
* Library [Aspose.Slides](../../../)