---
title: GetCustomAttributes()
second_title: Aspose.Slides for C++ API リファレンス
description: 型に適用されたすべてのカスタム属性を表すオブジェクトを含む配列を返します。
type: docs
weight: 586
url: /ja/system/typeinfo/getcustomattributes/
---
## TypeInfo::GetCustomAttributes() const メソッド

型に適用されたすべてのカスタム属性を表すオブジェクトを含む配列を返します。

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes() const
```
## TypeInfo::GetCustomAttributes(const TypeInfo\&, bool) const メソッド

型に適用された特定の属性を表すオブジェクトを含む配列を返します。

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | 検索対象となる属性の型。 |
| inherit | **bool** | 継承された属性も検索するかどうか。 |

## 参照

* Typedef [ArrayPtr](../../arrayptr/)
* クラス [SmartPtr](../../smartptr/)
* クラス [TypeInfo](../)
* 名前空間 [System](../../)
* Library [Aspose.Slides](../../../)