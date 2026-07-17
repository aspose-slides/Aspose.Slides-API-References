---
title: "System::Web::Services::Protocols"
second_title: Aspose.Slides C++ API 参考
description: 
type: docs
weight: 1080
url: /zh/system.web.services.protocols/
---
## 类

| 类 | 描述 |
| --- | --- |
| [Details_SoapException](./details_soapexception/) | 表示在通过 SOAP 调用方法时抛出的异常，并且发生错误。切勿手动创建此类的实例。请改用 SoapException 类。切勿将 SoapException 类的实例封装到 [System::SmartPtr](../system/smartptr/) 中。 |
| [HttpWebClientProtocol](./httpwebclientprotocol/) | 此基类用于所有使用 HTTP 的 XML [Web](../system.web/) 服务客户端代理。该类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [InvokeCompletedEventArgs](./invokecompletedeventargs/) | 此类的实例作为参数传递给 InvokeCompletedEventHandler 委托。该类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [SoapClientMessage](./soapclientmessage/) | 表示已发送的 SOAP 请求或已接收的 SOAP 响应中的数据。该类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/) | 指定所有从方法传递或返回的 SOAP 消息使用 Document 格式。该类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/) | 设置 SOAP 请求和响应的默认格式。该类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [SoapHeader](./soapheader/) | 表示 SOAP 头的内容。该类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [SoapHeaderAttribute](./soapheaderattribute/) | 指定 XML [Web](../system.web/) 服务方法或 XML [Web](../system.web/) 服务客户端可以处理的 SOAP 头。该类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [SoapHeaderCollection](./soapheadercollection/) | 包含 [SoapHeader](./soapheader/) 类实例的集合。 |
| [SoapHttpClientProtocol](./soaphttpclientprotocol/) | 当使用 SOAP 时，客户端代理服务必须继承此类。该类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [SoapMessage](./soapmessage/) | 表示 SOAP 消息。该类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [WebClientProtocol](./webclientprotocol/) | 此基类用于所有使用 ASP.NET 创建的 XML [Web](../system.web/) 服务客户端代理。该类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [SoapHeaderDirection](./soapheaderdirection/) | 枚举 SOAP 头的方向。 |
| [SoapMessageStage](./soapmessagestage/) | 枚举 SOAP 消息的处理阶段。 |
| [SoapParameterStyle](./soapparameterstyle/) | 枚举 SOAP 消息中参数的格式。 |
| [SoapProtocolVersion](./soapprotocolversion/) | 枚举 SOAP 的版本。 |
| [SoapServiceRoutingStyle](./soapserviceroutingstyle/) | 枚举将 SOAP 消息路由到 XML [Web](../system.web/) 服务的方式选项。 |
## 类型定义

| 类型定义 | 描述 |
| --- | --- |
| [SoapException](./soapexception/) |  |