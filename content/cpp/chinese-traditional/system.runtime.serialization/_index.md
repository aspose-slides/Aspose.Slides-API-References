---
title: "System::Runtime::Serialization"
second_title: Aspose.Slides for C++ API 參考文件
description: 
type: docs
weight: 794
url: /zh-hant/system.runtime.serialization/
---
## 類別

| Class | Description |
| --- | --- |
| [Details_SerializationException](./details_serializationexception/) |  |
| [FormatterConverter](./formatterconverter/) | 代表 [System::Runtime::Serialization::IFormatterConverter](./iformatterconverter/) 介面的基礎實作。 |
| [IFormatterConverter](./iformatterconverter/) | 提供 [System::Runtime::Serialization::SerializationInfo](./serializationinfo/) 實例與格式化程序提供的最適合解析 [System::Runtime::Serialization::SerializationInfo](./serializationinfo/) 內部資料的類別之間的連接。 |
| [ISerializable](./iserializable/) | 可序列化物件的介面。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。絕不要在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [SerializationInfo](./serializationinfo/) | 保留代表已序列化物件的具名欄位集合。未實作。此類別的物件應僅使用 [System::MakeObject()](../system/makeobject/) 函式分配。絕不要在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [StreamingContext](./streamingcontext/) | 虛擬類別，用於使使用 StreamingContext 的翻譯類別能編譯。不要透過 [SmartPtr](../system/smartptr/) 管理此類別的實例，必須僅在堆疊上分配。 |
## 型別別名

| Typedef | Description |
| --- | --- |
| [SerializationException](./serializationexception/) |  |