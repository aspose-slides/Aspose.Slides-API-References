---
title: Compile()
second_title: Aspose.Slides for C++ API 레퍼런스
description: XML SchemaObject Model(SOM)을 검증을 위한 스키마 정보로 컴파일합니다. 프로그래밍 방식으로 구축된 SOM의 구문 및 의미 구조를 확인하는 데 사용됩니다. 의미 검증은 컴파일 중에 수행됩니다.
type: docs
weight: 352
url: /ko/system.xml.schema/xmlschema/compile/
---
## XmlSchema::Compile(ValidationEventHandler) 메서드


XML [Schema](../../)[Object](../../../system/object/) 모델(SOM)을 검증을 위한 스키마 정보로 컴파일합니다. 프로그래밍 방식으로 구축된 SOM의 구문 및 의미 구조를 확인하는 데 사용됩니다. 의미 검증은 컴파일 중에 수행됩니다.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | XML [Schema](../../) 검증 오류에 대한 정보를 받는 검증 이벤트 처리기. |

## XmlSchema::Compile(ValidationEventHandler, const SharedPtr\<XmlResolver\>\&) 메서드


XML [Schema](../../)[Object](../../../system/object/) 모델(SOM)을 검증을 위한 스키마 정보로 컴파일합니다. 프로그래밍 방식으로 구축된 SOM의 구문 및 의미 구조를 확인하는 데 사용됩니다. 의미 검증은 컴파일 중에 수행됩니다.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler, const SharedPtr<XmlResolver> &resolver)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | XML [Schema](../../) 검증 오류에 대한 정보를 받는 검증 이벤트 처리기. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | **include** 및 **import** 요소에서 참조된 네임스페이스를 해석하는 데 사용되는 [XmlResolver](../../../system.xml/xmlresolver/). |

## See Also

* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlSchema](../)
* 클래스 [XmlResolver](../../../system.xml/xmlresolver/)
* 네임스페이스 [System::Xml::Schema](../../)
* 라이브러리 [Aspose.Slides](../../../)