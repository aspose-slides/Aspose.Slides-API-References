---
title: "System::Net::Cache"
second_title: Aspose.Slides for C++ API 参考
description: 
type: docs
weight: 664
url: /zh/system.net.cache/
---
## 类

| 类 | 描述 |
| --- | --- |
| [HttpRequestCachePolicy](./httprequestcachepolicy/) | HTTP 缓存策略，遵循 RFC2616 HTTP 缓存语义。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。不要在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言失败。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [RequestCachePolicy](./requestcachepolicy/) | 常用请求缓存策略，用于缓存 [Http](../system.net.http/)、FTP 等。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。不要在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言失败。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [RequestCacheLevel](./requestcachelevel/) | 此枚举描述适用于任何 [WebRequest](../system.net/webrequest/) 的缓存设置。 |
| [HttpRequestCacheLevel](./httprequestcachelevel/) | 此枚举描述 HTTP 的缓存设置。 |
| [HttpCacheAgeControl](./httpcacheagecontrol/) | CacheAgeControl 用于指定对缓存项的年龄和新鲜度的偏好。 |