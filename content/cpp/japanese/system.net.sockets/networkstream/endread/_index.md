---
title: EndRead()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された非同期読み取り操作が完了するまで待機します。
type: docs
weight: 261
url: /ja/system.net.sockets/networkstream/endread/
---
## NetworkStream::EndRead(System::SharedPtr\<IAsyncResult\>) メソッド


指定された非同期読み取り操作が完了するまで待機します。

```cpp
int32_t System::Net::Sockets::NetworkStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | 非同期読み取り操作を表す [IAsyncResult](../../../system/iasyncresult/) オブジェクト |

### 戻り値

**asyncResult** によって表される読み取り操作中に読み取られたバイト数

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IAsyncResult](../../../system/iasyncresult/)
* クラス [NetworkStream](../)
* 名前空間 [System::Net::Sockets](../../)
* ライブラリ [Aspose.Slides](../../../)