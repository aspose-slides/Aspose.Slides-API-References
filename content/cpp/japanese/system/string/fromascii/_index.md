---
title: FromAscii()
second_title: Aspose.Slides for C++ API リファレンス
description: ASCII 文字列から String を作成します。
type: docs
weight: 950
url: /ja/system/string/fromascii/
---
## String::FromAscii(const char *) メソッド

ASCII 文字列から [String](../) を作成します。

```cpp
static String System::String::FromAscii(const char *asciiStr)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| asciiStr | const char * | ASCII コードページでエンコードされたヌル終端文字列へのポインタ。 |

### 戻り値

[String](../) は渡された文字列を表すオブジェクトです。

## String::FromAscii(const char *, int) メソッド

ASCII 文字列から [String](../) を作成します。

```cpp
static String System::String::FromAscii(const char *asciiStr, int len)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| asciiStr | const char * | ASCII コードページでエンコードされた文字列へのポインタ。 |
| len | int | 処理する文字数。 |

### 戻り値

[String](../) は渡された文字列を表すオブジェクトです。

## String::FromAscii(const std::string\&) メソッド

ASCII 文字列から [String](../) を作成します。

```cpp
static String System::String::FromAscii(const std::string &asciiStr)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| asciiStr | const std::string\& | ASCII エンコードされた文字列。 |

### 戻り値

[String](../) は渡された文字列を表すオブジェクトです。

## 参照

* クラス [String](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)