---
title: GetHostByAddress()
second_title: Aspose.Slides for C++ API 參考文件
description: 使用指定的 IP 位址字串表示形式建立新的 IPHostEntry-class 實例。
type: docs
weight: 14
url: /zh-hant/system.net/dns/gethostbyaddress/
---
## Dns::GetHostByAddress(String) 方法

建立一個新的 IPHostEntry-class 實例，使用指定的 IP 位址的字串表示形式。

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(String address)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| address | [String](../../../system/string/) | IP 位址的字串表示形式。 |

### 傳回值

新建立的 IPHostEntry-class 實例。

## Dns::GetHostByAddress(System::SharedPtr\<IPAddress\>) 方法

建立一個新的 IPHostEntry-class 實例，使用指定的 IP 位址。

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(System::SharedPtr<IPAddress> address)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | IP 位址。 |

### 傳回值

新建立的 IPHostEntry-class 實例。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IPHostEntry](../../iphostentry/)
* 類別 [String](../../../system/string/)
* 類別 [Dns](../)
* 類別 [IPAddress](../../ipaddress/)
* 命名空間 [System::Net](../../)
* Library [Aspose.Slides](../../../)