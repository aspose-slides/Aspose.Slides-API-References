---
title: CheckPath()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 경로에 잘못된 문자가 포함되어 있는지 확인하여 경로가 유효한지 판단합니다. 경로에 잘못된 문자가 포함된 경우 예외가 발생합니다.
type: docs
weight: 209
url: /ko/system.io/path/checkpath/
---
## Path::CheckPath(const String\&, const String\&, bool) 메서드

지정된 경로에 잘못된 문자가 포함되어 있는지 확인하여 경로가 유효한지 판단합니다. 경로에 잘못된 문자가 포함된 경우 예외가 발생합니다.

```cpp
static void System::IO::Path::CheckPath(const String &path, const String &msg=s_msg_path, bool allow_empty=1)
```

### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 검사할 경로 |
| msg | const [String](../../../system/string/)\& | 예외 객체의 생성자에 전달할 메시지 |
| allow_empty | **bool** | 빈 문자열 또는 null 문자열을 올바른 경로로 간주할지 여부를 지정합니다 (true) 또는 그렇지 않음 (false); 이 매개변수가 false이고 **path**가 비어 있으면 ArgumentException이 발생합니다; 이 매개변수가 false이고 **path**가 null이면 ArgumentNullException이 발생합니다 |

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [Path](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)