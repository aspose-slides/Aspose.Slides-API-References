---
title: IsCppContainer
second_title: Aspose.Slides for C++ API リファレンス
description: "特定の型が STL スタイルのコンテナかどうかをチェックします。そのために、iterator および const_iterator メンバー型の存在を確認します。両方が存在すれば std::true_type を継承し、そうでなければ std::false_type を継承します。"
type: docs
weight: 40
url: /ja/system.testpredicates.typetraits/iscppcontainer/
---
## IsCppContainer struct


指定された型が STL スタイルのコンテナかどうかを確認します。そのために、iterator および const_iterator メンバー型の存在をチェックします。両方が存在すれば std::true_type を継承し、そうでなければ std::false_type を継承します。

```cpp
template<typename T,typename Enable>class IsCppContainer : public std::false_type
```


### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| T | チェック対象の型。 |
| Enable | SFINAE が機能するための形式的引数。 |

## 参照

* 名前空間 [System::TestPredicates::TypeTraits](../)
* ライブラリ [Aspose.Slides](../../)