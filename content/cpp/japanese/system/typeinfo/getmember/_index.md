---
title: GetMember()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された名前を持つメンバーの一覧を取得します。
type: docs
weight: 495
url: /ja/system/typeinfo/getmember/
---
## TypeInfo::GetMember(const String\&) const メソッド

指定された名前のメンバーのリストを取得します。

```cpp
ArrayPtr<SharedPtr<System::Reflection::MemberInfo>> System::TypeInfo::GetMember(const String &name) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | const [String](../../string/)\& | 取得するメンバーの名前。 |

### 戻り値

[Array](../../array/) のメンバー記述子（見つからない場合は空）。

## 参照

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* クラス [MemberInfo](../../../system.reflection/memberinfo/)
* クラス [String](../../string/)
* クラス [TypeInfo](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)