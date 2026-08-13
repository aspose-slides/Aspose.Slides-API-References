---
title: get_NameTable()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 원자화된 문자열 비교에 사용되는 XmlNameTable을 반환합니다.
type: docs
weight: 1
url: /ko/system.xml/xmlreadersettings/get_nametable/
---
## XmlReaderSettings::get_NameTable() 메서드

원자화된 문자열 비교에 사용되는 [XmlNameTable](../../xmlnametable/)를 반환합니다.

```cpp
SharedPtr<XmlNameTable> System::Xml::XmlReaderSettings::get_NameTable()
```

### 반환 값

[XmlNameTable](../../xmlnametable/)는 이 [XmlReaderSettings](../) 객체를 사용하여 생성된 모든 [XmlReader](../../xmlreader/) 인스턴스가 사용하는 모든 원자화된 문자열을 저장합니다. 기본값은 **nullptr**입니다. 생성된 [XmlReader](../../xmlreader/) 인스턴스는 이 값이 **nullptr**인 경우 새로운 빈 [NameTable](../../nametable/)을 사용합니다.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlNameTable](../../xmlnametable/)
* 클래스 [XmlReaderSettings](../)
* 네임스페이스 [System::Xml](../../)
* Library [Aspose.Slides](../../../)