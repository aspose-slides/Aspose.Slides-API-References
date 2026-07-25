---
title: GetDescription()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された値を持つ列挙定数の名前を返します。
type: docs
weight: 53
url: /ja/system/enum/getdescription/
---
## Enum::GetDescription(T) メソッド


指定された値を持つ列挙定数の名前を返します。

```cpp
template<class T> static std::enable_if<std::is_same<T, E>::value||std::is_convertible<T, UnderlyingType>::value, String>::type System::Enum<E, Guard>::GetDescription(T value)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | T | 名前を返す列挙定数の値 |

### 戻り値

指定された列挙定数の名前

## 参照

* 型定義 [UnderlyingType](../underlyingtype/)
* クラス [String](../../string/)
* 構造体 [Enum](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)