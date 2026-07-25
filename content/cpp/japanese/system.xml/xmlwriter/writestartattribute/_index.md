---
title: WriteStartAttribute()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたローカル名と名前空間 URI を持つ属性の開始を書き込みます。
type: docs
weight: 144
url: /ja/system.xml/xmlwriter/writestartattribute/
---
## XmlWriter::WriteStartAttribute(const String&, const String&) メソッド

指定されたローカル名と名前空間 URI を持つ属性の開始を書き込みます。

```cpp
void System::Xml::XmlWriter::WriteStartAttribute(const String &localName, const String &ns)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 属性のローカル名。 |
| ns | const [String](../../../system/string/)\& | 属性の名前空間 URI。 |

## XmlWriter::WriteStartAttribute(const String&, const String&, const String&) メソッド

派生クラスでオーバーライドされた場合、指定されたプレフィックス、ローカル名、および名前空間 URI を持つ属性の開始を書き込みます。

```cpp
virtual void System::Xml::XmlWriter::WriteStartAttribute(const String &prefix, const String &localName, const String &ns)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 属性の名前空間プレフィックス。 |
| localName | const [String](../../../system/string/)\& | 属性のローカル名。 |
| ns | const [String](../../../system/string/)\& | 属性の名前空間 URI。 |

## XmlWriter::WriteStartAttribute(const String&) メソッド

指定されたローカル名を持つ属性の開始を書き込みます。

```cpp
void System::Xml::XmlWriter::WriteStartAttribute(const String &localName)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 属性のローカル名。 |

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlWriter](../)
* 名前空間 [System::Xml](../../)
* Library [Aspose.Slides](../../../)