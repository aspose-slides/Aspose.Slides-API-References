---
title: "System::Security"
second_title: Aspose.Slides C++ API 参考
description: 
type: docs
weight: 807
url: /zh/system.security/
---
## 类

| 类 | 描述 |
| --- | --- |
| [Details_SecurityException](./details_securityexception/) |  |
| [SecureString](./securestring/) | 安全字符串，表示应保持机密的文本。此类不加密内部数据。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。不要在栈上或使用 operator new 创建此类型的实例，因为这将导致运行时错误和/或断言故障。始终将此类包装在 [System::SmartPtr](../system/smartptr/) 指针中，并使用该指针将其作为参数传递给函数。 |
| [SecureStringMarshal](./securestringmarshal/) | 用于分配和复制非托管内存块的方法集合。 |
| [SecurityElement](./securityelement/) | 用于编码安全对象的 XML 对象模型。未实现。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。不要在栈上或使用 operator new 创建此类型的实例，因为这将导致运行时错误和/或断言故障。始终将此类包装在 [System::SmartPtr](../system/smartptr/) 指针中，并使用该指针将其作为参数传递给函数。 |
## 类型定义

| 类型定义 | 描述 |
| --- | --- |
| [SecurityException](./securityexception/) |  |
| [SecureStringPtr](./securestringptr/) | [SecureString](./securestring/) 指针类型。