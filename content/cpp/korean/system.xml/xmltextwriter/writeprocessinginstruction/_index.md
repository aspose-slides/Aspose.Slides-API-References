---
title: WriteProcessingInstruction()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "이름과 텍스트 사이에 공백을 두고 다음과 같이 처리 지시문을 출력합니다: <?name text?>."
type: docs
weight: 326
url: /ko/system.xml/xmltextwriter/writeprocessinginstruction/
---
## XmlTextWriter::WriteProcessingInstruction(String, String) 메서드

이름과 텍스트 사이에 공백을 두고 처리 지시문을 다음과 같이 출력합니다: **<?name text?>**.

```cpp
void System::Xml::XmlTextWriter::WriteProcessingInstruction(String name, String text) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 처리 지시문의 이름. |
| text | [String](../../../system/string/) | 처리 지시문에 포함할 [Text](../../../system.text/). |
## 비고

이 메서드는 [XmlTextWriter::WriteStartDocument](../writestartdocument/)가 이미 호출된 후 XML 선언을 생성하는 데 사용됩니다.
## 또보기

* 클래스 [String](../../../system/string/)
* 클래스 [XmlTextWriter](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)