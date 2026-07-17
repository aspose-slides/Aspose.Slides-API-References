---
title: TryCreate()
second_title: Aspose.Slides for C++ API 参考
description: 构造一个表示指定 URI 的 Uri 对象；一个参数指定 URI 类型。
type: docs
weight: 508
url: /zh/system/uri/trycreate/
---
## Uri::TryCreate(const String\&, UriKind, SharedPtr\<Uri\>\&) 方法

构造一个 [Uri](../) 对象来表示指定的 URI；一个参数指定 URI 类型。

```cpp
static bool System::Uri::TryCreate(const String &uriString, UriKind uriKind, SharedPtr<Uri> &result)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | 要由构造的对象表示的字符串 URI |
| uriKind | [UriKind](../../urikind/) | 指定 URI 类型 |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 输出参数；如果构造成功，方法返回时指向新构造的 [Uri](../) 对象 |

### 返回值

如果构造成功返回 true，否则返回 false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const String\&, SharedPtr\<Uri\>\&) 方法

从表示基 URI 的指定 [Uri](../) 对象以及相对 URI 的字符串表示构造一个 [Uri](../) 对象。

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const String &relativeUri, SharedPtr<Uri> &result)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 基 URI |
| relativeUri | const [String](../../string/)\& | 要添加到基 URI 的相对 URI |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 输出参数；如果构造成功，方法返回时指向新构造的 [Uri](../) 对象 |

### 返回值

如果构造成功返回 true，否则返回 false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, SharedPtr\<Uri\>\&) 方法

从指定的基 URI 和相对 URI 构造一个 [Uri](../) 对象。

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri, SharedPtr<Uri> &result)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 基 URI |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 要添加到基 URI 的相对 URI |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 输出参数；如果构造成功，方法返回时指向新构造的 [Uri](../) 对象 |

### 返回值

如果构造成功返回 true，否则返回 false

## 另请参见

* 枚举 [UriKind](../../urikind/)
* 类型定义 [SharedPtr](../../sharedptr/)
* 类 [String](../../string/)
* 类 [Uri](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)