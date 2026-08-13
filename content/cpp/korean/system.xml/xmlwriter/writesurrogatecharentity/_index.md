---
title: WriteSurrogateCharEntity()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 파생 클래스에서 재정의될 경우, 대리 문자 쌍에 대한 대리 문자 엔터티를 생성하고 기록합니다.
type: docs
weight: 261
url: /ko/system.xml/xmlwriter/writesurrogatecharentity/
---
## XmlWriter::WriteSurrogateCharEntity(char16_t, char16_t) 메서드

파생 클래스에서 재정의될 경우, 대리 문자 쌍에 대한 대리 문자 엔터티를 생성하고 기록합니다.

```cpp
virtual void System::Xml::XmlWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lowChar | char16_t | 낮은 대리 문자입니다. 이는 0xDC00에서 0xDFFF 사이의 값이어야 합니다. |
| highChar | char16_t | 높은 대리 문자입니다. 이는 0xD800에서 0xDBFF 사이의 값이어야 합니다. |

## 참조

* 클래스 [XmlWriter](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)