---
title: GetCustomAttribute()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された型に適用された、指定された型のカスタム属性を返します。
type: docs
weight: 1
url: /ja/system/attribute/getcustomattribute/
---
## Attribute::GetCustomAttribute(const TypeInfo\&, const TypeInfo\&) メソッド

指定された型に適用された、指定された型のカスタム属性を返します。

```cpp
static Object::ptr System::Attribute::GetCustomAttribute(const TypeInfo &type, const TypeInfo &attributeType)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | 取得される型属性 |
| attributeType | const [TypeInfo](../../typeinfo/)\& | 取得する属性の型 |

### 戻り値

取得された属性、または指定された型にその種類の属性が存在しない場合は null を返します。

## 関連項目

* 型定義 [ptr](../../object/ptr/)
* クラス [TypeInfo](../../typeinfo/)
* クラス [Attribute](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)