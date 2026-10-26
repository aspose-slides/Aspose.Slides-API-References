---
title: "System::Text::RegularExpressions"
second_title: Aspose.Slides for C++ API 參考
description: 
type: docs
weight: 989
url: /zh-hant/system.text.regularexpressions/
---
## 類別

| 類別 | 說明 |
| --- | --- |
| [Capture](./capture/) | 單一子表達式匹配的結果。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [CaptureCollection](./capturecollection/) | 單一捕獲群組完成的捕獲列表。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [Group](./group/) | 單一捕獲群組匹配的結果。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [GroupCollection](./groupcollection/) | 單一匹配中的捕獲群組列表。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [GroupCollectionPtr](./groupcollectionptr/) | [Group](./group/) 集合指標。此類型是用來管理其他物件刪除的指標。應在堆疊上分配，並以值或 const 參考傳遞給函式。 |
| [Match](./match/) | [Single](../system/single/) 正則表達式在字串上的匹配。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [MatchCollection](./matchcollection/) | 反覆將正則表達式套用於字串所產生的匹配集合。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [Regex](./regex/) | 遵循 C# 類似語法的正則表達式。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |

## 函式

| 函式 | 說明 |
| --- | --- |
|  [ASPOSECPP_3RD_PARTY_UNCOPYBALE_TYPE_HOLDER](./asposecpp_3rd_party_uncopybale_type_holder/)(Detail::MatchHolder, MatchHolder, sizeof(Detail::DummyMatchHolder), Detail::DummyMatchHolder, MatchHolderAlias) | 用於保留 MatchHolder 類別而不包含它以及 PCRE2 的封裝器。 |

## 列舉

| 列舉 | 說明 |
| --- | --- |
| [RegexOptions](./regexoptions/) | [Regex](./regex/) 選項。 |

## 型別別名

| 型別別名 | 說明 |
| --- | --- |
| [UStringPtr](./ustringptr/) | 共享 UnicodeString 以避免複製。 |
| [CapturePtr](./captureptr/) | 指向單一捕獲物件的指標。 |
| [CaptureCollectionPtr](./capturecollectionptr/) | 指向捕獲集合的指標。 |
| [GroupPtr](./groupptr/) | 指向群組的指標。 |
| [RegexPtr](./regexptr/) | [Regex](./regex/) 指標。 |
| [MatchPtr](./matchptr/) | [Match](./match/) 指標。 |
| [MatchCollectionPtr](./matchcollectionptr/) | [Match](./match/) 集合指標。 |
| [MatchEvaluator](./matchevaluator/) | 用於評估匹配的委派類型。 |