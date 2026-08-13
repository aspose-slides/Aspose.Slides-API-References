---
title: Create()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 버퍼 크기와 옵션을 사용하여 새 파일을 생성(또는 기존 파일을 덮어쓰기)하고 읽기 및 쓰기 접근을 위해 엽니다.
type: docs
weight: 53
url: /ko/system.io/file/create/
---
## File::Create(const String\&, int32_t, FileOptions) 메서드

지정된 버퍼 크기와 옵션을 사용하여 새 파일을 생성(또는 기존 파일을 덮어쓰기)하고 읽기 및 쓰기 접근을 위해 엽니다.

```cpp
static FileStreamPtr System::IO::File::Create(const String &path, int32_t bufferSize=DefaultBufferSize, FileOptions options=FileOptions::None)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 생성하거나 덮어쓸 파일의 경로 |
| bufferSize | **int32_t** | 파일을 읽고 쓸 때 버퍼링되는 바이트 수 |
| options | [FileOptions](../../fileoptions/) | 파일을 생성하거나 덮어쓰는 방식을 지정합니다 |

### 반환 값

지정된 파일과 연결된 [FileStream](../../filestream/) 객체에 대한 공유 포인터

## 참조

* 열거형 [FileOptions](../../fileoptions/)
* 타입 정의 [FileStreamPtr](../../../system/filestreamptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [File](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)