---
title: IsStringByteSequence
second_title: Aspose.Slides for C++ API リファレンス
description: 型が文字列文字のシーケンスかどうかをチェックするテンプレートマジックです。
type: docs
weight: 1717
url: /ja/system/isstringbytesequence/
---
## IsStringByteSequence 構造体


型が文字列文字のシーケンスかどうかをチェックするテンプレートマジックです。

```cpp
template<typename T,typename CharT>class IsStringByteSequence : public std::integral_constant<bool, std::is_same<std::remove_const<std::remove_pointer<std::decay<T>::type>::type>::type, CharT>::value>
```


### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| T | チェック対象の型。 |
| CharT | 比較対象の文字型。 |

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)