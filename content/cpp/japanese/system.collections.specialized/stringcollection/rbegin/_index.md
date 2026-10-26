---
title: rbegin()
second_title: Aspose.Slides for C++ API リファレンス
description: 反転したコンテナの最初の要素へのリバースイテレータを返します。これは、反転していないコンテナの最後の要素に対応します。コンテナが空の場合、返されるイテレータは rend() と等価です。
type: docs
weight: 261
url: /ja/system.collections.specialized/stringcollection/rbegin/
---
## StringCollection::rbegin() メソッド

反転したコンテナの最初の要素へのリバースイテレータを返します。これは、反転していないコンテナの最後の要素に対応します。コンテナが空の場合、返されるイテレータは [rend()](../rend/) と等価です。

```cpp
reverse_iterator System::Collections::Specialized::StringCollection::rbegin() noexcept
```

### 戻り値

コンテナの最後の要素を指すイテレータです。

## StringCollection::rbegin() const メソッド

反転したコンテナの最初の要素へのリバースイテレータを返します。これは、反転していないコンテナの最後の要素に対応します。コンテナが空の場合、返されるイテレータは [rend()](../rend/) と等価です。

```cpp
const_reverse_iterator System::Collections::Specialized::StringCollection::rbegin() const noexcept
```

### 戻り値

const 修飾されたコンテナの最後の要素を指すイテレータです。

## 参照

* Typedef [reverse_iterator](../reverse_iterator/)
* Typedef [const_reverse_iterator](../const_reverse_iterator/)
* Class [StringCollection](../)
* Namespace [System::Collections::Specialized](../../)
* Library [Aspose.Slides](../../../)