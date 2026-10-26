---
title: operator!=()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトと指定された TypeInfo オブジェクトが等しくないかどうかを判定します。
type: docs
weight: 456
url: /ja/system/typeinfo/operator_not_equal/
---
## TypeInfo::operator!=(const TypeInfo\&) const メソッド


現在のオブジェクトと指定された [TypeInfo](../) オブジェクトが等しくないかどうかを判定します。

```cpp
bool System::TypeInfo::operator!=(const TypeInfo &info) const
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| info | const [TypeInfo](../)\& | 比較対象となる [TypeInfo](../) オブジェクト |

### 戻り値

オブジェクトのハッシュが等しくない場合は True、そうでない場合は false

## TypeInfo::operator!=(std::nullptr_t) const メソッド


現在の [TypeInfo](../) オブジェクトが null オブジェクトではないか、すなわち何らかの型を表しているかどうかを判定します。

```cpp
bool System::TypeInfo::operator!=(std::nullptr_t) const
```


### 戻り値

現在の [TypeInfo](../) オブジェクトが null オブジェクトでない場合は True、そうでない場合は false

## 参照

* クラス [TypeInfo](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)