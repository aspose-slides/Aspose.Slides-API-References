---
title: MakeSharedPtr()
second_title: Aspose.Slides for C++ API リファレンス
description: 生ポインタをスマートポインタに変換します。
type: docs
weight: 2900
url: /ja/system/makesharedptr/
---
## System::MakeSharedPtr(X *) 関数

生ポインタをスマートポインタに変換します。

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(X *p)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| X | 指す型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| p | X * | オブジェクトへの生ポインタ。 |

### 戻り値

オブジェクトへの共有スマートポインタ。

## System::MakeSharedPtr(const X *) 関数

生ポインタをスマートポインタに変換します。const ポインタ用のオーバーロードです。たとえば C# のメソッドが const として翻訳される際の 'this' 変数の使用に便利です。

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(const X *p)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| X | 指す型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| p | const X * | オブジェクトへの生ポインタ。 |

### 戻り値

オブジェクトへの共有スマートポインタ。

## 参照

* クラス [SmartPtr](../smartptr/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)