---
title: EnumerateDirectories()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 디렉터리 또는 지정된 디렉터리를 루트로 하는 전체 디렉터리 트리에서 지정된 검색 기준을 만족하는 디렉터리를 검색합니다.
type: docs
weight: 27
url: /ko/system.io/directory/enumeratedirectories/
---
## Directory::EnumerateDirectories(const String&, const String&, SearchOption) 메서드


지정된 디렉터리 또는 지정된 디렉터리를 루트로 하는 전체 디렉터리 트리에서 지정된 검색 기준을 만족하는 디렉터리를 검색합니다.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 검색할 디렉터리의 전체 경로나 상대 경로 |
| searchPattern | const [String](../../../system/string/)\& | 검색할 디렉터리의 이름 패턴 |
| searchOption | [SearchOption](../../searchoption/) | 검색을 지정된 디렉터리에서만 수행할지, 지정된 디렉터리를 루트로 하는 전체 디렉터리 트리에서 수행할지를 지정합니다 |

### 반환 값

찾은 디렉터리 중 이름이 **searchPattern**와 일치하는 디렉터리들의 전체 경로를 열거 가능한 컬렉션

## 참조

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)