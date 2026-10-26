---
title: IsServerFaultCode()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたコードが 'Server' SOAP フォルトコードと等しいかどうかを確認します。
type: docs
weight: 131
url: /ja/system.web.services.protocols/details_soapexception/isserverfaultcode/
---
## Details_SoapException::IsServerFaultCode(System::SharedPtr\<Xml::XmlQualifiedName\>) メソッド

指定されたコードが 'Server' SOAP フォルトコードと等しいかどうかを確認します。

```cpp
static bool System::Web::Services::Protocols::Details_SoapException::IsServerFaultCode(System::SharedPtr<Xml::XmlQualifiedName> code)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | 確認する SOAP フォルトコード。 |

### 戻り値

指定されたコードが 'Server' SOAP フォルトコードと等しい場合は true、そうでない場合は false を返します。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* クラス [Details_SoapException](../)
* 名前空間 [System::Web::Services::Protocols](../../)
* ライブラリ [Aspose.Slides](../../../)