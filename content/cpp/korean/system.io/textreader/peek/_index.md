---
title: Peek()
second_title: Aspose.Slides for C++ API 참조
description: 스트림에서 단일 문자를 읽지만 스트림의 읽기 커서를 변경하지 않습니다.
type: docs
weight: 27
url: /ko/system.io/textreader/peek/
---
## TextReader::Peek() 메서드

스트림에서 단일 문자를 읽고 스트림의 읽기 커서를 변경하지 않습니다.

```cpp
virtual int System::IO::TextReader::Peek()
```

### 반환 값

UTF-16 인코딩으로 인코드된 읽은 문자; 읽은 문자가 UTF-16 인코딩에서 두 개의 코드포인트로 표현되는 경우 높은 서러게이트만 반환됩니다; 문자를 읽지 못한 경우 -1이 반환됩니다

## 참조

* 클래스 [TextReader](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)