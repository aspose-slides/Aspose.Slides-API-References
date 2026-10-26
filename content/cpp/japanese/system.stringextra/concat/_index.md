---
title: Concat()
second_title: Aspose.Slides for C++ API リファレンス
description: 文字列配列を連結します。
type: docs
weight: 1
url: /ja/system.stringextra/concat/
---
## System::StringExtra::Concat(const ArrayPtr\<String\>\&) 関数

文字列配列を連結します。

```cpp
String System::StringExtra::Concat(const ArrayPtr<String> &parts)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| parts | const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\& | [Array](../../system/array/) の文字列を連結します。 |

### 戻り値

結合された文字列。

## System::StringExtra::Concat(const String\&, const String\&) 関数

文字列を連結します。

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | 連結する最初の文字列。 |
| str1 | const [String](../../system/string/)\& | 連結する二番目の文字列。 |

### 戻り値

結合されたパラメータ文字列。

## System::StringExtra::Concat(const String\&, const String\&, const String\&) 関数

文字列を連結します。

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | 連結する最初の文字列。 |
| str1 | const [String](../../system/string/)\& | 連結する二番目の文字列。 |
| str2 | const [String](../../system/string/)\& | 連結する三番目の文字列。 |

### 戻り値

結合されたパラメータ文字列。

## System::StringExtra::Concat(const String\&, const String\&, const String\&, const String\&) 関数

文字列を連結します。

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2, const String &str3)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | 連結する最初の文字列。 |
| str1 | const [String](../../system/string/)\& | 連結する二番目の文字列。 |
| str2 | const [String](../../system/string/)\& | 連結する三番目の文字列。 |
| str3 | const [String](../../system/string/)\& | 連結する四番目の文字列。 |

### 戻り値

結合されたパラメータ文字列。

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) 関数

複数のオブジェクトを文字列に変換し、結果の文字列を連結します。[SmartPtr](../../system/smartptr/) 型の特殊化。

```cpp
template<typename T> std::enable_if_t<IsSmartPtr<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) を変換して連結します。 |

### 戻り値

[String](../../system/string/) の文字列表現から結合された値。

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) 関数

複数のオブジェクトを文字列に変換し、結果の文字列を連結します。算術型の特殊化。

```cpp
template<typename T> std::enable_if_t<std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) を変換して連結します。 |

### 戻り値

[String](../../system/string/) の文字列表現から結合された値。

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) 関数

複数のオブジェクトを文字列に変換し、結果の文字列を連結します。構造体およびその他の値型の特殊化。

```cpp
template<typename T> std::enable_if_t<!IsSmartPtr<T>::value &&!std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) を変換して連結します。 |

### 戻り値

[String](../../system/string/) の文字列表現から結合された値。

## 参照

* Typedef [ArrayPtr](../../system/arrayptr/)
* Class [String](../../system/string/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Namespace [System::StringExtra](../)
* Library [Aspose.Slides](../../)