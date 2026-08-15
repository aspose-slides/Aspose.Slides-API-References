---
title: get_DeclaredMember()
second_title: Aspose.Slides for C++ API 參考
description: 取得具有指定名稱的成員清單。
type: docs
weight: 508
url: /zh-hant/system/typeinfo/get_declaredmember/
---
## TypeInfo::get_DeclaredMember(const String\&) const 方法

取得具有指定名稱的成員清單。

```cpp
ArrayPtr<SharedPtr<System::Reflection::MemberInfo>> System::TypeInfo::get_DeclaredMember(const String &name) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | const [String](../../string/)\& | 要取得的成員名稱。 |

### 回傳值

[Array](../../array/) 成員描述子（若未找到成員則為空）。

## 另請參閱

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* 類別 [MemberInfo](../../../system.reflection/memberinfo/)
* 類別 [String](../../string/)
* 類別 [TypeInfo](../)
* 命名空間 [System](../../)
* Library [Aspose.Slides](../../../)