---
title: IsWeakPtr
second_title: Aspose.Slides for C++ API リファレンス
description: "特定のクラスが System::WeakPtr の特殊化かどうかを確認するトレイトクラスです。インスタンスが実際に弱参照モードであるかはチェックしません。"
type: docs
weight: 1756
url: /ja/system/isweakptr/
---
## IsWeakPtr 構造体

特定のクラスが [System::WeakPtr](../weakptr/) の特殊化かどうかをチェックするトレイトクラスです。インスタンスが実際に弱参照モードであるかどうかはチェックしません。

```cpp
template<class T>class IsWeakPtr : public System::detail::is_a<T, System::WeakPtr>
```

### テンプレートパラメータ

| Parameter | Description |
| --- | --- |
| T | テスト対象の型。 |

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)