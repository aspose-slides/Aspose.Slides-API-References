---
title: IsNullOrEmpty()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクションが null または空かどうかを確認します。
type: docs
weight: 27
url: /ja/system/testtools/isnullarempty/
---
## TestTools::IsNullOrEmpty(const SharedPtr\<T\>\&) メソッド

コレクションが null または空かどうかを確認します。

```cpp
template<typename T> static bool System::TestTools::IsNullOrEmpty(const SharedPtr<T> &collection)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | コレクション型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| collection | const [SharedPtr](../../sharedptr/)\<T\>\& | チェック対象のコレクション。 |

### 戻り値

コレクションが null であるか要素数が 0 の場合は true、そうでない場合は false を返します。

## TestTools::IsNullOrEmpty(const System::String\&) メソッド

文字列が null または空かどうかを確認します。

```cpp
static bool System::TestTools::IsNullOrEmpty(const System::String &str)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) をチェックします。 |

### 戻り値

文字列が null であるか長さが 0 の場合は true、そうでない場合は false を返します。

## 参照

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Struct [TestTools](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)