---
title: Details_SoapException()
second_title: Aspose.Slides voor C++ API-referentie
description: Construeert een nieuw exemplaar.
type: docs
weight: 92
url: /nl/system.web.services.protocols/details_soapexception/details_soapexception/
---
## Details_SoapException::Details_SoapException() constructor

Construeert een nieuw exemplaar.

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException()
```

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>) constructor

Construeert een nieuw exemplaar.

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| message | [String](../../../system/string/) | Het exceptiebericht. |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | De exceptiecode. |

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>, Exception) constructor

Construeert een nieuw exemplaar.

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code, Exception innerException)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| message | [String](../../../system/string/) | Het exceptiebericht. |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | De exceptiecode. |
| innerException | [Exception](../../../system/exception/) | De interne exceptie. |

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>, String) constructor

Construeert een nieuw exemplaar.

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code, String actor)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| message | [String](../../../system/string/) | Het exceptiebericht. |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | De exceptiecode. |
| actor | [String](../../../system/string/) | Het code-gedeelte waar de exceptie wordt gegooid. |

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>, String, Exception) constructor

Construeert een nieuw exemplaar.

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code, String actor, Exception innerException)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| message | [String](../../../system/string/) | Het exceptiebericht. |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | De exceptiecode. |
| actor | [String](../../../system/string/) | Het code-gedeelte waar de exceptie wordt gegooid. |
| innerException | [Exception](../../../system/exception/) | De interne exceptie. |

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>, String, System::SharedPtr\<Xml::XmlNode\>) constructor

Construeert een nieuw exemplaar.

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code, String actor, System::SharedPtr<Xml::XmlNode> detail)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| message | [String](../../../system/string/) | Het exceptiebericht. |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | De exceptiecode. |
| actor | [String](../../../system/string/) | Het code-gedeelte waar de exceptie wordt gegooid. |
| detail | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlNode](../../../system.xml/xmlnode/)\> | Details over de gegooide exceptie. |

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>, String, System::SharedPtr\<Xml::XmlNode\>, Exception) constructor

Construeert een nieuw exemplaar.

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code, String actor, System::SharedPtr<Xml::XmlNode> detail, Exception innerException)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| message | [String](../../../system/string/) | Het exceptiebericht. |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | De exceptiecode. |
| actor | [String](../../../system/string/) | Het code-gedeelte waar de exceptie wordt gegooid. |
| detail | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlNode](../../../system.xml/xmlnode/)\> | Details over de gegooide exceptie. |
| innerException | [Exception](../../../system/exception/) | De interne exceptie. |

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>, System::SharedPtr\<SoapFaultSubCode\>) constructor

Construeert een nieuw exemplaar.

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code, System::SharedPtr<SoapFaultSubCode> subcode)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| message | [String](../../../system/string/) | Het exceptiebericht. |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | De exceptiecode. |
| subcode | [System::SharedPtr](../../../system/sharedptr/)\<SoapFaultSubCode\> | Optionele informatie uit het XML-element 'subcode'. |

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>, String, String, System::SharedPtr\<Xml::XmlNode\>, System::SharedPtr\<SoapFaultSubCode\>, Exception) constructor

Construeert een nieuw exemplaar.

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code, String actor, String role, System::SharedPtr<Xml::XmlNode> detail, System::SharedPtr<SoapFaultSubCode> subcode, Exception innerException)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| message | [String](../../../system/string/) | Het exceptiebericht. |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | De exceptiecode. |
| actor | [String](../../../system/string/) | Het code-gedeelte waar de exceptie wordt gegooid. |
| role | [String](../../../system/string/) | De rol van de XML-webservice die de exceptie gooit. |
| detail | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlNode](../../../system.xml/xmlnode/)\> | Details over de gegooide exceptie. |
| subcode | [System::SharedPtr](../../../system/sharedptr/)\<SoapFaultSubCode\> | Optionele informatie uit het XML-element 'subcode'. |
| innerException | [Exception](../../../system/exception/) | De interne exceptie. |

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>, String, String, String, System::SharedPtr\<Xml::XmlNode\>, System::SharedPtr\<SoapFaultSubCode\>, Exception) constructor

Construeert een nieuw exemplaar.

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code, String actor, String role, String lang, System::SharedPtr<Xml::XmlNode> detail, System::SharedPtr<SoapFaultSubCode> subcode, Exception innerException)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| message | [String](../../../system/string/) | Het exceptiebericht. |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | De exceptiecode. |
| actor | [String](../../../system/string/) | Het code-gedeelte waar de exceptie wordt gegooid. |
| role | [String](../../../system/string/) | De rol van de XML-webservice die de exceptie gooit. |
| lang | [String](../../../system/string/) | De taal die wordt gebruikt om exceptie-eigenschappen te lokaliseren. |
| detail | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlNode](../../../system.xml/xmlnode/)\> | Details over de gegooide exceptie. |
| subcode | [System::SharedPtr](../../../system/sharedptr/)\<SoapFaultSubCode\> | Optionele informatie uit het XML-element 'subcode'. |
| innerException | [Exception](../../../system/exception/) | De interne exceptie. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Exception](../../../system/exception/)
* Class [Details_SoapException](../)
* Class [String](../../../system/string/)
* Class [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* Class [XmlNode](../../../system.xml/xmlnode/)
* Namespace [System::Web::Services::Protocols](../../)
* Library [Aspose.Slides](../../../)