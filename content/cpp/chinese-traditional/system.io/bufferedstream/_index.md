---
title: BufferedStream
second_title: Aspose.Slides for C++ API 參考文件
description: "在另一個串流之上新增緩衝層。此類別的物件應僅使用 System::MakeObject() 函式分配。切勿在堆疊上或使用 new 運算子建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝為 System::SmartPtr 指標，並使用此指標作為參數傳遞給函式。"
type: docs
weight: 118
url: /zh-hant/system.io/bufferedstream/
---
## BufferedStream 類別

在另一個串流之上新增緩衝層。此類別的物件應僅使用 [System::MakeObject()](../../system/makeobject/) 函式分配。切勿在堆疊上或使用 new 運算子建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝為 [System::SmartPtr](../../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。

```cpp
class BufferedStream : public System::IO::Stream
```

## Methods

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | 啟動非同步讀取作業。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | 啟動非同步寫入作業。 |
|  [BufferedStream](./bufferedstream/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | 建構一個 [BufferedStream](./) 物件，該物件包裝指定的串流並使用 4096 位元組長的緩衝區。 |
|  [BufferedStream](./bufferedstream/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, int) | 建構一個 [BufferedStream](./) 物件，該物件包裝指定的串流並使用指定大小的緩衝區。 |
| virtual void [Close](../stream/close/)() | 關閉串流。 |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | 將位元組複製到指定的串流。 |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | 使用指定的緩衝區大小，將位元組複製到指定的串流。 |
| void [Dispose](../stream/dispose/)() override | 釋放目前物件使用的所有資源並關閉串流。 |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | 等候指定的非同步讀取作業完成。 |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | 結束非同步寫入作業。等候指定的非同步寫入作業完成。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使依 IEC 60559:1989 之規定 NaN 不等於任何值（包括 NaN）。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使依 IEC 60559:1989 之規定 NaN 不等於任何值（包括 NaN）。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| void [Flush](./flush/)() override | 將緩衝區內容寫入底層串流。 |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | 非同步清除此串流的所有緩衝區，將任何緩衝資料寫入底層裝置，並監控取消請求。 |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | 非同步清除此串流的所有緩衝區，將任何緩衝資料寫入底層裝置，並監控取消請求。 |
| **bool** [get_CanRead](./get_canread/)() const override | 判斷串流是否可讀。 |
| **bool** [get_CanSeek](./get_canseek/)() const override | 判斷串流是否支援定位。 |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | 取得決定目前串流是否可逾時的值。 |
| **bool** [get_CanWrite](./get_canwrite/)() const override | 判斷串流是否可寫。 |
| **int64_t** [get_Length](./get_length/)() const override | 傳回串流的長度。 |
| **int64_t** [get_Position](./get_position/)() const override | 傳回串流目前的位置。 |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | 取得以毫秒為單位、決定串流在逾時前嘗試讀取的時間值。 |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | 取得以毫秒為單位、決定串流在逾時前嘗試寫入的時間值。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數器資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守護物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的克隆。 |
| [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷貝建構子。實際上不會拷貝任何內容，只是初始化新物件，並允許子類別的拷貝建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不會拷貝任何內容，只是初始化新物件，並允許子類別的拷貝建構。 |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | 從底層串流讀取指定數量的位元組，並寫入指定的位元組陣列。 |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | 從底層串流讀取指定數量的位元組，並寫入指定的位元組陣列。 |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | 從串流讀取指定數量的位元組，並寫入指定的位元組陣列。 |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | 從串流讀取指定數量的位元組，並寫入指定的位元組跨度。 |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | 非同步從目前串流讀取一連串位元組，依讀取的位元組數前進串流位置，並監控取消請求。 |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | 非同步從目前串流讀取一連串位元組，依讀取的位元組數前進串流位置，並監控取消請求。 |
| int [ReadByte](./readbyte/)() override | 從底層串流讀取單一位元組，並回傳等同於該位元組值的 32 位整數。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 依參考比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 依參考比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | 設定目前物件所代表的串流位置。 |
| void [set_Position](./set_position/)(**int64_t**) override | 將緩衝區刷新至底層串流，然後設定串流的位置。 |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | 設定決定目前串流是否可逾時的值。 |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | 設定以毫秒為單位、決定串流在逾時前嘗試讀取的時間值。 |
| void [SetLength](./setlength/)(**int64_t**) override | 設定目前物件所代表的串流長度。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數器目前的值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守護物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | 將指定位元組陣列的子區段寫入底層串流。 |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | 將指定位元組陣列的子區段寫入底層串流。 |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | 將指定位元組陣列的子區段寫入串流。 |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | 將指定位元組跨度的子區段寫入串流。 |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | 非同步將一連串位元組寫入目前串流，依寫入的位元組數前進此串流位置，並監控取消請求。 |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | 非同步將一連串位元組寫入目前串流，依寫入的位元組數前進此串流位置，並監控取消請求。 |
| void [WriteByte](./writebyte/)(**uint8_t**) override | 將指定的無號 8 位元整數值寫入底層串流。 |
| virtual  [~BufferedStream](./~bufferedstream/)() | 解構函式。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## Fields

| Field | Description |
| --- | --- |
| static [Null](../stream/null/) | 沒有底層儲存的串流。 |

## See Also

* 類別 [Stream](../stream/)
* 命名空間 [System::IO](../)
* 函式庫 [Aspose.Slides](../../)