---
title: CloneNode()
second_title: Aspose.Slides for C++ API リファレンス
description: このノードの複製を作成します。エンティティノードはクローンできません。このメソッドを XmlEntity オブジェクトで呼び出すと例外がスローされます。
type: docs
weight: 170
url: /ja/system.xml/xmlentity/clonenode/
---
## XmlEntity::CloneNode(bool) メソッド


このノードの複製を作成します。エンティティノードはクローンできません。[XmlEntity](../) オブジェクトでこのメソッドを呼び出すと例外がスローされます。

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntity::CloneNode(bool deep) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| deep | **bool** | **true** は、指定されたノードのサブツリーを再帰的にクローンします。**false** は、ノード自体のみをクローンします。 |

### 戻り値

メソッドが呼び出された [XmlNode](../../xmlnode/) のコピーです。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlEntity](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)