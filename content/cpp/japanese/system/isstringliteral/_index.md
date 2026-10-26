---
title: IsStringLiteral
second_title: Aspose.Slides for C++ API リファレンス
description: 型が文字列リテラルかどうかをチェックするテンプレートマジック。
type: docs
weight: 1730
url: /ja/system/isstringliteral/
---
## IsStringLiteral struct

文字列リテラルかどうかをチェックするテンプレートマジック。

```cpp
template<typename T,typename CharT>class IsStringLiteral : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_array<T>::value>
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| T | チェック対象の型。 |
| CharT | 比較対象の文字型。 |

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)