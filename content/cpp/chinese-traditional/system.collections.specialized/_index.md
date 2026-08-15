---
title: "System::Collections::Specialized"
second_title: Aspose.Slides for C++ API 參考文件
description: 
type: docs
weight: 391
url: /zh-hant/system.collections.specialized/
---
## 類別

| 類別 | 說明 |
| --- | --- |
| [BitVector32](./bitvector32/) | 提供一個簡易的輕量位元向量，具有簡單的整數或 [Boolean](../system/boolean/) 存取方式，針對 32 位元儲存體。 |
| [NameValueCollection](./namevaluecollection/) | 收集相關的 [String](../system/string/) 鍵與 [String](../system/string/) 值，可透過鍵或索引存取。 |
| [StringCollection](./stringcollection/) | 字串的索引列表。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [StringCollectionPtr](./stringcollectionptr/) | 字串集合指標，具備存取運算子。 |
| [StringDictionary](./stringdictionary/) | [String](../system/string/) 到字串字典。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
## 函式

| 函式 | 說明 |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)(**BitVector32::Section**, **BitVector32::Section**) | 檢查兩個指定的物件是否相等。 |
| **bool** [operator!=](./operator_not_equal/)(**BitVector32::Section**, **BitVector32::Section**) | 檢查兩個指定的物件是否不相等。 |