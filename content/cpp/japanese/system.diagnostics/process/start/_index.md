---
title: Start()
second_title: Aspose.Slides for C++ API リファレンス
description: 事前定義されたパラメータでプロセスを開始します。
type: docs
weight: 14
url: /ja/system.diagnostics/process/start/
---
## Process::Start() メソッド

事前定義されたパラメータでプロセスを開始します。

```cpp
bool System::Diagnostics::Process::Start()
```

## Process::Start(const String\&, const String\&) メソッド

指定されたパスと引数でプロセスを開始します。

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const String &filename, const String &arguments=String::Empty)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | [Process](../) パス。 |
| arguments | const [String](../../../system/string/)\& | [Process](../) パラメータ。 |

### 戻り値

[Object](../../../system/object/) 新しく開始されたプロセスに添付された。

## Process::Start(const SharedPtr\<ProcessStartInfo\>\&) メソッド

指定されたパスと引数でプロセスを開始します。

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const SharedPtr<ProcessStartInfo> &start_info)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| start_info | const [SharedPtr](../../../system/sharedptr/)\<[ProcessStartInfo](../../processstartinfo/)\>\& | 開始するプロセスに関する情報。 |

### 戻り値

[Object](../../../system/object/) 新しく開始されたプロセスに添付された。

## 参照

* typedef [SharedPtr](../../../system/sharedptr/)
* クラス [Process](../)
* クラス [String](../../../system/string/)
* クラス [ProcessStartInfo](../../processstartinfo/)
* 名前空間 [System::Diagnostics](../../)
* ライブラリ [Aspose.Slides](../../../)