---
title: GetCustomAttributes()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが表す型に適用されたすべてのカスタム属性を表すオブジェクトの配列を返します。
type: docs
weight: 66
url: /ja/system.reflection/memberinfo/getcustomattributes/
---
## MemberInfo::GetCustomAttributes(const TypeInfo\&, bool) const method

現在のオブジェクトが表す型に適用されたすべてのカスタム属性を表すオブジェクトの配列を返します。

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit=false) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| attributeType | const [TypeInfo](../../../system/typeinfo/)\& | 検索する属性の型。 |
| inherit | **bool** | 継承された属性もチェックするかどうか。 |

## MemberInfo::GetCustomAttributes(bool) const method

現在のオブジェクトが表す型に適用されたすべてのカスタム属性を表すオブジェクトの配列を返します。

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(bool inherit=false) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inherit | **bool** | 継承された属性もチェックするかどうか。 |

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [TypeInfo](../../../system/typeinfo/)
* クラス [MemberInfo](../)
* 名前空間 [System::Reflection](../../)
* Library [Aspose.Slides](../../../)