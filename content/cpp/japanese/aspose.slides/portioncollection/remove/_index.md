---
title: Remove()
second_title: Aspose.Slides for C++ APIリファレンス
description: ICollection から特定のオブジェクトの最初の出現を削除します。
type: docs
weight: 131
url: /ja/aspose.slides/portioncollection/remove/
---
## PortionCollection::Remove(System::SharedPtr\<IPortion\>) メソッド


特定のオブジェクトを[ICollection](../../../system.collections.generic/icollection/)から最初に出現したものを削除します。

```cpp
bool Aspose::Slides::PortionCollection::Remove(System::SharedPtr<IPortion> item) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | [ICollection](../../../system.collections.generic/icollection/)から削除するオブジェクトです。 |

### 戻り値

*item* が [ICollection](../../../system.collections.generic/icollection/) から正常に削除された場合は true、そうでない場合は false。元の [ICollection](../../../system.collections.generic/icollection/) に *item* が見つからない場合も false を返します。

## 参照

* typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IPortion](../../iportion/)
* クラス [PortionCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)