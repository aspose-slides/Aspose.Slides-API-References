---
title: Path
second_title: Aspose.Slides for C++ API Reference
description: Provides methods for manipulating paths. This is a static type with no instance services. You should never create instances of it by any means.
type: docs
weight: 326
url: /cpp/system.io/path/
---
## Path class


Provides methods for manipulating paths. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class Path
```

## Methods

| Method | Description |
| --- | --- |
| static [String](../../system/string/) [ChangeExtension](./changeextension/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Changes the extension in the specified file path. |
| static void [CheckPath](./checkpath/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Determines if the specified path is valid by checking if it contains invalid characters. An exception is thrown if the path contains invalid characters. |
| static [String](../../system/string/) [Combine](./combine/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Combines the specified path segments into a single path inserting directory separator characters between the segments if necessary. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Combines two specified path segments into a single path inserting directory separator character between the segments if necessary. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Combines three specified path segments into a single path inserting directory separator characters between the segments if necessary. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Combines four specified path segments into a single path inserting directory separator characters between the segments if necessary. |
| static [String](../../system/string/) [GetDirectoryName](./getdirectoryname/)(const [String](../../system/string/)\&) | Returns the name of the directory referenced by the specified path. |
| static [String](../../system/string/) [GetExtension](./getextension/)(const [String](../../system/string/)\&) | Returns the extension of the file referenced by the specified path. |
| static [String](../../system/string/) [GetFileName](./getfilename/)(const [String](../../system/string/)\&) | Returns the name of the file referenced by the specified path. |
| static [String](../../system/string/) [GetFileNameWithoutExtension](./getfilenamewithoutextension/)(const [String](../../system/string/)\&) | Returns the name without extension of the file referenced by the specified path. |
| static [String](../../system/string/) [GetFullPath](./getfullpath/)(const [String](../../system/string/)\&) | Converts the specified path into absolute path. |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidFileNameChars](./getinvalidfilenamechars/)() | Returns an array containing characters that are not allowed in the names of files. |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidPathChars](./getinvalidpathchars/)() | Returns an array containing characters that are not allowed in path names. |
| static [String](../../system/string/) [GetPathRoot](./getpathroot/)(const [String](../../system/string/)\&) | Returns the root directory of the specified path. |
| static [String](../../system/string/) [GetRandomFileName](./getrandomfilename/)() | Returns a randomly generated file name. |
| static [String](../../system/string/) [GetTempFileName_](./gettempfilename_/)() | Creates a new file with a unique name and returns a full path to it. |
| static [String](../../system/string/) [GetTempFileNameSafe](./gettempfilenamesafe/)() | Creates a new file with a unique name and returns a full path to it. Is a synonym of [GetTempFileName_()](./gettempfilename_/) method. |
| static [String](../../system/string/) [GetTempPath](./gettemppath/)() | Returns the path of the current user's temporary directory. |
| static **bool** [HasExtension](./hasextension/)(const [String](../../system/string/)\&) | Determines if the specified path references a file with extension. |
| static **bool** [IsPathRooted](./ispathrooted/)(const [String](../../system/string/)\&) | Determines if the specified path contains a root. |
| static [String](../../system/string/) [NormalizePath](./normalizepath/)(const [String](../../system/string/)\&) | Normalizes the specified path. |
| static boost::filesystem::path [ToBoost](./toboost/)(const [String](../../system/string/)\&) | Returns an instance of boost::filesystem::path class that represents the specified path. |
| static [String](../../system/string/) [ToString](./tostring/)(const boost::filesystem::path\&) | Returns a string representation of the specified Boost's path object. |
## Fields

| Field | Description |
| --- | --- |
| static [AltDirectorySeparatorChar](./altdirectoryseparatorchar/) | An alternate character used to separate directory levels in a path. |
| static [DirectorySeparatorChar](./directoryseparatorchar/) | A character used to separate directory levels in a path. |
| static [PathSeparator](./pathseparator/) | A separator character used to separate path strings in environment variables. |
| static [VolumeSeparatorChar](./volumeseparatorchar/) | A volume separator character. |
## Remarks



```cpp
#include "system/io/path.h"
#include <iostream>

int main()
{
  using namespace System::IO;

  // Generate a random filename.
  auto filename = Path::GetRandomFileName();

  // Print information about file name.
  std::cout <<
    "Filename: " << Path::GetFileName(filename) << std::endl <<
    "Filename w/o an extension: " << Path::GetFileNameWithoutExtension(filename) << std::endl <<
    "Extension: " << Path::GetExtension(filename) << std::endl;

  return 0;
}
/*
This code example produces the following output:
Filename: qhuzkyqv.y6p
Filename w/o an extension: qhuzkyqv
Extension: .y6p
*/
```

## See Also

* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)