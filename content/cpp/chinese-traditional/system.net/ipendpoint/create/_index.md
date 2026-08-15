---
title: Create()
second_title: Aspose.Slides for C++ API 參考
description: 使用指定的 socket 位址建立 EndPoint 類別的新執行個體。
type: docs
weight: 92
url: /zh-hant/system.net/ipendpoint/create/
---
## IPEndPoint::Create(System::SharedPtr\<SocketAddress\>) 方法

使用指定的 socket address 建立 [EndPoint](../../endpoint/) 類別的新執行個體。

```cpp
System::SharedPtr<EndPoint> System::Net::IPEndPoint::Create(System::SharedPtr<SocketAddress> socketAddress) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| socketAddress | [System::SharedPtr](../../../system/sharedptr/)\<[SocketAddress](../../socketaddress/)\> | 將用於初始化新執行個體的 socket address。 |

### 返回值

新建立的 EndPoint-class 執行個體。

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [EndPoint](../../endpoint/)
* 類別 [SocketAddress](../../socketaddress/)
* 類別 [IPEndPoint](../)
* 命名空間 [System::Net](../../)
* 函式庫 [Aspose.Slides](../../../)