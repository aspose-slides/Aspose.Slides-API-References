---
title: Details_ExceptionWithFilename
second_title: Aspose.Slides C++ API 参考
description: 用于带文件名的异常的模板类。
type: docs
weight: 443
url: /zh/system/details_exceptionwithfilename/
---
## Details_ExceptionWithFilename 类

此模板类用于带文件名的异常。

```cpp
template<typename T,typename>class Details_ExceptionWithFilename : public T
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 异常基类。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| virtual [String](../string/) [get_FileName](./get_filename/)() const | 获取导致此异常的文件名。 |
| [String](../string/) [get_Message](./get_message/)() const override |  |
| [String](../string/) [ToString](./tostring/)() const override |  |

## 另见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)