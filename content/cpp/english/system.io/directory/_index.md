---
title: Directory
second_title: Aspose.Slides for C++ API Reference
description: Contains methods for manipulating directories. This is a static type with no instance services. You should never create instances of it by any means.
type: docs
weight: 222
url: /system.io/directory/
---
## Directory class


Contains methods for manipulating directories. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class Directory
```

## Methods

| Method | Description |
| --- | --- |
| static void [CreateDirectory_](./createdirectory_/)(const [String](../../system/string/)\&) | Creates all directories in the specified path if those don't exist. |
| static void [Delete](./delete/)(const [String](../../system/string/)\&, **bool**) | Removes the specified file or directory. Does not throw. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Searches for the directories that satisfy the specified search criteria either in the specified directory or in the whole directory tree rooted in the specified directory. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Searches for the files that satisfy the specified search criteria either in the specified directory or in the whole directory tree rooted in the specified directory. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFileSystemEntries](./enumeratefilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Searches for the files and directories that satisfy the specified search criteria either in the specified directory or in the whole directory tree rooted in the specified directory. |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | Determines if the specified path refers to existing directory. |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | Returns the creation time of the specified entity as local time. |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | Returns the creation time of the specified entity as UTC time. |
| static [String](../../system/string/) [GetCurrentDirectory](./getcurrentdirectory/)() | Returns the full name (including path) of the current directory. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Searches for the directories that satisfy the specified search criteria either in the specified directory or in the whole directory tree rooted in the specified directory. |
| static [String](../../system/string/) [GetDirectoryRoot](./getdirectoryroot/)(const [String](../../system/string/)\&) | Returns the root directory of the specified path. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Searches for the files that satisfy the specified search criteria either in the specified directory or in the whole directory tree rooted in the specified directory. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFileSystemEntries](./getfilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Searches for the files and directories that satisfy the specified search criteria either in the specified directory or in the whole directory tree rooted in the specified directory. |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | Returns the last access time of the specified entity as local time. |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | Returns the last access time of the specified entity as UTC time. |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | Returns the last write time of the specified entity as local time. |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | Returns the last write time of the specified entity as UTC time. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetLogicalDrives](./getlogicaldrives/)() | NOT IMPLEMENTED. |
| static [DirectoryInfoPtr](../../system/directoryinfoptr/) [GetParent](./getparent/)(const [String](../../system/string/)\&) | Returns a shared pointer to [DirectoryInfo](../directoryinfo/) object representing the parent directory of the specified entity. |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Moves the specified entity to the new location. If the entity to move is a directory, it is moved with all its content. |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Sets the creation time of the specified entity as local time. |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Sets the creation time of the specified entity as UTC time. |
| static void [SetCurrentDirectory](./setcurrentdirectory/)(const [String](../../system/string/)\&) | Sets the current directory. |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Sets the last access time of the specified entity as local time. |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Sets the last access time of the specified entity as UTC time. |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Sets the last write time of the specified entity as local time. |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Sets the last write time of the specified entity as UTC time. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [StringEnumerablePtr](./stringenumerableptr/) | An alias for a shared pointer to IEnumerable object that enumerates over a set of [String](../../system/string/) objects. |
## Remarks



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
  // Create strings that contain paths to directories.
  System::String discPath(u"C:\\");
  System::String directoryPath(u"C:\\Some directory");
  auto tempPath = System::IO::Path::GetTempPath();

  // Check if directories exist.
  PrintMessage(discPath);
  PrintMessage(directoryPath);
  PrintMessage(tempPath);

  // Print the temp directory information.
  std::cout <<
    "Creation Time: " << System::IO::Directory::GetCreationTime(tempPath) << std::endl <<
    "Last Access Time: " << System::IO::Directory::GetLastAccessTime(tempPath) << std::endl <<
    "Last Write Time: " << System::IO::Directory::GetLastWriteTime(tempPath) << std::endl;

  return 0;
}
/*
This code example produces the following output:
Directory 'C:\' exists.
Directory 'C:\Some directory' doesn't exist.
Directory 'C:\Users\lanor\AppData\Local\Temp\' exists.
Creation Time: 27.08.2021 14:21:42
Last Access Time: 07.10.2021 12:16:41
Last Write Time: 07.10.2021 12:16:41
*/
```

## See Also

* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)