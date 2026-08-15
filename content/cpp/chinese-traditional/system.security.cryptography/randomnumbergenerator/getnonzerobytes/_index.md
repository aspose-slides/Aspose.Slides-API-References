---
title: GetNonZeroBytes()
second_title: Aspose.Slides for C++ API 參考文件
description: 將現有陣列元素填入隨機的非零位元組。
type: docs
weight: 27
url: /zh-hant/system.security.cryptography/randomnumbergenerator/getnonzerobytes/
---
## RandomNumberGenerator::GetNonZeroBytes(ArrayPtr\<uint8_t\>) 方法

填充現有的陣列元素為隨機非零位元組。

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetNonZeroBytes(ArrayPtr<uint8_t> bytes)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要填充的位元組陣列。 |

## RandomNumberGenerator::GetNonZeroBytes(System::Details::ArrayView\<uint8_t\>) 方法

填充現有的陣列視圖元素為隨機非零位元組。

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetNonZeroBytes(System::Details::ArrayView<uint8_t> bytes)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | 要填充的位元組陣列視圖。 |

## RandomNumberGenerator::GetNonZeroBytes(System::Details::StackArray\<uint8_t, N\>\&) 方法

填充現有的堆疊陣列元素為隨機非零位元組。

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetNonZeroBytes(System::Details::StackArray<uint8_t, N> &bytes)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | 要填充的位元組堆疊陣列。 |

## 另見

* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [RandomNumberGenerator](../)
* 命名空間 [System::Security::Cryptography](../../)
* 函式庫 [Aspose.Slides](../../../)