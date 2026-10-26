---
title: With()
second_title: Aspose.Slides for C++ API リファレンス
description: 参照レコードをクローンし、イニシャライザファンクタを適用します。
type: docs
weight: 2614
url: /ja/system/with/
---
## System::With(const SharedPtr\<T\>\&, const A\&) 関数

参照レコードをクローンし、イニシャライザファンクタを適用します。

```cpp
template<typename T,typename A> SharedPtr<T> System::With(const SharedPtr<T> &record, const A &initializer)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | クローン対象のレコード型。 |
| A | 初期化ファンクタの型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| record | const [SharedPtr](../sharedptr/)\<T\>\& | クローンおよび初期化するオブジェクトへの共有ポインタ。 |
| initializer | const A\& | レコードクローンに適用される初期化ファンクタ。 |

### 戻り値

クローンされたレコードへの共有ポインタ。

## System::With(const T\&, const A\&) 関数

構造体レコードをコピーし、イニシャライザファンクタを適用します。

```cpp
template<typename T,typename A> T System::With(const T &record, const A &initializer)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | コピー対象のレコード型。 |
| A | 初期化ファンクタの型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| record | const T\& | コピーおよび初期化するレコード。 |
| initializer | const A\& | レコードコピーに適用される初期化ファンクタ。 |

### 戻り値

コピーされたレコード。

## 参照

* 型定義 [SharedPtr](../sharedptr/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)