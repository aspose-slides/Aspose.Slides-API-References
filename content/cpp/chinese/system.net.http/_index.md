---
title: "System::Net::Http"
second_title: Aspose.Slides C++ API 参考
description: 
type: docs
weight: 677
url: /zh/system.net.http/
---
## 类

| 类 | 描述 |
| --- | --- |
| [ByteArrayContent](./bytearraycontent/) | 表示 HTTP 内容为字节数组。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [Details_HttpRequestException](./details_httprequestexception/) | 基础异常类由 [HttpClient](./httpclient/) 和 [HttpMessageHandler](./httpmessagehandler/) 类抛出。切勿手动创建此类的实例。请改用 HttpRequestException 类。永远不要将 HttpRequestException 类的实例包装到 [System::SmartPtr](../system/smartptr/) 中。 |
| [HttpClient](./httpclient/) | 表示用于发送请求和接收响应的 HTTP 客户端的基类。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [HttpClientHandler](./httpclienthandler/) | 表示 [HttpClient](./httpclient/) 类使用的默认消息处理器。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [HttpContent](./httpcontent/) | 表示 HTTP 实体的内容。此类的 [Object](../system/object/) 只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [HttpMessageHandler](./httpmessagehandler/) | 表示 HTTP 消息处理器的基类型。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [HttpMessageInvoker](./httpmessageinvoker/) | 允许应用程序在 HTTP 处理程序链上调用 Send 方法。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [HttpMethod](./httpmethod/) | 表示 HTTP 方法。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [HttpRequestMessage](./httprequestmessage/) | 表示 HTTP 请求消息。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [HttpResponseMessage](./httpresponsemessage/) | 表示 HTTP 响应消息。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [HttpUtilities](./httputilities/) | 包含实用方法。 |
| [StringContent](./stringcontent/) | 表示 HTTP 内容为字符串。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |

## 函数

| 函数 | 描述 |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)([System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>, [System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>) |  |
| **bool** [operator!=](./operator_not_equal/)([System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>, [System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>) |  |

## 枚举

| 枚举 | 描述 |
| --- | --- |
| [HttpCompletionOption](./httpcompletionoption/) | 指示 [HttpClient](./httpclient/) 操作应何时完成。 |
| [HttpParseResult](./httpparseresult/) | 指示解析结果。 |

## 类型别名

| 类型别名 | 描述 |
| --- | --- |
| [HttpRequestException](./httprequestexception/) |  |