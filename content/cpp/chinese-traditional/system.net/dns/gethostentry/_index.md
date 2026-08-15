---
title: GetHostEntry()
second_title: Aspose.Slides 的 C++ API 參考
description: 使用包含主機名稱或 IP 位址的指定字串建立新的 IPHostEntry-class 實例。
type: docs
weight: 79
url: /zh-hant/system.net/dns/gethostentry/
---
## Dns::GetHostEntry(String) 方法

使用指定的包含主機名稱或 IP 位址的字串建立新的 IPHostEntry-class 實例。

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(String hostNameOrAddress)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | 包含主機名稱或 IP 位址的字串。 |

### 返回值

新的 IPHostEntry-class 實例。

## Dns::GetHostEntry(System::SharedPtr\<IPAddress\>) 方法

使用指定的 IP 位址建立新的 IPHostEntry-class 實例。

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(System::SharedPtr<IPAddress> address)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | IP 位址。 |

### 返回值

新的 IPHostEntry-class 實例。

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IPHostEntry](../../iphostentry/)
* 類別 [String](../../../system/string/)
* 類別 [Dns](../)
* 類別 [IPAddress](../../ipaddress/)
* 命名空間 [System::Net](../../)
* 函式庫 [Aspose.Slides](../../../)