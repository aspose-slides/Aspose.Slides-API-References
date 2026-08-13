---
title: EnumerateDirectories()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 객체가 나타내는 디렉터리에 위치한 모든 디렉터리를 포함하는 열거 가능한 컬렉션을 반환합니다.
type: docs
weight: 105
url: /ko/system.io/directoryinfo/enumeratedirectories/
---
## DirectoryInfo::EnumerateDirectories() 메서드

현재 객체가 나타내는 디렉터리 내에 위치한 모든 디렉터리를 포함하는 열거 가능한 컬렉션을 반환합니다.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories()
```

## DirectoryInfo::EnumerateDirectories(const String\&) 메서드

현재 객체가 나타내는 디렉터리에서 지정된 검색 기준을 만족하는 디렉터리를 검색합니다.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 검색할 디렉터리의 이름 패턴 |

### 반환값

검색 패턴 **searchPattern**과 일치하는 이름을 가진 찾아낸 디렉터리를 나타내는 [DirectoryInfo](../) 객체에 대한 공유 포인터들의 열거 가능한 컬렉션.

## DirectoryInfo::EnumerateDirectories(const String\&, SearchOption) 메서드

현재 객체가 나타내는 디렉터리 또는 해당 디렉터리를 루트로 하는 전체 디렉터리 트리에서 지정된 검색 기준을 만족하는 디렉터리를 검색합니다.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern, SearchOption searchOption)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 검색할 디렉터리의 이름 패턴 |
| searchOption | [SearchOption](../../searchoption/) | 검색을 현재 객체가 나타내는 디렉터리에서만 수행할지, 루트 디렉터리를 기준으로 한 전체 디렉터리 트리에서 수행할지를 지정합니다. |

### 반환값

이름이 **searchPattern**과 일치하는 찾아낸 디렉터리를 나타내는 [DirectoryInfo](../) 객체에 대한 공유 포인터들의 열거 가능한 컬렉션.

## 참조

* 열거형 [SearchOption](../../searchoption/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 타입정의 [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* 클래스 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 클래스 [DirectoryInfo](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)