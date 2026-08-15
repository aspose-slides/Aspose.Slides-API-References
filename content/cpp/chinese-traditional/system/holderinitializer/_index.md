---
title: HolderInitializer
second_title: Aspose.Slides for C++ API 參考
description: 此類別用於取得對物件實例的永久參考，無論它是左值或右值。若要取得此類參考，請使用 'HoldIfTemporary' 方法，該方法有三個重載。其中兩個接受右值作為參數，僅回傳對其的參考。第三個則相反，接受左值作為參數，建立指標複製，然後回傳對該複製品的參考。此外，類別還有 'Hold' 方法，可無條件持有傳入的值（用於複製本地堆疊變數或其子參考的值）。
type: docs
weight: 1639
url: /zh-hant/system/holderinitializer/
---
## HolderInitializer struct

此類別用於取得對物件實例的永久參考，無論它是左值或右值。若要取得此類參考，請使用 'HoldIfTemporary' 方法，該方法有三個重載。其中兩個接受右值作為參數，僅回傳對其的參考。第三個則相反，接受左值作為參數，建立指標複製，然後回傳對該複製品的參考。此外，類別還有 'Hold' 方法，可無條件持有傳入的值（用於複製本地堆疊變數或其子參考的值）。
```cpp
template<typename T,bool>class HolderInitializer
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | 要保持的物件類型。 |
| R | 如果 T 為參考型別（[SmartPtr](../smartptr/) 特化或 [System::String](../string/) 型別），且實際需要保持暫時性參考，則為 true；否則為 false。 |

## 方法

| 方法 | 說明 |
| --- | --- |
| const T\& [Hold](./hold/)(const T\&) | 將傳入的左值複製到 holder，然後回傳 holder 的參考。呼叫端應使用此方法無條件持有傳入的值。 |
| [HolderInitializer](./holderinitializer/)(T\&) | 使用傳入的參考初始化 holder 參考。 |
| const T\& [HoldIfTemporary](./holdiftemporary/)(const T\&) | 回傳對右值的參考（const） |
| const T\& [HoldIfTemporary](./holdiftemporary/)(T\&) | 回傳對右值的參考（非 const） |
| const T\& [HoldIfTemporary](./holdiftemporary/)(T\&&) | 將傳入的左值複製到 holder，然後回傳 holder 的參考。 |

## 另見

* 命名空間 [System](../)
* 程式庫 [Aspose.Slides](../../)