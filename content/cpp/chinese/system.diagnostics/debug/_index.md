---
title: Debug
second_title: Aspose.Slides for C++ API 参考
description: 收集调试方法，允许将调试信息发送给已注册的侦听器。所有输出函数仅在 Debug 中工作。这是一个没有实例服务的静态类型。绝不应以任何方式创建其实例。
type: docs
weight: 105
url: /zh/system.diagnostics/debug/
---
## 调试结构体

收集调试方法，允许将调试信息发送给已注册的侦听器。所有输出函数仅在 [Debug](./) 中工作。这是一个没有实例服务的静态类型。绝不应以任何方式创建其实例。

```cpp
class Debug
```

## 方法

| Method | Description |
| --- | --- |
| static void [Assert](./assert/)(**bool**) | 断言条件并在失败时发送信息。 |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&) | 断言条件并在失败时发送信息。 |
| static void [Assert](./assert/)(**bool**, const char *) | 断言条件并在失败时发送信息。 |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 断言条件并在失败时发送信息。 |
| static void [Fail](./fail/)(const [String](../../system/string/)\&) | 发送失败消息。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<[TraceListener](../tracelistener/)\>\>\> [get_Listeners](./get_listeners/)() | 访问静态监听器列表。 |
| static void [Print](./print/)(const [String](../../system/string/)\&) | 将消息打印到调试接口。 |
| static void [Print](./print/)(const [String](../../system/string/)\&, const [System::ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>\&) | 将消息打印到调试接口。 |
| static void [Write](./write/)(const [String](../../system/string/)\&) | 将字符串写入调试接口。 |
| static void [Write](./write/)(const char_t *) | 将字符串写入调试接口。 |
| static void [WriteIf](./writeif/)(**bool**, const [System::String](../../system/string/)\&) | 如果条件为真，则将字符串写入调试接口。 |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | 将行写入调试接口。 |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 将行写入调试接口。 |
| static void [WriteLine](./writeline/)(const char_t *) | 将行写入调试接口。 |
| static void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | 将行写入调试接口。 |
| static void [WriteLineIf](./writelineif/)(**bool**, const [System::String](../../system/string/)\&) | 如果条件为真，则将行写入调试接口。 |

## 另见

* 命名空间 [System::Diagnostics](../)
* 库 [Aspose.Slides](../../)