---
title: Save()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 파일에 XML 문서를 저장합니다. 지정된 파일이 이미 존재하는 경우, 이 메서드는 파일을 덮어씁니다.
type: docs
weight: 534
url: /ko/system.xml/xmldocument/save/
---
## XmlDocument::Save(String) 메서드

XML 문서를 지정된 파일에 저장합니다. 지정된 파일이 이미 존재하면 이 메서드는 파일을 덮어씁니다.

```cpp
virtual void System::Xml::XmlDocument::Save(String filename)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filename | [String](../../../system/string/) | 문서를 저장하려는 파일의 위치. |

## XmlDocument::Save(SharedPtr\<IO::Stream\>) 메서드

XML 문서를 지정된 스트림에 저장합니다.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::Stream> outStream)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| outStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | 저장하려는 스트림. |

## XmlDocument::Save(SharedPtr\<IO::TextWriter\>) 메서드

XML 문서를 지정된 TextWriter에 저장합니다.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::TextWriter> writer)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| writer | [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\> | 저장하려는 TextWriter. |

## XmlDocument::Save(SharedPtr\<XmlWriter\>) 메서드

XML 문서를 지정된 [XmlWriter](../../xmlwriter/)에 저장합니다.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<XmlWriter> w)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| w | [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../xmlwriter/)\> | 저장하려는 [XmlWriter](../../xmlwriter/). |

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [XmlDocument](../)
* 클래스 [Stream](../../../system.io/stream/)
* 클래스 [TextWriter](../../../system.io/textwriter/)
* 클래스 [XmlWriter](../../xmlwriter/)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)