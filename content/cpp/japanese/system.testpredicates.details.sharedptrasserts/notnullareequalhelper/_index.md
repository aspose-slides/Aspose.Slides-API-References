---
title: NotNullAreEqualHelper()
second_title: Aspose.Slides for C++ API リファレンス
description: 抽象コレクションを等価比較します。
type: docs
weight: 66
url: /ja/system.testpredicates.details.sharedptrasserts/notnullareequalhelper/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualHelper(const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&, const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&) function


抽象コレクションの等価比較を行います。

```cpp
template<typename T> bool System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualHelper(const SharedPtr<System::Collections::Generic::ICollection<T>> &lhs, const SharedPtr<System::Collections::Generic::ICollection<T>> &rhs)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 要素の型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | 左辺の値。 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | 右辺の値。 |

### 戻り値

gtest 形式のアサーション結果。

## 参照

* 型定義 [SharedPtr](../../system/sharedptr/)
* クラス [ICollection](../../system.collections.generic/icollection/)
* 名前空間 [System::TestPredicates::Details::SharedPtrAsserts](../)
* ライブラリ [Aspose.Slides](../../)