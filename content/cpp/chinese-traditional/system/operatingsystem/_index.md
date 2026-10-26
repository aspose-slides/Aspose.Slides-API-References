---
title: OperatingSystem
second_title: Aspose.Slides C++ API 參考文件
description: "代表特定的作業系統並提供相關資訊。此類別的物件應僅使用 System::MakeObject() 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。應始終將此類別包裝成 System::SmartPtr 指標，並使用該指標將其作為參數傳遞給函式。"
type: docs
weight: 1171
url: /zh-hant/system/operatingsystem/
---
## OperatingSystem 類別


代表特定的作業系統並提供相關資訊。此類別的物件應僅使用 [System::MakeObject()](../makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。應始終將此類別包裝成 [System::SmartPtr](../smartptr/) 指標，並使用該指標將其作為參數傳遞給函式。

```cpp
class OperatingSystem
```

## 方法

| 方法 | 說明 |
| --- | --- |
| [PlatformID](../platformid/) [get_Platform](./get_platform/)() const | 傳回目前物件所代表之作業系統的平臺識別碼。 |
| [String](../string/) [get_ServicePack](./get_servicepack/)() const | 傳回目前物件所代表之作業系統的 Service Pack 名稱。 |
| const [Version](../version/)\& [get_Version](./get_version/)() const | 傳回指向 [Version](../version/) 物件的常量參照，該物件表示目前物件所代表之作業系統的版本。 |
| [String](../string/) [get_VersionString](./get_versionstring/)() const | 傳回目前物件所代表之作業系統版本的字串表示。 |
| static **bool** [IsFreeBSD](./isfreebsd/)() | 指示目前應用程式是否在 FreeBSD 上執行。 |
| static **bool** [IsLinux](./islinux/)() | 指示目前應用程式是否在 Linux 上執行。 |
| static **bool** [IsMacOS](./ismacos/)() | 指示目前應用程式是否在 MacOS 上執行。 |
| static **bool** [IsOSPlatform](./isosplatform/)(const [String](../string/)\&) | 指示目前應用程式是否在指定的平臺上執行。 |
| static **bool** [IsWindows](./iswindows/)() | 指示目前應用程式是否在 [Windows](../../system.windows/) 上執行。 |
|  [OperatingSystem](./operatingsystem/)([PlatformID](../platformid/), const [Version](../version/)\&) | 建立一個實例，該實例表示以特定平臺 ID 和版本指定的作業系統。 |
|  [OperatingSystem](./operatingsystem/)([PlatformID](../platformid/), const [Version](../version/)\&, const [String](../string/)\&) | 建立一個實例，該實例表示以特定平臺 ID、版本與 Service Pack 指定的作業系統。 |
| [String](../string/) [ToString](./tostring/)() const | 傳回目前物件所代表之作業系統版本的字串表示。 |

## 參見

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)