---
title: ExceptionWrapper()
second_title: Aspose.Slides for C++ API リファレンス
description: ExceptionWrapper クラスの null インスタンスを構築します。このインスタンスは例外を表しません。
type: docs
weight: 14
url: /ja/system/exceptionwrapper/exceptionwrapper/
---
## ExceptionWrapper::ExceptionWrapper(std::nullptr_t) コンストラクタ

null インスタンスの [ExceptionWrapper](../) クラスを構築します。このインスタンスは例外を表しません。

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(std::nullptr_t)
```

## ExceptionWrapper::ExceptionWrapper(const ExceptionPtr\&) コンストラクタ

渡されたポインタを含む [ExceptionWrapper](../) クラスのインスタンスを構築します。

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionPtr &ptr)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ptr | const [ExceptionPtr](../../exceptionptr/)\& | Exception クラスのインスタンスへのスマートポインタ。 |

## ExceptionWrapper::ExceptionWrapper(const ExceptionWrapper\&) コンストラクタ

コピーコンストラクタ。

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionWrapper &other)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| other | const [ExceptionWrapper](../)\& | コピーすべきラッパークラスの他のインスタンス。 |

## ExceptionWrapper::ExceptionWrapper(ExceptionWrapper\&&) コンストラクタ

ムーブコンストラクタ。

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(ExceptionWrapper &&other) noexcept
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| other | [ExceptionWrapper](../)\&& | ムーブすべきラッパークラスの他のインスタンス。 |

## ExceptionWrapper::ExceptionWrapper(Args\&&...) コンストラクタ

Exception クラスのコンストラクタへパラメータを転送し、新しい Exception クラスのインスタンスを保持するスマートポインタを作成します。

```cpp
template<typename ...,typename> System::ExceptionWrapper<T>::ExceptionWrapper(Args &&...args)
```

## 参照

* 型定義 [ExceptionPtr](../../exceptionptr/)
* クラス [ExceptionWrapper](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)