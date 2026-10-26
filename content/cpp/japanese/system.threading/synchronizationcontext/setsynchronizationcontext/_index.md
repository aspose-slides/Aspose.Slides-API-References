---
title: SetSynchronizationContext()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のスレッドの同期コンテキストを設定します。
type: docs
weight: 53
url: /ja/system.threading/synchronizationcontext/setsynchronizationcontext/
---
## SynchronizationContext::SetSynchronizationContext(const SharedPtr\<SynchronizationContext\>\&) メソッド

現在のスレッドの同期コンテキストを設定します。

```cpp
static void System::Threading::SynchronizationContext::SetSynchronizationContext(const SharedPtr<SynchronizationContext> &syncContext)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| syncContext | const [SharedPtr](../../../system/sharedptr/)\<[SynchronizationContext](../)\>\& | 現在のスレッドに設定する同期コンテキストです。 |
## 備考

nullptr を渡すと、現在のスレッドの同期コンテキストがクリアされます。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [SynchronizationContext](../)
* 名前空間 [System::Threading](../../)
* ライブラリ [Aspose.Slides](../../../)