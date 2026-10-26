---
title: get_DeclaredMember()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された名前を持つメンバーのリストを取得します。
type: docs
weight: 508
url: /ja/system/typeinfo/get_declaredmember/
---
## TypeInfo::get_DeclaredMember(const String\&) const メソッド

指定された名前を持つメンバーのリストを取得します。

```cpp
ArrayPtr<SharedPtr<System::Reflection::MemberInfo>> System::TypeInfo::get_DeclaredMember(const String &name) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | const [String](../../string/)\& | 取得するメンバーの名前。 |

### 戻り値

[Array](../../array/) のメンバー記述子 (メンバーが見つからない場合は空です)。

## 参照

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* クラス [MemberInfo](../../../system.reflection/memberinfo/)
* クラス [String](../../string/)
* クラス [TypeInfo](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)