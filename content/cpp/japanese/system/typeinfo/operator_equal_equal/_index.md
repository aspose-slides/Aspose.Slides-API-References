---
title: operator==()
second_title: C++ 用 Aspose.Slides API リファレンス
description: 現在の TypeInfo オブジェクトと指定された TypeInfo オブジェクトが等しいかどうかを判断します。
type: docs
weight: 443
url: /ja/system/typeinfo/operator_equal_equal/
---
## TypeInfo::operator==(const TypeInfo\&) const メソッド

現在のオブジェクトと指定された [TypeInfo](../) オブジェクトが等しいかどうかを判定します。

```cpp
bool System::TypeInfo::operator==(const TypeInfo &info) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| info | const [TypeInfo](../)\& | 比較対象となる [TypeInfo](../) オブジェクト |

### 戻り値

オブジェクトのハッシュが等しい場合は true、そうでない場合は false

## TypeInfo::operator==(std::nullptr_t) const メソッド

現在の [TypeInfo](../) オブジェクトがヌルオブジェクトかどうかを判定します。つまり、何の型も表さないことを意味します。

```cpp
bool System::TypeInfo::operator==(std::nullptr_t) const
```

### 戻り値

現在の [TypeInfo](../) オブジェクトがヌルオブジェクトの場合は true、そうでない場合は false

## 参照

* クラス [TypeInfo](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)