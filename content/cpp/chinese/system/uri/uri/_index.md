---
title: Uri()
second_title: Aspose.Slides for C++ API 参考
description: 构造一个表示指定 URI 的 Uri 对象。
type: docs
weight: 287
url: /zh/system/uri/uri/
---
## Uri::Uri(const String\&) 构造函数

构造一个表示指定 URI 的 [Uri](../) 对象。

```cpp
System::Uri::Uri(const String &uriString)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | 用于表示正在构造的对象的字符串 URI |

## Uri::Uri(const String\&, bool) 构造函数

构造一个表示指定 URI 的 [Uri](../) 对象；一个参数指示是否应对 URI 进行转义。

```cpp
System::Uri::Uri(const String &uriString, bool dontEscape)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | 用于表示正在构造的对象的字符串 URI |
| dontEscape | **bool** | 指定是否不对 URI 进行转义 |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&, bool) 构造函数

从指定的表示基础 URI 的 [Uri](../) 对象和相对 URI 的字符串表示构造一个 [Uri](../) 对象；一个参数指定是否应对 URI 进行转义。

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri, bool dontEscape)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 基础 URI |
| relativeUri | const [String](../../string/)\& | 添加到基础 URI 的相对 URI |
| dontEscape | **bool** | 指定是否不对 URI 进行转义 |

## Uri::Uri(const String\&, UriKind) 构造函数

构造一个表示指定 URI 的 [Uri](../) 对象；一个参数指定 URI 的类型。

```cpp
System::Uri::Uri(const String &uriString, UriKind uriKind)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | 用于表示正在构造的对象的字符串 URI |
| uriKind | [UriKind](../../urikind/) | 指定 URI 的类型 |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&) 构造函数

从指定的基础和相对 URI 构造一个 [Uri](../) 对象。

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 基础 URI |
| relativeUri | const [String](../../string/)\& | 添加到基础 URI 的相对 URI |

## Uri::Uri(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) 构造函数

从指定的基础和相对 URI 构造一个 [Uri](../) 对象。

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 基础 URI |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 添加到基础 URI 的相对 URI |

## 另请参见

* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* 类 [String](../../string/)
* 类 [Uri](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)