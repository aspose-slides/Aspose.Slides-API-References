---
title: EnumerateFileSystemInfos()
second_title: Aspose.Slides for C++ API 참조
description: 현재 객체가 나타내는 디렉터리 내에 위치한 모든 파일 및 디렉터리를 포함하는 열거 가능 컬렉션을 반환합니다.
type: docs
weight: 131
url: /ko/system.io/directoryinfo/enumeratefilesysteminfos/
---
## DirectoryInfo::EnumerateFileSystemInfos() 메서드


현재 객체가 나타내는 디렉터리 내에 위치한 모든 파일과 디렉터리를 포함하는 열거 가능 컬렉션을 반환합니다.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos()
```

## DirectoryInfo::EnumerateFileSystemInfos(const String\&) 메서드


현재 객체가 나타내는 디렉터리에서 지정된 검색 기준을 만족하는 파일 및 디렉터리를 검색합니다.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 검색할 파일 및 디렉터리의 이름 패턴 |

### 반환 값

이름이 **searchPattern**와 일치하는 찾은 파일 및 디렉터리를 나타내는 [FileSystemInfo](../../filesysteminfo/) 객체에 대한 공유 포인터의 열거 가능 컬렉션

## DirectoryInfo::EnumerateFileSystemInfos(const String\&, SearchOption) 메서드


현재 객체가 나타내는 디렉터리에서 지정된 검색 기준을 만족하는 파일 및 디렉터리를 현재 객체가 나타내는 디렉터리만을 대상으로 하거나 해당 디렉터리를 루트로 하는 전체 디렉터리 트리에서 검색합니다.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 검색할 파일 및 디렉터리의 이름 패턴 |
| searchOption | [SearchOption](../../searchoption/) | 검색을 현재 객체가 나타내는 디렉터리에서만 수행할지, 해당 디렉터리를 루트로 하는 전체 디렉터리 트리에서 수행할지를 지정합니다 |

### 반환 값

이름이 **searchPattern**와 일치하는 찾은 파일 및 디렉터리를 나타내는 [FileSystemInfo](../../filesysteminfo/) 객체에 대한 공유 포인터의 열거 가능 컬렉션

## See Also

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)