---
title: ReadValueChunk()
second_title: Aspose.Slides for C++ API 참조
description: XML 문서에 포함된 대용량 텍스트 스트림을 읽습니다.
type: docs
weight: 807
url: /ko/system.xml/xmlreader/readvaluechunk/
---
## XmlReader::ReadValueChunk(ArrayPtr\<char16_t\>, int32_t, int32_t) 메서드

XML 문서에 포함된 큰 텍스트 스트림을 읽습니다.

```cpp
virtual int32_t System::Xml::XmlReader::ReadValueChunk(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | 텍스트 내용을 기록할 버퍼 역할을 하는 문자 배열입니다. 이 값은 **nullptr**일 수 없습니다. |
| index | **int32_t** | 버퍼 내에서 [XmlReader](../)가 결과를 복사하기 시작할 수 있는 오프셋입니다. |
| count | **int32_t** | 버퍼에 복사할 최대 문자 수입니다. 실제 복사된 문자 수는 이 메서드의 반환값입니다. |

### 반환값

버퍼에 읽힌 문자 수입니다. 더 이상 텍스트 내용이 없을 경우 0이 반환됩니다.

## 참고

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [XmlReader](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)