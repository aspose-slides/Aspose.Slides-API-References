---
title: Details_SoapException()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいインスタンスを作成します。
type: docs
weight: 92
url: /ja/system.web.services.protocols/details_soapexception/details_soapexception/
---
## Details_SoapException::Details_SoapException() コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException()
```

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| message | [String](../../../system/string/) | 例外メッセージです。 |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | 例外コードです。 |

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>, Exception) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code, Exception innerException)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| message | [String](../../../system/string/) | 例外メッセージです。 |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | 例外コードです。 |
| innerException | [Exception](../../../system/exception/) | 内部例外です。 |

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>, String) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code, String actor)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| message | [String](../../../system/string/) | 例外メッセージです。 |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | 例外コードです。 |
| actor | [String](../../../system/string/) | 例外がスローされるコード部分です。 |

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>, String, Exception) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code, String actor, Exception innerException)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| message | [String](../../../system/string/) | 例外メッセージです。 |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | 例外コードです。 |
| actor | [String](../../../system/string/) | 例外がスローされるコード部分です。 |
| innerException | [Exception](../../../system/exception/) | 内部例外です。 |

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>, String, System::SharedPtr\<Xml::XmlNode\>) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code, String actor, System::SharedPtr<Xml::XmlNode> detail)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| message | [String](../../../system/string/) | 例外メッセージです。 |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | 例外コードです。 |
| actor | [String](../../../system/string/) | 例外がスローされるコード部分です。 |
| detail | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlNode](../../../system.xml/xmlnode/)\> | スローされた例外の詳細です。 |

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>, String, System::SharedPtr\<Xml::XmlNode\>, Exception) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code, String actor, System::SharedPtr<Xml::XmlNode> detail, Exception innerException)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| message | [String](../../../system/string/) | 例外メッセージです。 |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | 例外コードです。 |
| actor | [String](../../../system/string/) | 例外がスローされるコード部分です。 |
| detail | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlNode](../../../system.xml/xmlnode/)\> | スローされた例外の詳細です。 |
| innerException | [Exception](../../../system/exception/) | 内部例外です。 |

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>, System::SharedPtr\<SoapFaultSubCode\>) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code, System::SharedPtr<SoapFaultSubCode> subcode)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| message | [String](../../../system/string/) | 例外メッセージです。 |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | 例外コードです。 |
| subcode | [System::SharedPtr](../../../system/sharedptr/)\<SoapFaultSubCode\> | 「subcode」XML 要素からのオプション情報です。 |

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>, String, String, System::SharedPtr\<Xml::XmlNode\>, System::SharedPtr\<SoapFaultSubCode\>, Exception) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code, String actor, String role, System::SharedPtr<Xml::XmlNode> detail, System::SharedPtr<SoapFaultSubCode> subcode, Exception innerException)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| message | [String](../../../system/string/) | 例外メッセージです。 |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | 例外コードです。 |
| actor | [String](../../../system/string/) | 例外がスローされるコード部分です。 |
| role | [String](../../../system/string/) | 例外をスローする XML Web サービスのロールです。 |
| detail | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlNode](../../../system.xml/xmlnode/)\> | スローされた例外の詳細です。 |
| subcode | [System::SharedPtr](../../../system/sharedptr/)\<SoapFaultSubCode\> | 「subcode」XML 要素からのオプション情報です。 |
| innerException | [Exception](../../../system/exception/) | 内部例外です。 |

## Details_SoapException::Details_SoapException(String, System::SharedPtr\<Xml::XmlQualifiedName\>, String, String, String, System::SharedPtr\<Xml::XmlNode\>, System::SharedPtr\<SoapFaultSubCode\>, Exception) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Web::Services::Protocols::Details_SoapException::Details_SoapException(String message, System::SharedPtr<Xml::XmlQualifiedName> code, String actor, String role, String lang, System::SharedPtr<Xml::XmlNode> detail, System::SharedPtr<SoapFaultSubCode> subcode, Exception innerException)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| message | [String](../../../system/string/) | 例外メッセージです。 |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | 例外コードです。 |
| actor | [String](../../../system/string/) | 例外がスローされるコード部分です。 |
| role | [String](../../../system/string/) | 例外をスローする XML Web サービスのロールです。 |
| lang | [String](../../../system/string/) | 例外プロパティのローカライズに使用される言語です。 |
| detail | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlNode](../../../system.xml/xmlnode/)\> | スローされた例外の詳細です。 |
| subcode | [System::SharedPtr](../../../system/sharedptr/)\<SoapFaultSubCode\> | 「subcode」XML 要素からのオプション情報です。 |
| innerException | [Exception](../../../system/exception/) | 内部例外です。 |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [Exception](../../../system/exception/)
* クラス [Details_SoapException](../)
* クラス [String](../../../system/string/)
* クラス [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* クラス [XmlNode](../../../system.xml/xmlnode/)
* 名前空間 [System::Web::Services::Protocols](../../)
* ライブラリ [Aspose.Slides](../../../)