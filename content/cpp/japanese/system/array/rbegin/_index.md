---
title: rbegin()
second_title: Aspose.Slides for C++ API リファレンス
description: 反転したコンテナの最初の要素へのリバースイテレータを返します。これは、非反転コンテナの最後の要素に対応します。コンテナが空の場合、返されるイテレータは rend() と等しくなります。
type: docs
weight: 469
url: /ja/system/array/rbegin/
---
## Array::rbegin() メソッド

反転したコンテナの最初の要素へのリバースイテレータを返します。これは、非反転コンテナの最後の要素に対応します。コンテナが空の場合、返されるイテレータは [rend()](../rend/) と等しくなります。

```cpp
reverse_iterator System::Array<T>::rbegin() noexcept
```

### 戻り値

コンテナの最後の要素を指すイテレータ。

## Array::rbegin() const メソッド

反転したコンテナの最初の要素へのリバースイテレータを返します。これは、非反転コンテナの最後の要素に対応します。コンテナが空の場合、返されるイテレータは [rend()](../rend/) と等しくなります。

```cpp
const_reverse_iterator System::Array<T>::rbegin() const noexcept
```

### 戻り値

const 修飾されたコンテナの最後の要素を指すイテレータ。

## 参照

* Typedef [reverse_iterator](../reverse_iterator/)
* Typedef [const_reverse_iterator](../const_reverse_iterator/)
* クラス [Array](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)