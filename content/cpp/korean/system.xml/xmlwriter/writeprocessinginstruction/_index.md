---
title: WriteProcessingInstruction()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "파생 클래스에서 오버라이드될 경우, 이름과 텍스트 사이에 공백이 있는 처리 지시문을 다음과 같이 작성합니다: <?name text?>."
type: docs
weight: 196
url: /ko/system.xml/xmlwriter/writeprocessinginstruction/
---
## XmlWriter::WriteProcessingInstruction(String, String) 메서드

When overridden in a derived class, writes out a processing instruction with a space between the name and text as follows: **<?name text?>**.

```cpp
virtual void System::Xml::XmlWriter::WriteProcessingInstruction(String name, String text)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 처리 지시문의 이름입니다. |
| text | [String](../../../system/string/) | 처리 지시문에 포함할 텍스트입니다. |

## 비고

이 메서드는 [XmlWriter::WriteStartDocument](../writestartdocument/)가 이미 호출된 후 XML 선언을 생성하는 데 사용됩니다.

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [XmlWriter](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)