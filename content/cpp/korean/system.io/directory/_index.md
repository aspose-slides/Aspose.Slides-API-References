---
title: Directory
second_title: Aspose.Slides for C++ API 레퍼런스
description: 디렉터리를 조작하기 위한 메서드를 포함합니다. 이는 인스턴스 서비스를 제공하지 않는 정적 타입입니다. 어떤 방법으로도 인스턴스를 생성해서는 안 됩니다.
type: docs
weight: 235
url: /ko/system.io/directory/
---
## Directory 클래스

Contains methods for manipulating directories. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class Directory
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static void [CreateDirectory_](./createdirectory_/)(const [String](../../system/string/)\&) | 지정된 경로에 존재하지 않으면 모든 디렉터리를 생성합니다. |
| static void [Delete](./delete/)(const [String](../../system/string/)\&, **bool**) | 지정된 파일 또는 디렉터리를 제거합니다. 예외를 발생시키지 않습니다. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | 지정된 디렉터리 또는 지정된 디렉터리를 루트로 하는 전체 디렉터리 트리에서 지정된 검색 기준을 충족하는 디렉터리를 검색합니다. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | 지정된 디렉터리 또는 지정된 디렉터리를 루트로 하는 전체 디렉터리 트리에서 지정된 검색 기준을 충족하는 파일을 검색합니다. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFileSystemEntries](./enumeratefilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | 지정된 디렉터리 또는 지정된 디렉터리를 루트로 하는 전체 디렉터리 트리에서 지정된 검색 기준을 충족하는 파일 및 디렉터리를 검색합니다. |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | 지정된 경로가 기존 디렉터리를 가리키는지 확인합니다. |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | 지정된 엔터티의 생성 시간을 로컬 시간으로 반환합니다. |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | 지정된 엔터티의 생성 시간을 UTC 시간으로 반환합니다. |
| static [String](../../system/string/) [GetCurrentDirectory](./getcurrentdirectory/)() | 현재 디렉터리의 전체 이름(경로 포함)을 반환합니다. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | 지정된 디렉터리 또는 지정된 디렉터리를 루트로 하는 전체 디렉터리 트리에서 지정된 검색 기준을 충족하는 디렉터리를 검색합니다. |
| static [String](../../system/string/) [GetDirectoryRoot](./getdirectoryroot/)(const [String](../../system/string/)\&) | 지정된 경로의 루트 디렉터리를 반환합니다. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | 지정된 디렉터리 또는 지정된 디렉터리를 루트로 하는 전체 디렉터리 트리에서 지정된 검색 기준을 충족하는 파일을 검색합니다. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFileSystemEntries](./getfilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | 지정된 디렉터리 또는 지정된 디렉터리를 루트로 하는 전체 디렉터리 트리에서 지정된 검색 기준을 충족하는 파일 및 디렉터리를 검색합니다. |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | 지정된 엔터티의 마지막 접근 시간을 로컬 시간으로 반환합니다. |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | 지정된 엔터티의 마지막 접근 시간을 UTC 시간으로 반환합니다. |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | 지정된 엔터티의 마지막 쓰기 시간을 로컬 시간으로 반환합니다. |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | 지정된 엔터티의 마지막 쓰기 시간을 UTC 시간으로 반환합니다. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetLogicalDrives](./getlogicaldrives/)() | 구현되지 않음. |
| static [DirectoryInfoPtr](../../system/directoryinfoptr/) [GetParent](./getparent/)(const [String](../../system/string/)\&) | 지정된 엔터티의 상위 디렉터리를 나타내는 [DirectoryInfo](../directoryinfo/) 객체에 대한 공유 포인터를 반환합니다. |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 지정된 엔터티를 새로운 위치로 이동합니다. 이동 대상이 디렉터리인 경우, 모든 내용과 함께 이동합니다. |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | 지정된 엔터티의 생성 시간을 로컬 시간으로 설정합니다. |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | 지정된 엔터티의 생성 시간을 UTC 시간으로 설정합니다. |
| static void [SetCurrentDirectory](./setcurrentdirectory/)(const [String](../../system/string/)\&) | 현재 디렉터리를 설정합니다. |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | 지정된 엔터티의 마지막 접근 시간을 로컬 시간으로 설정합니다. |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | 지정된 엔터티의 마지막 접근 시간을 UTC 시간으로 설정합니다. |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | 지정된 엔터티의 마지막 쓰기 시간을 로컬 시간으로 설정합니다. |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | 지정된 엔터티의 마지막 쓰기 시간을 UTC 시간으로 설정합니다. |

## 타입 별칭

| 타입 별칭 | 설명 |
| --- | --- |
| [StringEnumerablePtr](./stringenumerableptr/) | [String](../../system/string/) 객체 집합을 열거하는 IEnumerable 객체에 대한 공유 포인터의 별칭입니다. |

## 비고



```cpp
#include "system/io/directory.h"
#include "system/io/path.h"
#include "system/string.h"
#include <iostream>

void PrintMessage(const System::String &path)
{
  std::cout << "Directory '" << path << (System::IO::Directory::Exists(path) ? "' exists." : "' doesn't exist.") << std::endl;
}

int main()
{
  // 디렉터리 경로를 포함하는 문자열을 생성합니다.
  System::String discPath(u"C:\\");
  System::String directoryPath(u"C:\\Some directory");
  auto tempPath = System::IO::Path::GetTempPath();

  // 디렉터리가 존재하는지 확인합니다.
  PrintMessage(discPath);
  PrintMessage(directoryPath);
  PrintMessage(tempPath);

  // 임시 디렉터리 정보를 출력합니다.
  std::cout <<
    "Creation Time: " << System::IO::Directory::GetCreationTime(tempPath) << std::endl <<
    "Last Access Time: " << System::IO::Directory::GetLastAccessTime(tempPath) << std::endl <<
    "Last Write Time: " << System::IO::Directory::GetLastWriteTime(tempPath) << std::endl;

  return 0;
}
/*
이 코드 예제는 다음과 같은 출력을 생성합니다:
디렉터리 'C:\' 존재합니다.
디렉터리 'C:\Some directory' 존재하지 않습니다.
디렉터리 'C:\Users\lanor\AppData\Local\Temp\' 존재합니다.
생성 시간: 27.08.2021 14:21:42
마지막 접근 시간: 07.10.2021 12:16:41
마지막 쓰기 시간: 07.10.2021 12:16:41
*/
```

## 관련 항목

* 네임스페이스 [System::IO](../)
* 라이브러리 [Aspose.Slides](../../)