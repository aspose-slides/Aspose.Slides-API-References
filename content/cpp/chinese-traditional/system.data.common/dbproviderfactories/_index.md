---
title: DbProviderFactories
second_title: Aspose.Slides C++ API 參考
description: "用於取得 DB 供應者工廠的 API。此類別的物件只能使用 System::MakeObject() 函式進行配置。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 System::SmartPtr 指標，並使用該指標作為參數傳遞給函式。"
type: docs
weight: 53
url: /zh-hant/system.data.common/dbproviderfactories/
---
## DbProviderFactories 類別

用於取得 DB 供應者工廠的 API。此類別的物件只能使用 [System::MakeObject()](../../system/makeobject/) 函式來配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝為 [System::SmartPtr](../../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。

```cpp
class DbProviderFactories
```

## 方法

| 方法 | 說明 |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[DbProviderFactory](../dbproviderfactory/)\> [GetFactory](./getfactory/)(const [String](../../system/string/)\&) | 依名稱取得 DB 供應者工廠。 |
## 另請參閱

* 命名空間 [System::Data::Common](../)
* 程式庫 [Aspose.Slides](../../)