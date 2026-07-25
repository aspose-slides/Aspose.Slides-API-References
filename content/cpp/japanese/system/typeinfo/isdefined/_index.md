---
title: IsDefined()
second_title: Aspose.Slides for C++ API リファレンス
description: 未実装です。指定された型またはその派生型の属性が1つ以上このメンバーに適用されているかどうかを示します。
type: docs
weight: 157
url: /ja/system/typeinfo/isdefined/
---
## TypeInfo::IsDefined(const TypeInfo&, bool) const メソッド

未実装です。指定された型またはその派生型の属性が1つ以上このメンバーに適用されているかどうかを示します。

```cpp
bool System::TypeInfo::IsDefined(const TypeInfo &attributeType, bool inherit) const
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | 検索対象のカスタム属性の型です。検索には派生型も含まれます。 |
| inherit | **bool** | 属性を検索するためにこのメンバーの継承チェーンを検索する場合は true、そうでない場合は false。このパラメータはプロパティとイベントでは無視されます。 |

### 戻り値

属性型またはその派生型のインスタンスが1つ以上このメンバーに適用されている場合は true、そうでない場合は false。

## 参照

* クラス [TypeInfo](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)