---
title: SignData()
second_title: Aspose.Slides for C++ API 參考文件
description: 計算指定輸入值的簽章。
type: docs
weight: 183
url: /zh-hant/system.security.cryptography/dsacryptoserviceprovider/signdata/
---
## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&) method

計算指定輸入值的簽章。

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) 以讀取輸入資料。 |

### Return Value

[DSA](../../dsa/) 簽章給指定資料。

## DSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&) method

計算指定輸入值的簽章。

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 用於讀取待簽章資料的串流。 |

### Return Value

[DSA](../../dsa/) 簽章給指定資料。

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t) method

計算指定輸入值的簽章。

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) 以讀取輸入資料。 |
| offset | **int32_t** | 輸入緩衝區切片的起始索引。 |
| count | **int32_t** | 輸入緩衝區切片的大小。 |

### Return Value

[DSA](../../dsa/) 簽章給指定資料。

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) method

使用指定的雜湊演算法計算指定資料陣列的雜湊值，並對結果進行簽章。

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 輸入資料陣列。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 雜湊演算法。返回 [DSA](../../dsa/) 簽章給輸入資料。 |

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) method

使用指定的雜湊演算法計算指定資料陣列的雜湊值，並對結果進行簽章。

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 輸入資料陣列。 |
| offset | **int32_t** | 在 **data** 中的偏移。 |
| count | **int32_t** | 作為輸入資料的位元組數。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 雜湊演算法。返回 [DSA](../../dsa/) 簽章給輸入資料。 |

## DSACryptoServiceProvider::SignData(const StreamPtr\&, const HashAlgorithmName\&) method

使用指定的雜湊演算法計算指定二進位串流的雜湊值，並對結果進行簽章。

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | 二進位串流。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 雜湊演算法。返回 [DSA](../../dsa/) 簽章給輸入資料。 |

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [DSACryptoServiceProvider](../)
* Class [Stream](../../../system.io/stream/)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)