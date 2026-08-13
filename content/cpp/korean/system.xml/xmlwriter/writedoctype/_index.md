---
title: WriteDocType()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 파생 클래스에서 재정의될 경우, 지정된 이름과 선택적 속성을 사용하여 DOCTYPE 선언을 작성합니다.
type: docs
weight: 79
url: /ko/system.xml/xmlwriter/writedoctype/
---
## XmlWriter::WriteDocType(const String\&, const String\&, const String\&, const String\&) 메서드

파생 클래스에서 재정의될 때, 지정된 이름과 선택적 속성을 사용하여 DOCTYPE 선언을 작성합니다.

```cpp
virtual void System::Xml::XmlWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | DOCTYPE의 이름입니다. 비어 있을 수 없습니다. |
| pubid | const [String](../../../system/string/)\& | null이 아니면 PUBLIC "pubid" "sysid"를 추가로 작성하며, 여기서 **pubid**와 **sysid**는 전달된 인수의 값으로 대체됩니다. |
| sysid | const [String](../../../system/string/)\& | **pubid**가 **nullptr**이고 **sysid**가 null이 아니면 SYSTEM "sysid"를 작성하며, 여기서 **sysid**는 이 인수의 값으로 대체됩니다. |
| subset | const [String](../../../system/string/)\& | null이 아니면 [subset]를 작성하며, 여기서 subset은 이 인수의 값으로 대체됩니다. |

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [XmlWriter](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)