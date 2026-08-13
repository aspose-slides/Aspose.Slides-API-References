---
title: ReadElementContentAsBase64()
second_title: Aspose.Slides for C++ API 참조
description: 요소를 읽고 Base64 콘텐츠를 디코딩합니다.
type: docs
weight: 768
url: /ko/system.xml/xmlreader/readelementcontentasbase64/
---
## XmlReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) 메서드

요소를 읽고 **Base64** 콘텐츠를 디코딩합니다.

```cpp
virtual int32_t System::Xml::XmlReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 결과 텍스트를 복사할 버퍼입니다. 이 값은 **nullptr**일 수 없습니다. |
| index | **int32_t** | 결과 복사를 시작할 버퍼의 오프셋입니다. |
| count | **int32_t** | 버퍼에 복사할 최대 바이트 수입니다. 실제 복사된 바이트 수는 이 메서드에서 반환됩니다. |

### 반환 값

버퍼에 기록된 바이트 수입니다.

## 참조

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)