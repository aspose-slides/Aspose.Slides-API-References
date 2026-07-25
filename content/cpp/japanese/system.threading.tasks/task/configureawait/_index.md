---
title: ConfigureAwait()
second_title: Aspose.Slides for C++ API リファレンス
description: このタスクの await がコンテキストのキャプチャに関してどのように振る舞うかを構成します。
type: docs
weight: 144
url: /ja/system.threading.tasks/task/configureawait/
---
## Task::ConfigureAwait(bool) const メソッド


このタスクの await の動作がコンテキストのキャプチャに関してどのように振る舞うかを設定します。

```cpp
Runtime::CompilerServices::ConfiguredTaskAwaitable System::Threading::Tasks::Task::ConfigureAwait(bool continueOnCapturedContext) const
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | キャプチャされたコンテキストで続行するかどうか |

### 戻り値

[Runtime::CompilerServices::ConfiguredTaskAwaitable](../../../system.runtime.compilerservices/configuredtaskawaitable/) 構成された awaitable

## 関連項目

* クラス [ConfiguredTaskAwaitable](../../../system.runtime.compilerservices/configuredtaskawaitable/)
* クラス [Task](../)
* 名前空間 [System::Threading::Tasks](../../)
* ライブラリ [Aspose.Slides](../../../)