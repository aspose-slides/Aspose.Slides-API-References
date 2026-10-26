---
title: IsSupersetOf()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のセットが他のコンテナの上位集合であるかどうかを確認します。
type: docs
weight: 79
url: /ja/system.collections.generic/iset/issupersetof/
---
## ISet::IsSupersetOf(IEnumerablePtr) メソッド

現在のセットが他のコンテナの上位集合かどうかを確認します。

```cpp
virtual bool System::Collections::Generic::ISet<T>::IsSupersetOf(IEnumerablePtr other)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| other | [IEnumerablePtr](../ienumerableptr/) | チェック対象となるサブセット。 |

### 戻り値

True if all elements in **other** are present in set, false otherwise.

## 参照

* Typedef [IEnumerablePtr](../ienumerableptr/)
* クラス [ISet](../)
* 名前空間 [System::Collections::Generic](../../)
* ライブラリ [Aspose.Slides](../../../)