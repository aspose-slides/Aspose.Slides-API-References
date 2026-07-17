---
title: "System::Drawing::Printing"
second_title: Aspose.Slides for C++ API 参考
description: 
type: docs
weight: 521
url: /zh/system.drawing.printing/
---
## 类

| 类 | 描述 |
| --- | --- |
| [Margins](./margins/) | 表示打印页的边距。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。永远不要在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [PageSettings](./pagesettings/) | 表示打印页的设置。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。永远不要在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [PaperSize](./papersize/) | 指定纸张的尺寸。 |
| [PrintController](./printcontroller/) | 控制文档的打印方式，当从 [Windows](../system.windows/) Forms 应用程序打印时。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。永远不要在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [PrintDocument](./printdocument/) | 在从 [Windows](../system.windows/) Forms 应用程序打印时，将输出发送到打印机。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。永远不要在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [PrinterResolution](./printerresolution/) | 表示打印机的分辨率。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。永远不要在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [PrinterSettings](./printersettings/) | 表示打印机的设置。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。永远不要在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [PrintEventArgs](./printeventargs/) | 提供 BeginPrint 和 EndPrint 事件的数据。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。永远不要在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [PrintPageEventArgs](./printpageeventargs/) | 提供 PrintPage 事件的数据。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。永远不要在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [QueryPageSettingsEventArgs](./querypagesettingseventargs/) | 提供 QueryPageSettings 事件的数据。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。永远不要在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [StandardPrintController](./standardprintcontroller/) | 指定将信息发送到打印机的打印控制器。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。永远不要在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [PaperKind](./paperkind/) | 指定标准纸张尺寸。 |
| [PrintAction](./printaction/) | 指定打印操作的类型。 |
| [PrintRange](./printrange/) | 指定要打印的页面。 |
## 类型别名

| 类型别名 | 描述 |
| --- | --- |
| [PrintPageEventHandler](./printpageeventhandler/) | 处理 PrintPage 事件的函数类型。 |
| [PrintEventHandler](./printeventhandler/) | 处理 BeginPrint 和 EndPrint 事件的函数对象类型。 |