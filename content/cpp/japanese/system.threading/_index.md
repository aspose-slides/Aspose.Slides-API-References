---
title: "System::Threading"
second_title: Aspose.Slides for C++ APIリファレンス
description: 
type: docs
weight: 1002
url: /ja/system.threading/
---
## クラス

| クラス | 説明 |
| --- | --- |
| [AutoResetEvent](./autoresetevent/) | 待機スレッドに自動リセットで通知するイベント。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new でインスタンスを作成しないでください。実行時エラーやアサーション違反の原因になります。このクラスは必ず [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを引数として関数に渡してください。 |
| [CancellationToken](./cancellationtoken/) | 操作をキャンセルすべきことを通知する機能を伝播します。このクラスはスレッド間で協調的にキャンセルを行うための仕組みを提供し、あるスレッドが他のスレッドに対してキャンセルを通知できます。 |
| [CancellationTokenRegistration](./cancellationtokenregistration/) | キャンセルトークンコールバックの登録を表します。 |
| [CancellationTokenSource](./cancellationtokensource/) | キャンセル通知をトリガーできるキャンセルトークンソースです。 |
| [Details_SemaphoreFullException](./details_semaphorefullexception/) |  |
| [Details_SynchronizationLockException](./details_synchronizationlockexception/) |  |
| [Details_ThreadAbortException](./details_threadabortexception/) |  |
| [Details_ThreadInterruptedException](./details_threadinterruptedexception/) |  |
| [Details_ThreadStateException](./details_threadstateexception/) |  |
| [EventWaitHandle](./eventwaithandle/) | 待機スレッドに送信できるイベント。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new でインスタンスを作成しないでください。実行時エラーやアサーション違反の原因になります。このクラスは必ず [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを引数として関数に渡してください。 |
| [Interlocked](./interlocked/) | スレッドセーフな操作の API を提供します。インスタンスを持たない静的型で、インスタンスを作成してはいけません。 |
| [ManualResetEvent](./manualresetevent/) | 自動リセットしない待機スレッドに通知するイベント。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new でインスタンスを作成しないでください。実行時エラーやアサーション違反の原因になります。このクラスは必ず [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを引数として関数に渡してください。 |
| [Monitor](./monitor/) | クラス [Monitor](./monitor/) はオブジェクトへのアクセスを同期するメカニズムを提供します。 |
| [Mutex](./mutex/) | [Mutex](./mutex/) 実装です。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new でインスタンスを作成しないでください。実行時エラーやアサーション違反の原因になります。このクラスは必ず [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを引数として関数に渡してください。 |
| [Semaphore](./semaphore/) | [Semaphore](./semaphore/) 実装です。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new でインスタンスを作成しないでください。実行時エラーやアサーション違反の原因になります。このクラスは必ず [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを引数として関数に渡してください。 |
| [SynchronizationContext](./synchronizationcontext/) | 同期コンテキストをさまざまな同期操作に跨って伝搬する基本機能を提供します。 |
| [Thread](./thread/) | [Thread](./thread/) 実装です。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new でインスタンスを作成しないでください。実行時エラーやアサーション違反の原因になります。このクラスは必ず [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを引数として関数に渡してください。 |
| [ThreadPool](./threadpool/) | [Thread](./thread/) プール API で、ジョブをキューにプッシュし、ワーカースレッドプールがそれらを取得できるようにします。インスタンスを持たない静的型で、インスタンスを作成してはいけません。 |
| [ThreadPoolImpl](./threadpoolimpl/) | [Thread](./thread/) プール内部データです。アクセス関数によりメモリ管理が行われるシングルトン型です。直接インスタンスを作成しないでください。 |
| [Timer](./timer/) | [Timer](./timer/) クラスは、遅延後に別スレッドでジョブアイテムを実行します。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new でインスタンスを作成しないでください。実行時エラーやアサーション違反の原因になります。このクラスは必ず [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを引数として関数に渡してください。 |
| [TimerQueue](./timerqueue/) | [Timer](./timer/) オブジェクトを扱うキューです。これは単なる実装です。[Timer](./timer/) オブジェクトは自動的に登録されるため、使用するために手動で登録する必要はありません。代わりに [Timer](./timer/) クラス API を使用してください。このキューはアクセス関数によりメモリ管理が行われるシングルトン型で、直接インスタンスを作成しないでください。 |
| [WaitHandle](./waithandle/) | 待機プリミティブの基底クラス。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new でインスタンスを作成しないでください。実行時エラーやアサーション違反の原因になります。このクラスは必ず [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを引数として関数に渡してください。 |
## 構造体

| 構造体 | 説明 |
| --- | --- |
| [Timeout](./timeout/) | [Threading](./) タイムアウト特別値です。インスタンスを持たない静的型で、インスタンスを作成してはいけません。 |
## 列挙型

| 列挙型 | 説明 |
| --- | --- |
| [ApartmentState](./apartmentstate/) | スレッドのアパートメント状態を設定します。 |
| [EventResetMode](./eventresetmode/) | イベント状態のリセット方法を示します。 |
| [ThreadState](./threadstate/) | スレッドの状態です。 |
## 型定義

| 型定義 | 説明 |
| --- | --- |
| [ThreadStateException](./threadstateexception/) |  |
| [SemaphoreFullException](./semaphorefullexception/) |  |
| [SynchronizationLockException](./synchronizationlockexception/) |  |
| [ThreadAbortException](./threadabortexception/) |  |
| [ThreadInterruptedException](./threadinterruptedexception/) |  |
| [SendOrPostCallback](./sendorpostcallback/) |  |
| [ParameterizedThreadStart](./parameterizedthreadstart/) | [Thread](./thread/) 関数（単一パラメータ）。 |
| [ThreadStart](./threadstart/) | [Thread](./thread/) 関数（パラメータなし）。 |
| [WaitCallback](./waitcallback/) | スポットが空いたときに実行されるコールバック項目。 |
| [TimerCallback](./timercallback/) | タイマーによって呼び出されるコールバック関数。 |
| [wait_handle_t](./wait_handle_t/) | ハンドル型。 |