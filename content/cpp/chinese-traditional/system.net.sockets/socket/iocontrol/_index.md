---
title: IOControl()
second_title: Aspose.Slides for C++ API 參考
description: 設定套接字的低階作業模式。
type: docs
weight: 703
url: /zh-hant/system.net.sockets/socket/iocontrol/
---
## Socket::IOControl(int32_t, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) 方法

設定套接字的低階作業模式。

```cpp
int32_t System::Net::Sockets::Socket::IOControl(int32_t ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```

### Arguments

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| ioControlCode | **int32_t** | 執行操作的控制碼。 |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 包含輸入資料的位元組陣列。 |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 包含輸出資料的位元組陣列。 |

### Return Value

**optionOutValue** 參數中的位元組數。

## Socket::IOControl(IOControlCode, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) 方法

設定套接字的低階作業模式。

```cpp
int32_t System::Net::Sockets::Socket::IOControl(IOControlCode ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```

### Arguments

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| ioControlCode | [IOControlCode](../../iocontrolcode/) | 執行操作的控制碼。 |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 包含輸入資料的位元組陣列。 |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 包含輸出資料的位元組陣列。 |

### Return Value

**optionOutValue** 參數中的位元組數。

## 另見

* Enum [IOControlCode](../../iocontrolcode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [Socket](../)
* 命名空間 [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)