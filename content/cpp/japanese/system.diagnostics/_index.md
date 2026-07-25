---
title: "System::Diagnostics"
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 469
url: /ja/system.diagnostics/
---
## クラス

| クラス | 説明 |
| --- | --- |
| [FileVersionInfo](./fileversioninfo/) | ファイル バージョンに関する情報を提供します。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。この型のインスタンスをスタック上で作成したり operator new を使用したりしないでください。そうしないと実行時エラーやアサーション違反が発生します。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数の引数として渡してください。 |
| [PerformanceCounter](./performancecounter/) | PerformanceCounter を使用した翻訳コードのコンパイル用のダミークラスです。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。この型のインスタンスをスタック上で作成したり operator new を使用したりしないでください。そうしないと実行時エラーやアサーション違反が発生します。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数の引数として渡してください。 |
| [Process](./process/) | プロセス情報の取得と操作をカプセル化します。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。この型のインスタンスをスタック上で作成したり operator new を使用したりしないでください。そうしないと実行時エラーやアサーション違反が発生します。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数の引数として渡してください。 |
| [ProcessStartInfo](./processstartinfo/) | プロセス開始パラメータを記述します。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。この型のインスタンスをスタック上で作成したり operator new を使用したりしないでください。そうしないと実行時エラーやアサーション違反が発生します。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数の引数として渡してください。 |
| [StackFrame](./stackframe/) | 単一のスタックフレームに関する情報を取得します。MSVS のみ。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。この型のインスタンスをスタック上で作成したり operator new を使用したりしないでください。そうしないと実行時エラーやアサーション違反が発生します。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数の引数として渡してください。 |
| [StackTrace](./stacktrace/) | スタックフレームのコレクションです。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。この型のインスタンスをスタック上で作成したり operator new を使用したりしないでください。そうしないと実行時エラーやアサーション違反が発生します。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数の引数として渡してください。 |
| [Stopwatch](./stopwatch/) | 時間測定を可能にします。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。この型のインスタンスをスタック上で作成したり operator new を使用したりしないでください。そうしないと実行時エラーやアサーション違反が発生します。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数の引数として渡してください。 |
| [TraceListener](./tracelistener/) | デバッグとトレース情報に応答するインターフェースです。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。この型のインスタンスをスタック上で作成したり operator new を使用したりしないでください。そうしないと実行時エラーやアサーション違反が発生します。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数の引数として渡してください。 |
## 構造体

| 構造体 | 説明 |
| --- | --- |
| [Debug](./debug/) | デバッグ情報を登録リスナーに送信できるデバッグメソッドのコレクションです。すべての出力関数は [Debug](./debug/) のみで動作します。これはインスタンスサービスを持たない静的型です。いかなる手段でもインスタンスを作成しないでください。 |
| [Debugger](./debugger/) | [Debugger](./debugger/) インターフェースです。これはインスタンスサービスを持たない静的型です。いかなる手段でもインスタンスを作成しないでください。 |
| [Trace](./trace/) | デバッガートレースにアクセスするインターフェースを提供します（存在する場合）。[Debug](./debug/) モードのみで動作します。これはインスタンスサービスを持たない静的型です。いかなる手段でもインスタンスを作成しないでください。 |
## 列挙体

| 列挙体 | 説明 |
| --- | --- |
| [ProcessWindowStyle](./processwindowstyle/) | プロセスウィンドウのスタイルを表します。 |
| [TraceEventType](./traceeventtype/) | トレースを引き起こしたイベントの種類を識別します。 |
| [TraceLevel](./tracelevel/) | [System.Diagnostics.Debug](./debug/)、[System.Diagnostics.Trace](./trace/) および System.Diagnostics.TraceSwitch クラスに対して出力するメッセージを指定します。 |
## 型エイリアス

| 型エイリアス | 説明 |
| --- | --- |
| [StopwatchPtr](./stopwatchptr/) | ポインタ型です。 |