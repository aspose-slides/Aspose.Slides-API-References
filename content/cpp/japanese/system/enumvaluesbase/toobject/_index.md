---
title: ToObject()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された 64 ビット符号なし整数値を列挙体メンバーに変換します。
type: docs
weight: 40
url: /ja/system/enumvaluesbase/toobject/
---
## EnumValuesBase::ToObject(const TypeInfo\&, uint64_t) メソッド

指定された 64 ビット符号なし整数値を列挙体メンバーに変換します。

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, uint64_t value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | 返す列挙型。 |
| value | **uint64_t** | 列挙体メンバーに変換する値。 |

### 戻り値

値に設定された列挙体のインスタンス。

## EnumValuesBase::ToObject(const TypeInfo\&, const SharedPtr\<Object\>\&) メソッド

指定された整数値を持つオブジェクトを列挙体メンバーに変換します。

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, const SharedPtr<Object> &value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | 返す列挙型。 |
| value | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 列挙体メンバーに変換される値。 |

### 戻り値

value が設定された列挙体オブジェクト。

## 参照

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [TypeInfo](../../typeinfo/)
* Class [EnumValuesBase](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)