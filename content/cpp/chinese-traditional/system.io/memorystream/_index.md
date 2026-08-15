---
title: MemoryStream
second_title: Aspose.Slides for C++ API 參考文件
description: "代表一個從記憶體讀寫的串流。此類別的物件只能使用 System::MakeObject() 函式分配。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤或斷言失敗。請始終將此類別包裝於 System::SmartPtr 指標，並使用該指標作為參數傳遞給函式。"
type: docs
weight: 326
url: /zh-hant/system.io/memorystream/
---
## MemoryStream 類別


Represents a stream that reads from and writes to memory. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class MemoryStream : public System::IO::Stream
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | 啟動非同步讀取作業。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | 啟動非同步寫入作業。 |
| void [Close](./close/)() override | 關閉串流。 |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | 將位元組複製到指定的串流。 |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | 將位元組複製到指定的串流，使用指定的緩衝區大小。 |
| void [Dispose](../stream/dispose/)() override | 釋放目前物件使用的所有資源並關閉串流。 |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | 等待指定的非同步讀取作業完成。 |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | 結束非同步寫入作業。等待指定的非同步寫入作業完成。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| void [Flush](./flush/)() override | 不執行任何操作。 |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | 非同步清除此串流的所有緩衝區，將任何緩衝資料寫入底層裝置，並監視取消請求。 |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | 非同步清除此串流的所有緩衝區，將任何緩衝資料寫入底層裝置，並監視取消請求。 |
| **bool** [get_CanRead](./get_canread/)() const override | 判斷串流是否可讀。 |
| **bool** [get_CanSeek](./get_canseek/)() const override | 判斷串流是否支援尋找。 |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | 取得決定目前串流是否會逾時的值。 |
| **bool** [get_CanWrite](./get_canwrite/)() const override | 判斷串流是否可寫。 |
| int [get_Capacity](./get_capacity/)() | 傳回底層記憶體緩衝區的目前容量。 |
| **int64_t** [get_Length](./get_length/)() const override | 傳回串流的長度（位元組）。 |
| **int64_t** [get_Position](./get_position/)() const override | 傳回串流目前的位置。 |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | 取得以毫秒為單位的值，決定串流在逾時前嘗試讀取的時間長度。 |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | 取得以毫秒為單位的值，決定串流在逾時前嘗試寫入的時間長度。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBuffer](./getbuffer/)() | 傳回指向底層緩衝區的指標。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的類比。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。C# [System.Object.GetType()](../../system/object/gettype/) 呼叫的類比。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述型別的實例。C# 'is' 運算子的類比。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的類比。啟用自訂型別的複製。 |
|  [MemoryStream](./memorystream/)() | 建立 [MemoryStream](./) 類別的新實例，初始容量為 0。 |
|  [MemoryStream](./memorystream/)(int) | 建立 [MemoryStream](./) 類別的新實例，表示基於指定大小記憶體緩衝區的串流。 |
|  [MemoryStream](./memorystream/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **bool**) | 建立 [MemoryStream](./) 類別的新實例，表示連接到指定記憶體緩衝區的記憶體串流。參數指定串流是否可寫。 |
|  [MemoryStream](./memorystream/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int, **bool**, **bool**) | 建立 [MemoryStream](./) 類別的新實例，表示連接到指定記憶體緩衝區段（從指定索引開始，包含指定元素數量）的記憶體串流。參數指定串流是否可寫，以及是否可以呼叫 GetBytes() 方法。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | 從串流讀取指定數量的位元組，並寫入指定的位元組陣列。 |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | 從串流讀取指定數量的位元組，並寫入指定的位元組陣列。 |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | 從串流讀取指定數量的位元組，並寫入指定的位元組陣列。 |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | 從串流讀取指定數量的位元組，並寫入指定的位元組跨度。 |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | 非同步從目前串流讀取位元組序列，依讀取的位元組數量前移串流位置，並監視取消請求。 |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | 非同步從目前串流讀取位元組序列，依讀取的位元組數量前移串流位置，並監視取消請求。 |
| int [ReadByte](./readbyte/)() override | 從串流讀取單一位元組，並傳回與該位元組值等價的 32 位整數。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 針對字串與 nullptr 情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 針對字串情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 依指定值減少共享參考計數。 |
| **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | 設定由目前物件代表的串流位置。 |
| void [set_Capacity](./set_capacity/)(int) | 設定底層記憶體緩衝區的容量。 |
| void [set_Position](./set_position/)(**int64_t**) override | 設定串流的位置。 |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | 設定決定目前串流是否會逾時的值。 |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | 設定以毫秒為單位的值，決定串流在逾時前嘗試讀取的時間長度。 |
| void [SetLength](./setlength/)(**int64_t**) override | 設定由目前物件代表的串流長度。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板引數設為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並傳回共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ToArray](./toarray/)() | 以位元組陣列返回底層記憶體緩衝區的副本。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的類比。啟用自訂物件轉換為字串。 |
| **bool** [TryGetBuffer](./trygetbuffer/)([ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\&) | 返回此串流所建立的 unsigned 位元組陣列。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | 將指定位元組陣列的指定子範圍寫入串流。 |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | 將指定位元組陣列的指定子範圍寫入串流。 |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | 將指定位元組陣列的指定子範圍寫入串流。 |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | 將指定位元組跨度的指定子範圍寫入串流。 |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | 非同步將位元組序列寫入目前串流，依寫入的位元組數量前移此串流的當前位置，並監視取消請求。 |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | 非同步將位元組序列寫入目前串流，依寫入的位元組數量前移此串流的當前位置，並監視取消請求。 |
| void [WriteByte](./writebyte/)(**uint8_t**) override | 將指定的 unsigned 8 位整數值寫入串流。 |
| virtual void [WriteTo](./writeto/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>) | 將底層緩衝區的內容寫入指定的串流。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 欄位

| 欄位 | 說明 |
| --- | --- |
| static [Null](../stream/null/) | 沒有底層儲存的串流。 |

## 型別別名

| 型別別名 | 說明 |
| --- | --- |
| [Ptr](./ptr/) | 指向自身的共享指標別名。 |

## 另請參閱

* 類別 [Stream](../stream/)
* 命名空間 [System::IO](../)
* 函式庫 [Aspose.Slides](../../)