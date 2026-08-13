---
title: CopyTo()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 객체가 나타내는 파일을 지정된 위치에 복사합니다. 대상 파일이 이미 존재하면 복사에 실패합니다.
type: docs
weight: 105
url: /ko/system.io/fileinfo/copyto/
---
## FileInfo::CopyTo(const String\&) 메서드

현재 객체가 나타내는 파일을 지정된 위치에 복사합니다. 대상 파일이 이미 존재하면 복사에 실패합니다.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | 대상 파일 이름 |

### 반환 값

복사를 나타내는 [FileInfo](../) 객체

## FileInfo::CopyTo(const String\&, bool) 메서드

현재 객체가 나타내는 파일을 지정된 위치에 복사합니다. 매개변수는 기존 대상 파일을 덮어쓸지 여부를 지정합니다.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName, bool overwrite)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | 대상 파일 이름 |
| overwrite | **bool** | 대상 파일이 이미 존재하면 복사에 실패하고, 기존 대상 파일을 덮어써야 하면 true, 그렇지 않으면 false |

### 반환 값

복사를 나타내는 [FileInfo](../) 객체

## 참고

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [FileInfo](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)