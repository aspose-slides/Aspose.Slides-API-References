---
title: Directory
second_title: Aspose.Slides for C++ API 参考
description: 包含用于操作目录的方法。这是一个没有实例服务的静态类型。绝不应以任何方式创建其实例。
type: docs
weight: 235
url: /zh/system.io/directory/
---
## Directory 类

包含用于操作目录的方法。这是一个没有实例服务的静态类型。绝不应以任何方式创建其实例。

```cpp
class Directory
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static void [CreateDirectory_](./createdirectory_/)(const [String](../../system/string/)\&) | 如果指定的路径不存在，则创建该路径中的所有目录。 |
| static void [Delete](./delete/)(const [String](../../system/string/)\&, **bool**) | 删除指定的文件或目录。不会抛出异常。 |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | 搜索满足指定搜索条件的目录，搜索范围可以是指定的目录或以指定目录为根的整个目录树。 |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | 搜索满足指定搜索条件的文件，搜索范围可以是指定的目录或以指定目录为根的整个目录树。 |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFileSystemEntries](./enumeratefilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | 搜索满足指定搜索条件的文件和目录，搜索范围可以是指定的目录或以指定目录为根的整个目录树。 |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | 确定指定的路径是否指向现有目录。 |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | 返回指定实体的创建时间（本地时间）。 |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | 返回指定实体的创建时间（UTC 时间）。 |
| static [String](../../system/string/) [GetCurrentDirectory](./getcurrentdirectory/)() | 返回当前目录的完整名称（包括路径）。 |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | 搜索满足指定搜索条件的目录，搜索范围可以是指定的目录或以指定目录为根的整个目录树。 |
| static [String](../../system/string/) [GetDirectoryRoot](./getdirectoryroot/)(const [String](../../system/string/)\&) | 返回指定路径的根目录。 |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | 搜索满足指定搜索条件的文件，搜索范围可以是指定的目录或以指定目录为根的整个目录树。 |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFileSystemEntries](./getfilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | 搜索满足指定搜索条件的文件和目录，搜索范围可以是指定的目录或以指定目录为根的整个目录树。 |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | 返回指定实体的上次访问时间（本地时间）。 |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | 返回指定实体的上次访问时间（UTC 时间）。 |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | 返回指定实体的上次写入时间（本地时间）。 |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | 返回指定实体的上次写入时间（UTC 时间）。 |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetLogicalDrives](./getlogicaldrives/)() | 未实现。 |
| static [DirectoryInfoPtr](../../system/directoryinfoptr/) [GetParent](./getparent/)(const [String](../../system/string/)\&) | 返回指向表示指定实体父目录的 [DirectoryInfo](../directoryinfo/) 对象的共享指针。 |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 将指定实体移动到新位置。如果要移动的实体是目录，则连同其所有内容一起移动。 |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | 设置指定实体的创建时间（本地时间）。 |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | 设置指定实体的创建时间（UTC 时间）。 |
| static void [SetCurrentDirectory](./setcurrentdirectory/)(const [String](../../system/string/)\&) | 设置当前目录。 |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | 设置指定实体的上次访问时间（本地时间）。 |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | 设置指定实体的上次访问时间（UTC 时间）。 |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | 设置指定实体的上次写入时间（本地时间）。 |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | 设置指定实体的上次写入时间（UTC 时间）。 |

## 类型别名

| 类型别名 | 描述 |
| --- | --- |
| [StringEnumerablePtr](./stringenumerableptr/) | IEnumerable 对象的共享指针别名，用于枚举一组 [String](../../system/string/) 对象。 |

## 备注



```cpp
#include "system/io/directory.h"
#include "system/io/path.h"
#include "system/string.h"
#include <iostream>

void PrintMessage(const System::String &path)
{
  std::cout << "Directory '" << path << (System::IO::Directory::Exists(path) ? "' exists." : "' doesn't exist.") << std::endl;
}

int main()
{
  // 创建包含目录路径的字符串。
  System::String discPath(u"C:\\");
  System::String directoryPath(u"C:\\Some directory");
  auto tempPath = System::IO::Path::GetTempPath();

  // 检查目录是否存在。
  PrintMessage(discPath);
  PrintMessage(directoryPath);
  PrintMessage(tempPath);

  // 打印临时目录信息。
  std::cout <<
    "Creation Time: " << System::IO::Directory::GetCreationTime(tempPath) << std::endl <<
    "Last Access Time: " << System::IO::Directory::GetLastAccessTime(tempPath) << std::endl <<
    "Last Write Time: " << System::IO::Directory::GetLastWriteTime(tempPath) << std::endl;

  return 0;
}
/*
此代码示例产生以下输出：
Directory 'C:\' 已存在。
Directory 'C:\Some directory' 不存在。
Directory 'C:\Users\lanor\AppData\Local\Temp\' 已存在。
创建时间: 27.08.2021 14:21:42
最后访问时间: 07.10.2021 12:16:41
最后写入时间: 07.10.2021 12:16:41
*/
```

## 另请参阅

* 命名空间 [System::IO](../)
* 库 [Aspose.Slides](../../)