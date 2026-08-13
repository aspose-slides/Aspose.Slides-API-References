---
title: PeekChar()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 읽기 커서를 변경하지 않고 입력 스트림에서 단일 문자를 읽습니다.
type: docs
weight: 53
url: /ko/system.io/binaryreader/peekchar/
---
## BinaryReader::PeekChar() 메서드

입력 스트림에서 단일 문자를 읽지만 스트림의 읽기 커서를 변경하지 않습니다.

```cpp
virtual int System::IO::BinaryReader::PeekChar()
```

### 반환 값

UTF-16 인코딩으로 인코딩된 읽은 문자; 읽은 문자가 UTF-16 인코딩에서 두 개의 코드포인트로 표현되는 경우 고위 서러게이트만 반환됩니다; 문자를 읽지 못한 경우 -1이 반환됩니다

## 관련 항목

* 클래스 [BinaryReader](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)