---
title: ArrayInitializerCast()
second_title: Aspose.Slides for C++ API リファレンス
description: 配列の基本値を変換します (C# では暗黙的に行われますが、C++ は行われないようです)。
type: docs
weight: 209
url: /ja/system/objectext/arrayinitializercast/
---
## ObjectExt::ArrayInitializerCast(From ...) メソッド


配列の基本値を変換します (C# では暗黙的に行われますが、C++ では行われないようです)。

```cpp
template<typename To,typename ...> static std::enable_if<(std::is_fundamental<To>::value), std::array<To, sizeof...(From)>>::type System::ObjectExt::ArrayInitializerCast(From ...args)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| To | 対象の型。 |
| From | ソース型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| args | From ... | 変換して対象配列にプッシュする値。 |

### 戻り値

[Array](../../array/) 同じ順序で変換されたすべての引数のコピーを含む。

## 参照

* クラス [ObjectExt](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)