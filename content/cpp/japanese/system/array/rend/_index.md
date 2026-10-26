---
title: rend()
second_title: Aspose.Slides for C++ API リファレンス
description: 逆順コンテナの最後の要素の次の要素への逆イテレータを返します。これは、逆順でないコンテナの最初の要素の前の要素に相当します。この要素はプレースホルダーとして機能し、アクセスしようとすると未定義動作になります。
type: docs
weight: 495
url: /ja/system/array/rend/
---
## Array::rend() メソッド


逆順コンテナの最後の要素の次の要素への逆イテレータを返します。これは、逆順でないコンテナの最初の要素の前の要素に相当します。この要素はプレースホルダーとして機能し、アクセスしようとすると未定義動作になります。

```cpp
reverse_iterator System::Array<T>::rend() noexcept
```


### 戻り値

コンテナの最初の要素の前にある理論上の要素を指すイテレータです。

## Array::rend() const メソッド


逆順コンテナの最後の要素の次の要素への逆イテレータを返します。これは、逆順でないコンテナの最初の要素の前の要素に相当します。この要素はプレースホルダーとして機能し、アクセスしようとすると未定義動作になります。

```cpp
const_reverse_iterator System::Array<T>::rend() const noexcept
```


### 戻り値

const 修飾されたコンテナの最初の要素の前にある理論上の要素を指すイテレータです。

## 参照

* 型定義 [reverse_iterator](../reverse_iterator/)
* 型定義 [const_reverse_iterator](../const_reverse_iterator/)
* クラス [Array](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)