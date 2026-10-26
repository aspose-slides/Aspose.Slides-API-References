---
title: Replace()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 대상 파일의 내용을 현재 FileInfo 객체가 나타내는 파일로 교체하고, 교체된 파일의 백업을 생성합니다.
type: docs
weight: 131
url: /ko/system.io/fileinfo/replace/
---
## FileInfo::Replace(const String\&, const String\&) 메서드


지정된 대상 파일의 내용을 현재 [FileInfo](../) 객체가 나타내는 파일로 교체하고, 교체된 파일의 백업을 생성합니다.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | 교체할 파일의 이름 |
| destinationBackupFileName | const [String](../../../system/string/)\& | 백업 파일의 이름 |

### 반환 값

**destinationFileName**이 가리키는 파일을 나타내는 FileInfor 객체

## FileInfo::Replace(const String\&, const String\&, bool) 메서드


지정된 대상 파일의 내용을 현재 [FileInfo](../) 객체가 나타내는 파일로 교체하고, 교체된 파일의 백업을 생성합니다.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | 교체할 파일의 이름 |
| destinationBackupFileName | const [String](../../../system/string/)\& | 백업 파일의 이름 |
| ignoreMetadataErrors | **bool** | 교체된 파일에서 교체 파일로의 병합 오류를 무시할지 여부를 지정합니다 (true이면 무시, false이면 무시하지 않음) |

### 반환 값

**destinationFileName**이 가리키는 파일을 나타내는 FileInfor 객체

## 또 보기

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [FileInfo](../)
* 네임스페이스 [System::IO](../../)
* Library [Aspose.Slides](../../../)