---
title: Directory
second_title: Aspose.Slides for C++ API 參考
description: 包含用於操作目錄的方法。這是一個靜態型別，沒有實例服務。絕不應以任何方式建立其實例。
type: docs
weight: 235
url: /zh-hant/system.io/directory/
---
## Directory 類別

包含用於操作目錄的方法。這是一個靜態型別，沒有實例服務。絕不應以任何方式建立其實例。

```cpp
class Directory
```

## 方法

| 方法 | 說明 |
| --- | --- |
| static void [CreateDirectory_](./createdirectory_/)(const [String](../../system/string/)\&) | 若指定的路徑不存在，則建立所有目錄。 |
| static void [Delete](./delete/)(const [String](../../system/string/)\&, **bool**) | 刪除指定的檔案或目錄。不會拋出例外。 |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | 搜尋符合指定搜尋條件的目錄，搜尋範圍可以是指定的目錄，亦或是以該目錄為根的整個目錄樹。 |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | 搜尋符合指定搜尋條件的檔案，搜尋範圍可以是指定的目錄，亦或是以該目錄為根的整個目錄樹。 |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFileSystemEntries](./enumeratefilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | 搜尋符合指定搜尋條件的檔案與目錄，搜尋範圍可以是指定的目錄，亦或是以該目錄為根的整個目錄樹。 |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | 判斷指定的路徑是否指向現有的目錄。 |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | 傳回指定實體的建立時間（本機時間）。 |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | 傳回指定實體的建立時間（UTC 時間）。 |
| static [String](../../system/string/) [GetCurrentDirectory](./getcurrentdirectory/)() | 傳回目前目錄的完整名稱（含路徑）。 |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | 搜尋符合指定搜尋條件的目錄，搜尋範圍可以是指定的目錄，亦或是以該目錄為根的整個目錄樹。 |
| static [String](../../system/string/) [GetDirectoryRoot](./getdirectoryroot/)(const [String](../../system/string/)\&) | 傳回指定路徑的根目錄。 |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | 搜尋符合指定搜尋條件的檔案，搜尋範圍可以是指定的目錄，亦或是以該目錄為根的整個目錄樹。 |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFileSystemEntries](./getfilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | 搜尋符合指定搜尋條件的檔案與目錄，搜尋範圍可以是指定的目錄，亦或是以該目錄為根的整個目錄樹。 |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | 傳回指定實體的最後存取時間（本機時間）。 |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | 傳回指定實體的最後存取時間（UTC 時間）。 |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | 傳回指定實體的最後寫入時間（本機時間）。 |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | 傳回指定實體的最後寫入時間（UTC 時間）。 |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetLogicalDrives](./getlogicaldrives/)() | 未實作。 |
| static [DirectoryInfoPtr](../../system/directoryinfoptr/) [GetParent](./getparent/)(const [String](../../system/string/)\&) | 傳回指向 [DirectoryInfo](../directoryinfo/) 物件的共享指標，該物件代表指定實體的父目錄。 |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 將指定實體移動到新位置。若要移動的實體是目錄，則會連同其內容一起移動。 |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | 設定指定實體的建立時間（本機時間）。 |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | 設定指定實體的建立時間（UTC 時間）。 |
| static void [SetCurrentDirectory](./setcurrentdirectory/)(const [String](../../system/string/)\&) | 設定目前目錄。 |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | 設定指定實體的最後存取時間（本機時間）。 |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | 設定指定實體的最後存取時間（UTC 時間）。 |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | 設定指定實體的最後寫入時間（本機時間）。 |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | 設定指定實體的最後寫入時間（UTC 時間）。 |

## 型別別名

| 型別別名 | 說明 |
| --- | --- |
| [StringEnumerablePtr](./stringenumerableptr/) | IEnumerable 物件的共享指標別名，用於列舉一組 [String](../../system/string/) 物件。 |

## 備註



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
  // 建立包含目錄路徑的字串。
  System::String discPath(u"C:\\");
  System::String directoryPath(u"C:\\Some directory");
  auto tempPath = System::IO::Path::GetTempPath();

  // 檢查目錄是否存在。
  PrintMessage(discPath);
  PrintMessage(directoryPath);
  PrintMessage(tempPath);

  // 列印暫存目錄資訊。
  std::cout <<
    "Creation Time: " << System::IO::Directory::GetCreationTime(tempPath) << std::endl <<
    "Last Access Time: " << System::IO::Directory::GetLastAccessTime(tempPath) << std::endl <<
    "Last Write Time: " << System::IO::Directory::GetLastWriteTime(tempPath) << std::endl;

  return 0;
}
/*
此程式碼示例產生以下輸出：
目錄 'C:\' 存在。
目錄 'C:\Some directory' 不存在。
目錄 'C:\Users\lanor\AppData\Local\Temp\' 存在。
建立時間: 27.08.2021 14:21:42
最後存取時間: 07.10.2021 12:16:41
最後寫入時間: 07.10.2021 12:16:41
*/
```

## 另請參閱

* 命名空間 [System::IO](../)
* 函式庫 [Aspose.Slides](../../)