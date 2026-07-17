---
title: Add()
second_title: Aspose.Slides 的 C++ API 参考
description: 向集合中添加 cookie。
type: docs
weight: 53
url: /zh/system.net/cookiecollection/add/
---
## CookieCollection::Add(const System::SharedPtr\<Cookie\>\&) 方法

向集合中添加 cookie。

```cpp
void System::Net::CookieCollection::Add(const System::SharedPtr<Cookie> &cookie) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cookie | const [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\>\& | 要添加的 cookie。 |

## CookieCollection::Add(System::SharedPtr\<CookieCollection\>) 方法

从指定的集合中添加 cookie 到当前集合。

```cpp
void System::Net::CookieCollection::Add(System::SharedPtr<CookieCollection> cookies)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../)\> | 将 cookie 复制到当前集合的来源集合。 |

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Cookie](../../cookie/)
* 类 [CookieCollection](../)
* 命名空间 [System::Net](../../)
* 库 [Aspose.Slides](../../../)