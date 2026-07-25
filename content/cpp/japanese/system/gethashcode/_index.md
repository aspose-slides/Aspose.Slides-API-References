---
title: GetHashCode()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたスカラー値のハッシュコードを返します。
type: docs
weight: 2484
url: /ja/system/gethashcode/
---
## System::GetHashCode(const T\&) 関数

指定されたスカラー値のハッシュコードを返します。

```cpp
template<typename T> std::enable_if<std::is_scalar<T>::value, int>::type System::GetHashCode(const T &obj)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 関数がハッシュコードを生成する値の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | const T\& | ハッシュコードを生成する値 |

### 戻り値

指定された値に対して生成されたハッシュコード

## System::GetHashCode(const T\&) 関数

指定されたオブジェクトのハッシュコードを返します。

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&System::IsSmartPtr<T>::value, int>::type System::GetHashCode(const T &obj)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 関数がハッシュコードを生成するオブジェクトの型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | const T\& | ハッシュコードを生成するオブジェクトを指す[SmartPtr](../smartptr/) |

### 戻り値

指定されたオブジェクトに対して生成されたハッシュコード

## System::GetHashCode(const T\&) 関数

指定された例外オブジェクトのハッシュコードを返します。

```cpp
template<typename T> std::enable_if<System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 関数がハッシュコードを生成するオブジェクトの型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | const T\& | ハッシュコードを生成するオブジェクトを含むException Wrapper |

### 戻り値

指定されたオブジェクトに対して生成されたハッシュコード

## System::GetHashCode(const T\&) 関数

スマートポインタでも例外でもない指定されたオブジェクトのハッシュコードを返します。

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&!System::IsSmartPtr<T>::value &&!System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 関数がハッシュコードを生成するオブジェクトの型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | const T\& | ハッシュコードを生成するオブジェクトへの const 参照 |

### 戻り値

指定されたオブジェクトに対して生成されたハッシュコード

## System::GetHashCode(const std::thread::id\&) 関数

std::thread::id 用の特殊化; 指定されたスレッドオブジェクトのハッシュコードを返します。

```cpp
int System::GetHashCode(const std::thread::id &id)
```

## 参照

* 構造体 [IsSmartPtr](../issmartptr/)
* 構造体 [IsExceptionWrapper](../isexceptionwrapper/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)