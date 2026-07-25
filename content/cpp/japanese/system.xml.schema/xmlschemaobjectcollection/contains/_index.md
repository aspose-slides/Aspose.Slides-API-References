---
title: Contains()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された XmlSchemaObject が XmlSchemaObjectCollection に含まれているかどうかを示します。
type: docs
weight: 92
url: /ja/system.xml.schema/xmlschemaobjectcollection/contains/
---
## XmlSchemaObjectCollection::Contains(const SharedPtr\<XmlSchemaObject\>\&) メソッド

指定された[XmlSchemaObject](../../xmlschemaobject/)が[XmlSchemaObjectCollection](../)に含まれているかどうかを示します。

```cpp
bool System::Xml::Schema::XmlSchemaObjectCollection::Contains(const SharedPtr<XmlSchemaObject> &item)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaObject](../../xmlschemaobject/)\>\& | [XmlSchemaObject](../../xmlschemaobject/)です。 |

### 戻り値

**true** は、指定された修飾名がコレクションに含まれている場合です。そうでない場合は **false** が返されます。**nullptr** が指定された場合、名前がnullの修飾名が存在しないため **false** が返されます。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaObject](../../xmlschemaobject/)
* Class [XmlSchemaObjectCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)