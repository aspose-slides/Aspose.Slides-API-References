---
title: Create()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的 URI 创建 WebRequest 类的新实例。
type: docs
weight: 53
url: /zh/system.net/webrequest/create/
---
## WebRequest::Create(String) 方法

创建使用指定 URI 的 [WebRequest](../) 类的新实例。

```cpp
static System::SharedPtr<WebRequest> System::Net::WebRequest::Create(String requestUriString)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| requestUriString | [String](../../../system/string/) | 用于创建 [WebRequest](../) 类新实例的 URI。 |

### 返回值

新创建的 WebRequest-class 实例。

## WebRequest::Create(System::SharedPtr\<Uri\>) 方法

创建使用指定 URI 的 [WebRequest](../) 类的新实例。

```cpp
static System::SharedPtr<WebRequest> System::Net::WebRequest::Create(System::SharedPtr<Uri> requestUri)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| requestUri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 用于创建 [WebRequest](../) 类新实例的 URI。 |

### 返回值

新创建的 WebRequest-class 实例。

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [WebRequest](../)
* Class [String](../../../system/string/)
* Class [Uri](../../../system/uri/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)