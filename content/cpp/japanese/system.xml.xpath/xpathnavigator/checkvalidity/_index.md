---
title: CheckValidity()
second_title: Aspose.Slides for C++ API リファレンス
description: XPathNavigator の XML データが、提供された XML スキーマ定義言語 (XSD) スキーマに準拠しているかを検証します。
type: docs
weight: 755
url: /ja/system.xml.xpath/xpathnavigator/checkvalidity/
---
## XPathNavigator::CheckValidity(SharedPtr\<System::Xml::Schema::XmlSchemaSet\>, System::Xml::Schema::ValidationEventHandler) メソッド


[XPathNavigator](../) に含まれる XML データが、提供された XML [Schema](../../../system.xml.schema/) 定義言語 (XSD) スキーマに準拠しているかどうかを検証します。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::CheckValidity(SharedPtr<System::Xml::Schema::XmlSchemaSet> schemas, System::Xml::Schema::ValidationEventHandler validationEventHandler)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)\> | [XPathNavigator](../) に含まれる XML データの検証に使用されるスキーマを含む XmlSchemaSet。 |
| validationEventHandler | [System::Xml::Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | スキーマ検証の警告とエラーに関する情報を受け取る ValidationEventHandler。 |

### 戻り値

スキーマ検証エラーが発生しなかった場合は **true**、それ以外の場合は **false**。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* クラス [XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)
* クラス [XPathNavigator](../)
* 名前空間 [System::Xml::XPath](../../)
* ライブラリ [Aspose.Slides](../../../)