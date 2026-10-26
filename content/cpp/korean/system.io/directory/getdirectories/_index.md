---
title: GetDirectories()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 디렉터리 또는 해당 디렉터리를 루트로 하는 전체 디렉터리 트리에서 지정된 검색 기준을 만족하는 디렉터리를 검색합니다.
type: docs
weight: 66
url: /ko/system.io/directory/getdirectories/
---
## Directory::GetDirectories(const String&, const String&, SearchOption) 메서드

지정된 디렉터리 또는 지정된 디렉터리를 루트로 하는 전체 디렉터리 트리에서 지정된 검색 기준을 만족하는 디렉터리를 검색합니다.

```cpp
static ArrayPtr<String> System::IO::Directory::GetDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 검색할 디렉터리의 전체 경로나 상대 경로 |
| searchPattern | const [String](../../../system/string/)\& | 검색할 디렉터리 이름 패턴 |
| searchOption | [SearchOption](../../searchoption/) | 지정된 디렉터리만 검색할지 전체 디렉터리 트리를 검색할지를 지정 |

### 반환값

**searchPattern**과 일치하는 이름을 가진 찾아낸 디렉터리들의 전체 경로 배열

## 참고

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)