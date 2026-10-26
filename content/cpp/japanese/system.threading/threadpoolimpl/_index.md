---
title: ThreadPoolImpl
second_title: Aspose.Slides for C++ API リファレンス
description: スレッドプールの内部データです。これはアクセス関数によりメモリ管理が行われるシングルトンタイプです。直接インスタンスを作成してはいけません。
type: docs
weight: 235
url: /ja/system.threading/threadpoolimpl/
---
## ThreadPoolImpl クラス


[Thread](../thread/) プール内部データ。これはアクセス関数でメモリ管理が行われるシングルトン型です。直接インスタンスを作成してはいけません。

```cpp
class ThreadPoolImpl
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| void [GetAvailableThreads](./getavailablethreads/)(int\&, int\&) | 利用可能なスレッド数を取得します。 |
| static **bool**\& [GetInitialized](./getinitialized/)() | 初期化状態のシングルトンを取得します。 |
| void [GetMaxThreads](./getmaxthreads/)(int\&, int\&) | 同時スレッドの最大数を取得します。 |
| void [GetMinThreads](./getminthreads/)(int\&, int\&) | プールによって作成されるスレッドの最小数を取得します。 |
| void [JoinAll](./joinall/)() | すべての所有スレッドに参加します。無期限に待機します。 |
| **bool** [QueueUserWorkItem](./queueuserworkitem/)([WaitCallback](../waitcallback/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | キューに作業項目を追加します。 |
| **bool** [SetMaxThreads](./setmaxthreads/)(int, int) | プールが所有するスレッド数を設定します。 |
| **bool** [SetMinThreads](./setminthreads/)(int, int) | プールが所有するスレッドの最小数を設定します。 |
|  [ThreadPoolImpl](./threadpoolimpl/)() | コンストラクタ。 |
|  [~ThreadPoolImpl](./~threadpoolimpl/)() | デストラクタ。まだ終了していない場合はすべてのスレッドに参加します。 |
## 参照

* 名前空間 [System::Threading](../)
* ライブラリ [Aspose.Slides](../../)