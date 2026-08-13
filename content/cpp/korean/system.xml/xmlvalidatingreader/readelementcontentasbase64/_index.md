---
title: ReadElementContentAsBase64()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 요소를 읽고 Base64 콘텐츠를 디코딩합니다.
type: docs
weight: 586
url: /ko/system.xml/xmlvalidatingreader/readelementcontentasbase64/
---
## XmlValidatingReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) method


요소를 읽고 Base64 콘텐츠를 디코딩합니다.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 결과 텍스트를 복사할 버퍼입니다. 이 값은 **nullptr**일 수 없습니다. |
| index | **int32_t** | 결과를 복사하기 시작할 버퍼 내 오프셋입니다. |
| count | **int32_t** | 버퍼에 복사할 최대 바이트 수입니다. 실제 복사된 바이트 수는 이 메서드에서 반환됩니다. |

### Return Value

버퍼에 기록된 바이트 수입니다.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)