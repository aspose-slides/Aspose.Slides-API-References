---
title: AppendFormat()
second_title: Aspose.Slides for C++ API 参考
description: 将格式化的字符串追加到构建器。
type: docs
weight: 131
url: /zh/system.text/stringbuilder/appendformat/
---
## StringBuilder::AppendFormat(const String&, const TArgs&...) 方法

将格式化的字符串追加到构建器。

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const String &format, const TArgs &... args)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| TArgs | 参数类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| format | const [String](../../../system/string/)& | 格式字符串。 |
| args | const TArgs&... | 要插入到格式字符串位置的参数。 |

### 返回值

此指针。

## StringBuilder::AppendFormat(const SharedPtr\<IFormatProvider\>&, const String&, const TArgs&...) 方法

将格式化的字符串追加到构建器。

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const SharedPtr<IFormatProvider> &fp, const String &format, const TArgs &... args)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| TArgs | 参数类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fp | const [SharedPtr](../../../system/sharedptr/)<[IFormatProvider](../../../system/iformatprovider/)>& | 格式提供程序；已忽略。 |
| format | const [String](../../../system/string/)& | 格式字符串。 |
| args | const TArgs&... | 要插入到格式字符串位置的参数。 |

### 返回值

此指针。

## 另请参见

* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类 [StringBuilder](../)
* 类 [String](../../../system/string/)
* 类 [IFormatProvider](../../../system/iformatprovider/)
* 命名空间 [System::Text](../../)
* 库 [Aspose.Slides](../../../)