---
title: IsStringPointer
second_title: Aspose.Slides for C++ API リファレンス
description: 型が文字列へのポインタかどうかをチェックするテンプレートマジックです。
type: docs
weight: 1743
url: /ja/system/isstringpointer/
---
## IsStringPointer struct

型が文字列へのポインタかどうかをチェックするテンプレートマジックです。

```cpp
template<typename T,typename CharT>class IsStringPointer : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_pointer<T>::value>
```

### Template parameters

| パラメータ | 説明 |
| --- | --- |
| T | チェック対象の型。 |
| CharT | 確認する文字型。 |

## See Also

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)