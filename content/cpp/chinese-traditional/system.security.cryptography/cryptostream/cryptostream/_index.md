---
title: CryptoStream()
second_title: Aspose.Slides for C++ API 參考文件
description: 建構式。
type: docs
weight: 1
url: /zh-hant/system.security.cryptography/cryptostream/cryptostream/
---
## CryptoStream::CryptoStream(const SharedPtr\<System::IO::Stream\>\&, const SharedPtr\<ICryptoTransform\>\&, CryptoStreamMode) 建構式

建構式。

```cpp
System::Security::Cryptography::CryptoStream::CryptoStream(const SharedPtr<System::IO::Stream> &stream, const SharedPtr<ICryptoTransform> &transform, CryptoStreamMode mode)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | 要封裝的串流。 |
| transform | const [SharedPtr](../../../system/sharedptr/)\<[ICryptoTransform](../../icryptotransform/)\>\& | 在傳送/讀取資料至/自串流時，用於處理資料的轉換函式。 |
| mode | [CryptoStreamMode](../../cryptostreammode/) | 串流方向。 |

## 另請參閱

* 列舉 [CryptoStreamMode](../../cryptostreammode/)
* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [Stream](../../../system.io/stream/)
* 類別 [ICryptoTransform](../../icryptotransform/)
* 類別 [CryptoStream](../)
* 命名空間 [System::Security::Cryptography](../../)
* 函式庫 [Aspose.Slides](../../../)