---
title: ConformanceLevel
second_title: Aspose.Slides for C++ API 참조
description: XmlReader 및 XmlWriter 객체가 수행하는 입력 또는 출력 검사의 양을 지정합니다.
type: docs
weight: 625
url: /ko/system.xml/conformancelevel/
---
## ConformanceLevel 열거형

[XmlReader](../xmlreader/) 및 [XmlWriter](../xmlwriter/) 객체가 수행하는 입력 또는 출력 검사량을 지정합니다.

```cpp
enum class ConformanceLevel
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Auto | 0 | [XmlReader](../xmlreader/) 또는 [XmlWriter](../xmlwriter/) 객체는 문서 수준인지 조각 수준인지 확인을 수행해야 하는지를 자동으로 감지하고 적절한 검사를 수행합니다. 다른 [XmlReader](../xmlreader/) 또는 [XmlWriter](../xmlwriter/) 객체를 래핑하는 경우, 외부 객체는 추가적인 적합성 검사를 수행하지 않습니다. 적합성 검사는 기본 객체에 맡겨집니다. |
| Fragment | 1 | XML 데이터는 W3C에서 정의한 [well-formed XML fragment](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities)입니다. 이 적합성 수준은 루트 요소가 없을 수 있지만 그 외에는 잘 형성된 XML 문서를 나타냅니다. 이 수준의 검사는 읽거나 쓰는 스트림이 어떤 프로세서에 의해 [XML 1.0 external parsed entity](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities)으로 사용될 수 있음을 보장합니다. |
| Document | 2 | XML 데이터는 W3C에서 정의한 잘 형성된 [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed)의 규칙을 준수합니다. 이 수준의 검사는 읽거나 쓰는 스트림이 어떤 프로세서에 의해 [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed)으로 사용될 수 있음을 보장합니다. |

## 참고

* 네임스페이스 [System::Xml](../)
* 라이브러리 [Aspose.Slides](../../)