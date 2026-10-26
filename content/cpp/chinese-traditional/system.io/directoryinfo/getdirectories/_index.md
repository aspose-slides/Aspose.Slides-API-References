---
title: GetDirectories()
second_title: Aspose.Slides for C++ API 參考
description: 傳回一個陣列，包含指向代表目前物件所表示目錄中所有目錄之 DirectoryInfo 物件的共享指標。
type: docs
weight: 144
url: /zh-hant/system.io/directoryinfo/getdirectories/
---
## DirectoryInfo::GetDirectories() 方法

傳回一個陣列，包含指向代表目前物件所表示目錄中所有目錄之 [DirectoryInfo](../) 物件的共享指標。

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories()
```

## DirectoryInfo::GetDirectories(const String\&) 方法

在目前物件所表示的目錄中搜尋符合指定搜尋條件的目錄。

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 要搜尋之目錄的名稱模式 |

### 傳回值

傳回一個陣列，包含指向其名稱符合 **searchPattern** 的已找到目錄之 [DirectoryInfo](../) 物件的共享指標。

## DirectoryInfo::GetDirectories(const String\&, SearchOption) 方法

在目前物件所表示的目錄或以該目錄為根的整個目錄樹中，搜尋符合指定搜尋條件的目錄。

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern, SearchOption searchOption)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 要搜尋之目錄的名稱模式 |
| searchOption | [SearchOption](../../searchoption/) | 指定是僅在目前物件所表示的目錄內搜尋，或在以該目錄為根的整個目錄樹中搜尋 |

### 傳回值

傳回一個陣列，包含指向其名稱符合 **searchPattern** 的已找到目錄之 [DirectoryInfo](../) 物件的共享指標。

## 另請參閱

* 列舉 [SearchOption](../../searchoption/)
* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 型別別名 [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* 類別 [DirectoryInfo](../)
* 類別 [String](../../../system/string/)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)