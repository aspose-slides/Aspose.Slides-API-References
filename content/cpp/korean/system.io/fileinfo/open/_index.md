---
title: Open()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 객체가 나타내는 파일을 지정된 모드로 열어 읽기 및 쓰기를 수행하고 공유하지 않습니다.
type: docs
weight: 183
url: /ko/system.io/fileinfo/open/
---
## FileInfo::Open(FileMode) 메서드

현재 객체가 나타내는 파일을 지정된 모드로 열어 읽기 및 쓰기를 수행하고 공유하지 않습니다.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | 파일을 열 모드를 지정합니다 |

### 반환 값

현재 객체가 나타내는 파일과 연관된 [FileStream](../../filestream/) 객체

## FileInfo::Open(FileMode, FileAccess) 메서드

현재 객체가 나타내는 파일을 지정된 모드와 지정된 접근 유형으로 열고 공유하지 않습니다.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | 파일을 열 모드를 지정합니다 |
| access | [FileAccess](../../fileaccess/) | 요청된 접근 유형 |

### 반환 값

현재 객체가 나타내는 파일과 연관된 [FileStream](../../filestream/) 객체

## FileInfo::Open(FileMode, FileAccess, FileShare) 메서드

현재 객체가 나타내는 파일을 지정된 모드와 지정된 접근 유형 및 공유 옵션으로 엽니다.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access, FileShare share)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | 파일을 열 모드를 지정합니다 |
| access | [FileAccess](../../fileaccess/) | 요청된 접근 유형 |
| share | [FileShare](../../fileshare/) | 다른 [FileStream](../../filestream/) 객체가 열린 파일에 대해 갖는 접근 유형 |

### 반환 값

현재 객체가 나타내는 파일과 연관된 [FileStream](../../filestream/) 객체

## 참고

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* 클래스 [FileInfo](../)
* 네임스페이스 [System::IO](../../)
* Library [Aspose.Slides](../../../)