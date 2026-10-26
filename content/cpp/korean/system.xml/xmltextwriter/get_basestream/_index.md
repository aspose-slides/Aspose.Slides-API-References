---
title: get_BaseStream()
second_title: Aspose.Slides for C++ API 참조
description: 기본 스트림 객체를 반환합니다.
type: docs
weight: 1
url: /ko/system.xml/xmltextwriter/get_basestream/
---
## XmlTextWriter::get_BaseStream() 메서드

기본 스트림 객체를 반환합니다.

```cpp
SharedPtr<IO::Stream> System::Xml::XmlTextWriter::get_BaseStream()
```

### 반환 값

[XmlTextWriter](../)가 쓰고 있는 스트림 또는 **nullptr**는 [XmlTextWriter](../)가 StreamWriter 클래스를 상속하지 않는 TextWriter를 사용하여 구성된 경우입니다.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Stream](../../../system.io/stream/)
* 클래스 [XmlTextWriter](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)