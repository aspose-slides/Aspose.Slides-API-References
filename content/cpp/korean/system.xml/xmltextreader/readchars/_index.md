---
title: ReadChars()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 요소의 텍스트 내용을 문자 버퍼에 읽어들입니다. 이 메서드는 임베디드 텍스트의 대용량 스트림을 연속적으로 호출하여 읽도록 설계되었습니다.
type: docs
weight: 755
url: /ko/system.xml/xmltextreader/readchars/
---
## XmlTextReader::ReadChars(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) 메서드

요소의 텍스트 내용을 문자 버퍼에 읽어들입니다. 이 메서드는 임베디드 텍스트의 대용량 스트림을 연속적으로 호출하여 읽도록 설계되었습니다.

```cpp
int32_t System::Xml::XmlTextReader::ReadChars(const ArrayPtr<char16_t> &buffer, int32_t index, int32_t count)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | 텍스트 내용이 기록되는 버퍼 역할을 하는 문자 배열. |
| index | **int32_t** | **buffer** 내에서 메서드가 텍스트 내용을 쓰기 시작할 수 있는 위치. |
| count | **int32_t** | **buffer**에 기록할 문자 수. |

### 반환 값

읽은 문자 수입니다. 리더가 요소에 위치하지 않았거나 현재 컨텍스트에서 반환할 텍스트 내용이 더 이상 없을 경우 0이 될 수 있습니다.

## 참고

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [XmlTextReader](../)
* 네임스페이스 [System::Xml](../../)
* Library [Aspose.Slides](../../../)