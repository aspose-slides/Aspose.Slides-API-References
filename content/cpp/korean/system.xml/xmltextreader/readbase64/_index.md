---
title: ReadBase64()
second_title: Aspose.Slides for C++ API 레퍼런스
description: Base64를 디코딩하고 디코딩된 바이너리 바이트를 반환합니다.
type: docs
weight: 768
url: /ko/system.xml/xmltextreader/readbase64/
---
## XmlTextReader::ReadBase64(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 메서드

Base64를 디코딩하고 디코딩된 바이너리 바이트를 반환합니다.

```cpp
int32_t System::Xml::XmlTextReader::ReadBase64(const ArrayPtr<uint8_t> &array, int32_t offset, int32_t len)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<**uint8\>\& | 텍스트 내용이 기록되는 버퍼 역할을 하는 문자 배열. |
| offset | **int32_t** | 메서드가 버퍼에 쓰기를 시작할 수 있는 위치를 지정하는 배열의 0 기반 인덱스. |
| len | **int32_t** | 버퍼에 기록할 바이트 수. |

### 반환값

버퍼에 기록된 바이트 수.

## 참고

* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [XmlTextReader](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)