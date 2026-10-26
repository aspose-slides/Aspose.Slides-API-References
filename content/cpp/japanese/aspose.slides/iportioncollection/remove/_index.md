---
title: Remove()
second_title: Aspose.Slides for C++ API リファレンス
description: ICollection から特定のオブジェクトの最初の出現を削除します。
type: docs
weight: 92
url: /ja/aspose.slides/iportioncollection/remove/
---
## IPortionCollection::Remove(System::SharedPtr\<IPortion\>) メソッド

指定されたオブジェクトの最初の出現を [ICollection](../../../system.collections.generic/icollection/) から削除します。

```cpp
virtual bool Aspose::Slides::IPortionCollection::Remove(System::SharedPtr<IPortion> item)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | [ICollection](../../../system.collections.generic/icollection/) から削除するオブジェクト。 |

### 戻り値

*item* が [ICollection](../../../system.collections.generic/icollection/) から正常に削除された場合は true、そうでない場合は false。元の [ICollection](../../../system.collections.generic/icollection/) に *item* が見つからない場合も false が返されます。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IPortion](../../iportion/)
* クラス [IPortionCollection](../)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)