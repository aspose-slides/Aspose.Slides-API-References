---
title: EndRead()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された非同期読み取り操作が完了するまで待機します。
type: docs
weight: 183
url: /ja/system.io/stream/endread/
---
## Stream::EndRead(System::SharedPtr\<System::IAsyncResult\>) メソッド


指定された非同期読み取り操作が完了するまで待機します。

```cpp
virtual int System::IO::Stream::EndRead(System::SharedPtr<System::IAsyncResult> asyncResult)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[System::IAsyncResult](../../../system/iasyncresult/)\> | 非同期読み取り操作を表す [IAsyncResult](../../../system/iasyncresult/) オブジェクト |

### 戻り値

**asyncResult** によって表される読み取り操作中に読み取られたバイト数

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IAsyncResult](../../../system/iasyncresult/)
* クラス [Stream](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)