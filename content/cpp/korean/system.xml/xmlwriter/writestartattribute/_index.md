---
title: WriteStartAttribute()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 로컬 이름 및 네임스페이스 URI를 가진 속성의 시작을 기록합니다.
type: docs
weight: 144
url: /ko/system.xml/xmlwriter/writestartattribute/
---
## XmlWriter::WriteStartAttribute(const String\&, const String\&) 메서드

지정된 로컬 이름 및 네임스페이스 URI를 가진 속성의 시작을 기록합니다.

```cpp
void System::Xml::XmlWriter::WriteStartAttribute(const String &localName, const String &ns)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 속성의 로컬 이름입니다. |
| ns | const [String](../../../system/string/)\& | 속성의 네임스페이스 URI입니다. |

## XmlWriter::WriteStartAttribute(const String\&, const String\&, const String\&) 메서드

파생 클래스에서 재정의된 경우, 지정된 접두사, 로컬 이름 및 네임스페이스 URI를 가진 속성의 시작을 기록합니다.

```cpp
virtual void System::Xml::XmlWriter::WriteStartAttribute(const String &prefix, const String &localName, const String &ns)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 속성의 네임스페이스 접두사입니다. |
| localName | const [String](../../../system/string/)\& | 속성의 로컬 이름입니다. |
| ns | const [String](../../../system/string/)\& | 속성의 네임스페이스 URI입니다. |

## XmlWriter::WriteStartAttribute(const String\&) 메서드

지정된 로컬 이름을 가진 속성의 시작을 기록합니다.

```cpp
void System::Xml::XmlWriter::WriteStartAttribute(const String &localName)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 속성의 로컬 이름입니다. |

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [XmlWriter](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)