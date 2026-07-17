---
title: GetCookieHeader()
second_title: Aspose.Slides for C++ API 参考
description: 返回一个包含与指定 URI 关联的 cookie 的 HTTP 标头。
type: docs
weight: 170
url: /zh/system.net/cookiecontainer/getcookieheader/
---
## CookieContainer::GetCookieHeader(System::SharedPtr\<Uri\>) 方法

返回一个包含与指定 URI 关联的 cookie 的 HTTP 标头。

```cpp
String System::Net::CookieContainer::GetCookieHeader(System::SharedPtr<Uri> uri)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 用于构建标头名称的 URI。 |

### 返回值

返回一个包含与指定 URI 关联的 cookie 的 HTTP 标头。

## CookieContainer::GetCookieHeader(System::SharedPtr\<Uri\>, String\&) 方法

返回一个包含与指定 URI 关联的 cookie 的 HTTP 标头。

```cpp
String System::Net::CookieContainer::GetCookieHeader(System::SharedPtr<Uri> uri, String &optCookie2)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 用于构建标头名称的 URI。 |
| optCookie2 | [String](../../../system/string/)\& | 输出参数，将分配具有最高支持版本的 cookie。 |

### 返回值

返回一个包含与指定 URI 关联的 cookie 的 HTTP 标头。

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [Uri](../../../system/uri/)
* 类 [CookieContainer](../)
* 命名空间 [System::Net](../../)
* 库 [Aspose.Slides](../../../)