---
title: AppendText()
second_title: Aspose.Slides for C++ API 참조
description: UTF-8 인코딩을 사용하여 지정된 파일에 텍스트를 추가하는 StreamWriter 객체를 생성합니다. 지정된 파일이 존재하지 않으면 파일이 생성됩니다.
type: docs
weight: 27
url: /ko/system.io/file/appendtext/
---
## File::AppendText(const String\&) 메서드

지정된 파일에 텍스트를 UTF-8 인코딩으로 추가하는 [StreamWriter](../../streamwriter/) 객체를 생성합니다. 지정된 파일이 존재하지 않으면 파일이 생성됩니다.

```cpp
static StreamWriterPtr System::IO::File::AppendText(const String &path)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 열거나 생성할 파일의 경로 |

### 반환값

지정된 파일과 연결된 생성된 [StreamWriter](../../streamwriter/) 객체에 대한 공유 포인터

## 참조

* Typedef [StreamWriterPtr](../../../system/streamwriterptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [File](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)