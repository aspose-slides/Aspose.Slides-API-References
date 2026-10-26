---
title: FileVersionInfo
second_title: Aspose.Slides for C++ API 參考
description: "提供有關檔案版本的資訊。此類別的物件應僅使用 System::MakeObject() 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 System::SmartPtr 指標，並使用此指標作為參數傳遞給函式。"
type: docs
weight: 1
url: /zh-hant/system.diagnostics/fileversioninfo/
---
## FileVersionInfo 類別

提供有關檔案版本的資訊。此類別的物件應僅使用 [System::MakeObject()](../../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為這會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。

```cpp
class FileVersionInfo
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [String](../../system/string/) [get_ProductVersion](./get_productversion/)() const | 取得產品版本欄位。 |
| static [SharedPtr](../../system/sharedptr/)\<[System::Diagnostics::FileVersionInfo](./)\> [GetVersionInfo](./getversioninfo/)(const [String](../../system/string/)\&) | 取得檔案版本資訊；未實作。 |
## 另請參閱

* 命名空間 [System::Diagnostics](../)
* 函式庫 [Aspose.Slides](../../)