---
title: CollectionsToMsg()
second_title: Aspose.Slides for C++ API リファレンス
description: メッセージ表現のために2つのコレクションをシリアライズします。
type: docs
weight: 53
url: /ja/system/collectionasserthelper/collectionstomsg/
---
## CollectionAssertHelper::CollectionsToMsg(const System::String\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) メソッド

メッセージ表現のために2つのコレクションをシリアライズします。

```cpp
template<typename T1,typename T2> static System::String System::CollectionAssertHelper::CollectionsToMsg(const System::String &extra_msg, const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | 期待されるコレクション要素の型。 |
| T2 | 実際のコレクション要素の型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| extra_msg | const [System::String](../../string/)\& | 結果のメッセージで期待値の前に挿入されるカスタム文字列 |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | 期待されるコレクション。 |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | 実際のコレクション。 |

### 戻り値

コレクションの内容に関するユーザーフレンドリーなメッセージ。

## 参照

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struct [CollectionAssertHelper](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)