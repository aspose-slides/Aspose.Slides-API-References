---
title: VerifySetDefaults()
second_title: Aspose.Slides C++ API 参考
description: 验证并设置默认属性的值。
type: docs
weight: 482
url: /zh/system.net/cookie/verifysetdefaults/
---
## Cookie::VerifySetDefaults(CookieVariant, System::SharedPtr\<Uri\>, bool, String, bool, bool) 方法

验证并设置默认属性的值。

```cpp
bool System::Net::Cookie::VerifySetDefaults(CookieVariant variant, System::SharedPtr<Uri> uri, bool isLocalDomain, String localDomain, bool setDefault, bool shouldThrow)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| variant | [CookieVariant](../../cookievariant/) | Cookie 的规范。 |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 用于初始化内部字段的 Uri 类实例。 |
| isLocalDomain | **bool** | 指示 cookie 是否被推送到本地域的值。 |
| localDomain | [String](../../../system/string/) | 本地域名。 |
| setDefault | **bool** | 指示是否必须使用默认值初始化 cookie 属性的值。 |
| shouldThrow | **bool** | 指示在指定值无效时是否应抛出异常的值。 |

### 返回值

当所有值有效时返回 true，否则返回 false。

## 另见

* 枚举 [CookieVariant](../../cookievariant/)
* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类 [Uri](../../../system/uri/)
* 类 [String](../../../system/string/)
* 类 [Cookie](../)
* 命名空间 [System::Net](../../)
* 库 [Aspose.Slides](../../../)