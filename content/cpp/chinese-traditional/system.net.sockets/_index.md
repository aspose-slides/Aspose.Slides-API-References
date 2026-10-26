---
title: "System::Net::Sockets"
second_title: Aspose.Slides C++ API 參考文件
description: 
type: docs
weight: 729
url: /zh-hant/system.net.sockets/
---
## 類別

| 類別 | 描述 |
| --- | --- |
| [Details_SocketException](./details_socketexception/) | 表示當發生 socket 錯誤時拋出的例外。切勿手動建立此類別的實例。請改用 SocketException 類別。切勿將 SocketException 類別的實例包裝成 [System::SmartPtr](../system/smartptr/)。 |
| [IPPacketInformation](./ippacketinformation/) | 表示封包的資訊。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式來配置。切勿在堆疊上或使用 operator new 建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [LingerOption](./lingeroption/) | 指定在呼叫 Close() 或 Close() 方法後，socket 是否仍保持連線。它亦指定在資料持續傳送時，socket 保持連線的時間。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式來配置。切勿在堆疊上或使用 operator new 建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [NetworkStream](./networkstream/) | 提供網路存取資料的底層串流。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式來配置。切勿在堆疊上或使用 operator new 建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [Socket](./socket/) | [Socket](./socket/) 類別實作 Berkeley sockets 介面。 |
| [TcpClient](./tcpclient/) | 表示 TCP 網路服務的用戶端。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式來配置。切勿在堆疊上或使用 operator new 建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [TcpListener](./tcplistener/) | 表示 TCP 網路服務的監聽器。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式來配置。切勿在堆疊上或使用 operator new 建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [UdpClient](./udpclient/) | 提供使用者資料報協定 (UDP) 網路服務。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式來配置。切勿在堆疊上或使用 operator new 建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |

## 函式

| 函式 | 描述 |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)([IPPacketInformation](./ippacketinformation/), [IPPacketInformation](./ippacketinformation/)) |  |
| **bool** [operator!=](./operator_not_equal/)([IPPacketInformation](./ippacketinformation/), [IPPacketInformation](./ippacketinformation/)) |  |

## 列舉型別

| 列舉 | 描述 |
| --- | --- |
| [SocketType](./sockettype/) | 列舉 socket 類型。 |
| [AddressFamily](./addressfamily/) | 列舉位址族群。 |
| [IOControlCode](./iocontrolcode/) | 列舉 [IO](../system.io/) 控制碼。 |
| [ProtocolFamily](./protocolfamily/) | 列舉協議族群。 |
| [ProtocolType](./protocoltype/) | 列舉協議類型。 |
| [SelectMode](./selectmode/) | 指定用於輪詢 socket 狀態的模式。 |
| [SocketError](./socketerror/) | 列舉 socket 錯誤類型。 |
| [SocketFlags](./socketflags/) | 提供 socket 訊息的常數值。 |
| [SocketOptionLevel](./socketoptionlevel/) | 定義 '[Socket](./socket/)' 類別的 socket 選項等級。 |
| [SocketOptionName](./socketoptionname/) | 定義 [Socket](./socket/) 類別的 socket 選項名稱。 |
| [SocketShutdown](./socketshutdown/) | 定義 [Socket.Shutdown](./socket/shutdown/) 方法使用的常數。 |

## 型別別名

| 型別別名 | 描述 |
| --- | --- |
| [SocketException](./socketexception/) |  |