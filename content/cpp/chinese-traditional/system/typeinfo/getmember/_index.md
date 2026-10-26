---
title: GetMember()
second_title: Aspose.Slides for C++ API 參考
description: 取得指定名稱的成員列表。
type: docs
weight: 495
url: /zh-hant/system/typeinfo/getmember/
---
## TypeInfo::GetMember(const String\&) const 方法

取得指定名稱的成員列表。

```cpp
ArrayPtr<SharedPtr<System::Reflection::MemberInfo>> System::TypeInfo::GetMember(const String &name) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | const [String](../../string/)\& | 要取得的成員名稱。 |

### 返回值

[Array](../../array/) 的成員描述子（如果未找到成員則為空）。

## 另見

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* 類別 [MemberInfo](../../../system.reflection/memberinfo/)
* 類別 [String](../../string/)
* 類別 [TypeInfo](../)
* 命名空間 [System](../../)
* Library [Aspose.Slides](../../../)