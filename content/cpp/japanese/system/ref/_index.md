---
title: Ref()
second_title: Aspose.Slides for C++ API リファレンス
description: DynamicWeakPtr オブジェクトへの参照を作成します。関数引数を参照で渡す際にトランスレータによって使用されます。
type: docs
weight: 2458
url: /ja/system/ref/
---
## System::Ref(DynamicWeakPtr\<T, trunkMode, weakLeafs...\>\&) function

[DynamicWeakPtr](../dynamicweakptr/) オブジェクトへの参照を作成します。関数引数を参照で渡す際にトランスレータによって使用されます。

```cpp
template<typename T,SmartPtrMode,unsigned int ...> DynamicWeakPtr<T, trunkMode, weakLeafs...>::Reference System::Ref(DynamicWeakPtr<T, trunkMode, weakLeafs...> &ptr)
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| T | ポインタ先の型。 |
| trunkMode | スマートポインタ自体のモード。 |
| weakLeafs | SetTemplateWeakPtr メソッドを呼び出す必要があるテンプレート引数のインデックス。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ptr | [DynamicWeakPtr](../dynamicweakptr/)\<T, trunkMode, weakLeafs...\>\& | 参照を作成するスマートポインタ。 |

### 戻り値

スマートポインタ参照。

## System::Ref(T\&) function

オブジェクトへの参照を取得するためのヘルパー関数です。[System::DynamicWeakPtr](../dynamicweakptr/) が代入後に参照されたオブジェクトを更新することを保証するために使用されます。

```cpp
template<typename T> T & System::Ref(T &value)
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 参照を作成する型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | T\& | 参照を作成する値。 |

### 戻り値

この関数に渡された値への参照。

## 関連項目

* Class [DynamicWeakPtr](../dynamicweakptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)