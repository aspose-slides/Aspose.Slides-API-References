---
title: "System::Diagnostics"
second_title: Aspose.Slides for C++ API 參考
description: 
type: docs
weight: 469
url: /zh-hant/system.diagnostics/
---
## 類別

| 類別 | 描述 |
| --- | --- |
| [FileVersionInfo](./fileversioninfo/) | 提供有關檔案版本的資訊。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。絕不要在堆疊上或使用 operator new 建立此類型的實例，因為這會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標將其傳遞給函式作為參數。 |
| [PerformanceCounter](./performancecounter/) | 用於編譯使用 PerformanceCounter 的翻譯程式碼的虛擬類別。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。絕不要在堆疊上或使用 operator new 建立此類型的實例，因為這會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標將其傳遞給函式作為參數。 |
| [Process](./process/) | 封裝行程資訊與操作。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。絕不要在堆疊上或使用 operator new 建立此類型的實例，因為這會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標將其傳遞給函式作為參數。 |
| [ProcessStartInfo](./processstartinfo/) | 描述行程啟動參數。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。絕不要在堆疊上或使用 operator new 建立此類型的實例，因為這會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標將其傳遞給函式作為參數。 |
| [StackFrame](./stackframe/) | 取得單一堆疊框架的資訊。MSVS only. 此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。絕不要在堆疊上或使用 operator new 建立此類型的實例，因為這會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標將其傳遞給函式作為參數。 |
| [StackTrace](./stacktrace/) | 堆疊框架的集合。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。絕不要在堆疊上或使用 operator new 建立此類型的實例，因為這會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標將其傳遞給函式作為參數。 |
| [Stopwatch](./stopwatch/) | 允許時間測量。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。絕不要在堆疊上或使用 operator new 建立此類型的實例，因為這會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標將其傳遞給函式作為參數。 |
| [TraceListener](./tracelistener/) | 介面，用於回應除錯與追蹤資訊。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。絕不要在堆疊上或使用 operator new 建立此類型的實例，因為這會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標將其傳遞給函式作為參數。 |
## 結構

| 結構 | 描述 |
| --- | --- |
| [Debug](./debug/) | 收集除錯方法，允許它將除錯資訊傳送給已註冊的監聽程式。所有輸出函式僅在 [Debug](./debug/) 中運作。這是一個靜態型別，沒有實例服務。請絕不要以任何方式建立其實例。 |
| [Debugger](./debugger/) | [Debugger](./debugger/) 介面。這是一個靜態型別，沒有實例服務。請絕不要以任何方式建立其實例。 |
| [Trace](./trace/) | 提供存取除錯器追蹤（如果有）的介面。僅在 [Debug](./debug/) 模式下工作。這是一個靜態型別，沒有實例服務。請絕不要以任何方式建立其實例。 |
## 列舉

| 列舉 | 描述 |
| --- | --- |
| [ProcessWindowStyle](./processwindowstyle/) | 行程視窗的樣式。 |
| [TraceEventType](./traceeventtype/) | 識別導致追蹤的事件類型。 |
| [TraceLevel](./tracelevel/) | 指定要為 [System.Diagnostics.Debug](./debug/)、[System.Diagnostics.Trace](./trace/) 與 System.Diagnostics.TraceSwitch 類別輸出的訊息。 |
## 型別別名

| 型別別名 | 描述 |
| --- | --- |
| [StopwatchPtr](./stopwatchptr/) | 指標類型。 |