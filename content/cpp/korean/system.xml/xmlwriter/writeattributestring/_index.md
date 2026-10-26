---
title: WriteAttributeString()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 파생 클래스에서 재정의될 경우, 지정된 로컬 이름, 네임스페이스 URI 및 값을 사용하여 속성을 씁니다.
type: docs
weight: 131
url: /ko/system.xml/xmlwriter/writeattributestring/
---
## XmlWriter::WriteAttributeString(const String\&, const String\&, const String\&) 메서드

파생 클래스에서 재정의될 경우, 지정된 로컬 이름, 네임스페이스 URI 및 값을 사용하여 속성을 씁니다.

```cpp
void System::Xml::XmlWriter::WriteAttributeString(const String &localName, const String &ns, const String &value)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 속성의 로컬 이름입니다. |
| ns | const [String](../../../system/string/)\& | 속성과 연결할 네임스페이스 URI입니다. |
| value | const [String](../../../system/string/)\& | 속성의 값입니다. |

## XmlWriter::WriteAttributeString(const String\&, const String\&) 메서드

파생 클래스에서 재정의될 경우, 지정된 로컬 이름과 값으로 속성을 씁니다.

```cpp
void System::Xml::XmlWriter::WriteAttributeString(const String &localName, const String &value)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 속성의 로컬 이름입니다. |
| value | const [String](../../../system/string/)\& | 속성의 값입니다. |

## XmlWriter::WriteAttributeString(const String\&, const String\&, const String\&, const String\&) 메서드

파생 클래스에서 재정의될 경우, 지정된 접두사, 로컬 이름, 네임스페이스 URI 및 값을 사용하여 속성을 씁니다.

```cpp
void System::Xml::XmlWriter::WriteAttributeString(const String &prefix, const String &localName, const String &ns, const String &value)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 속성의 네임스페이스 접두사입니다. |
| localName | const [String](../../../system/string/)\& | 속성의 로컬 이름입니다. |
| ns | const [String](../../../system/string/)\& | 속성의 네임스페이스 URI입니다. |
| value | const [String](../../../system/string/)\& | 속성의 값입니다. |

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [XmlWriter](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)