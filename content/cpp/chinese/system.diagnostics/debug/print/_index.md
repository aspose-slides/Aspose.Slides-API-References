---
title: Print()
second_title: Aspose.Slides for C++ API 参考
description: 将消息打印到调试接口。
type: docs
weight: 79
url: /zh/system.diagnostics/debug/print/
---
## Debug::Print(const String\&) 方法

将消息打印到调试接口。

```cpp
static void System::Diagnostics::Debug::Print(const String &message)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | const [String](../../../system/string/)\& | 要写入的消息。 |

## Debug::Print(const String\&, const System::ArrayPtr\<SharedPtr\<System::Object\>\>\&) 方法

将消息打印到调试接口。

```cpp
static void System::Diagnostics::Debug::Print(const String &format, const System::ArrayPtr<SharedPtr<System::Object>> &args)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | 格式字符串。 |
| args | const [System::ArrayPtr](../../../system/arrayptr/)\<[SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\>\& | 用于替换格式字符串的参数。 |

## 另请参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [Object](../../../system/object/)
* 结构体 [Debug](../)
* 命名空间 [System::Diagnostics](../../)
* 库 [Aspose.Slides](../../../)