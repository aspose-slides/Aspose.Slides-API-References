---
title: CreateHttp()
second_title: Aspose.Slides C++ API 参考
description: 使用指定的 URI 创建 WebRequest 类的新实例。
type: docs
weight: 79
url: /zh/system.net/webrequest/createhttp/
---
## WebRequest::CreateHttp(String) 方法

使用指定的 URI 创建 [WebRequest](../) 类的新实例。

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(String requestUriString)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| requestUriString | [String](../../../system/string/) | 用于创建 [WebRequest](../) 类新实例的 URI。 |

### 返回值

新创建的 WebRequest 类实例。

## 备注

当指定的 URI 以除 [http://](http://) 或 [https://](https://) 之外的任何方案开头时，将抛出 NotSupportedException。

## WebRequest::CreateHttp(System::SharedPtr\<Uri\>) 方法

使用指定的 URI 创建 [WebRequest](../) 类的新实例。

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(System::SharedPtr<Uri> requestUri)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| requestUri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 用于创建 [WebRequest](../) 类新实例的 URI。 |

### 返回值

新创建的 WebRequest 类实例。

## 备注

当指定的 URI 以除 [http://](http://) 或 [https://](https://) 之外的任何方案开头时，将抛出 NotSupportedException。

## 参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [HttpWebRequest](../../httpwebrequest/)
* 类 [String](../../../system/string/)
* 类 [WebRequest](../)
* 类 [Uri](../../../system/uri/)
* 命名空间 [System::Net](../../)
* Library [Aspose.Slides](../../../)