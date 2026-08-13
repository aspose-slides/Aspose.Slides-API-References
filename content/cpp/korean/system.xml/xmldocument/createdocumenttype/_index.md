---
title: CreateDocumentType()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새로운 XmlDocumentType 객체를 반환합니다.
type: docs
weight: 313
url: /ko/system.xml/xmldocument/createdocumenttype/
---
## XmlDocument::CreateDocumentType(const String\&, const String\&, const String\&, const String\&) 메서드

새로운 [XmlDocumentType](../../xmldocumenttype/) 객체를 반환합니다.

```cpp
virtual SharedPtr<XmlDocumentType> System::Xml::XmlDocument::CreateDocumentType(const String &name, const String &publicId, const String &systemId, const String &internalSubset)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | 문서 유형의 이름입니다. |
| publicId | const [String](../../../system/string/)\& | 문서 유형의 공개 식별자 또는 **nullptr**입니다. 외부 DTD 서브셋의 위치를 지정하기 위해 공개 URI와 시스템 식별자를 지정할 수 있습니다. |
| systemId | const [String](../../../system/string/)\& | 문서 유형의 시스템 식별자 또는 **nullptr**입니다. 외부 DTD 서브셋의 파일 위치 URL을 지정합니다. |
| internalSubset | const [String](../../../system/string/)\& | 문서 유형의 DTD 내부 서브셋 또는 **nullptr**입니다. |

### 반환값

새로운 [XmlDocumentType](../../xmldocumenttype/)입니다.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlDocumentType](../../xmldocumenttype/)
* 클래스 [String](../../../system/string/)
* 클래스 [XmlDocument](../)
* 네임스페이스 [System::Xml](../../)
* Library [Aspose.Slides](../../../)