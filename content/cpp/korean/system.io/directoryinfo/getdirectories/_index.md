---
title: GetDirectories()
second_title: Aspose.Slides for C++ API 참조
description: 현재 객체가 나타내는 디렉터리에 위치한 모든 디렉터리를 나타내는 DirectoryInfo 객체에 대한 공유 포인터를 포함하는 배열을 반환합니다.
type: docs
weight: 144
url: /ko/system.io/directoryinfo/getdirectories/
---
## DirectoryInfo::GetDirectories() 메서드


현재 객체가 나타내는 디렉터리 내에 위치한 모든 디렉터리를 나타내는 [DirectoryInfo](../) 객체에 대한 공유 포인터를 포함하는 배열을 반환합니다.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories()
```

## DirectoryInfo::GetDirectories(const String\&) 메서드


현재 객체가 나타내는 디렉터리에서 지정된 검색 기준을 만족하는 디렉터리를 검색합니다.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 검색할 디렉터리의 이름 패턴 |

### 반환 값

이름이 **searchPattern**와 일치하는 찾은 디렉터리를 나타내는 [DirectoryInfo](../) 객체에 대한 공유 포인터 배열을 반환합니다.

## DirectoryInfo::GetDirectories(const String\&, SearchOption) 메서드


현재 객체가 나타내는 디렉터리 또는 그 디렉터리를 루트로 하는 전체 디렉터리 트리에서 지정된 검색 기준을 만족하는 디렉터리를 검색합니다.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern, SearchOption searchOption)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 검색할 디렉터리의 이름 패턴 |
| searchOption | [SearchOption](../../searchoption/) | 검색을 현재 객체가 나타내는 디렉터리에서만 수행할지, 그 디렉터리를 루트로 하는 전체 디렉터리 트리에서 수행할지를 지정합니다 |

### 반환 값

이름이 **searchPattern**와 일치하는 찾은 디렉터리를 나타내는 [DirectoryInfo](../) 객체에 대한 공유 포인터 배열을 반환합니다.

## 참고

* 열거형 [SearchOption](../../searchoption/)
* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 타입정의 [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* 클래스 [DirectoryInfo](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)