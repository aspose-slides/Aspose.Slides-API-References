---
title: BasicSTDOStreamWrapper
second_title: Aspose.Slides for C++ API 參考文件
description: "代表一個類似 System.IO.Stream 的包裝器，用於 std::basic_ostream 及其衍生物件。此類別的物件只能透過 System::MakeObject() 函式配置。切勿在堆疊上或使用 operator new 建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝為 System::SmartPtr 指標，並使用該指標作為參數傳遞給函式。"
type: docs
weight: 27
url: /zh-hant/system.io/basicstdostreamwrapper/
---
## BasicSTDOStreamWrapper 類別

此類別代表一個 [System.IO.Stream](../stream/) 類似的包裝器，適用於 std::basic_ostream 及其衍生物件。此類別的物件只能透過 [System::MakeObject()](../../system/makeobject/) 函式配置。切勿在堆疊上或使用 operator new 建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝為 [System::SmartPtr](../../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。

```cpp
template<typename T,typename>class BasicSTDOStreamWrapper : public virtual System::IO::STDIOStreamWrapperBase<T>
```

## 方法

| 方法 | 說明 |
| --- | --- |
|  [BasicSTDOStreamWrapper](./basicstdostreamwrapper/)(std::basic_ostream\<[char_type](../stdiostreamwrapperbase/char_type/), [traits_type](../stdiostreamwrapperbase/traits_type/)\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)) | 建構 [BasicSTDOStreamWrapper](./) 的新實例。 |
|  [BasicSTDOStreamWrapper](./basicstdostreamwrapper/)(const [BasicSTDOStreamWrapper](./)\&) | 拷貝建構函式。已刪除。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | 啟動非同步讀取作業。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | 啟動非同步寫入作業。 |
| virtual void [Close](../stream/close/)() | 關閉資料流。 |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | 將位元組複製到指定的資料流。 |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | 使用指定的緩衝區大小，將位元組複製到指定的資料流。 |
| void [Dispose](../stream/dispose/)() override | 釋放目前物件使用的所有資源並關閉資料流。 |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | 等待指定的非同步讀取作業完成。 |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | 結束非同步寫入作業。等待指定的非同步寫入作業完成。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點數比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點數比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| void [Flush](./flush/)() override | 清除此資料流的緩衝區，並將所有已緩衝的資料寫入底層儲存。 |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | 非同步清除此資料流的所有緩衝區，導致任何已緩衝的資料寫入底層裝置，並監控取消請求。 |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | 非同步清除此資料流的所有緩衝區，導致任何已緩衝的資料寫入底層裝置，並監控取消請求。 |
| **bool** [get_CanRead](../stdiostreamwrapperbase/get_canread/)() const override | 判斷資料流是否支援讀取。 |
| **bool** [get_CanSeek](../stdiostreamwrapperbase/get_canseek/)() const override | 判斷資料流是否支援定位。 |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | 取得決定目前資料流是否會逾時的值。 |
| **int64_t** [get_Length](../stdiostreamwrapperbase/get_length/)() const override | 傳回資料流的長度。 |
| **int64_t** [get_Position](../stdiostreamwrapperbase/get_position/)() const override | 傳回資料流的目前位置。 |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | 取得以毫秒為單位的值，決定資料流在逾時前嘗試讀取的時間長度。 |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | 取得以毫秒為單位的值，決定資料流在逾時前嘗試寫入的時間長度。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊功能。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為目標類型 targetType 所描述的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷貝建構函式。實際上不會複製任何內容，只是初始化新物件並允許子類別的拷貝建構。 |
| [BasicSTDOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSTDOStreamWrapper](./)\&) | 拷貝指派運算子。已刪除。 |
| [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\& [operator=](../stdiostreamwrapperbase/operator_equal/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | 拷貝指派運算子。已刪除。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的拷貝建構。 |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | 如果包裝模式為二進位，從資料流讀取指定數量的位元組；否則讀取指定數量的字元並轉換為 **uint8_t** 類型。將讀取結果寫入指定的位元組陣列。不支援！ |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | 從資料流讀取指定數量的位元組，並寫入指定的位元組陣列。 |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | 從資料流讀取指定數量的位元組，並寫入指定的位元組陣列。 |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | 從資料流讀取指定數量的位元組，並寫入指定的位元組跨度。 |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | 非同步從目前資料流讀取一連串位元組，根據讀取的位元組數前進位置，並監控取消請求。 |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | 非同步從目前資料流讀取一連串位元組，根據讀取的位元組數前進位置，並監控取消請求。 |
| int [ReadByte](./readbyte/)() override | 如果包裝模式為二進位，從最後解碼的字元儲存中讀取單一位元組；否則從資料流讀取單一字元並轉換為 **uint8_t** 類型。不支援！ |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 依參考比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 依參考比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 將值型別物件與 nullptr 進行參考比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 針對字串和 nullptr 的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化版。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 針對字串的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化版。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
|  [RTTI_INFO_TEMPLATE_CLASS](./rtti_info_template_class/)([ThisType](../stdiostreamwrapperbase/thistype/), [ThisTypeBaseTypesInfo](../stdiostreamwrapperbase/thistypebasetypesinfo/)) | RTTI 資訊。 |
| **int64_t** [Seek](../stdiostreamwrapperbase/seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | 設定目前物件所代表的資料流位置。 |
| void [set_Position](../stdiostreamwrapperbase/set_position/)(**int64_t**) override | 設定資料流的位置。 |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | 設定決定目前資料流是否會逾時的值。 |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | 設定以毫秒為單位的值，決定資料流在逾時前嘗試讀取的時間長度。 |
| void [SetLength](./setlength/)(**int64_t**) override | 設定目前物件所代表的資料流長度。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並返回共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
|  [STDIOStreamWrapperBase](../stdiostreamwrapperbase/stdiostreamwrapperbase/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | 拷貝建構函式。已刪除。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | 如果包裝模式為二進位，將指定位元組陣列中指定的子範圍寫入資料流；否則將該子範圍的位元組轉換為 char_type 類型，再寫入資料流。 |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | 將指定位元組陣列中指定的子範圍寫入資料流。 |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | 將指定位元組陣列中指定的子範圍寫入資料流。 |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | 將指定位元組跨度中指定的子範圍寫入資料流。 |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | 非同步將位元組序列寫入目前資料流，根據寫入的位元組數前進位置，並監控取消請求。 |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | 非同步將位元組序列寫入目前資料流，根據寫入的位元組數前進位置，並監控取消請求。 |
| void [WriteByte](./writebyte/)(**uint8_t**) override | 如果包裝模式為二進位，將指定的 unsigned 8 位元整數值寫入資料流；否則將其轉換為 char_type 類型後寫入資料流。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 欄位

| 欄位 | 說明 |
| --- | --- |
| static [Null](../stream/null/) | 沒有底層儲存的資料流。 |

## 型別別名

| 型別別名 | 說明 |
| --- | --- |
| [ThisType](./thistype/) |  |
| [BaseType](./basetype/) |  |
| [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/) |  |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |

## 參見

* 類別 [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)
* 命名空間 [System::IO](../)
* 函式庫 [Aspose.Slides](../../)