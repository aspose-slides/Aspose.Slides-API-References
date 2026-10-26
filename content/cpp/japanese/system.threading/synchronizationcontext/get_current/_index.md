---
title: get_Current()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のスレッドの同期コンテキストを取得します。
type: docs
weight: 40
url: /ja/system.threading/synchronizationcontext/get_current/
---
## SynchronizationContext::get_Current() メソッド


現在のスレッドの同期コンテキストを取得します。

```cpp
static const SharedPtr<SynchronizationContext> & System::Threading::SynchronizationContext::get_Current()
```


### 戻り値

SharedPtr<SynchronizationContext> 現在のスレッドの同期コンテキストへの共有ポインタです。
## 備考



現在のスレッドに同期コンテキストが設定されていない場合、null を返します。 

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [SynchronizationContext](../)
* 名前空間 [System::Threading](../../)
* ライブラリ [Aspose.Slides](../../../)