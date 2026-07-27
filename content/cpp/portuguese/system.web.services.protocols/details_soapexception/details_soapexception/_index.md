---
title: Details_SoapException()
second_title: Referência da API Aspose.Slides for C++
description: Constrói uma nova instância.
type: docs
weight: 92
url: /pt/system.web.services.protocols/details_soapexception/details_soapexception/
---
## Details_SoapException::Details_SoapException() construtor

Constrói uma nova instância.

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException()
```

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>) construtor

Constrói uma nova instância.

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| message | [String](../../../system/string/) | The exception message. |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | The exception code. |

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>, Exception) construtor

Constrói uma nova instância.

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code, Exception innerException)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| message | [String](../../../system/string/) | The exception message. |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | The exception code. |
| innerException | [Exception](../../../system/exception/) | The inner exception. |

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>, String) construtor

Constrói uma nova instância.

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code, String actor)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| message | [String](../../../system/string/) | The exception message. |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | The exception code. |
| actor | [String](../../../system/string/) | The code piece where the exception is thrown. |

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>, String, Exception) construtor

Constrói uma nova instância.

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code, String actor, Exception innerException)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| message | [String](../../../system/string/) | The exception message. |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | The exception code. |
| actor | [String](../../../system/string/) | The code piece where the exception is thrown. |
| innerException | [Exception](../../../system/exception/) | The inner exception. |

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>, String, System::SharedPtr\<Xml::XmlNode\>) construtor

Constrói uma nova instância.

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code, String actor, System::SharedPtr<Xml::XmlNode> detail)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| message | [String](../../../system/string/) | The exception message. |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | The exception code. |
| actor | [String](../../../system/string/) | The code piece where the exception is thrown. |
| detail | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlNode](../../../system.xml/xmlnode/)\> | Details about the thrown exception. |

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>, String, System::SharedPtr\<Xml::XmlNode\>, Exception) construtor

Constrói uma nova instância.

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code, String actor, System::SharedPtr<Xml::XmlNode> detail, Exception innerException)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| message | [String](../../../system/string/) | The exception message. |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | The exception code. |
| actor | [String](../../../system/string/) | The code piece where the exception is thrown. |
| detail | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlNode](../../../system.xml/xmlnode/)\> | Details about the thrown exception. |
| innerException | [Exception](../../../system/exception/) | The inner exception. |

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>, System::SharedPtr\<SoapFaultSubCode\>) construtor

Constrói uma nova instância.

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code, System::SharedPtr<SoapFaultSubCode> subcode)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| message | [String](../../../system/string/) | The exception message. |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | The exception code. |
| subcode | [System::SharedPtr](../../../system/sharedptr/)\<SoapFaultSubCode\> | Optional information from the 'subcode' XML element. |

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>, String, String, System::SharedPtr\<Xml::XmlNode\>, System::SharedPtr\<SoapFaultSubCode\>, Exception) construtor

Constrói uma nova instância.

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code, String actor, String role, System::SharedPtr<Xml::XmlNode> detail, System::SharedPtr<SoapFaultSubCode> subcode, Exception innerException)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| message | [String](../../../system/string/) | The exception message. |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | The exception code. |
| actor | [String](../../../system/string/) | The code piece where the exception is thrown. |
| role | [String](../../../system/string/) | The role of the XML web service that throws the exception. |
| detail | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlNode](../../../system.xml/xmlnode/)\> | Details about the thrown exception. |
| subcode | [System::SharedPtr](../../../system/sharedptr/)\<SoapFaultSubCode\> | Optional information from the 'subcode' XML element. |
| innerException | [Exception](../../../system/exception/) | The inner exception. |

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>, String, String, String, System::SharedPtr\<Xml::XmlNode\>, System::SharedPtr\<SoapFaultSubCode\>, Exception) construtor

Constrói uma nova instância.

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code, String actor, String role, String lang, System::SharedPtr<Xml::XmlNode> detail, System::SharedPtr<SoapFaultSubCode> subcode, Exception innerException)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| message | [String](../../../system/string/) | The exception message. |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | The exception code. |
| actor | [String](../../../system/string/) | The code piece where the exception is thrown. |
| role | [String](../../../system/string/) | The role of the XML web service that throws the exception. |
| lang | [String](../../../system/string/) | The language, which is used to localize exception properties. |
| detail | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlNode](../../../system.xml/xmlnode/)\> | Details about the thrown exception. |
| subcode | [System::SharedPtr](../../../system/sharedptr/)\<SoapFaultSubCode\> | Optional information from the 'subcode' XML element. |
| innerException | [Exception](../../../system/exception/) | The inner exception. |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Exception](../../../system/exception/)
* Classe [Details_SoapException](../)
* Classe [String](../../../system/string/)
* Classe [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* Classe [XmlNode](../../../system.xml/xmlnode/)
* Namespace [System::Web::Services::Protocols](../../)
* Biblioteca [Aspose.Slides](../../../)