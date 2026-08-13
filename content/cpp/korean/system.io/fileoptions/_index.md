---
title: FileOptions
second_title: Aspose.Slides for C++ API 레퍼런스
description: FileStream 객체를 생성하기 위한 고급 옵션을 나타냅니다.
type: docs
weight: 521
url: /ko/system.io/fileoptions/
---
## FileOptions enum

[FileStream](../filestream/) 객체를 생성하기 위한 고급 옵션을 나타냅니다.

```cpp
enum class FileOptions
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| None | 0 | 추가 옵션이 없습니다. |
| Encrypted | 16384 | 파일이 암호화되었습니다. 구현되지 않음. |
| DeleteOnClose | 67108864 | 파일은 더 이상 사용되지 않을 때 자동으로 삭제되어야 합니다. |
| SequentialScan | 134217728 | 파일은 순차적으로 접근되어야 합니다. |
| RandomAccess | 268435456 | 파일이 무작위로 접근됩니다. |
| Asynchronous | 1073741824 | 파일은 비동기 I/O 작업에 사용할 수 있습니다. |
| WriteThrough | n/a | 모든 쓰기 작업은 중간 캐시를 우회하여 디스크에 직접 기록되어야 합니다. |

## 참고

* 네임스페이스 [System::IO](../)
* 라이브러리 [Aspose.Slides](../../)