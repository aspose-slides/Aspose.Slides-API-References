---
title: GetFiles()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 디렉터리 또는 지정된 디렉터리를 루트로 하는 전체 디렉터리 트리에서 지정된 검색 기준을 만족하는 파일을 검색합니다.
type: docs
weight: 79
url: /ko/system.io/directory/getfiles/
---
## Directory::GetFiles(const String\&, const String\&, SearchOption) 메서드


지정된 디렉터리 또는 지정된 디렉터리를 루트로 하는 전체 디렉터리 트리에서 지정된 검색 기준을 만족하는 파일을 검색합니다.

```cpp
static ArrayPtr<String> System::IO::Directory::GetFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 검색할 디렉터리의 전체 경로나 상대 경로 |
| searchPattern | const [String](../../../system/string/)\& | 검색할 파일의 이름 패턴 |
| searchOption | [SearchOption](../../searchoption/) | 검색을 지정된 디렉터리에서만 수행할지, 지정된 디렉터리를 루트로 하는 전체 디렉터리 트리에서 수행할지를 지정합니다 |

### 반환 값

찾은 파일 중 이름이 **searchPattern**와 일치하는 파일들의 전체 경로 배열

## 참고

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)