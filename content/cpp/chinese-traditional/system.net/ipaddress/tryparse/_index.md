---
title: TryParse()
second_title: Aspose.Slides for C++ API 參考
description: 嘗試將傳入的字串轉換為 IPAddress 類別的實例。
type: docs
weight: 222
url: /zh-hant/system.net/ipaddress/tryparse/
---
## IPAddress::TryParse(String, System::SharedPtr\<IPAddress\>\&) method

嘗試將傳入的字串轉換為 [IPAddress](../) 類別的實例。

```cpp
static bool System::Net::IPAddress::TryParse(String ipString, System::SharedPtr<IPAddress> &address)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| ipString | [String](../../../system/string/) | 要解析的字串。 |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../)\>\& | 解析後的物件將指派給的實例。 |

### 返回值

當解析成功完成時傳回 True，否則傳回 false。

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [IPAddress](../)
* 命名空間 [System::Net](../../)
* 函式庫 [Aspose.Slides](../../../)