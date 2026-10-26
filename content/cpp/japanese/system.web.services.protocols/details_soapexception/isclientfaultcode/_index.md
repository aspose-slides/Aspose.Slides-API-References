---
title: IsClientFaultCode()
second_title: C++ 用 Aspose.Slides API リファレンス
description: 指定されたコードが 'Client' SOAP フォルトコードと等しいかどうかを確認します。
type: docs
weight: 105
url: /ja/system.web.services.protocols/details_soapexception/isclientfaultcode/
---
## Details_SoapException::IsClientFaultCode(System::SharedPtr\<Xml::XmlQualifiedName\>) メソッド

指定されたコードが 'Client' SOAP フォルトコードと等しいかどうかを確認します。

```cpp
static bool System::Web::Services::Protocols::Details_SoapException::IsClientFaultCode(System::SharedPtr<Xml::XmlQualifiedName> code)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | 確認する SOAP フォルトコード。 |

### 戻り値

指定されたコードが 'Client' SOAP フォルトコードと等しい場合は True、そうでない場合は False が返されます。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* クラス [Details_SoapException](../)
* 名前空間 [System::Web::Services::Protocols](../../)
* ライブラリ [Aspose.Slides](../../../)