---
title: Details_SoapException()
second_title: Référence de l'API Aspose.Slides pour C++
description: Construit une nouvelle instance.
type: docs
weight: 92
url: /fr/system.web.services.protocols/details_soapexception/details_soapexception/
---
## Details_SoapException::Details_SoapException() constructeur


Construit une nouvelle instance.

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException()
```

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>) constructeur


Construit une nouvelle instance.

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| message | [String](../../../system/string/) | Le message de l'exception. |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | Le code de l'exception. |

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>, Exception) constructeur


Construit une nouvelle instance.

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code, Exception innerException)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| message | [String](../../../system/string/) | Le message de l'exception. |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | Le code de l'exception. |
| innerException | [Exception](../../../system/exception/) | L'exception interne. |

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>, String) constructeur


Construit une nouvelle instance.

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code, String actor)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| message | [String](../../../system/string/) | Le message de l'exception. |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | Le code de l'exception. |
| actor | [String](../../../system/string/) | La partie du code où l'exception est levée. |

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>, String, Exception) constructeur


Construit une nouvelle instance.

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code, String actor, Exception innerException)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| message | [String](../../../system/string/) | Le message de l'exception. |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | Le code de l'exception. |
| actor | [String](../../../system/string/) | La partie du code où l'exception est levée. |
| innerException | [Exception](../../../system/exception/) | L'exception interne. |

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>, String, System::SharedPtr\<Xml::XmlNode\>) constructeur


Construit une nouvelle instance.

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code, String actor, System::SharedPtr<Xml::XmlNode> detail)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| message | [String](../../../system/string/) | Le message de l'exception. |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | Le code de l'exception. |
| actor | [String](../../../system/string/) | La partie du code où l'exception est levée. |
| detail | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlNode](../../../system.xml/xmlnode/)\> | Détails concernant l'exception levée. |

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>, String, System::SharedPtr\<Xml::XmlNode\>, Exception) constructeur


Construit une nouvelle instance.

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code, String actor, System::SharedPtr<Xml::XmlNode> detail, Exception innerException)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| message | [String](../../../system/string/) | Le message de l'exception. |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | Le code de l'exception. |
| actor | [String](../../../system/string/) | La partie du code où l'exception est levée. |
| detail | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlNode](../../../system.xml/xmlnode/)\> | Détails concernant l'exception levée. |
| innerException | [Exception](../../../system/exception/) | L'exception interne. |

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>, System::SharedPtr\<SoapFaultSubCode\>) constructeur


Construit une nouvelle instance.

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code, System::SharedPtr<SoapFaultSubCode> subcode)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| message | [String](../../../system/string/) | Le message de l'exception. |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | Le code de l'exception. |
| subcode | [System::SharedPtr](../../../system/sharedptr/)\<SoapFaultSubCode\> | Informations optionnelles provenant de l'élément XML 'subcode'. |

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>, String, String, System::SharedPtr\<Xml::XmlNode\>, System::SharedPtr\<SoapFaultSubCode\>, Exception) constructeur


Construit une nouvelle instance.

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code, String actor, String role, System::SharedPtr<Xml::XmlNode> detail, System::SharedPtr<SoapFaultSubCode> subcode, Exception innerException)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| message | [String](../../../system/string/) | Le message de l'exception. |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | Le code de l'exception. |
| actor | [String](../../../system/string/) | La partie du code où l'exception est levée. |
| role | [String](../../../system/string/) | Le rôle du service Web XML qui lève l'exception. |
| detail | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlNode](../../../system.xml/xmlnode/)\> | Détails concernant l'exception levée. |
| subcode | [System::SharedPtr](../../../system/sharedptr/)\<SoapFaultSubCode\> | Informations optionnelles provenant de l'élément XML 'subcode'. |
| innerException | [Exception](../../../system/exception/) | L'exception interne. |

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>, String, String, String, System::SharedPtr\<Xml::XmlNode\>, System::SharedPtr\<SoapFaultSubCode\>, Exception) constructeur


Construit une nouvelle instance.

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code, String actor, String role, String lang, System::SharedPtr<Xml::XmlNode> detail, System::SharedPtr<SoapFaultSubCode> subcode, Exception innerException)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| message | [String](../../../system/string/) | Le message de l'exception. |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | Le code de l'exception. |
| actor | [String](../../../system/string/) | La partie du code où l'exception est levée. |
| role | [String](../../../system/string/) | Le rôle du service Web XML qui lève l'exception. |
| lang | [String](../../../system/string/) | La langue utilisée pour localiser les propriétés de l'exception. |
| detail | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlNode](../../../system.xml/xmlnode/)\> | Détails concernant l'exception levée. |
| subcode | [System::SharedPtr](../../../system/sharedptr/)\<SoapFaultSubCode\> | Informations optionnelles provenant de l'élément XML 'subcode'. |
| innerException | [Exception](../../../system/exception/) | L'exception interne. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Exception](../../../system/exception/)
* Classe [Details_SoapException](../)
* Classe [String](../../../system/string/)
* Classe [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* Classe [XmlNode](../../../system.xml/xmlnode/)
* Espace de noms [System::Web::Services::Protocols](../../)
* Bibliothèque [Aspose.Slides](../../../)