---
title: TryGetFirst()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクションの最初の要素を取得しようとします。
type: docs
weight: 248
url: /ja/system.collections.generic.details/trygetfirst/
---
## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, bool\&) 関数

コレクションの最初の要素を取得しようとします。

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, bool &found)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | コレクション要素の型です。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | 要素を取得する対象のコレクションです。 |
| found | **bool**\& | 出力パラメータです。コレクションに要素が含まれる場合は true を返し、そうでない場合は false を返します。 |

### 戻り値

最初のコレクション要素を返します。コレクションが空の場合は型のデフォルト値が返されます。

## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, const Func\<T, bool\>\&, bool\&) 関数

述語関数を満たすコレクションの最初の要素を取得しようとします。

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, const Func<T, bool> &predicate, bool &found)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | コレクション要素の型です。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | 要素を取得する対象のコレクションです。 |
| predicate | const [Func](../../system/func/)\<T, **bool**\>\& | 述語関数です。 |
| found | **bool**\& | 出力パラメータです。コレクションに要素が含まれる場合は true を返し、そうでない場合は false を返します。 |

### 戻り値

最初のコレクション要素を返します。指定された述語関数を満たす要素が見つからない場合は型のデフォルト値が返されます。

## 参照

* クラス [IEnumerable](../../system.collections.generic/ienumerable/)
* クラス [Func](../../system/func/)
* 名前空間 [System::Collections::Generic::Details](../)
* ライブラリ [Aspose.Slides](../../)