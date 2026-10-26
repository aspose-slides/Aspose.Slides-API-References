---
title: "System::Drawing::Printing"
second_title: Aspose.Slides for C++ API 參考手冊
description: 
type: docs
weight: 521
url: /zh-hant/system.drawing.printing/
---
## 類別

| 類別 | 說明 |
| --- | --- |
| [Margins](./margins/) | 表示列印頁面的邊距。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [PageSettings](./pagesettings/) | 表示列印頁面的設定。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [PaperSize](./papersize/) | 指定紙張的尺寸。 |
| [PrintController](./printcontroller/) | 控制文件在從 [Windows](../system.windows/) Forms 應用程式列印時的列印方式。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [PrintDocument](./printdocument/) | 在從 [Windows](../system.windows/) Forms 應用程式列印時，將輸出傳送至印表機。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [PrinterResolution](./printerresolution/) | 表示印表機的解析度。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [PrinterSettings](./printersettings/) | 表示印表機的設定。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [PrintEventArgs](./printeventargs/) | 提供 BeginPrint 與 EndPrint 事件的資料。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [PrintPageEventArgs](./printpageeventargs/) | 提供 PrintPage 事件的資料。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [QueryPageSettingsEventArgs](./querypagesettingseventargs/) | 提供 QueryPageSettings 事件的資料。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [StandardPrintController](./standardprintcontroller/) | 指定將資訊傳送至印表機的列印控制器。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式配置。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
## 列舉

| 列舉 | 說明 |
| --- | --- |
| [PaperKind](./paperkind/) | 指定標準紙張尺寸。 |
| [PrintAction](./printaction/) | 指定列印操作的類型。 |
| [PrintRange](./printrange/) | 指定列印哪些頁面。 |
## 型別別名

| 型別別名 | 說明 |
| --- | --- |
| [PrintPageEventHandler](./printpageeventhandler/) | 處理 PrintPage 事件的函式類型。 |
| [PrintEventHandler](./printeventhandler/) | 處理 BeginPrint 與 EndPrint 事件的函式物件類型。 |