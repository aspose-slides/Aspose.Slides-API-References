---
title: WriteDocType()
second_title: Aspose.Slides の C++ API リファレンス
description: 派生クラスでオーバーライドされた場合、指定された名前とオプション属性で DOCTYPE 宣言を書き込みます。
type: docs
weight: 79
url: /ja/system.xml/xmlwriter/writedoctype/
---
## XmlWriter::WriteDocType(const String&, const String&, const String&, const String&) メソッド

派生クラスでオーバーライドされた場合、指定された名前とオプション属性で DOCTYPE 宣言を書き込みます。

```cpp
virtual void System::Xml::XmlWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | const [String](../../../system/string/)& | DOCTYPE の名前です。空であってはなりません。 |
| pubid | const [String](../../../system/string/)& | nullでない場合、PUBLIC "pubid" "sysid" も書き込みます。このとき **pubid** と **sysid** は与えられた引数の値に置き換えられます。 |
| sysid | const [String](../../../system/string/)& | **pubid** が **nullptr** で、**sysid** が nullでない場合、SYSTEM "sysid" を書き込みます。このとき **sysid** はこの引数の値に置き換えられます。 |
| subset | const [String](../../../system/string/)& | nullでない場合、[subset] を書き込みます。このとき subset はこの引数の値に置き換えられます。 |

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlWriter](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)