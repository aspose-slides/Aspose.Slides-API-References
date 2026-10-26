---
title: Copy()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 파일을 지정된 위치로 복사합니다. 대상 파일이 이미 존재하는 경우, 매개변수를 통해 덮어쓸지 여부를 지정합니다.
type: docs
weight: 40
url: /ko/system.io/file/copy/
---
## File::Copy(const String\&, const String\&, bool) 메서드

지정된 파일을 지정된 위치로 복사합니다. 대상 파일이 이미 존재하는 경우, 매개변수에 따라 덮어쓸지 여부를 지정합니다.

```cpp
static void System::IO::File::Copy(const String &sourceFileName, const String &destFileName, bool overwrite=false)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceFileName | const [String](../../../system/string/)\& | 복사할 파일의 경로 |
| destFileName | const [String](../../../system/string/)\& | 복사할 파일의 새 위치 경로 |
| overwrite | **bool** | 기존 대상 파일을 덮어써야 하면 True, 대상 파일이 이미 존재하면 복사가 실패하도록 하려면 false |

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [File](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)