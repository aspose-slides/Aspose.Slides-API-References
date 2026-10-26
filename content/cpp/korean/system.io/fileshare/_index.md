---
title: FileShare
second_title: Aspose.Slides C++ API 참조
description: 다른 FileStream 객체가 열려 있는 파일에 대해 가질 수 있는 액세스 종류를 지정합니다.
type: docs
weight: 534
url: /ko/system.io/fileshare/
---
## FileShare 열거형

열려 있는 파일에 대해 다른 [FileStream](../filestream/) 객체가 가질 수 있는 액세스 유형을 지정합니다.

```cpp
enum class FileShare
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| None | 0 | 액세스 없음. |
| Read | 1 | 읽기 전용 액세스. |
| Write | 2 | 쓰기 전용 액세스. |
| ReadWrite | 3 | 읽기 및 쓰기 액세스. |
| Delete | 4 | 파일을 삭제할 수 있습니다. |
| Inheritable | 16 | 파일 핸들을 자식 프로세스가 상속하도록 합니다. |

## 관련 항목

* 네임스페이스 [System::IO](../)
* 라이브러리 [Aspose.Slides](../../)