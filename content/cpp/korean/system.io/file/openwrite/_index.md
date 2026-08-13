---
title: OpenWrite()
second_title: C++용 Aspose.Slides API 참조
description: 지정된 파일을 쓰기 전용으로 열며, 공유 없이 'OpenOrCreate' 모드로 엽니다.
type: docs
weight: 274
url: /ko/system.io/file/openwrite/
---
## File::OpenWrite(const String\&) 메서드

지정된 파일을 쓰기 전용으로 열며, 'OpenOrCreate' 모드이며 공유가 없습니다.

```cpp
static FileStreamPtr System::IO::File::OpenWrite(const String &path)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 열 파일의 경로 |

### 반환 값

열린 파일과 연결된 [FileStream](../../filestream/) 객체

## 참조

* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [File](../)
* 네임스페이스 [System::IO](../../)
* Library [Aspose.Slides](../../../)