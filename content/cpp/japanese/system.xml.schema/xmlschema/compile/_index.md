---
title: Compile()
second_title: Aspose.Slides for C++ API リファレンス
description: XML スキーマオブジェクトモデル (SOM) を検証用のスキーマ情報にコンパイルします。プログラムで構築された SOM の構文および意味構造をチェックするために使用されます。意味的検証はコンパイル時に実行されます。
type: docs
weight: 352
url: /ja/system.xml.schema/xmlschema/compile/
---
## XmlSchema::Compile(ValidationEventHandler) メソッド

XML [Schema](../../)[Object](../../../system/object/) モデル (SOM) を検証用のスキーマ情報にコンパイルします。プログラムで構築された SOM の構文および意味構造をチェックするために使用されます。意味的検証はコンパイル時に実行されます。

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | XML [Schema](../../) 検証エラーに関する情報を受け取る検証イベントハンドラです。 |

## XmlSchema::Compile(ValidationEventHandler, const SharedPtr\<XmlResolver\>\&) メソッド

XML [Schema](../../)[Object](../../../system/object/) モデル (SOM) を検証用のスキーマ情報にコンパイルします。プログラムで構築された SOM の構文および意味構造をチェックするために使用されます。意味的検証はコンパイル時に実行されます。

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler, const SharedPtr<XmlResolver> &resolver)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | XML [Schema](../../) 検証エラーに関する情報を受け取る検証イベントハンドラです。 |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) は **include** と **import** 要素で参照される名前空間を解決するために使用されます。 |

## 参照

* 型定義 [ValidationEventHandler](../../validationeventhandler/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [XmlSchema](../)
* クラス [XmlResolver](../../../system.xml/xmlresolver/)
* 名前空間 [System::Xml::Schema](../../)
* ライブラリ [Aspose.Slides](../../../)