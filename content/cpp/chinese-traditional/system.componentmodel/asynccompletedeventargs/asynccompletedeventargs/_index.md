---
title: AsyncCompletedEventArgs()
second_title: Aspose.Slides for C++ API 參考文件
description: 建構函式。
type: docs
weight: 1
url: /zh-hant/system.componentmodel/asynccompletedeventargs/asynccompletedeventargs/
---
## AsyncCompletedEventArgs::AsyncCompletedEventArgs() 建構函式

建構函式。

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs()
```

## AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception\&, bool, const System::SharedPtr\<System::Object\>\&) 建構函式

初始化 [System.ComponentModel.AsyncCompletedEventArgs](../) 類別的新執行個體。

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception &error, bool canceled, const System::SharedPtr<System::Object> &userState)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| error | const [System::Exception](../../../system/exception/)\& | 在非同步操作期間發生的任何錯誤。 |
| canceled | **bool** | 指示非同步操作是否已取消的值。 |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | 傳遞給 [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../backgroundworker/runworkerasync/)([System.Object](../../../system/object/)) 方法的可選使用者提供的狀態物件。 |

## 另請參閱

* 型別定義 [Exception](../../../system/exception/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [AsyncCompletedEventArgs](../)
* 類別 [Object](../../../system/object/)
* 命名空間 [System::ComponentModel](../../)
* 程式庫 [Aspose.Slides](../../../)