---
title: Details_FileNotFoundException
second_title: "Aspose.Slides for C++ API 参考"
description: "当尝试访问磁盘上不存在的文件时抛出的异常。不要手动创建该类的实例。请改用 FileNotFoundException 类。不要将 FileNotFoundException 类的实例包装到 System::SmartPtr 中。"
type: docs
weight: 183
url: /zh/system.io/details_filenotfoundexception/
---
## Details_FileNotFoundException 类

当尝试访问磁盘上不存在的文件时抛出的异常。不要手动创建该类的实例。请改用 FileNotFoundException 类。不要将 FileNotFoundException 类的实例包装到 [System::SmartPtr](../../system/smartptr/) 中。

```cpp
class Details_FileNotFoundException : public System::Details_ExceptionWithFilename<Details_IOException>
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual [String](../../system/string/) [get_FileName](../../system/details_exceptionwithfilename/get_filename/)() const | 获取导致此异常的文件的名称。 |
| [String](../../system/string/) [get_Message](../../system/details_exceptionwithfilename/get_message/)() const override |  |
| [String](../../system/string/) [ToString](../../system/details_exceptionwithfilename/tostring/)() const override |  |

## 另请参阅

* 类 [Details_ExceptionWithFilename](../../system/details_exceptionwithfilename/)
* 命名空间 [System::IO](../)
* 库 [Aspose.Slides](../../)