---
title: IsBoxable
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された型のボクシングがサポートされているかをチェックするテンプレート述語です。
type: docs
weight: 1665
url: /ja/system/isboxable/
---
## IsBoxable 構造体


Template predicate that checks if boxing of the specified type is supported.

```cpp
template<typename T>class IsBoxable : public std::integral_constant<bool, std::is_base_of<Details::BoxableObjectBase, T>::value||std::is_arithmetic<T>::value||std::is_enum<T>::value>
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | チェックする型 |

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)