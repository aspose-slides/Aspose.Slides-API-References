---
title: Yield()
second_title: Aspose.Slides for C++ API リファレンス
description: await されたときに、現在のコンテキストに非同期で制御を戻す await 可能なタスクを作成します。
type: docs
weight: 222
url: /ja/system.threading.tasks/yield/
---
## System::Threading::Tasks::Yield() 関数

await されたときに、現在のコンテキストに非同期で制御を戻す await 可能なタスクを作成します。

```cpp
Runtime::CompilerServices::YieldAwaitable System::Threading::Tasks::Yield()
```

### 戻り値

制御を譲渡するために await できる YieldAwaitable。

## 備考

このメソッドは、非同期メソッドに制御の譲渡を強制し、続行する前に他の保留中の作業が処理されるようにするのに役立ちます。

## 参照

* クラス [YieldAwaitable](../../system.runtime.compilerservices/yieldawaitable/)
* 名前空間 [System::Threading::Tasks](../)
* ライブラリ [Aspose.Slides](../../)