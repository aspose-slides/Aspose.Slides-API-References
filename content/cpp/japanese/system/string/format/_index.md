---
title: Format()
second_title: Aspose.Slides for C++ API リファレンス
description: C# スタイルで文字列をフォーマットします。
type: docs
weight: 885
url: /ja/system/string/format/
---
## String::Format(const SharedPtr\<IFormatProvider\>\&, const String\&, const Args\&...) method

C# スタイルで文字列をフォーマットします。

```cpp
template<class...> String System::String::Format(const SharedPtr<IFormatProvider> &fp, const String &format, const Args &... args)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| Args | 文字列をフォーマットするための引数。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fp | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 引数を文字列に変換するために使用するフォーマットプロバイダー。 |
| format | const [String](../)\& | フォーマット文字列。 |
| args | const Args\&... | 文字列をフォーマットするための引数。 |

## String::Format(std::nullptr_t, const String\&, const Args\&...) method

C# スタイルで文字列をフォーマットします。

```cpp
template<class...> String System::String::Format(std::nullptr_t, const String &format, const Args &... args)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| Args | 文字列をフォーマットするための引数。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| format | std::nullptr_t | フォーマット文字列。 |
| args | const [String](../)\& | 文字列をフォーマットするための引数。 |

## String::Format(std::nullptr_t, const char16_t(&), const Args\&...) method

C# スタイルで文字列をフォーマットします。

```cpp
template<std::size_t,class...> String System::String::Format(std::nullptr_t, const char16_t(&format)[N], const Args &... args)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| Args | 文字列をフォーマットするための引数。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| format | std::nullptr_t | フォーマット文字列。 |
| args | const char16_t(&) | 文字列をフォーマットするための引数。 |

## String::Format(const String\&, const Args\&...) method

C# スタイルで文字列をフォーマットします。

```cpp
template<class...> String System::String::Format(const String &format, const Args &... args)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| Args | 文字列をフォーマットするための引数。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| format | const [String](../)\& | フォーマット文字列。 |
| args | const Args\&... | 文字列をフォーマットするための引数。 |

## String::Format(const String\&, const System::ArrayPtr\<T\>\&) method

C# スタイルで文字列をフォーマットします。

```cpp
template<class T> String System::String::Format(const String &format, const System::ArrayPtr<T> &args)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | 文字列をフォーマットするための引数。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| format | const [String](../)\& | フォーマット文字列。 |
| args | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | 文字列をフォーマットするための引数。 |

## 参照

* typedef [SharedPtr](../../sharedptr/)
* typedef [ArrayPtr](../../arrayptr/)
* クラス [String](../)
* クラス [IFormatProvider](../../iformatprovider/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)