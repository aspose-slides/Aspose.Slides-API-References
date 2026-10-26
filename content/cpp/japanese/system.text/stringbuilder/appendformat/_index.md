---
title: AppendFormat()
second_title: Aspose.Slides の C++ API リファレンス
description: フォーマットされた文字列をビルダーに追加します。
type: docs
weight: 131
url: /ja/system.text/stringbuilder/appendformat/
---
## StringBuilder::AppendFormat(const String\&, const TArgs\&...) method

フォーマットされた文字列をビルダーに追加します。

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const String &format, const TArgs &... args)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| TArgs | 引数の型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | フォーマット文字列。 |
| args | const TArgs\&... | フォーマット文字列の位置に挿入する引数。 |

### 戻り値

このポインタ。

## StringBuilder::AppendFormat(const SharedPtr\<IFormatProvider\>\&, const String\&, const TArgs\&...) method

フォーマットされた文字列をビルダーに追加します。

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const SharedPtr<IFormatProvider> &fp, const String &format, const TArgs &... args)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| TArgs | 引数の型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fp | const [SharedPtr](../../../system/sharedptr/)\<[IFormatProvider](../../../system/iformatprovider/)\>\& | フォーマットプロバイダー; 無視されます。 |
| format | const [String](../../../system/string/)\& | フォーマット文字列。 |
| args | const TArgs\&... | フォーマット文字列の位置に挿入する引数。 |

### 戻り値

このポインタ。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [StringBuilder](../)
* クラス [String](../../../system/string/)
* クラス [IFormatProvider](../../../system/iformatprovider/)
* 名前空間 [System::Text](../../)
* Library [Aspose.Slides](../../../)