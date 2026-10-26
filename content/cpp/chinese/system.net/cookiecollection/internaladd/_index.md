---
title: InternalAdd()
second_title: Aspose.Slides C++ API 参考
description: 将指定的 cookie 添加到集合中。
type: docs
weight: 118
url: /zh/system.net/cookiecollection/internaladd/
---
## CookieCollection::InternalAdd(System::SharedPtr\<Cookie\>, bool) 方法

将指定的 cookie 添加到集合中。

```cpp
int32_t System::Net::CookieCollection::InternalAdd(System::SharedPtr<Cookie> cookie, bool isStrict)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | 要添加的 cookie。 |
| isStrict | **bool** | 当必须用指定的 cookie 替换旧的时为 true，否则为 false。 |

### 返回值

当指定的 cookie 替换了旧的时返回 0，否则返回 1。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Cookie](../../cookie/)
* 类 [CookieCollection](../)
* 命名空间 [System::Net](../../)
* 库 [Aspose.Slides](../../../)