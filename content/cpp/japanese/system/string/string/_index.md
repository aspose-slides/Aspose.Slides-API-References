---
title: String()
second_title: Aspose.Slides for C++ APIリファレンス
description: デフォルトコンストラクタ。null とみなされる文字列オブジェクトを作成します。
type: docs
weight: 14
url: /ja/system/string/string/
---
## String::String() コンストラクタ

デフォルトコンストラクタ。null とみなされる文字列オブジェクトを作成します。

```cpp
System::String::String()
```

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char16_t\>::value\>::type *) コンストラクタ

文字列リテラルに基づいて文字列を構築します。リテラルを null 終端文字列とみなし、リテラルのサイズに基づいて対象文字列の長さを計算します。

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char16_t>::value>::type *=nullptr)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | T\& | [String](../) リテラルポインタ。 |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char16_t\>::value\>::type *) コンストラクタ

文字列ポインタに基づいて文字列を構築します。指された文字列を null 終端文字列と見なし、null 文字に基づいて対象文字列の長さを計算します。

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char16_t>::value>::type *=nullptr)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const T\& | 文字列ポインタ。 |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char\>::value\>::type *) コンストラクタ

文字列リテラルに基づいて文字列を構築します。リテラルを UTF8 の null 終端文字列とみなし、リテラルのサイズに基づいて対象文字列の長さを計算します。

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char>::value>::type *=nullptr)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | T\& | [String](../) リテラルポインタ。 |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char\>::value\>::type *) コンストラクタ

文字列ポインタに基づいて文字列を構築します。指された文字列を UTF8 の null 終端文字列と見なし、null 文字に基づいて対象文字列の長さを計算します。

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char>::value>::type *=nullptr)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const T\& | 文字列ポインタ。 |

## String::String(const char16_t *, int) コンストラクタ

文字列ポインタと明示的な長さから文字列を構築します。

```cpp
System::String::String(const char16_t *str, int length)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const char16_t * | [String](../) ポインタ、リテラルまたは配列である可能性があります。 |
| length | int | 明示的な文字列長さ |

## String::String(const ReadOnlySpan\<char16_t\>\&) コンストラクタ

[System.String](../) クラスの新しいインスタンスを、指定された読み取り専用スパンで示された Unicode 文字で初期化します。

```cpp
System::String::String(const ReadOnlySpan<char16_t> &value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [ReadOnlySpan](../../readonlyspan/)\<char16_t\>\& | Unicode 文字の読み取り専用スパン。 |

## String::String(const char *, int) コンストラクタ

文字列ポインタと明示的な長さから文字列を構築します。

```cpp
System::String::String(const char *str, int length)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const char * | [String](../) UTF8 データへのポインタ、リテラルまたは配列である可能性があります。 |
| length | int | 明示的な文字列長さ |

## String::String(const char16_t *, int, int) コンストラクタ

開始位置から指定された長さを使用して文字列ポインタから文字列を構築します。

```cpp
System::String::String(const char16_t *str, int start, int length)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const char16_t * | [String](../) ポインタ、リテラルまたは配列である可能性があります。 |
| start | int | 開始位置。 |
| length | int | [String](../) 長さ。 |

## String::String(const char16_t, int) コンストラクタ

フィルコンストラクタ。

```cpp
System::String::String(const char16_t ch, int count)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ch | const char16_t | フィル文字。 |
| count | int | 対象長さ。 |

## String::String(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) コンストラクタ

nullptr コンストラクタ。他のテンプレートコンストラクタとの優先順位を解決するためにテンプレートとして宣言されています。

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<std::is_same<T, std::nullptr_t>::value>::type *=nullptr)
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| T | nullptr_t である必要があります |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const T\& | nullptr |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, wchar_t\>::value\>::type *) コンストラクタ

ワイド文字列リテラルに基づいて文字列を構築します。リテラルを null 終端文字列とみなし、リテラルのサイズに基づいて対象文字列の長さを計算します。**wchar_t** からの変換は一部のプラットフォームで時間がかかるため、暗黙的な変換は許可されません。

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, wchar_t>::value>::type *=nullptr)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | T\& | [String](../) リテラルポインタ。 |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, wchar_t\>::value\>::type *) コンストラクタ

ワイド文字列ポインタに基づいて文字列を構築します。指された文字列を null 終端文字列と見なし、null 文字に基づいて対象文字列の長さを計算します。**wchar_t** からの変換は一部のプラットフォームで時間がかかるため、暗黙的な変換は許可されません。

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, wchar_t>::value>::type *=nullptr)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const T\& | 文字列ポインタ。 |

## String::String(const wchar_t *, int) コンストラクタ

ワイド文字列ポインタと明示的な長さから文字列を構築します。**wchar_t** からの変換は一部のプラットフォームで時間がかかるため、暗黙的な変換は許可されません。

```cpp
System::String::String(const wchar_t *str, int length)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const **wchar_t** * | [String](../) ポインタ、リテラルまたは配列である可能性があります。 |
| length | int | 明示的な文字列長さ |

## String::String(const wchar_t, int) コンストラクタ

フィルコンストラクタ。**wchar_t** からの変換は一部のプラットフォームで時間がかかるため、暗黙的な変換は許可されません。

```cpp
System::String::String(const wchar_t ch, int count=1)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ch | const **wchar_t** | フィル文字。 |
| count | int | 対象長さ。 |

## String::String(const String\&) コンストラクタ

コピーコンストラクタ。

```cpp
System::String::String(const String &str)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) をコピーします。 |

