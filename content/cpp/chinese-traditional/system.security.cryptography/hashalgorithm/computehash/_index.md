---
title: ComputeHash()
second_title: Aspose.Slides for C++ API 參考
description: 對緩衝區進行雜湊。
type: docs
weight: 14
url: /zh-hant/system.security.cryptography/hashalgorithm/computehash/
---
## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&) 方法


對緩衝區進行雜湊。

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 原始緩衝區。 |

### 返回值

計算出的雜湊值。

## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&, int, int) 方法


對緩衝區切片進行雜湊。

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer, int offset, int count)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 原始緩衝區。 |
| offset | int | 原始緩衝區的偏移量。 |
| count | int | 從原始緩衝區使用的位元組數。 |

### 返回值

計算出的雜湊值。

## HashAlgorithm::ComputeHash(SharedPtr\<IO::Stream\> const\&) 方法


讀取流直至結束，並計算讀取資料的雜湊。

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(SharedPtr<IO::Stream> const &inputStream)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| inputStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> const\& | 用於讀取資料的流。 |

### 返回值

整個流資料的計算雜湊值。

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [HashAlgorithm](../)
* 類別 [Stream](../../../system.io/stream/)
* 命名空間 [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)