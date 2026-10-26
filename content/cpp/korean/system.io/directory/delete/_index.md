---
title: Delete()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 파일 또는 디렉터리를 제거합니다. 예외를 발생시키지 않습니다.
type: docs
weight: 14
url: /ko/system.io/directory/delete/
---
## Directory::Delete(const String\&, bool) 메서드

지정된 파일 또는 디렉터리를 제거합니다. 예외를 발생시키지 않습니다.

```cpp
static void System::IO::Directory::Delete(const String &path, bool recursive=false)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 제거될 디렉터리 또는 파일의 경로 |
| recursive | **bool** | **path**가 비어 있지 않은 디렉터리를 지정하는 경우, **recursive**는 디렉터리의 모든 내용을 재귀적으로 제거할지 여부를 지정합니다; **path**가 지정한 디렉터리가 비어 있지 않고 **recursive**가 'false'인 경우 작업이 실패합니다 |

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [Directory](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)