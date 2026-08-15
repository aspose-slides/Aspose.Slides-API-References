---
title: Details_SoapException()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立新執行個體。
type: docs
weight: 92
url: /zh-hant/system.web.services.protocols/details_soapexception/details_soapexception/
---
## Details_SoapException::Details_SoapException() 建構函式

建立新執行個體。

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException()
```

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>) 建構函式

建立新執行個體。

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| message | [String](../../../system/string/) | 例外訊息。 |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | 例外代碼。 |

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>, Exception) 建構函式

建立新執行個體。

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code, Exception innerException)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| message | [String](../../../system/string/) | 例外訊息。 |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | 例外代碼。 |
| innerException | [Exception](../../../system/exception/) | 內部例外。 |

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>, String) 建構函式

建立新執行個體。

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code, String actor)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| message | [String](../../../system/string/) | 例外訊息。 |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | 例外代碼。 |
| actor | [String](../../../system/string/) | 拋出例外的程式碼片段。 |

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>, String, Exception) 建構函式

建立新執行個體。

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code, String actor, Exception innerException)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| message | [String](../../../system/string/) | 例外訊息。 |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | 例外代碼。 |
| actor | [String](../../../system/string/) | 拋出例外的程式碼片段。 |
| innerException | [Exception](../../../system/exception/) | 內部例外。 |

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>, String, System::SharedPtr\<Xml::XmlNode\>) 建構函式

建立新執行個體。

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code, String actor, System::SharedPtr<Xml::XmlNode> detail)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| message | [String](../../../system/string/) | 例外訊息。 |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | 例外代碼。 |
| actor | [String](../../../system/string/) | 拋出例外的程式碼片段。 |
| detail | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlNode](../../../system.xml/xmlnode/)\> | 拋出例外的詳細資訊。 |

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>, String, System::SharedPtr\<Xml::XmlNode\>, Exception) 建構函式

建立新執行個體。

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code, String actor, System::SharedPtr<Xml::XmlNode> detail, Exception innerException)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| message | [String](../../../system/string/) | 例外訊息。 |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | 例外代碼。 |
| actor | [String](../../../system/string/) | 拋出例外的程式碼片段。 |
| detail | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlNode](../../../system.xml/xmlnode/)\> | 拋出例外的詳細資訊。 |
| innerException | [Exception](../../../system/exception/) | 內部例外。 |

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>, System::SharedPtr\<SoapFaultSubCode\>) 建構函式

建立新執行個體。

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code, System::SharedPtr<SoapFaultSubCode> subcode)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| message | [String](../../../system/string/) | 例外訊息。 |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | 例外代碼。 |
| subcode | [System::SharedPtr](../../../system/sharedptr/)\<SoapFaultSubCode\> | 來自 “subcode” XML 元素的可選資訊。 |

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>, String, String, System::SharedPtr\<Xml::XmlNode\>, System::SharedPtr\<SoapFaultSubCode\>, Exception) 建構函式

建立新執行個體。

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code, String actor, String role, System::SharedPtr<Xml::XmlNode> detail, System::SharedPtr<SoapFaultSubCode> subcode, Exception innerException)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| message | [String](../../../system/string/) | 例外訊息。 |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | 例外代碼。 |
| actor | [String](../../../system/string/) | 拋出例外的程式碼片段。 |
| role | [String](../../../system/string/) | 拋出例外的 XML Web 服務的角色。 |
| detail | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlNode](../../../system.xml/xmlnode/)\> | 拋出例外的詳細資訊。 |
| subcode | [System::SharedPtr](../../../system/sharedptr/)\<SoapFaultSubCode\> | 來自 “subcode” XML 元素的可選資訊。 |
| innerException | [Exception](../../../system/exception/) | 內部例外。 |

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>, String, String, String, System::SharedPtr\<Xml::XmlNode\>, System::SharedPtr\<SoapFaultSubCode\>, Exception) 建構函式

建立新執行個體。

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code, String actor, String role, String lang, System::SharedPtr<Xml::XmlNode> detail, System::SharedPtr<SoapFaultSubCode> subcode, Exception innerException)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| message | [String](../../../system/string/) | 例外訊息。 |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | 例外代碼。 |
| actor | [String](../../../system/string/) | 拋出例外的程式碼片段。 |
| role | [String](../../../system/string/) | 拋出例外的 XML Web 服務的角色。 |
| lang | [String](../../../system/string/) | 用於本地化例外屬性的語言。 |
| detail | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlNode](../../../system.xml/xmlnode/)\> | 拋出例外的詳細資訊。 |
| subcode | [System::SharedPtr](../../../system/sharedptr/)\<SoapFaultSubCode\> | 來自 “subcode” XML 元素的可選資訊。 |
| innerException | [Exception](../../../system/exception/) | 內部例外。 |

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Exception](../../../system/exception/)
* Class [Details_SoapException](../)
* Class [String](../../../system/string/)
* Class [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* Class [XmlNode](../../../system.xml/xmlnode/)
* Namespace [System::Web::Services::Protocols](../../)
* Library [Aspose.Slides](../../../)