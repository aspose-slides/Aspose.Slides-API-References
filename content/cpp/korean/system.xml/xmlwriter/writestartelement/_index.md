---
title: WriteStartElement()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 파생 클래스에서 재정의될 경우, 지정된 시작 태그를 작성하고 지정된 네임스페이스와 연결합니다.
type: docs
weight: 92
url: /ko/system.xml/xmlwriter/writestartelement/
---
## XmlWriter::WriteStartElement(const String\&, const String\&) 메서드

파생 클래스에서 재정의될 경우, 지정된 시작 태그를 작성하고 해당 네임스페이스와 연결합니다.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName, const String &ns)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 요소의 로컬 이름입니다. |
| ns | const [String](../../../system/string/)\& | 요소와 연결할 네임스페이스 URI입니다. 이 네임스페이스가 이미 범위 내에 있고 관련된 접두사가 있는 경우, 작성자는 자동으로 해당 접두사도 작성합니다. |

## XmlWriter::WriteStartElement(const String\&, const String\&, const String\&) 메서드

파생 클래스에서 재정의될 경우, 지정된 시작 태그를 작성하고 해당 네임스페이스 및 접두사와 연결합니다.

```cpp
virtual void System::Xml::XmlWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 요소의 네임스페이스 접두사입니다. |
| localName | const [String](../../../system/string/)\& | 요소의 로컬 이름입니다. |
| ns | const [String](../../../system/string/)\& | 요소와 연결할 네임스페이스 URI입니다. |

## XmlWriter::WriteStartElement(const String\&) 메서드

파생 클래스에서 재정의될 경우, 지정된 로컬 이름으로 시작 태그를 작성합니다.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 요소의 로컬 이름입니다. |

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [XmlWriter](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)