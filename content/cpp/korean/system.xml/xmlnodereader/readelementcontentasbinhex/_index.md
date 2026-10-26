---
title: ReadElementContentAsBinHex()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 요소를 읽고 BinHex 콘텐츠를 디코딩합니다.
type: docs
weight: 482
url: /ko/system.xml/xmlnodereader/readelementcontentasbinhex/
---
## XmlNodeReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) 메서드

버퍼를 읽고 BinHex 콘텐츠를 디코딩합니다.

```cpp
int32_t System::Xml::XmlNodeReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 결과 텍스트를 복사할 버퍼입니다. 이 값은 **nullptr**일 수 없습니다. |
| index | **int32_t** | 결과 복사를 시작할 버퍼의 오프셋입니다. |
| count | **int32_t** | 버퍼에 복사할 최대 바이트 수입니다. 실제 복사된 바이트 수는 이 메서드에서 반환됩니다. |

### 반환 값

버퍼에 기록된 바이트 수입니다.

## 참조

* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [XmlNodeReader](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)