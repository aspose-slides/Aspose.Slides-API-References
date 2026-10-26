---
title: IsEmpty()
second_title: Aspose.Slides for C++ API リファレンス
description: 文字列が空かどうかを確認します。
type: docs
weight: 14
url: /ja/system/testtools/isempty/
---
## TestTools::IsEmpty(const System::String\&) メソッド


文字列が空かどうかを確認します。

```cpp
static bool System::TestTools::IsEmpty(const System::String &str)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) が空かどうかを確認する対象。 |

### 戻り値

文字列が空（長さ0）である場合は true、そうでない場合は false を返します。

## TestTools::IsEmpty(const SharedPtr\<T\>\&) メソッド


コレクションが空かどうかを確認します。

```cpp
template<typename T> static bool System::TestTools::IsEmpty(const SharedPtr<T> &collection)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | コレクションの型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| collection | const [SharedPtr](../../sharedptr/)\<T\>\& | 確認対象のコレクション。 |

### 戻り値

コレクションの要素数が 0 の場合は true、そうでない場合は false を返します。

## 参照

* Typedef [SharedPtr](../../sharedptr/)
* クラス [String](../../string/)
* Struct [TestTools](../)
* 名前空間 [System](../../)
* Library [Aspose.Slides](../../../)