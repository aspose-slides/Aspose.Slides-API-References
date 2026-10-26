---
title: ReportProgress()
second_title: Aspose.Slides for C++ API リファレンス
description: "System::ComponentModel::BackgroundWorker::ProgressChanged イベントを発生させます。"
type: docs
weight: 40
url: /ja/system.componentmodel/backgroundworker/reportprogress/
---
## BackgroundWorker::ReportProgress(int) メソッド


**System::ComponentModel::BackgroundWorker::ProgressChanged** イベントを発生させます。

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| percentProgress | int | バックグラウンド操作が完了したパーセンテージ（0 から 100）です。 |

## BackgroundWorker::ReportProgress(int, const System::SharedPtr\<System::Object\>\&) メソッド


**System::ComponentModel::BackgroundWorker::ProgressChanged** イベントを userState オブジェクトと共に発生させます。

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress, const System::SharedPtr<System::Object> &userState)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| percentProgress | int | バックグラウンド操作が完了したパーセンテージ（0 から 100）です。 |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | System::ComponentModel::BackgroundWorker::RunWorkerAsync(System::Object) に渡される状態オブジェクトです。 |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [BackgroundWorker](../)
* クラス [Object](../../../system/object/)
* 名前空間 [System::ComponentModel](../../)
* ライブラリ [Aspose.Slides](../../../)