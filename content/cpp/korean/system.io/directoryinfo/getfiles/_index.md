---
title: GetFiles()
second_title: Aspose.Slides for C++ API 참고 문서
description: 현재 객체가 나타내는 디렉터리 내에 위치한 모든 디렉터리를 나타내는 FileInfo 객체에 대한 공유 포인터를 포함하는 배열을 반환합니다.
type: docs
weight: 157
url: /ko/system.io/directoryinfo/getfiles/
---
## DirectoryInfo::GetFiles() 메서드

현재 객체가 나타내는 디렉터리 내에 위치한 모든 디렉터리를 나타내는 [FileInfo](../../fileinfo/) 객체에 대한 공유 포인터를 포함하는 배열을 반환합니다.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles()
```

## DirectoryInfo::GetFiles(const String\&) 메서드

현재 객체가 나타내는 디렉터리에서 지정된 검색 기준을 만족하는 파일을 검색합니다.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 검색할 파일의 이름 패턴 |

### 반환값

이름이 **searchPattern**와 일치하는 검색된 파일을 나타내는 [FileInfo](../../fileinfo/) 객체에 대한 공유 포인터 배열

## DirectoryInfo::GetFiles(const String\&, SearchOption) 메서드

현재 객체가 나타내는 디렉터리 또는 해당 디렉터리를 루트로 하는 전체 디렉터리 트리에서 지정된 검색 기준을 만족하는 파일을 검색합니다.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern, SearchOption searchOption)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 검색할 파일의 이름 패턴 |
| searchOption | [SearchOption](../../searchoption/) | 검색을 현재 객체가 나타내는 디렉터리에서만 수행할지, 해당 디렉터리를 루트로 하는 전체 디렉터리 트리에서 수행할지를 지정합니다. |

### 반환값

이름이 **searchPattern**와 일치하는 검색된 파일을 나타내는 [FileInfo](../../fileinfo/) 객체에 대한 공유 포인터 배열

## 참조

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)