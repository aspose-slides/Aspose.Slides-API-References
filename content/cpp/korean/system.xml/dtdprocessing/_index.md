---
title: DtdProcessing
second_title: Aspose.Slides for C++ API 레퍼런스
description: DTD를 처리하기 위한 옵션을 지정합니다. DtdProcessing 열거형은 XmlReaderSettings 클래스에서 사용됩니다.
type: docs
weight: 638
url: /ko/system.xml/dtdprocessing/
---
## DtdProcessing 열거형

DTD를 처리하기 위한 옵션을 지정합니다. DtdProcessing 열거형은 [XmlReaderSettings](../xmlreadersettings/) 클래스에서 사용됩니다.

```cpp
enum class DtdProcessing
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Prohibit | 0 | DTD가 발견될 때 DTD가 금지되었다는 메시지를 포함한 XmlException이 발생함을 지정합니다. 이것이 기본 동작입니다. |
| Ignore | 1 | DOCTYPE 요소를 무시합니다. DTD 처리가 이루어지지 않으며, 출력 시 DTD/DOCTYPE이 손실됩니다. |
| Parse | 2 | DTD를 구문 분석하는 데 사용됩니다. |

## 참고

* 네임스페이스 [System::Xml](../)
* 라이브러리 [Aspose.Slides](../../)