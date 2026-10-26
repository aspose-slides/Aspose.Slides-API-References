---
title: ToString()
second_title: Aspose.Slides for C++ APIリファレンス
description: XmlQualifiedName の文字列値を返します。
type: docs
weight: 79
url: /ja/system.xml/xmlqualifiedname/tostring/
---
## XmlQualifiedName::ToString() const method


[XmlQualifiedName](../) の文字列値を返します。

```cpp
String System::Xml::XmlQualifiedName::ToString() const override
```


### 戻り値

**namespace:localname** の形式での [XmlQualifiedName](../) の文字列値。オブジェクトに名前空間が定義されていない場合、このメソッドはローカル名だけを返します。

## XmlQualifiedName::ToString(const String\&, const String\&) method


[XmlQualifiedName](../) の文字列値を返します。

```cpp
static String System::Xml::XmlQualifiedName::ToString(const String &name, const String &ns)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | オブジェクトの名前。 |
| ns | const [String](../../../system/string/)\& | オブジェクトの名前空間。 |

### 戻り値

**namespace:localname** の形式での [XmlQualifiedName](../) の文字列値。オブジェクトに名前空間が定義されていない場合、このメソッドはローカル名だけを返します。

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlQualifiedName](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)