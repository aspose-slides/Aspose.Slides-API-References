---
title: Format()
second_title: Aspose.Slides C++ API 参考
description: 以 C# 样式格式化字符串。
type: docs
weight: 885
url: /zh/system/string/format/
---
## String::Format(const SharedPtr\<IFormatProvider\>\&, const String\&, const Args\&...) 方法

以 C# 样式格式化字符串。

```cpp
template<class...> String System::String::Format(const SharedPtr<IFormatProvider> &fp, const String &format, const Args &... args)
```

### 模板参数

| 参数 | 说明 |
| --- | --- |
| Args | 参数用于格式化字符串。 |

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| fp | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 用于将参数转换为字符串的格式提供程序。 |
| format | const [String](../)\& | 格式字符串。 |
| args | const Args\&... | 参数用于格式化字符串。 |

## String::Format(std::nullptr_t, const String\&, const Args\&...) 方法

以 C# 样式格式化字符串。

```cpp
template<class...> String System::String::Format(std::nullptr_t, const String &format, const Args &... args)
```

### 模板参数

| 参数 | 说明 |
| --- | --- |
| Args | 参数用于格式化字符串。 |

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| format | std::nullptr_t | 格式字符串。 |
| args | const [String](../)\& | 参数用于格式化字符串。 |

## String::Format(std::nullptr_t, const char16_t(&), const Args\&...) 方法

以 C# 样式格式化字符串。

```cpp
template<std::size_t,class...> String System::String::Format(std::nullptr_t, const char16_t(&format)[N], const Args &... args)
```

### 模板参数

| 参数 | 说明 |
| --- | --- |
| Args | 参数用于格式化字符串。 |

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| format | std::nullptr_t | 格式字符串。 |
| args | const char16_t(&) | 参数用于格式化字符串。 |

## String::Format(const String\&, const Args\&...) 方法

以 C# 样式格式化字符串。

```cpp
template<class...> String System::String::Format(const String &format, const Args &... args)
```

### 模板参数

| 参数 | 说明 |
| --- | --- |
| Args | 参数用于格式化字符串。 |

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| format | const [String](../)\& | 格式字符串。 |
| args | const Args\&... | 参数用于格式化字符串。 |

## String::Format(const String\&, const System::ArrayPtr\<T\>\&) 方法

以 C# 样式格式化字符串。

```cpp
template<class T> String System::String::Format(const String &format, const System::ArrayPtr<T> &args)
```

### 模板参数

| 参数 | 说明 |
| --- | --- |
| T | 参数用于格式化字符串。 |

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| format | const [String](../)\& | 格式字符串。 |
| args | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | 参数用于格式化字符串。 |

## 另见

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* 类 [String](../)
* 类 [IFormatProvider](../../iformatprovider/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)