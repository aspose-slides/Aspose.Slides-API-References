---
title: ValueAs()
second_title: Aspose.Slides for C++ API リファレンス
description: 名前空間プレフィックスを解決するために指定された IXmlNamespaceResolver オブジェクトを使用して、検証された XML 要素または属性の値を指定された型として返します。
type: docs
weight: 144
url: /ja/system.xml.schema/xmlatomicvalue/valueas/
---
## XmlAtomicValue::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) method

検証済みの XML 要素または属性の値を、名前空間プレフィックスを解決するために指定された [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) オブジェクトを使用して指定された型として返します。

```cpp
SharedPtr<Object> System::Xml::Schema::XmlAtomicValue::ValueAs(const TypeInfo &type, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | const [TypeInfo](../../../system/typeinfo/)\& | 検証済みの XML 要素または属性の値を返す型。 |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | 名前空間プレフィックスを解決するために使用される [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) オブジェクト。 |

### 戻り値

要求された型としての、検証済みの XML 要素または属性の値。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [TypeInfo](../../../system/typeinfo/)
* クラス [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* クラス [XmlAtomicValue](../)
* 名前空間 [System::Xml::Schema](../../)
* ライブラリ [Aspose.Slides](../../../)