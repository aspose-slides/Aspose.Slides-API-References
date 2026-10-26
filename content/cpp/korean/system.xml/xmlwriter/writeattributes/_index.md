---
title: WriteAttributes()
second_title: Aspose.Slides for C++ API 참조
description: 파생 클래스에서 오버라이드되면, XmlReader의 현재 위치에서 찾은 모든 속성을 기록합니다.
type: docs
weight: 417
url: /ko/system.xml/xmlwriter/writeattributes/
---
## XmlWriter::WriteAttributes(SharedPtr\<XmlReader\>, bool) 메서드

When overridden in a derived class, writes out all the attributes found at the current position in the [XmlReader](../../xmlreader/).

```cpp
virtual void System::Xml::XmlWriter::WriteAttributes(SharedPtr<XmlReader> reader, bool defattr)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | [XmlReader](../../xmlreader/)에서 속성을 복사하는 원본. |
| defattr | **bool** | [XmlReader](../../xmlreader/)에서 기본 속성을 복사하려면 **true**; 그렇지 않으면 **false**. |

## 관련 내용

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlReader](../../xmlreader/)
* 클래스 [XmlWriter](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)