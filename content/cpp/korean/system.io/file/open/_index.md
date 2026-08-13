---
title: Open()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 파일을 지정된 모드로 열어 읽기 및 쓰기를 수행하며 공유를 하지 않습니다.
type: docs
weight: 235
url: /ko/system.io/file/open/
---
## File::Open(const String\&, FileMode) method


지정된 파일을 지정된 모드로 열어 읽기 및 쓰기를 수행하며 공유를 하지 않습니다.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode)
```


### Arguments

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 열 파일의 경로 |
| mode | [FileMode](../../filemode/) | 파일을 여는 모드를 지정합니다. |

### Return Value

A [FileStream](../../filestream/) object associated with the opened file

## File::Open(const String\&, FileMode, FileAccess, FileShare) method


지정된 파일을 지정된 모드로 열고, 지정된 접근 유형 및 공유 옵션을 사용합니다.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::None)
```


### Arguments

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 열 파일의 경로 |
| mode | [FileMode](../../filemode/) | 파일을 여는 모드를 지정합니다. |
| access | [FileAccess](../../fileaccess/) | 요청된 접근 유형 |
| share | [FileShare](../../fileshare/) | 다른 [FileStream](../../filestream/) 객체가 열린 파일에 대해 갖는 접근 유형 |

### Return Value

A [FileStream](../../filestream/) object associated with the opened file

## See Also

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)