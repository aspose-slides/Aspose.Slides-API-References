---
title: Replace()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 한 파일의 내용을 다른 파일로 교체하고 교체된 파일의 백업을 생성합니다.
type: docs
weight: 339
url: /ko/system.io/file/replace/
---
## File::Replace(const String\&, const String\&, const String\&, bool) 메서드


한 파일의 내용을 다른 파일로 교체하고 교체된 파일의 백업을 생성합니다.

```cpp
static void System::IO::File::Replace(const String &sourceFileName, const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors=1)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceFileName | const [String](../../../system/string/)\& | 교체할 파일의 이름 |
| destinationFileName | const [String](../../../system/string/)\& | 교체될 파일의 이름 |
| destinationBackupFileName | const [String](../../../system/string/)\& | 백업 파일의 이름 |
| ignoreMetadataErrors | **bool** | 교체된 파일에서 교체 파일로의 병합 오류를 무시할지 여부를 지정합니다 (true) 또는 (false) |

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [File](../)
* 네임스페이스 [System::IO](../../)
* Library [Aspose.Slides](../../../)