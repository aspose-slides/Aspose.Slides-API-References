---
title: IEnumerableToStr()
second_title: Aspose.Slides for C++ API リファレンス
description: 要素の文字列表現を結合して、コレクションを文字列に変換します。
type: docs
weight: 40
url: /ja/system/collectionasserthelper/ienumerabletostr/
---
## CollectionAssertHelper::IEnumerableToStr(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T\>\>\&) メソッド

コレクションの要素の文字列表現を結合して、文字列に変換します。

```cpp
template<typename T> static System::String System::CollectionAssertHelper::IEnumerableToStr(const System::SharedPtr<System::Collections::Generic::IEnumerable<T>> &ie)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | コレクション要素の型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ie | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T\>\>\& | チェック対象のコレクション。 |

## 戻り値

コレクションの結合された値。

## 参照

* typedef [SharedPtr](../../sharedptr/)
* クラス [String](../../string/)
* クラス [IEnumerable](../../../system.collections.generic/ienumerable/)
* 構造体 [CollectionAssertHelper](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)