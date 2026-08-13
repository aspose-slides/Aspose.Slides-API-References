---
title: WriteSurrogateCharEntity()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 대리 문자 쌍에 대한 대리 문자 엔터티를 생성하고 기록합니다.
type: docs
weight: 391
url: /ko/system.xml/xmltextwriter/writesurrogatecharentity/
---
## XmlTextWriter::WriteSurrogateCharEntity(char16_t, char16_t) 메서드


대리 문자 쌍에 대한 대리 문자 엔터티를 생성하고 기록합니다.

```cpp
void System::Xml::XmlTextWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lowChar | char16_t | 낮은 서러게이트입니다. 이 값은 **0xDC00**와 **0xDFFF** 사이여야 합니다. |
| highChar | char16_t | 높은 서러게이트입니다. 이 값은 **0xD800**와 **0xDBFF** 사이여야 합니다. |

## 참고

* 클래스 [XmlTextWriter](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)