---
title: WriteState
second_title: Aspose.Slides for C++ API 참조
description: XmlWriter의 상태를 지정합니다.
type: docs
weight: 755
url: /ko/system.xml/writestate/
---
## WriteState 열거형

[XmlWriter](../xmlwriter/)의 상태를 지정합니다.

```cpp
enum class WriteState
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Start | 0 | XmlWriter::Write 메서드가 아직 호출되지 않았음을 나타냅니다. |
| Prolog | 1 | 프로로그가 작성되고 있음을 나타냅니다. |
| Element | 2 | 요소 시작 태그가 작성되고 있음을 나타냅니다. |
| Attribute | 3 | 속성 값이 작성되고 있음을 나타냅니다. |
| Content | 4 | 요소 내용이 작성되고 있음을 나타냅니다. |
| Closed | 5 | [XmlWriter::Close](../xmlwriter/close/) 메서드가 호출되었음을 나타냅니다. |
| Error | 6 | 예외가 발생하여 [XmlWriter](../xmlwriter/)이(가) 잘못된 상태가 되었습니다. [XmlWriter::Close](../xmlwriter/close/) 메서드를 호출하여 [XmlWriter](../xmlwriter/)을(를) [WriteState::Closed](./) 상태로 만들 수 있습니다. 다른 [XmlWriter](../xmlwriter/) 메서드 호출은 InvalidOperationException을 발생시킵니다. |

## 참고

* 네임스페이스 [System::Xml](../)
* 라이브러리 [Aspose.Slides](../../)