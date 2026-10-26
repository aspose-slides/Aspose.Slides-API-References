---
title: ReadState
second_title: Aspose.Slides for C++ API 레퍼런스
description: 리더의 상태를 지정합니다.
type: docs
weight: 703
url: /ko/system.xml/readstate/
---
## ReadState 열거형

리더의 상태를 지정합니다.

```cpp
enum class ReadState
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Initial | 0 | [XmlReader::Read](../xmlreader/read/) 메서드가 호출되지 않았습니다. |
| Interactive | 1 | [XmlReader::Read](../xmlreader/read/) 메서드가 호출되었습니다. 리더에서 추가 메서드를 호출할 수 있습니다. |
| Error | 2 | 읽기 작업이 계속되지 못하도록 하는 오류가 발생했습니다. |
| EndOfFile | 3 | 파일 끝에 성공적으로 도달했습니다. |
| Closed | 4 | [XmlReader::Close](../xmlreader/close/) 메서드가 호출되었습니다. |

## 참고

* 네임스페이스 [System::Xml](../)
* 라이브러리 [Aspose.Slides](../../)