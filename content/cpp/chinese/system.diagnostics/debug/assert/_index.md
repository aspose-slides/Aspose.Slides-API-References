---
title: Assert()
second_title: Aspose.Slides C++ API 参考
description: 断言条件并在失败时发送信息。
type: docs
weight: 14
url: /zh/system.diagnostics/debug/assert/
---
## Debug::Assert(bool) 方法

断言条件并在失败时发送信息。

```cpp
static void System::Diagnostics::Debug::Assert(bool condition)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| condition | **bool** | 条件值。 |

## Debug::Assert(bool, const String\&) 方法

断言条件并在失败时发送信息。

```cpp
static void System::Diagnostics::Debug::Assert(bool condition, const String &message)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| condition | **bool** | 条件值。 |
| message | const [String](../../../system/string/)\& | 在断言失败时填充的消息。 |

## Debug::Assert(bool, const char *) 方法

断言条件并在失败时发送信息。

```cpp
static void System::Diagnostics::Debug::Assert(bool condition, const char *message)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| condition | **bool** | 条件值。 |
| message | const char * | 在断言失败时填充的消息。 |

## Debug::Assert(bool, const String\&, const String\&) 方法

断言条件并在失败时发送信息。

```cpp
static void System::Diagnostics::Debug::Assert(bool condition, const String &message, const String &detailMessage)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| condition | **bool** | 条件值。 |
| message | const [String](../../../system/string/)\& | 在断言失败时填充的消息。 |
| detailMessage | const [String](../../../system/string/)\& | 在断言失败时填充的详细消息。 |

## 另见

* 类 [String](../../../system/string/)
* 结构体 [Debug](../)
* 命名空间 [System::Diagnostics](../../)
* 库 [Aspose.Slides](../../../)