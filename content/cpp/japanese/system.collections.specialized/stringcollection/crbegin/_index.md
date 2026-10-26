---
title: crbegin()
second_title: Aspose.Slides for C++ API リファレンス
description: 逆コンテナの最初の要素へのリバースイテレータを返します。これは非逆コンテナの最後の要素に対応します。コンテナが空の場合、返されるイテレータは crend() と等しくなります。
type: docs
weight: 274
url: /ja/system.collections.specialized/stringcollection/crbegin/
---
## StringCollection::crbegin() const メソッド


リバースイテレータを返し、逆コンテナの最初の要素を指します。これは非逆コンテナの最後の要素に対応します。コンテナが空の場合、返されるイテレータは [crend()](../crend/) と等しくなります。

```cpp
const_reverse_iterator System::Collections::Specialized::StringCollection::crbegin() const noexcept
```


### 戻り値

コンテナの最後の const 修飾された要素を指すイテレータです。

## 参照

* 型定義 [const_reverse_iterator](../const_reverse_iterator/)
* クラス [StringCollection](../)
* 名前空間 [System::Collections::Specialized](../../)
* ライブラリ [Aspose.Slides](../../../)