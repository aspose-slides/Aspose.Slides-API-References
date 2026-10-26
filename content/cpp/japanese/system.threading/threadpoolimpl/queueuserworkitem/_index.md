---
title: QueueUserWorkItem()
second_title: Aspose.Slides for C++ API リファレンス
description: 作業項目をキューに追加します。
type: docs
weight: 1
url: /ja/system.threading/threadpoolimpl/queueuserworkitem/
---
## ThreadPoolImpl::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) メソッド

キューに作業項目を追加します。

```cpp
bool System::Threading::ThreadPoolImpl::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | 実行するコールバック関数。 |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | コールバック関数の引数。 |

### 戻り値

常に true を返します。

## 参照

* 型定義 [WaitCallback](../../waitcallback/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [ThreadPoolImpl](../)
* 名前空間 [System::Threading](../../)
* ライブラリ [Aspose.Slides](../../../)