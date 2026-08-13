---
title: EnumerateFiles()
second_title: Aspose.Slides for C++ API 참조
description: 현재 객체가 나타내는 디렉터리에 위치한 모든 파일을 포함하는 열거 가능한 컬렉션을 반환합니다.
type: docs
weight: 118
url: /ko/system.io/directoryinfo/enumeratefiles/
---
## DirectoryInfo::EnumerateFiles() 메서드

현재 객체가 나타내는 디렉터리 내에 위치한 모든 파일을 포함하는 열거 가능한 컬렉션을 반환합니다.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles()
```

## DirectoryInfo::EnumerateFiles(const String\&) 메서드

현재 객체가 나타내는 디렉터리에서 지정된 검색 기준을 만족하는 파일을 검색합니다.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 검색할 파일의 이름 패턴 |

### 반환 값

이름이 **searchPattern**과 일치하는 찾은 파일을 나타내는 [FileInfo](../../fileinfo/) 객체에 대한 공유 포인터들의 열거 가능한 컬렉션

## DirectoryInfo::EnumerateFiles(const String\&, SearchOption) 메서드

현재 객체가 나타내는 디렉터리 또는 해당 디렉터리를 루트로 하는 전체 디렉터리 트리에서 지정된 검색 기준을 만족하는 파일을 검색합니다.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern, SearchOption searchOption)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 검색할 파일의 이름 패턴 |
| searchOption | [SearchOption](../../searchoption/) | 검색을 현재 객체가 나타내는 디렉터리에서만 수행할지, 해당 디렉터리를 루트로 하는 전체 디렉터리 트리에서 수행할지를 지정합니다. |

### 반환 값

이름이 **searchPattern**과 일치하는 찾은 파일을 나타내는 [FileInfo](../../fileinfo/) 객체에 대한 공유 포인터들의 열거 가능한 컬렉션

## 참고

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* 클래스 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 클래스 [DirectoryInfo](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::IO](../../)
* Library [Aspose.Slides](../../../)