---
title: GetFileSystemEntries()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 검색 기준을 만족하는 파일 및 디렉터리를 지정된 디렉터리 또는 지정된 디렉터리를 루트로 하는 전체 디렉터리 트리에서 검색합니다.
type: docs
weight: 92
url: /ko/system.io/directory/getfilesystementries/
---
## Directory::GetFileSystemEntries(const String\&, const String\&, SearchOption) 메서드

지정된 디렉터리 또는 지정된 디렉터리를 루트로 하는 전체 디렉터리 트리에서 지정된 검색 기준을 만족하는 파일 및 디렉터리를 검색합니다.

```cpp
static ArrayPtr<String> System::IO::Directory::GetFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 검색할 디렉터리의 전체 경로나 상대 경로 |
| searchPattern | const [String](../../../system/string/)\& | 검색할 파일 및 디렉터리의 이름 패턴 |
| searchOption | [SearchOption](../../searchoption/) | 검색을 지정된 디렉터리에서만 수행할지, 지정된 디렉터리를 루트로 하는 전체 디렉터리 트리에서 수행할지 지정합니다 |

### 반환 값

이름이 **searchPattern**과 일치하는 찾은 파일 및 디렉터리의 전체 경로 배열

## 참고

* 열거형 [SearchOption](../../searchoption/)
* 타입 정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [Directory](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)