---
title: get_NameTable()
second_title: Aspose.Slides for C++ API リファレンス
description: 原子化された文字列比較に使用される XmlNameTable を返します。
type: docs
weight: 1
url: /ja/system.xml/xmlreadersettings/get_nametable/
---
## XmlReaderSettings::get_NameTable() メソッド

原子化された文字列比較に使用される [XmlNameTable](../../xmlnametable/) を返します。

```cpp
SharedPtr<XmlNameTable> System::Xml::XmlReaderSettings::get_NameTable()
```

### 戻り値

この [XmlReaderSettings](../) オブジェクトを使用して作成されたすべての [XmlReader](../../xmlreader/) インスタンスで使用される原子化された文字列をすべて格納する [XmlNameTable](../../xmlnametable/) です。デフォルトは **nullptr** です。作成された [XmlReader](../../xmlreader/) インスタンスは、この値が **nullptr** の場合、新しい空の [NameTable](../../nametable/) を使用します。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [XmlNameTable](../../xmlnametable/)
* クラス [XmlReaderSettings](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)