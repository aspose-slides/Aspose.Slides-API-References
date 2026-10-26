---
title: Path
second_title: Aspose.Slides for C++ API 레퍼런스
description: 경로를 조작하는 메서드를 제공합니다. 이것은 인스턴스 서비스를 갖지 않는 정적 타입입니다. 어떠한 방법으로도 인스턴스를 생성해서는 안 됩니다.
type: docs
weight: 339
url: /ko/system.io/path/
---
## Path 클래스

경로를 조작하는 메서드를 제공합니다. 이것은 인스턴스 서비스를 갖지 않는 정적 타입입니다. 어떠한 방법으로도 인스턴스를 생성해서는 안 됩니다.

```cpp
class Path
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static [String](../../system/string/) [ChangeExtension](./changeextension/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 지정된 파일 경로의 확장자를 변경합니다. |
| static void [CheckPath](./checkpath/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | 지정된 경로에 잘못된 문자가 포함되어 있는지 확인하여 경로가 유효한지 판단합니다. 경로에 잘못된 문자가 포함되어 있으면 예외가 발생합니다. |
| static [String](../../system/string/) [Combine](./combine/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | 필요에 따라 세그먼트 사이에 디렉터리 구분자를 삽입하여 지정된 경로 세그먼트를 하나의 경로로 결합합니다. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 필요에 따라 세그먼트 사이에 디렉터리 구분자를 삽입하여 두 개의 지정된 경로 세그먼트를 하나의 경로로 결합합니다. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 필요에 따라 세그먼트 사이에 디렉터리 구분자를 삽입하여 세 개의 지정된 경로 세그먼트를 하나의 경로로 결합합니다. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 필요에 따라 세그먼트 사이에 디렉터리 구분자를 삽입하여 네 개의 지정된 경로 세그먼트를 하나의 경로로 결합합니다. |
| static [String](../../system/string/) [GetDirectoryName](./getdirectoryname/)(const [String](../../system/string/)\&) | 지정된 경로가 참조하는 디렉터리 이름을 반환합니다. |
| static [String](../../system/string/) [GetExtension](./getextension/)(const [String](../../system/string/)\&) | 지정된 경로가 참조하는 파일의 확장자를 반환합니다. |
| static [String](../../system/string/) [GetFileName](./getfilename/)(const [String](../../system/string/)\&) | 지정된 경로가 참조하는 파일 이름을 반환합니다. |
| static [String](../../system/string/) [GetFileNameWithoutExtension](./getfilenamewithoutextension/)(const [String](../../system/string/)\&) | 지정된 경로가 참조하는 파일의 확장자 없는 이름을 반환합니다. |
| static [String](../../system/string/) [GetFullPath](./getfullpath/)(const [String](../../system/string/)\&) | 지정된 경로를 절대 경로로 변환합니다. |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidFileNameChars](./getinvalidfilenamechars/)() | 파일 이름에 허용되지 않는 문자들을 포함하는 배열을 반환합니다. |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidPathChars](./getinvalidpathchars/)() | 경로 이름에 허용되지 않는 문자들을 포함하는 배열을 반환합니다. |
| static [String](../../system/string/) [GetPathRoot](./getpathroot/)(const [String](../../system/string/)\&) | 지정된 경로의 루트 디렉터리를 반환합니다. |
| static [String](../../system/string/) [GetRandomFileName](./getrandomfilename/)() | 무작위로 생성된 파일 이름을 반환합니다. |
| static [String](../../system/string/) [GetTempFileName_](./gettempfilename_/)() | 고유한 이름의 새 파일을 생성하고 해당 파일의 전체 경로를 반환합니다. |
| static [String](../../system/string/) [GetTempFileNameSafe](./gettempfilenamesafe/)() | 고유한 이름의 새 파일을 생성하고 해당 파일의 전체 경로를 반환합니다. [GetTempFileName_()](./gettempfilename_/) 메서드와 동의어입니다. |
| static [String](../../system/string/) [GetTempPath](./gettemppath/)() | 현재 사용자의 임시 디렉터리 경로를 반환합니다. |
| static **bool** [HasExtension](./hasextension/)(const [String](../../system/string/)\&) | 지정된 경로가 확장자를 가진 파일을 참조하는지 판단합니다. |
| static **bool** [IsPathRooted](./ispathrooted/)(const [String](../../system/string/)\&) | 지정된 경로에 루트가 포함되어 있는지 판단합니다. |
| static [String](../../system/string/) [NormalizePath](./normalizepath/)(const [String](../../system/string/)\&) | 지정된 경로를 정규화합니다. |
| static boost::filesystem::path [ToBoost](./toboost/)(const [String](../../system/string/)\&) | 지정된 경로를 나타내는 boost::filesystem::path 클래스의 인스턴스를 반환합니다. |
| static [String](../../system/string/) [ToString](./tostring/)(const boost::filesystem::path\&) | 지정된 Boost의 경로 객체를 문자열 형태로 반환합니다. |

## 필드

| 필드 | 설명 |
| --- | --- |
| static [AltDirectorySeparatorChar](./altdirectoryseparatorchar/) | 경로에서 디렉터리 수준을 구분하는 데 사용되는 대체 문자입니다. |
| static [DirectorySeparatorChar](./directoryseparatorchar/) | 경로에서 디렉터리 수준을 구분하는 데 사용되는 문자입니다. |
| static [PathSeparator](./pathseparator/) | 환경 변수에서 경로 문자열을 구분하는 데 사용되는 구분자 문자입니다. |
| static [VolumeSeparatorChar](./volumeseparatorchar/) | 볼륨 구분자 문자입니다. |

## 비고



```cpp
#include "system/io/path.h"
#include <iostream>

int main()
{
  using namespace System::IO;

  // 무작위 파일 이름을 생성합니다.
  auto filename = Path::GetRandomFileName();

  // 파일 이름에 대한 정보를 출력합니다.
  std::cout <<
    "Filename: " << Path::GetFileName(filename) << std::endl <<
    "Filename w/o an extension: " << Path::GetFileNameWithoutExtension(filename) << std::endl <<
    "Extension: " << Path::GetExtension(filename) << std::endl;

  return 0;
}
/*
이 코드 예제는 다음 출력 결과를 생성합니다:
파일 이름: qhuzkyqv.y6p
확장자 없는 파일 이름: qhuzkyqv
확장자: .y6p
*/
```

## 또 보기

* 네임스페이스 [System::IO](../)
* 라이브러리 [Aspose.Slides](../../)