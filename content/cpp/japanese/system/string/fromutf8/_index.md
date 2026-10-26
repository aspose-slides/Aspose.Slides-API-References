---
title: FromUtf8()
second_title: Aspose.Slides for C++ APIリファレンス
description: utf8文字列からStringを作成します。
type: docs
weight: 898
url: /ja/system/string/fromutf8/
---
## String::FromUtf8(const char *) メソッド

utf8 文字列から [String](../) を作成します。

```cpp
static String System::String::FromUtf8(const char *utf8)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| utf8 | const char * | utf8 コードページでエンコードされた、null 終端の文字列へのポインタです。 |

### 戻り値

[String](../) オブジェクトは、渡された文字列を表します。

## String::FromUtf8(const char *, int) メソッド

utf8 文字列から [String](../) を作成します。

```cpp
static String System::String::FromUtf8(const char *utf8, int len)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| utf8 | const char * | utf8 コードページでエンコードされた文字列へのポインタです。 |
| len | int | 処理対象の文字数。 |

### 戻り値

[String](../) オブジェクトは、渡された文字列を表します。

## String::FromUtf8(const uint8_t *) メソッド

utf8 文字列から [String](../) を作成します。

```cpp
static String System::String::FromUtf8(const uint8_t *utf8)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| utf8 | const **uint8_t** * | utf8 コードページでエンコードされた、null 終端の文字列へのポインタです。 |

### 戻り値

[String](../) オブジェクトは、渡された文字列を表します。

## String::FromUtf8(const std::string\&) メソッド

utf8 文字列から [String](../) を作成します。

```cpp
static String System::String::FromUtf8(const std::string &utf8)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| utf8 | const std::string\& | utf8 コードページでエンコードされた文字列へのポインタです。 |

### 戻り値

[String](../) オブジェクトは、渡された文字列を表します。

## 参照

* クラス [String](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)