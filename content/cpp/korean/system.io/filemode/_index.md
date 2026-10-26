---
title: FileMode
second_title: Aspose.Slides C++ API 레퍼런스
description: 파일을 여는 방법을 지정합니다.
type: docs
weight: 508
url: /ko/system.io/filemode/
---
## FileMode 열거형

파일을 여는 방법을 지정합니다.

```cpp
enum class FileMode
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| CreateNew | 1 | 새 파일을 생성합니다. 파일이 이미 존재하면 예외가 발생합니다. |
| Create | 2 | 새 파일을 생성합니다. 파일이 이미 존재하면 덮어씁니다. |
| Open | 3 | 기존 파일을 엽니다. 파일이 존재하지 않으면 예외가 발생합니다. |
| OpenOrCreate | 4 | 파일이 존재하면 기존 파일을 열고, 존재하지 않으면 새 파일을 생성합니다. |
| Truncate | 5 | 기존 파일을 열고 비워서 빈 파일로 만듭니다. 파일이 존재하지 않으면 예외가 발생합니다. |
| Append | 6 | 파일이 존재하면 기존 파일을 열고 끝으로 이동하며, 존재하지 않으면 새 파일을 생성합니다. |

## 참고

* 네임스페이스 [System::IO](../)
* 라이브러리 [Aspose.Slides](../../)