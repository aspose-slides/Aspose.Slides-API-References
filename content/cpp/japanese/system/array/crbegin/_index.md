---
title: crbegin()
second_title: Aspose.Slides for C++ APIリファレンス
description: リバースされたコンテナの最初の要素へのリバースイテレータを返します。これは、リバースされていないコンテナの最後の要素に対応します。コンテナが空の場合、返されたイテレータは crend() と等価です。
type: docs
weight: 482
url: /ja/system/array/crbegin/
---
## Array::crbegin() const メソッド

リバース コンテナの最初の要素へのリバースイテレータを返します。これは、リバースされていないコンテナの最後の要素に対応します。コンテナが空の場合、返されるイテレータは [crend()](../crend/) と等価です。

```cpp
const_reverse_iterator System::Array<T>::crbegin() const noexcept
```

### 戻り値

コンテナの最後の const 修飾要素を指すイテレータです。

## 参照

* 型定義 [const_reverse_iterator](../const_reverse_iterator/)
* クラス [Array](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)