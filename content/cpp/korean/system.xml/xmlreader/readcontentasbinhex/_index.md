---
title: ReadContentAsBinHex()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 콘텐츠를 읽고 BinHex 디코딩된 바이너리 바이트를 반환합니다.
type: docs
weight: 781
url: /ko/system.xml/xmlreader/readcontentasbinhex/
---
## XmlReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) 메서드

콘텐츠를 읽고 **BinHex** 디코딩된 바이너리 바이트를 반환합니다.

```cpp
virtual int32_t System::Xml::XmlReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 결과 텍스트를 복사할 버퍼입니다. 이 값은 **nullptr**일 수 없습니다. |
| index | **int32_t** | 버퍼에서 결과 복사를 시작할 오프셋입니다. |
| count | **int32_t** | 버퍼에 복사할 최대 바이트 수입니다. 실제 복사된 바이트 수는 이 메서드에서 반환됩니다. |

### 반환 값

버퍼에 기록된 바이트 수입니다.

## 또 보기

* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [XmlReader](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)