---
title: CopyTo()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクション内のすべての XmlSchemaObject を、指定されたインデックスから開始して、指定された配列にコピーします。
type: docs
weight: 118
url: /ja/system.xml.schema/xmlschemaobjectcollection/copyto/
---
## XmlSchemaObjectCollection::CopyTo(const ArrayPtr\<SharedPtr\<XmlSchemaObject\>\>\&, int32_t) メソッド

コレクション内のすべての XmlSchemaObject を、指定されたインデックスから始めて、指定された配列にコピーします。

```cpp
void System::Xml::Schema::XmlSchemaObjectCollection::CopyTo(const ArrayPtr<SharedPtr<XmlSchemaObject>> &array, int32_t index)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<[SharedPtr](../../../system/sharedptr/)\<[XmlSchemaObject](../../xmlschemaobject/)\>\>\& | コピー元の [XmlSchemaObjectCollection](../) からコピーされた要素の宛先となる配列です。配列は0ベースのインデックスを持つ必要があります。 |
| index | **int32_t** | コピーを開始する配列内の0ベースインデックスです。 |

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [XmlSchemaObject](../../xmlschemaobject/)
* クラス [XmlSchemaObjectCollection](../)
* 名前空間 [System::Xml::Schema](../../)
* ライブラリ [Aspose.Slides](../../../)