---
title: XmlParserContext()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "지정된 XmlNameTable, XmlNamespaceManager, xml:lang 및 xml:space 값을 사용하여 XmlParserContext 클래스의 새 인스턴스를 초기화합니다."
type: docs
weight: 261
url: /ko/system.xml/xmlparsercontext/xmlparsercontext/
---
## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace) constructor

지정된 [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang**, **xml:space** 값을 사용하여 [XmlParserContext](../) 클래스의 새 인스턴스를 초기화합니다.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | 문자열을 원자화하는 데 사용할 [XmlNameTable](../../xmlnametable/)입니다. 이 값이 **nullptr**인 경우, **nsMgr**를 구성하는 데 사용된 이름 테이블이 대신 사용됩니다. 원자화된 문자열에 대한 자세한 내용은 [XmlNameTable](../../xmlnametable/)를 참조하십시오. |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | 네임스페이스 정보를 조회하는 데 사용할 [XmlNamespaceManager](../../xmlnamespacemanager/)이며, **nullptr**일 수 있습니다. |
| xmlLang | const [String](../../../system/string/)\& | **xml:lang** 범위. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | **xml:space** 범위를 나타내는 XmlSpace 값입니다. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) constructor

지정된 [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang**, **xml:space**, 인코딩 값을 사용하여 [XmlParserContext](../) 클래스의 새 인스턴스를 초기화합니다.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | 문자열을 원자화하는 데 사용할 [XmlNameTable](../../xmlnametable/)입니다. 이 값이 **nullptr**인 경우, **nsMgr**를 구성하는 데 사용된 이름 테이블이 대신 사용됩니다. 원자화된 문자열에 대한 자세한 내용은 [XmlNameTable](../../xmlnametable/)를 참조하십시오. |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | 네임스페이스 정보를 조회하는 데 사용할 [XmlNamespaceManager](../../xmlnamespacemanager/)이며, **nullptr**일 수 있습니다. |
| xmlLang | const [String](../../../system/string/)\& | **xml:lang** 범위. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | **xml:space** 범위를 나타내는 XmlSpace 값입니다. |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | 인코딩 설정을 나타내는 Encoding 객체입니다. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace) constructor

지정된 [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), 기본 URI, **xml:lang**, **xml:space**, 문서 유형 값을 사용하여 [XmlParserContext](../) 클래스의 새 인스턴스를 초기화합니다.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | 문자열을 원자화하는 데 사용할 [XmlNameTable](../../xmlnametable/)입니다. 이 값이 **nullptr**인 경우, **nsMgr**를 구성하는 데 사용된 이름 테이블이 대신 사용됩니다. 원자화된 문자열에 대한 자세한 내용은 [XmlNameTable](../../xmlnametable/)를 참조하십시오. |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | 네임스페이스 정보를 조회하는 데 사용할 [XmlNamespaceManager](../../xmlnamespacemanager/)이며, **nullptr**일 수 있습니다. |
| docTypeName | const [String](../../../system/string/)\& | 문서 유형 선언의 이름입니다. |
| pubId | const [String](../../../system/string/)\& | 공용 식별자입니다. |
| sysId | const [String](../../../system/string/)\& | 시스템 식별자입니다. |
| internalSubset | const [String](../../../system/string/)\& | 내부 DTD 서브셋입니다. DTD 서브셋은 엔티티 해석에 사용되며, 문서 검증에는 사용되지 않습니다. |
| baseURI | const [String](../../../system/string/)\& | XML 조각의 기본 URI입니다(조각이 로드된 위치). |
| xmlLang | const [String](../../../system/string/)\& | **xml:lang** 범위. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | **xml:space** 범위를 나타내는 XmlSpace 값입니다. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) constructor

지정된 [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), 기본 URI, **xml:lang**, **xml:space**, 인코딩 및 문서 유형 값을 사용하여 [XmlParserContext](../) 클래스의 새 인스턴스를 초기화합니다.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | 문자열을 원자화하는 데 사용할 [XmlNameTable](../../xmlnametable/)입니다. 이 값이 **nullptr**인 경우, **nsMgr**를 구성하는 데 사용된 이름 테이블이 대신 사용됩니다. 원자화된 문자열에 대한 자세한 내용은 [XmlNameTable](../../xmlnametable/)를 참조하십시오. |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | 네임스페이스 정보를 조회하는 데 사용할 [XmlNamespaceManager](../../xmlnamespacemanager/)이며, **nullptr**일 수 있습니다. |
| docTypeName | const [String](../../../system/string/)\& | 문서 유형 선언의 이름입니다. |
| pubId | const [String](../../../system/string/)\& | 공용 식별자입니다. |
| sysId | const [String](../../../system/string/)\& | 시스템 식별자입니다. |
| internalSubset | const [String](../../../system/string/)\& | 내부 DTD 서브셋입니다. DTD는 엔티티 해석에 사용되며, 문서 검증에는 사용되지 않습니다. |
| baseURI | const [String](../../../system/string/)\& | XML 조각의 기본 URI입니다(조각이 로드된 위치). |
| xmlLang | const [String](../../../system/string/)\& | **xml:lang** 범위. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | **xml:space** 범위를 나타내는 XmlSpace 값입니다. |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | 인코딩 설정을 나타내는 Encoding 객체입니다. |

## 참고

* 열거형 [XmlSpace](../../xmlspace/)
* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlNameTable](../../xmlnametable/)
* 클래스 [XmlNamespaceManager](../../xmlnamespacemanager/)
* 클래스 [String](../../../system/string/)
* 클래스 [XmlParserContext](../)
* 클래스 [Encoding](../../../system.text/encoding/)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)