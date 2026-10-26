---
title: Path
second_title: Aspose.Slides for C++ API 参考
description: 提供用于操作路径的方法。这是一个没有实例服务的静态类型。绝不应以任何方式创建其实例。
type: docs
weight: 339
url: /zh/system.io/path/
---
## Path 类

提供用于操作路径的方法。这是一个没有实例服务的静态类型。绝不应以任何方式创建其实例。

```cpp
class Path
```

## 方法

| Method | Description |
| --- | --- |
| static [String](../../system/string/) [ChangeExtension](./changeextension/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 更改指定文件路径的扩展名。 |
| static void [CheckPath](./checkpath/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | 通过检查指定路径是否包含无效字符来确定其是否有效。如果路径包含无效字符，则会抛出异常。 |
| static [String](../../system/string/) [Combine](./combine/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | 将指定的路径片段组合成单个路径，并在必要时在片段之间插入目录分隔符字符。 |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 将两个指定的路径片段组合成单个路径，并在必要时在片段之间插入目录分隔符字符。 |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 将三个指定的路径片段组合成单个路径，并在必要时在片段之间插入目录分隔符字符。 |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 将四个指定的路径片段组合成单个路径，并在必要时在片段之间插入目录分隔符字符。 |
| static [String](../../system/string/) [GetDirectoryName](./getdirectoryname/)(const [String](../../system/string/)\&) | 返回指定路径所引用的目录名称。 |
| static [String](../../system/string/) [GetExtension](./getextension/)(const [String](../../system/string/)\&) | 返回指定路径所引用的文件的扩展名。 |
| static [String](../../system/string/) [GetFileName](./getfilename/)(const [String](../../system/string/)\&) | 返回指定路径所引用的文件名称。 |
| static [String](../../system/string/) [GetFileNameWithoutExtension](./getfilenamewithoutextension/)(const [String](../../system/string/)\&) | 返回指定路径所引用的文件的无扩展名名称。 |
| static [String](../../system/string/) [GetFullPath](./getfullpath/)(const [String](../../system/string/)\&) | 将指定路径转换为绝对路径。 |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidFileNameChars](./getinvalidfilenamechars/)() | 返回一个数组，包含文件名中不允许使用的字符。 |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidPathChars](./getinvalidpathchars/)() | 返回一个数组，包含路径名中不允许使用的字符。 |
| static [String](../../system/string/) [GetPathRoot](./getpathroot/)(const [String](../../system/string/)\&) | 返回指定路径的根目录。 |
| static [String](../../system/string/) [GetRandomFileName](./getrandomfilename/)() | 返回随机生成的文件名。 |
| static [String](../../system/string/) [GetTempFileName_](./gettempfilename_/)() | 创建一个具有唯一名称的新文件并返回其完整路径。 |
| static [String](../../system/string/) [GetTempFileNameSafe](./gettempfilenamesafe/)() | 创建一个具有唯一名称的新文件并返回其完整路径。是 [GetTempFileName_()](./gettempfilename_/) 方法的同义词。 |
| static [String](../../system/string/) [GetTempPath](./gettemppath/)() | 返回当前用户临时目录的路径。 |
| static **bool** [HasExtension](./hasextension/)(const [String](../../system/string/)\&) | 确定指定路径是否引用了带扩展名的文件。 |
| static **bool** [IsPathRooted](./ispathrooted/)(const [String](../../system/string/)\&) | 确定指定路径是否包含根目录。 |
| static [String](../../system/string/) [NormalizePath](./normalizepath/)(const [String](../../system/string/)\&) | 规范化指定的路径。 |
| static boost::filesystem::path [ToBoost](./toboost/)(const [String](../../system/string/)\&) | 返回一个表示指定路径的 boost::filesystem::path 类的实例。 |
| static [String](../../system/string/) [ToString](./tostring/)(const boost::filesystem::path\&) | 返回指定 Boost 路径对象的字符串表示。 |
## 字段

| Field | Description |
| --- | --- |
| static [AltDirectorySeparatorChar](./altdirectoryseparatorchar/) | 用于在路径中分隔目录层级的备用字符。 |
| static [DirectorySeparatorChar](./directoryseparatorchar/) | 用于在路径中分隔目录层级的字符。 |
| static [PathSeparator](./pathseparator/) | 用于在环境变量中分隔路径字符串的分隔符字符。 |
| static [VolumeSeparatorChar](./volumeseparatorchar/) | 卷分隔符字符。 |
## 备注



```cpp
#include "system/io/path.h"
#include <iostream>

int main()
{
  using namespace System::IO;

  // 生成随机文件名。
  auto filename = Path::GetRandomFileName();

  // 打印文件名信息。
  std::cout <<
    "Filename: " << Path::GetFileName(filename) << std::endl <<
    "Filename w/o an extension: " << Path::GetFileNameWithoutExtension(filename) << std::endl <<
    "Extension: " << Path::GetExtension(filename) << std::endl;

  return 0;
}
/*
此代码示例产生以下输出：
Filename: qhuzkyqv.y6p
Filename w/o an extension: qhuzkyqv
Extension: .y6p
*/
```

## 另请参见

* 命名空间 [System::IO](../)
* 库 [Aspose.Slides](../../)