---
title: CollectionAssertHelper
second_title: Aspose.Slides for C++ API リファレンス
description: コレクション関連操作のためのHeler API。
type: docs
weight: 1548
url: /ja/system/collectionasserthelper/
---
## CollectionAssertHelper struct

コレクション関連操作のためのHeler API。

```cpp
class CollectionAssertHelper
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| static **bool** [CheckDiffForAll](./checkdiffforall/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | すべてのコレクション要素が述語を満たすことを確認します。 |
| static **bool** [CheckDiffForAny](./checkdiffforany/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | 任意のコレクション要素が述語を満たすことを確認します。 |
| static [System::String](../string/) [CollectionsToMsg](./collectionstomsg/)(const [System::String](../string/)\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | メッセージ表現のために2つのコレクションをシリアライズします。 |
| static [System::String](../string/) [IEnumerableToStr](./ienumerabletostr/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>\&) | 要素の文字列表現を結合してコレクションを文字列に変換します。 |
| static [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<T1, **int32_t**\>\> [MakeDiff](./makediff/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | 2つのコレクション間の「diff」を計算します。各コレクションの要素をキーとした結果の値は、要素が「expected」コレクションに多く出現すれば正、 「actual」コレクションに多く出現すれば負、 両方で同数出現すればゼロになります。 |
| static [System::String](../string/) [ToFullMessage](./tofullmessage/)(const [System::String](../string/)\&) | メッセージ本文として使用される文字列をフォーマットします。 |

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)