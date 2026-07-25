---
title: Post()
second_title: Aspose.Slides for C++ API リファレンス
description: コールバックを非同期で実行します。
type: docs
weight: 14
url: /ja/system.threading/synchronizationcontext/post/
---
## SynchronizationContext::Post(SendOrPostCallback, SharedPtr\<Object\>) メソッド


コールバックを非同期で実行します。

```cpp
virtual void System::Threading::SynchronizationContext::Post(SendOrPostCallback d, SharedPtr<Object> state)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| d | [SendOrPostCallback](../../sendorpostcallback/) | 実行するコールバック。 |
| state | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/) をコールバック引数として渡す。 |

## 関連項目

* 型定義 [SendOrPostCallback](../../sendorpostcallback/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [SynchronizationContext](../)
* 名前空間 [System::Threading](../../)
* ライブラリ [Aspose.Slides](../../../)