## String::String(String\&&) コンストラクタ

ムーブコンストラクタ。

```cpp
System::String::String(String &&str) noexcept
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | [String](../)\&& | [String](../) からデータをムーブします。 |

## String::String(const ArrayPtr\<char16_t\>\&) コンストラクタ

文字配列全体を文字列に変換します。

```cpp
System::String::String(const ArrayPtr<char16_t> &arr)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | [Array](../../array/) を文字列に変換します。 |

## String::String(const ArrayPtr\<char16_t\>\&, int, int) コンストラクタ

文字配列のサブレンジを文字列に変換します。パラメータが配列の範囲外の場合、空文字列が構築されます。

```cpp
System::String::String(const ArrayPtr<char16_t> &arr, int offset, int len)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | 文字配列。 |
| offset | int | サブ配列開始インデックス。 |
| len | int | サブ配列の長さ。 |

## String::String(const codeporting_icu::UnicodeString\&) コンストラクタ

UnicodeString を [String](../) にラップします。

```cpp
System::String::String(const codeporting_icu::UnicodeString &str)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const codeporting_icu::UnicodeString\& | UnicodeString を [String](../) にラップします。 |

## String::String(codeporting_icu::UnicodeString\&&) コンストラクタ

ムーブコンストラクタ。

```cpp
System::String::String(codeporting_icu::UnicodeString &&str) noexcept
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | codeporting_icu::UnicodeString\&& | UnicodeString を [String](../) にラップします。 |

## String::String(const std::wstring\&) コンストラクタ

[String](../) を widestring から作成します。

```cpp
System::String::String(const std::wstring &str)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const std::wstring\& | widestring を [String](../) に変換します。 |

## String::String(const std::u16string\&) コンストラクタ

[String](../) を utf16 文字列から作成します。

```cpp
System::String::String(const std::u16string &str)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const std::u16string\& | utf16 文字列を [String](../) に変換します。 |

## String::String(const std::string\&) コンストラクタ

UTF-8 形式で表現された std::string 文字列から [String](../) を作成します。

```cpp
System::String::String(const std::string &utf8str)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| utf8str | const std::string\& | std::string 文字列を [String](../) に変換します。 |

## String::String(const std::u32string\&) コンストラクタ

[String](../) を std::u32string 文字列から作成します。

```cpp
System::String::String(const std::u32string &u32str)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| u32str | const std::u32string\& | std::u32string 文字列を [String](../) に変換します。 |

## 参照

* 型定義 [ArrayPtr](../../arrayptr/)
* クラス [String](../)
* クラス [ReadOnlySpan](../../readonlyspan/)
* 構造体 [IsStringLiteral](../../isstringliteral/)
* 構造体 [IsStringPointer](../../isstringpointer/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)