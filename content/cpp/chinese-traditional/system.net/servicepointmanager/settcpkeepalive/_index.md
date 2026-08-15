---
title: SetTcpKeepAlive()
second_title: Aspose.Slides for C++ API 參考
description: 設定指示是否啟用 'Keep-Alive' 選項的值。
type: docs
weight: 326
url: /zh-hant/system.net/servicepointmanager/settcpkeepalive/
---
## ServicePointManager::SetTcpKeepAlive(bool, int32_t, int32_t) 方法

設定指示是否啟用 'Keep-Alive' 選項的值。

```cpp
static void System::Net::ServicePointManager::SetTcpKeepAlive(bool enabled, int32_t keepAliveTime, int32_t keepAliveInterval)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| enabled | **bool** | 指示是否啟用 'Keep-Alive' 選項的值。 |
| keepAliveTime | **int32_t** | 以毫秒為單位的逾時時間，在此之後會傳送第一個 'Keep-Alive' 封包。 |
| keepAliveInterval | **int32_t** | 以毫秒為單位的逾時時間，介於傳送 'Keep-Alive' 封包之間。 |

## 另請參閱

* 類別 [ServicePointManager](../)
* 名稱空間 [System::Net](../../)
* 函式庫 [Aspose.Slides](../../../)