---
title: GetCustomAttribute()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが表す型に適用され、指定されたタイプを持つカスタム属性を検索します。
type: docs
weight: 573
url: /ja/system/typeinfo/getcustomattribute/
---
## TypeInfo::GetCustomAttribute(const TypeInfo\&) const メソッド


Searches for the custom attribute applied having the specified type and applied to the type reprsented by the current object.

```cpp
ObjectPtr System::TypeInfo::GetCustomAttribute(const TypeInfo &attributeType) const
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | 検索対象の属性の型を表す [TypeInfo](../) オブジェクトへの定数参照 |

### 戻り値

検索条件に一致する属性が見つからなかった場合は null-pointer、見つかった属性を表すオブジェクトへのポインタを返します

## 参照

* クラス [SmartPtr](../../smartptr/)
* クラス [TypeInfo](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)