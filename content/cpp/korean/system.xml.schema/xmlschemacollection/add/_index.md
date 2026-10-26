---
title: Add()
second_title: Aspose.Slides for C++ API 참조
description: 주어진 URL에 위치한 스키마를 스키마 컬렉션에 추가합니다.
type: docs
weight: 40
url: /ko/system.xml.schema/xmlschemacollection/add/
---
## XmlSchemaCollection::Add(const String\&, const String\&) 메서드

지정된 URL에 위치한 스키마를 스키마 컬렉션에 추가합니다.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const String &uri)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | 스키마와 연결된 네임스페이스 URI. XML 스키마의 경우 일반적으로 **targetNamespace** 입니다. |
| uri | const [String](../../../system/string/)\& | 로드할 스키마를 지정하는 URL입니다. |

### 반환 값

[XmlSchema](../../xmlschema/) 를 스키마 컬렉션에 추가한 결과; 추가되는 스키마가 XDR 스키마이거나 스키마에 컴파일 오류가 있는 경우 **nullptr** 반환.

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&) 메서드

[XmlReader](../../../system.xml/xmlreader/)에 포함된 스키마를 스키마 컬렉션에 추가합니다.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | 스키마와 연결된 네임스페이스 URI. XML 스키마의 경우 일반적으로 **targetNamespace** 입니다. |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 추가할 스키마를 포함하는 [XmlReader](../../../system.xml/xmlreader/). |

### 반환 값

[XmlSchema](../../xmlschema/) 를 스키마 컬렉션에 추가한 결과; 추가되는 스키마가 XDR 스키마이거나 스키마에 컴파일 오류가 있는 경우 **nullptr** 반환.

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) 메서드

[XmlReader](../../../system.xml/xmlreader/)에 포함된 스키마를 스키마 컬렉션에 추가합니다. 지정된 [XmlResolver](../../../system.xml/xmlresolver/)는 외부 리소스를 해결하는 데 사용됩니다.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | 스키마와 연결된 네임스페이스 URI. XML 스키마의 경우 일반적으로 **targetNamespace** 입니다. |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 추가할 스키마를 포함하는 [XmlReader](../../../system.xml/xmlreader/). |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | **include** 및 **import** 요소 또는 **x-schema** 속성(XDR 스키마)에서 참조되는 네임스페이스를 해결하는 데 사용되는 [XmlResolver](../../../system.xml/xmlresolver/). 이 값이 **nullptr**이면 외부 참조가 해결되지 않습니다. |

### 반환 값

[XmlSchema](../../xmlschema/) 를 스키마 컬렉션에 추가한 결과; 추가되는 스키마가 XDR 스키마이거나 스키마에 컴파일 오류가 있는 경우 **nullptr** 반환.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&) 메서드

[XmlSchema](../../xmlschema/)를 컬렉션에 추가합니다.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | 컬렉션에 추가할 [XmlSchema](../../xmlschema/). |

### 반환 값

[XmlSchema](../../xmlschema/) 객체를 반환합니다.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) 메서드

[XmlSchema](../../xmlschema/)를 컬렉션에 추가합니다. 지정된 [XmlResolver](../../../system.xml/xmlresolver/)는 외부 참조를 해결하는 데 사용됩니다.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | 컬렉션에 추가할 [XmlSchema](../../xmlschema/). |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | **include** 및 **import** 요소에서 참조되는 네임스페이스를 해결하는 데 사용되는 [XmlResolver](../../../system.xml/xmlresolver/). 이 값이 **nullptr**이면 외부 참조가 해결되지 않습니다. |

### 반환 값

스키마 컬렉션에 추가된 [XmlSchema](../../xmlschema/).

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchemaCollection\>\&) 메서드

주어진 컬렉션에 정의된 모든 네임스페이스(연관된 스키마 포함)를 이 컬렉션에 추가합니다.

```cpp
void System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchemaCollection> &schema)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaCollection](../)\>\& | 이 컬렉션에 추가하려는 [XmlSchemaCollection](../). |

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlSchemaCollection](../)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)