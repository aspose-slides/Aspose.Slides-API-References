---
title: ReadElementContentAsBinHex()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 요소를 읽고 BinHex 콘텐츠를 디코딩합니다.
type: docs
weight: 677
url: /ko/system.xml/xmltextreader/readelementcontentasbinhex/
---
## XmlTextReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) 메서드

요소를 읽고 **BinHex** 콘텐츠를 디코딩합니다.

```cpp
int32_t System::Xml::XmlTextReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 결과 텍스트를 복사할 버퍼. 이 값은 **nullptr**일 수 없습니다. |
| index | **int32_t** | 버퍼에서 결과 복사를 시작할 오프셋. |
| count | **int32_t** | 버퍼에 복사할 최대 바이트 수. 실제 복사된 바이트 수는 이 메서드의 반환값입니다. |

### 반환값

버퍼에 기록된 바이트 수.

## 참고

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [XmlTextReader](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)