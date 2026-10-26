---
title: OperatingSystem()
second_title: Aspose.Slides for C++ API 參考
description: 建立一個表示特定平台 ID 與版本的作業系統實例。
type: docs
weight: 1
url: /zh-hant/system/operatingsystem/operatingsystem/
---
## OperatingSystem::OperatingSystem(PlatformID, const Version\&) 建構函式

建立一個表示特定平台 ID 與版本的作業系統實例。

```cpp
System::OperatingSystem::OperatingSystem(PlatformID platform, const Version &version)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| platform | [PlatformID](../../platformid/) | 要由所建構的物件表示之作業系統的平台識別碼 |
| version | const [Version](../../version/)\& | 要由所建構的物件表示之作業系統的版本 |

## OperatingSystem::OperatingSystem(PlatformID, const Version\&, const String\&) 建構函式

建立一個表示特定平台 ID、版本與服務包的作業系統實例。

```cpp
System::OperatingSystem::OperatingSystem(PlatformID platform, const Version &version, const String &service_pack)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| platform | [PlatformID](../../platformid/) | 要由所建構的物件表示之作業系統的平台識別碼 |
| version | const [Version](../../version/)\& | 要由所建構的物件表示之作業系統的版本 |
| service_pack | const [String](../../string/)\& | 要由所建構的物件表示之作業系統的服務包名稱 |

## 另請參閱

* Enum [PlatformID](../../platformid/)
* 類別 [Version](../../version/)
* 類別 [OperatingSystem](../)
* 類別 [String](../../string/)
* 名稱空間 [System](../../)
* Library [Aspose.Slides](../../../)