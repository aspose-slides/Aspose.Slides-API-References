---
title: GetBytes()
second_title: Aspose.Slides for C++ API 參考
description: 將現有陣列元素填入隨機位元組。
type: docs
weight: 14
url: /zh-hant/system.security.cryptography/randomnumbergenerator/getbytes/
---
## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>) 方法

將現有陣列元素填入隨機位元組。

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要填入的位元組陣列。 |

## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>, int, int) 方法

將現有陣列切片填入隨機位元組。

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes, int offset, int count)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要填入切片的位元組陣列。 |
| offset | int | 切片的起始索引。 |
| count | int | 切片大小。 |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>) 方法

將現有陣列視圖元素填入隨機位元組。

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | 要填入的位元組陣列視圖。 |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>, int, int) 方法

將現有陣列視圖切片填入隨機位元組。

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes, int offset, int count)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | 要填入切片的位元組陣列視圖。 |
| offset | int | 切片的起始索引。 |
| count | int | 切片大小。 |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&) 方法

將現有堆疊陣列元素填入隨機位元組。

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | 要填入的位元組堆疊陣列。 |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&, int, int) 方法

將現有堆疊陣列切片填入隨機位元組。

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes, int offset, int count)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | 要填入切片的位元組堆疊陣列。 |
| offset | int | 切片的起始索引。 |
| count | int | 切片大小。 |

## 另見

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [RandomNumberGenerator](../)
* 命名空間 [System::Security::Cryptography](../../)
* 函式庫 [Aspose.Slides](../../../)