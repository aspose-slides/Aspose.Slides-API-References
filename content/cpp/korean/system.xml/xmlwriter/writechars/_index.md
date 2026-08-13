---
title: WriteChars()
second_title: Aspose.Slides C++용 API 레퍼런스
description: 파생 클래스에서 재정의될 경우, 텍스트를 한 번에 하나의 버퍼씩 씁니다.
type: docs
weight: 274
url: /ko/system.xml/xmlwriter/writechars/
---
## XmlWriter::WriteChars(ArrayPtr\<char16_t\>, int32_t, int32_t) 메서드


파생 클래스에서 재정의될 경우, 텍스트를 한 번에 하나의 버퍼씩 씁니다.

```cpp
virtual void System::Xml::XmlWriter::WriteChars(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | 작성할 텍스트를 포함하는 문자 배열입니다. |
| index | **int32_t** | 버퍼에서 작성할 텍스트 시작 위치를 나타내는 위치입니다. |
| count | **int32_t** | 작성할 문자 수입니다. |

## 참고

* 타입 정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [XmlWriter](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)