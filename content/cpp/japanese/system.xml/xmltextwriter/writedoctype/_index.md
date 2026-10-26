---
title: WriteDocType()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された名前とオプション属性で DOCTYPE 宣言を書き込みます。
type: docs
weight: 222
url: /ja/system.xml/xmltextwriter/writedoctype/
---
## XmlTextWriter::WriteDocType(const String&, const String&, const String&, const String&) メソッド

指定された名前とオプション属性で DOCTYPE 宣言を書き込みます。

```cpp
void System::Xml::XmlTextWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | DOCTYPE の名前です。空であってはなりません。 |
| pubid | const [String](../../../system/string/)\& | null でなければ、PUBLIC "pubid" "sysid" も書き込みます。**pubid** と **sysid** はそれぞれ与えられた引数の値に置き換えられます。 |
| sysid | const [String](../../../system/string/)\& | **pubid** が null で、**sysid** が null でない場合、SYSTEM "sysid" を書き込みます。**sysid** はこの引数の値に置き換えられます。 |
| subset | const [String](../../../system/string/)\& | null でなければ、[subset] を書き込みます。subset はこの引数の値に置き換えられます。 |

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlTextWriter](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)