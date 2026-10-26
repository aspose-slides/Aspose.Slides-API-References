---
title: NewLineHandling
second_title: Aspose.Slides for C++ API 레퍼런스
description: 줄 바꿈을 처리하는 방법을 지정합니다.
type: docs
weight: 690
url: /ko/system.xml/newlinehandling/
---
## NewLineHandling 열거형

줄 바꿈을 처리하는 방법을 지정합니다.

```cpp
enum class NewLineHandling
```

### Values

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Replace | 0 | 새 줄 문자는 [XmlWriterSettings::set_NewLineChars](../xmlwritersettings/set_newlinechars/) 값에 지정된 문자와 일치하도록 교체됩니다. |
| Entitize | 1 | 새 줄 문자는 엔티티화됩니다. 이 설정은 출력이 정규화된 [XmlReader](../xmlreader/)에 의해 읽힐 때 모든 문자를 보존합니다. |
| None | 2 | 새 줄 문자는 변경되지 않습니다. 출력은 입력과 동일합니다. |

## 참고

* 네임스페이스 [System::Xml](../)
* 라이브러리 [Aspose.Slides](../../)