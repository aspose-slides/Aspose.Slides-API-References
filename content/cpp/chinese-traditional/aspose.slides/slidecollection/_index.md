---
title: SlideCollection
second_title: Aspose.Slides for C++ API 參考
description: 表示投影片的集合。
type: docs
weight: 5188
url: /zh-hant/aspose.slides/slidecollection/
---
## SlideCollection class

表示投影片的集合。

```cpp
class SlideCollection : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Presentation>>,
                        public Aspose::Slides::ISlideCollection
```

## Methods

| 方法 | 描述 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [AddClone](./addclone/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) override | 在集合的末端加入指定投影片的副本。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [AddClone](./addclone/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\>) override | 在指定章節的末端加入指定投影片的副本。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [AddClone](./addclone/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\>) override | 在集合的末端加入指定投影片的副本。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [AddClone](./addclone/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlide](../imasterslide/)\>, **bool**) override | 將指定來源投影片的副本加入集合的末端。系統會自動從指定的母片中選取適當的版面配置（適當的版面配置是具有與來源投影片相同類型或名稱的版面配置）。如果不存在適當的版面配置，則會克隆來源投影片的版面配置（若 allowCloneMissingLayout 為 true）或拋出 PptxEditException（若 allowCloneMissingLayout 為 false）。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [AddEmptySlide](./addemptyslide/)([System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\>) override | 在集合的末端加入一張新的空白投影片。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [AddFromHtml](./addfromhtml/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../aspose.slides.import/iexternalresourceresolver/)\>, [System::String](../../system/string/)) override | 從 HTML 文字建立投影片並將其加入集合的末端。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [AddFromHtml](./addfromhtml/)([System::String](../../system/string/)) override | 從 HTML 文字建立投影片並將其加入集合的末端。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [AddFromHtml](./addfromhtml/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../aspose.slides.import/iexternalresourceresolver/)\>, [System::String](../../system/string/)) override | 從 HTML 文字建立投影片並將其加入集合的末端。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [AddFromHtml](./addfromhtml/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>) override | 從 HTML 文字建立投影片並將其加入集合的末端。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [AddFromHtml](./addfromhtml/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../aspose.slides.import/iexternalresourceresolver/)\>, [System::String](../../system/string/)) override | 從 HTML 文字建立投影片並將其加入集合的末端。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [AddFromHtml](./addfromhtml/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | 從 HTML 文字建立投影片並將其加入集合的末端。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [AddFromPdf](./addfrompdf/)([System::String](../../system/string/)) override | 從 PDF 文件建立投影片並將其加入集合的末端。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [AddFromPdf](./addfrompdf/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Import::PdfImportOptions](../../aspose.slides.import/pdfimportoptions/)\>) override | 根據 PDF 匯入選項，從 PDF 文件建立投影片並將其加入集合的末端。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [AddFromPdf](./addfrompdf/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | 從 PDF 文件建立投影片並將其加入集合的末端。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [AddFromPdf](./addfrompdf/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Import::PdfImportOptions](../../aspose.slides.import/pdfimportoptions/)\>) override | 從 PDF 文件建立投影片並將其加入集合的末端。 |
| [iterator](./iterator/) [begin](./begin/)() | 取得指向集合第一個元素（若有）的迭代器。 |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | 取得指向集合 const 限定實例第一個元素（若有）的迭代器。 |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | 取得指向集合第一個 const 限定元素（若有）的迭代器。 |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | 取得指向集合最後一個 const 限定元素之後的位置的迭代器（若有）。 |
| void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\>, **int32_t**) override | 將集合中所有元素複製到指定的陣列。 |
| virtual void [CopyTo](../igenericcollection/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, **int32_t**) | 將集合中所有元素複製到指定的陣列。 |
| [iterator](./iterator/) [end](./end/)() | 取得指向集合最後一個元素之後的位置的迭代器（若有）。 |
| [const_iterator](./const_iterator/) [end](./end/)() const | 取得指向集合 const 限定實例最後一個元素之後的位置的迭代器（若有）。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，儘管根據 IEC 60559:1989 標準，NaN 不等於任何值，包含 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，儘管根據 IEC 60559:1989 標準，NaN 不等於任何值，包含 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| **int32_t** [get_Count](./get_count/)() override | 取得集合實際包含的元素數量。唯讀 **int32_t**。 |
| **bool** [get_IsSynchronized](./get_issynchronized/)() override | 傳回一個值，指示對集合的存取是否已同步（執行緒安全）。唯讀 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_SyncRoot](./get_syncroot/)() override | 傳回同步根。唯讀 [System::Object](../../system/object/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\>\> [GetEnumerator](./getenumerator/)() override | 傳回用於遍歷集合的列舉器。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的類比。啟用自訂物件的雜湊功能。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [idx_get](./idx_get/)(**int32_t**) override | 取得指定索引處的元素。唯讀 [Slide](../slide/)。 |
| **int32_t** [IndexOf](./indexof/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) override | 傳回指定投影片在集合中的索引。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [InsertClone](./insertclone/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) override | 在集合的指定位置插入指定投影片的副本。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [InsertClone](./insertclone/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\>) override | 在集合的指定位置插入指定投影片的副本。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [InsertClone](./insertclone/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlide](../imasterslide/)\>, **bool**) override | 在集合的指定位置插入指定來源投影片的副本。系統會自動從指定的母片中選取適當的版面配置（適當的版面配置是具有與來源投影片相同類型或名稱的版面配置）。如果不存在適當的版面配置，則會克隆來源投影片的版面配置（若 allowCloneMissingLayout 為 true）或拋出 PptxEditException（若 allowCloneMissingLayout 為 false）。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [InsertEmptySlide](./insertemptyslide/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\>) override | 在集合的指定位置插入指定投影片的副本。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [InsertFromHtml](./insertfromhtml/)(**int32_t**, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../aspose.slides.import/iexternalresourceresolver/)\>, [System::String](../../system/string/)) override | 從 HTML 文字建立投影片並將它們插入集合的指定位置。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [InsertFromHtml](./insertfromhtml/)(**int32_t**, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../aspose.slides.import/iexternalresourceresolver/)\>, [System::String](../../system/string/), **bool**) override | 從 HTML 文字建立投影片並將它們插入集合的指定位置。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [InsertFromHtml](./insertfromhtml/)(**int32_t**, [System::String](../../system/string/)) override | 從 HTML 文字建立投影片並將它們插入集合的指定位置。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [InsertFromHtml](./insertfromhtml/)(**int32_t**, [System::String](../../system/string/), **bool**) override | 從 HTML 文字建立投影片並將它們插入集合的指定位置。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [InsertFromHtml](./insertfromhtml/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../aspose.slides.import/iexternalresourceresolver/)\>, [System::String](../../system/string/)) override | 從 HTML 文字建立投影片並將它們插入集合的指定位置。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [InsertFromHtml](./insertfromhtml/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>) override | 從 HTML 文字建立投影片並將它們插入集合的指定位置。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [InsertFromHtml](./insertfromhtml/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../aspose.slides.import/iexternalresourceresolver/)\>, [System::String](../../system/string/)) override | 從 HTML 文字建立投影片並將它們插入集合的指定位置。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [InsertFromHtml](./insertfromhtml/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../aspose.slides.import/iexternalresourceresolver/)\>, [System::String](../../system/string/), **bool**) override | 從 HTML 文字建立投影片並將它們插入集合的指定位置。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [InsertFromHtml](./insertfromhtml/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | 從 HTML 文字建立投影片並將它們插入集合的指定位置。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [InsertFromHtml](./insertfromhtml/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, **bool**) override | 從 HTML 文字建立投影片並將它們插入集合的指定位置。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 描述的類型實例。相當於 C# 的 'is' 運算子。 |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | 對序列套用累加函式。 |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | 判斷序列的所有元素是否滿足條件。 |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | 判斷序列是否包含任何元素。 |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | 判斷序列中是否存在任意元素或符合條件的元素。 |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | 計算數值序列的平均值。 |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 對輸入序列每個元素套用轉換函式後，計算所得值序列的平均值。 |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | 將元素轉型為指定類型。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | 串接兩個序列。 |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | 判斷序列是否包含指定的值。 |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | 傳回序列中元素的數量（透過直接計數計算）。 |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 傳回滿足指定條件的序列元素數量。 |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | 傳回序列中指定索引的元素。 |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | 傳回序列中指定索引的元素。 |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | 傳回序列的第一個元素。 |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 傳回符合指定條件的序列第一個元素。 |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | 傳回序列的第一個元素，若序列為空則返回預設值。 |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | 傳回符合條件的序列首個元素，若未找到則返回預設值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | 將序列的元素分組。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | 將序列的元素分組。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | 傳回序列的最後一個元素。 |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | 傳回序列的最後一個元素，若序列為空則返回預設值。 |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 對通用序列的每個元素套用轉換函式，並返回最大結果值。 |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 對通用序列的每個元素套用轉換函式，並返回最小結果值。 |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | 根據指定類型過濾序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | 根據 keySelector 所選擇的鍵值，以升冪順序排序序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | 根據 keySelector 所選擇的鍵值，以降冪順序排序序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | 反轉序列中元素的順序。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 轉換序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | 根據元素的索引，將序列的每個元素轉換成新的形式。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | 對序列的每個元素進行投射，並將產生的序列合併成一個序列。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | 跳過序列起始位置的指定數量連續元素，並返回其餘部分。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | 返回序列起始位置的指定數量連續元素。 |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | 從序列建立陣列。 |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | 從序列建立 List<T>。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | 根據指定的謂詞過濾序列。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的類比。啟用自訂類型的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷貝建構函式。實際上不會拷貝任何內容，只是初始化新物件並允許子類別的拷貝建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不會拷貝任何內容，只是初始化新物件並允許子類別的拷貝建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 將值型別物件與 nullptr 進行參考比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的字串與 nullptr 情況的特殊化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的字串情況的特殊化。 |
| void [Remove](./remove/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) override | 從集合中移除首次出現的指定物件。 |
| void [RemoveAt](./removeat/)(**int32_t**) override | 移除集合中指定索引處的元素。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定值。 |
| void [Reorder](./reorder/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) override | 將投影片從集合移動到指定位置。 |
| void [Reorder](./reorder/)(**int32_t**, const [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\>\&) override | 將投影片從集合移動到指定位置。[Slides](../) 將從索引開始依列表中出現的順序放置。 |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的當前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 減少共享參考計數並返回其值。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [ToArray](./toarray/)() override | 建立並返回包含所有投影片的陣列。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [ToArray](./toarray/)(**int32_t**, **int32_t**) override | 建立並返回包含指定範圍內所有投影片的陣列。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的類比。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | 取得指向集合 const 限定實例第一個元素（若有）的迭代器。 |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | 取得指向集合第一個元素（若有）的迭代器。 |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | 取得指向集合 const 限定實例最後一個元素之後的位置的迭代器（若有）。 |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeEndIterator](./virtualizeenditerator/)() override | 取得指向集合最後一個元素之後的位置的迭代器（若有）。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 減少弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## Typedefs

| 型別別名 | 描述 |
| --- | --- |
| [iterator_holder_type](./iterator_holder_type/) | 用於目前集合的迭代器類型之集合類型。 |
| [iterator](./iterator/) | 迭代器類型。 |
| [const_iterator](./const_iterator/) | 常量迭代器類型。 |
| [virtualized_iterator_element](./virtualized_iterator_element/) | 虛擬化元素類型。 |
| [virtualized_iterator](./virtualized_iterator/) | 虛擬化類型。 |

## 另請參閱

* 類別 [DomObject](../domobject/)
* 類別 [ISlideCollection](../islidecollection/)
* 名稱空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)