---
title: UnknownIsNull()
second_title: Aspose.Slides for C++ APIリファレンス
description: 不明な型のオブジェクトが nullptr かどうかをチェックします。スカラー以外の型のオーバーロードです。
type: docs
weight: 144
url: /ja/system/objectext/unknownisnull/
---
## ObjectExt::UnknownIsNull(T) メソッド


不明な型のオブジェクトが nullptr かどうかをチェックします。スカラー以外の型のオーバーロードです。

```cpp
template<typename T> static std::enable_if<!std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | [Object](../../object/) 型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | T | [Object](../../object/) をチェックする。 |

### 戻り値

'obj == nullptr' が true の場合は true、そうでない場合は false。

## ObjectExt::UnknownIsNull(T) メソッド


不明な型のオブジェクトが nullptr かどうかをチェックします。スカラー型のオーバーロードです。

```cpp
template<typename T> static std::enable_if<std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | [Object](../../object/) 型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | T | [Object](../../object/) をチェックする。 |

### 戻り値

常に false を返します。

## 参照

* クラス [ObjectExt](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)