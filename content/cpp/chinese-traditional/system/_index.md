---
title: System
second_title: Aspose.Slides for C++ API 參考手冊
description: 
type: docs
weight: 274
url: /zh-hant/system/
---
## Classes

| Class | Description |
| --- | --- |
| [Activator](./activator/) | 包含用於建立物件類型的方法。 |
| [Array](./array/) | 表示陣列資料結構的類別。此類別的物件應僅使用 [System::MakeArray()](./makearray/) 與 [System::MakeObject()](./makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。始終將此類別包裝為 [System::SmartPtr](./smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [ArrayBase](./arraybase/) | [System.Array](./array/) 類別的虛擬類別（所有陣列的抽象基底類別），可根據需求添加功能。 |
| [ArraySegment](./arraysegment/) | 表示一維陣列的區段。此類型應在堆疊上配置，並以值或參照傳遞給函式。切勿使用 [System::SmartPtr](./smartptr/) 類別管理此類型的物件。 |
| [Attribute](./attribute/) | 自訂屬性的基底類別。此類別的物件應僅使用 [System::MakeObject()](./makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。始終將此類別包裝為 [System::SmartPtr](./smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [BitConverter](./bitconverter/) | 包含執行位元組序列與值型別之間相互轉換的方法。這是一個沒有實例服務的靜態類別。您不應以任何方式建立其實例。 |
| [Boolean](./boolean/) | 保存 [System.Boolean](./boolean/) .[Net](../system.net/) 類型之靜態成員的類別。 |
| [BoxedEnum](./boxedenum/) | 表示盒裝列舉值。此類別的物件應僅使用 [System::MakeObject()](./makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。始終將此類別包裝為 [System::SmartPtr](./smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [BoxedValue](./boxedvalue/) | 表示盒裝值。此類別的物件應僅使用 [System::MakeObject()](./makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。始終將此類別包裝為 [System::SmartPtr](./smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [BoxedValue< ValueTuple< Args... > >](./boxedvalue_tmpl_valuetuple_tmpl_args_dots__end_tmpl__end_tmpl/) | 值元組的盒裝版本。 |
| [BoxedValueBase](./boxedvaluebase/) | 定義介面並實作代表盒裝值之子類別之基本方法的基底類別。此類別的物件應僅使用 [System::MakeObject()](./makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。始終將此類別包裝為 [System::SmartPtr](./smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [Buffer](./buffer/) | 包含操作原始位元組陣列的方法。這是一個沒有實例服務的靜態類型。您不應以任何方式建立其實例。 |
| [Byte](./byte/) | 包含用於操作無號 8 位元整數的方法。 |
| [Char](./char/) | 提供操作以 UTF-16 代碼單位表示之字元的方法。這是一個沒有實例服務的靜態類型。您不應以任何方式建立其實例。 |
| [Comparison](./comparison/) | 表示指向比較相同類型兩個物件之方法的指標。此類型應在堆疊上配置，並以值或參照傳遞給函式。切勿使用 [System::SmartPtr](./smartptr/) 類別管理此類型的物件。 |
| [Console](./console/) | 提供將資料輸出到標準輸出串流的方法。這是一個沒有實例服務的靜態類型。您不應以任何方式建立其實例。 |
| [ConsoleOutput](./consoleoutput/) | 表示標準輸出串流。此類別的物件應僅使用 [System::MakeObject()](./makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。始終將此類別包裝為 [System::SmartPtr](./smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [DateTime](./datetime/) | 表示時間連續體上特定的日期與時間值。此類型應在堆疊上配置，並以值或參照傳遞給函式。切勿使用 [System::SmartPtr](./smartptr/) 類別管理此類型的物件。 |
| [DateTimeOffset](./datetimeoffset/) | 包含相對於協調世界時的日期與時間。此類別的物件應僅使用 [System::MakeObject()](./makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。始終將此類別包裝為 [System::SmartPtr](./smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [DBNull](./dbnull/) | 表示不存在的值。此類別的物件應僅使用 [System::MakeObject()](./makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。始終將此類別包裝為 [System::SmartPtr](./smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [Decimal](./decimal/) | 表示十進位數字。此類型應在堆疊上配置，並以值或參照傳遞給函式。切勿使用 [System::SmartPtr](./smartptr/) 類別管理此類型的物件。 |
| [DefaultBoxedValue](./defaultboxedvalue/) | [BoxedValue](./boxedvalue/) 類別的實作。允許在不重複共通程式碼的情況下宣告其 BoxingValue 特化。此類別的物件應僅使用 [System::MakeObject()](./makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。始終將此類別包裝為 [System::SmartPtr](./smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [Delegate< ReturnType(ArgumentTypes...)>](./delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/) | 表示指向函式、方法或函式物件的指標。此類型應在堆疊上配置，並以值或參照傳遞給函式。切勿使用 [System::SmartPtr](./smartptr/) 類別管理此類型的物件。 |
| [Details_AggregateException](./details_aggregateexception/) | 表示包含多個內部例外的例外。 |
| [Details_ApplicationException](./details_applicationexception/) | 表示應用程式（而非系統）例外之類別的基底類別。切勿手動建立此類別的實例。請改用 ApplicationException 類別。切勿將 ApplicationException 類別的實例包裝為 [System::SmartPtr](./smartptr/)。 |
| [Details_ArgumentException](./details_argumentexception/) | 當傳遞給被呼叫方法的參數無效時，會拋出 ArgumentException。切勿手動建立此類別的實例。請改用 ArgumentException 類別。切勿將 ArgumentException 類別的實例包裝為 [System::SmartPtr](./smartptr/)。 |
| [Details_ArgumentNullException](./details_argumentnullexception/) |  |
| [Details_ArgumentOutOfRangeException](./details_argumentoutofrangeexception/) | 當被呼叫的方法傳入超出預期範圍的參數時，會拋出 ArgumentOutOfRangeException。切勿手動建立此類別的實例。請改用 ArgumentOutOfRangeException 類別。切勿將 ArgumentOutOfRangeException 類別的實例包裝為 [System::SmartPtr](./smartptr/)。 |
| [Details_ArithmeticException](./details_arithmeticexception/) | 當在執行算術運算、轉換或類型轉換操作時發生錯誤，會拋出 ArithmeticException。切勿手動建立此類別的實例。請改用 ArithmeticException 類別。切勿將 ArithmeticException 類別的實例包裝為 [System::SmartPtr](./smartptr/)。 |
| [Details_BadImageFormatException](./details_badimageformatexception/) | 當動態連結庫 (DLL) 或可執行程式的檔案映像無效時，會拋出此例外。切勿手動建立此類別的實例。請改用 BadImageFormatException 類別。切勿將 BadImageFormatException 類別的實例包裝為 [System::SmartPtr](./smartptr/)。 |
| [Details_DataMisalignedException](./details_datamisalignedexception/) |  |
| [Details_DivideByZeroException](./details_dividebyzeroexception/) | 當在算術運算中嘗試除以 0 時，會拋出 DivideByZeroException。切勿手動建立此類別的實例。請改用 DivideByZeroException 類別。切勿將 DivideByZeroException 類別的實例包裝為 [System::SmartPtr](./smartptr/)。 |
| [Details_Exception](./details_exception/) | 表示例外。切勿手動建立此類別的實例。請改用 Exception 類別。切勿將 Exception 類別的實例包裝為 [System::SmartPtr](./smartptr/)。 |
| [Details_ExceptionWithErrorCode](./details_exceptionwitherrorcode/) | 具有錯誤代碼之例外的模板類別。 |
| [Details_ExceptionWithFilename](./details_exceptionwithfilename/) | 具有檔案名稱之例外的模板類別。 |
| [Details_ExecutionEngineException](./details_executionengineexception/) | ExecutionEngineException 僅為相容性原因而保留。 |
| [Details_FormatException](./details_formatexception/) | 當方法參數的格式無效時，會拋出 FormatException。切勿手動建立此類別的實例。請改用 FormatException 類別。切勿將 FormatException 類別的實例包裝為 [System::SmartPtr](./smartptr/)。 |
| [Details_IndexOutOfRangeException](./details_indexoutofrangeexception/) | 當以超出範圍的索引存取集合元素時，會拋出 IndexOutOfRangeException。切勿手動建立此類別的實例。請改用 IndexOutOfRangeException 類別。切勿將 IndexOutOfRangeException 類別的實例包裝為 [System::SmartPtr](./smartptr/)。 |
| [Details_InvalidCastException](./details_invalidcastexception/) | 當嘗試無效的轉型或不正確的顯式轉換時，會拋出 InvalidCastException。切勿手動建立此類別的實例。請改用 InvalidCastException 類別。切勿將 InvalidCastException 類別的實例包裝為 [System::SmartPtr](./smartptr/)。 |
| [Details_InvalidOperationException](./details_invalidoperationexception/) | 當在狀態與此呼叫不一致的物件上呼叫方法時，會拋出此例外。切勿手動建立此類別的實例。請改用 InvalidOperationException 類別。切勿將 InvalidOperationException 類別的實例包裝為 [System::SmartPtr](./smartptr/)。 |
| [Details_InvalidProgramException](./details_invalidprogramexception/) | InvalidProgramException 僅為相容性原因而保留。切勿手動建立此類別的實例。請改用 InvalidProgramException 類別。切勿將 InvalidProgramException 類別的實例包裝為 [System::SmartPtr](./smartptr/)。 |
| [Details_InvalidTimeZoneException](./details_invalidtimezoneexception/) | 當時區資訊無效時，會拋出 InvalidTimeZoneException。切勿手動建立此類別的實例。請改用 InvalidTimeZoneException 類別。切勿將 InvalidTimeZoneException 類別的實例包裝為 [System::SmartPtr](./smartptr/)。 |
| [Details_MemberAccessException](./details_memberaccessexception/) | 當嘗試存取不存在的類別成員或未被允許的成員時，會拋出 MemberAccessException。切勿手動建立此類別的實例。請改用 MemberAccessException 類別。切勿將 MemberAccessException 類別的實例包裝為 [System::SmartPtr](./smartptr/)。 |
| [Details_MethodAccessException](./details_methodaccessexception/) | 當嘗試存取不存在的方法或未被允許的方法時，會拋出 MethodAccessException。切勿手動建立此類別的實例。請改用 MethodAccessException 類別。切勿將 MethodAccessException 類別的實例包裝為 [System::SmartPtr](./smartptr/)。 |
| [Details_NotImplementedException](./details_notimplementedexception/) | 當呼叫尚未實作且作為存根的方法時，會拋出 NotImplementedException。切勿手動建立此類別的實例。請改用 NotImplementedException 類別。切勿將 NotImplementedException 類別的實例包裝為 [System::SmartPtr](./smartptr/)。 |
| [Details_NotSupportedException](./details_notsupportedexception/) | 當呼叫的方法不支援或對串流的操作不受支援時，會拋出 NotSupportedException。切勿手動建立此類別的實例。請改用 NotSupportedException 類別。切勿將 NotSupportedException 類別的實例包裝為 [System::SmartPtr](./smartptr/)。 |
| [Details_NullReferenceException](./details_nullreferenceexception/) | 當嘗試取消參照 null 參考時，會拋出 NullReferenceException。切勿手動建立此類別的實例。請改用 NullReferenceException 類別。切勿將 NullReferenceException 類別的實例包裝為 [System::SmartPtr](./smartptr/)。 |
| [Details_ObjectDisposedException](./details_objectdisposedexception/) | 當在已釋放的物件上呼叫方法時，會拋出 ObjectDisposedException。切勿手動建立此類別的實例。請改用 ObjectDisposedException 類別。切勿將 ObjectDisposedException 類別的實例包裝為 [System::SmartPtr](./smartptr/)。 |
| [Details_OperationCanceledException](./details_operationcanceledexception/) | 當執行緒的作業被取消時，會拋出 OperationCanceledException。切勿手動建立此類別的實例。請改用 OperationCanceledException 類別。切勿將 OperationCanceledException 類別的實例包裝為 [System::SmartPtr](./smartptr/)。 |
| [Details_OutOfMemoryException](./details_outofmemoryexception/) |  |
| [Details_OverflowException](./details_overflowexception/) | 當操作導致溢位時，會拋出 OverflowException。切勿手動建立此類別的實例。請改用 OverflowException 類別。切勿將 OverflowException 類別的實例包裝為 [System::SmartPtr](./smartptr/)。 |
| [Details_PlatformNotSupportedException](./details_platformnotsupportedexception/) | PlatformNotSupportedException 被拋出，當某個功能在特定平台上無法執行。永遠不要手動建立此類別的實例。請改用 PlatformNotSupportedException 類別。永遠不要將 PlatformNotSupportedException 類別的實例包裝成 [System::SmartPtr](./smartptr/)。 |
| [Details_RankException](./details_rankexception/) | RankException 被拋出，當傳遞給方法的陣列參數的維度數量與預期不同。永遠不要手動建立此類別的實例。請改用 RankException 類別。永遠不要將 RankException 類別的實例包裝成 [System::SmartPtr](./smartptr/)。 |
| [Details_StackOverflowException](./details_stackoverflowexception/) | StackOverflowException 被拋出，當執行緒的執行堆疊溢位時。永遠不要手動建立此類別的實例。請改用 StackOverflowException 類別。永遠不要將 StackOverflowException 類別的實例包裝成 [System::SmartPtr](./smartptr/)。 |
| [Details_SystemException](./details_systemexception/) | 此為代表系統（而非應用程式）例外的類別的基底類別。永遠不要手動建立此類別的實例。請改用 SystemException 類別。永遠不要將 SystemException 類別的實例包裝成 [System::SmartPtr](./smartptr/)。 |
| [Details_TimeoutException](./details_timeoutexception/) | TimeoutException 表示分配給程序或操作的時間已過期。永遠不要手動建立此類別的實例。請改用 TimeoutException 類別。永遠不要將 TimeoutException 類別的實例包裝成 [System::SmartPtr](./smartptr/)。 |
| [Details_TimeZoneNotFoundException](./details_timezonenotfoundexception/) | TimeZoneNotFoundException 被拋出，當找不到時區資訊時。永遠不要手動建立此類別的實例。請改用 TimeZoneNotFoundException 類別。永遠不要將 TimeZoneNotFoundException 類別的實例包裝成 [System::SmartPtr](./smartptr/)。 |
| [Details_TypeInitializationException](./details_typeinitializationexception/) |  |
| [Details_UnauthorizedAccessException](./details_unauthorizedaccessexception/) | UnauthorizedAccessException 被拋出，當作業系統因 I/O 錯誤或安全錯誤而拒絕存取時。永遠不要手動建立此類別的實例。請改用 UnauthorizedAccessException 類別。永遠不要將 UnauthorizedAccessException 類別的實例包裝成 [System::SmartPtr](./smartptr/)。 |
| [Details_UriFormatException](./details_uriformatexception/) | UriFormatException 被拋出，當 URI 的格式無效時。永遠不要手動建立此類別的實例。請改用 UriFormatException 類別。永遠不要將 UriFormatException 類別的實例包裝成 [System::SmartPtr](./smartptr/)。 |
| [DynamicWeakPtr](./dynamicweakptr/) | 智慧指標類別，用於追蹤已儲存物件之模板參數的指標模式，並在每次指派後更新它們。此型別是用來管理其他物件刪除的指標。應在堆疊上分配，並以值或 const 參考傳遞給函式。 |
| [EnumValues](./enumvalues/) | 提供關於列舉型別 **E** 之列舉常數的中繼資訊。 |
| [EnumValuesBase](./enumvaluesbase/) | 代表列舉型別之中繼資訊之類別的基底類別。 |
| [EventArgs](./eventargs/) | 此為代表在事件觸發時傳遞給事件訂閱者之情境的類別的基底類別。此類別的物件只能使用 [System::MakeObject()](./makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤或斷言失敗。必須將此類別包裝成 [System::SmartPtr](./smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [ExceptionWrapper](./exceptionwrapper/) | 此模板代表從 Exception 類別衍生的例外之包裝器。 |
| [FlagsAttribute](./flagsattribute/) | 表示此列舉可視為位元欄位；亦即，一組。 |
| [Func](./func/) | 函式委託。此型別應在堆疊上分配，並以值或參考傳遞給函式。切勿使用 [System::SmartPtr](./smartptr/) 類別來管理此型別的物件。 |
| [GC](./gc/) | 代表一個模擬的垃圾收集，其行為更像是什麼都不做的存根。這是沒有實例服務的靜態型別。無論如何都不應建立其實例。 |
| [Guid](./guid/) | 代表一個 Globally Unique IDentifier。此型別應在堆疊上分配，並以值或參考傳遞給函式。切勿使用 [System::SmartPtr](./smartptr/) 類別來管理此型別的物件。 |
| [IAsyncResult](./iasyncresult/) | 代表非同步操作的狀態。此類別的物件只能使用 [System::MakeObject()](./makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤或斷言失敗。必須將此類別包裝成 [System::SmartPtr](./smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [ICloneable](./icloneable/) | 定義一個允許物件複製 — 建立物件副本的方法。此類別的物件只能使用 [System::MakeObject()](./makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤或斷言失敗。必須將此類別包裝成 [System::SmartPtr](./smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [IComparable](./icomparable/) | 定義一個比較兩個物件的方法。此類別的物件只能使用 [System::MakeObject()](./makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤或斷言失敗。必須將此類別包裝成 [System::SmartPtr](./smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [IConvertible](./iconvertible/) | 定義將實作之參考或值型別的值轉換為具有等價值的共通語言執行階段型別的方法。此類別的物件只能使用 [System::MakeObject()](./makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤或斷言失敗。必須將此類別包裝成 [System::SmartPtr](./smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [ICustomFormatter](./icustomformatter/) | 定義對指定物件所表示之值的字串表示進行自訂格式化的方法。此類別的物件只能使用 [System::MakeObject()](./makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤或斷言失敗。必須將此類別包裝成 [System::SmartPtr](./smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [IDisposable](./idisposable/) | 定義釋放目前物件所擁有資源的方法。此類別的物件只能使用 [System::MakeObject()](./makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤或斷言失敗。必須將此類別包裝成 [System::SmartPtr](./smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [IEquatable](./iequatable/) | 定義判斷兩個物件相等性的方法。此類別的物件只能使用 [System::MakeObject()](./makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤或斷言失敗。必須將此類別包裝成 [System::SmartPtr](./smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [IFormatProvider](./iformatprovider/) | 定義提供格式資訊的方法。此類別的物件只能使用 [System::MakeObject()](./makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤或斷言失敗。必須將此類別包裝成 [System::SmartPtr](./smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [IFormattable](./iformattable/) | 定義使用指定的格式字串與格式提供者來格式化目前物件值的方法。 |
| [Index](./index/) | 代表集合中的索引。索引可以從起始位置或結尾位置計算。此型別應在堆疊上分配，並以值或參考傳遞給函式。切勿使用 [System::SmartPtr](./smartptr/) 類別來管理此型別的物件。 |
| [Int16](./int16/) | 包含用於處理 16 位元整數的方法。 |
| [Int32](./int32/) | 包含用於處理 32 位元整數的方法。 |
| [Int64](./int64/) | 包含用於處理 64 位元整數的方法。 |
| [LockContext](./lockcontext/) | 實作 C# lock() 陳述式的防護物件。 |
| [MarshalByRefObject](./marshalbyrefobject/) | 提供在啟用遠端傳遞的應用程式中跨應用程式域邊界存取物件的功能。此類別的物件只能使用 [System::MakeObject()](./makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤或斷言失敗。必須將此類別包裝成 [System::SmartPtr](./smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [MulticastDelegate< ReturnType(ArgumentTypes...)>](./multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/) | 代表委派的集合。此型別應在堆疊上分配，並以值或參考傳遞給函式。切勿使用 [System::SmartPtr](./smartptr/) 類別來管理此型別的物件。 |
| [Nullable](./nullable/) | 前向宣告。 |
| [NullableUtils](./nullableutils/) | 代表 C# [System.Nullable](./nullable/)（無型別參數）的靜態類別。因 C++ 無法重載類別模板而無法使用原始名稱。支援可指派為 null 的值型別。此類別不可被繼承。 |
| [Object](./object/) | 此為啟用在 C# 中使用 [System.Object](./object/) 類別可用方法的基底類別。所有在翻譯環境中使用的非平凡類別皆應繼承它。 |
| [ObjectExt](./objectext/) | 提供模擬 C# [Object](./object/) 方法（針對非 Object C++ 型別如字串、數字等）的靜態方法。這是一個沒有實例服務的靜態型別。無論如何都不應建立其實例。 |
| [ObjectType](./objecttype/) | 提供實作物件型別取得器的靜態方法。這是一個沒有實例服務的靜態型別。無論如何都不應建立其實例。 |
| [OperatingSystem](./operatingsystem/) | 代表特定作業系統並提供相關資訊。此類別的物件只能使用 [System::MakeObject()](./makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤或斷言失敗。必須將此類別包裝成 [System::SmartPtr](./smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [Random](./random/) | 代表一個偽隨機數產生器。此類別的物件只能使用 [System::MakeObject()](./makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤或斷言失敗。必須將此類別包裝成 [System::SmartPtr](./smartptr/) 指標，並使用該指標作為參數傳遞給函式。 |
| [Range](./range/) | 代表具有起始與結束索引的範圍。此型別應在堆疊上分配，並以值或參考傳遞給函式。切勿使用 [System::SmartPtr](./smartptr/) 類別來管理此型別的物件。 |
| [ReadOnlySpan](./readonlyspan/) | 前向宣告以在 [Span](./span/) 類別中使用。 |
| [ScopedCulture](./scopedculture/) | 代表在此範圍內使用的文化。 |
| [SmartPtr](./smartptr/) | 用於包裹在堆上分配的類型的指標類別。用它來管理繼承 [Object](./object/) 的類別的記憶體。此指標類型遵循侵入式指標語意。參考計數器要麼儲存在 [Object](./object/) 本身，要麼儲存在與 [Object](./object/) 實例緊密相連的計數結構中。無論如何，所有 [SmartPtr](./smartptr/) 實例都會形成單一擁有權群組，與 std::shared_ptr 類別的行為不同。只要有其他 [SmartPtr](./smartptr/) 實例持有相同物件的共享參考，將原始指標轉換為 [SmartPtr](./smartptr/) 是安全的。[SmartPtr](./smartptr/) 類別實例可以處於兩種狀態之一：共享指標與弱指標。為了保持物件存活，應確保對它的共享參考計數為正。弱指標與共享指標皆可用來存取指向的物件（呼叫方法、讀寫欄位等），但弱指標不參與共享指標的參考計數。當最後一個指向它的「共享」[SmartPtr](./smartptr/) 指標被銷毀時，[Object](./object/) 會被刪除。因此，請確保在不存在其他共享 [SmartPtr](./smartptr/) 指標指向該物件時（例如物件建構或銷毀期間）不會發生此情況。使用 System::Object::ThisProtector 哨兵物件（於 C++ 程式碼中）或 CppCTORSelfReference、CppSelfReference 屬性（於 C# 程式碼中）來解決此問題。同樣地，請使用 [System::WeakPtr](./weakptr/) 指標類別或 [System::SmartPtrMode::Weak](./smartptrmode/) 指標模式（於 C++ 程式碼中）或 CppWeakPtr 屬性（於 C# 程式碼中）來斷開循環參考。若兩個或以上物件使用「共享」指標相互參考，它們將永遠不會被刪除。若要在執行時切換指標類型（弱或共享），請使用 [System::SmartPtr<T>::set_Mode()](./smartptr/set_mode/) 方法或 [System::DynamicWeakPtr](./dynamicweakptr/) 類別。[SmartPtr](./smartptr/) 類別不包含任何虛擬方法，只有在自行建立記憶體管理策略時才應繼承它。此類型是用於管理其他物件刪除的指標。它應該在堆疊上分配，並以值或 const 參考傳遞給函式。 |
| [SmartPtrInfo](./smartptrinfo/) | 用於測試與修改 [SmartPtr](./smartptr/) 內容的服務類別，無需了解最終類型。用於垃圾回收與循環參考偵測等。可視為「指向指標」的概念。我們無法使用 [SmartPtr](./smartptr/) 的基本類型，因為它沒有；因此改用此「info」類別。 |
| [Span](./span/) | 表示一塊任意記憶體的連續區域，類似於 C++20 的 std::span。 |
| [String](./string/) | [String](./string/) 類別在整個函式庫中使用。於翻譯程式碼時，作為 C# [System.String](./string/) 的替代品。出於最佳化考量，它不被視為 [Object](./object/) 的子類別。此類型應在堆疊上分配，並以值或參考傳遞給函式。切勿使用 [System::SmartPtr](./smartptr/) 類別來管理此類型的物件。 |
| [StringComparer](./stringcomparer/) | 使用不同的比較模式來比較字串。此類別的物件只能透過 [System::MakeObject()](./makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，否則會導致執行時錯誤或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](./smartptr/) 指標，並以該指標作為參數傳遞給函式。 |
| [StringHashCompiletime](./stringhashcompiletime/) | 從 C 字串產生雜湊值的輔助類別。 |
| [TimeSpan](./timespan/) | 表示一段時間間隔。此類型應在堆疊上分配，並以值或參考傳遞給函式。切勿使用 [System::SmartPtr](./smartptr/) 類別來管理此類型的物件。 |
| [TimeZone](./timezone/) | 表示一個時區。此類別的物件只能透過 [System::MakeObject()](./makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，否則會導致執行時錯誤或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](./smartptr/) 指標，並以該指標作為參數傳遞給函式。 |
| [TimeZoneInfo](./timezoneinfo/) | 表示描述特定時區的資訊。此類別的物件只能透過 [System::MakeObject()](./makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，否則會導致執行時錯誤或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](./smartptr/) 指標，並以該指標作為參數傳遞給函式。 |
| [Tuple](./tuple/) | 表示 tuple 資料結構的類別，最多 8 個項目。 |
| [TupleFactory](./tuplefactory/) | 提供用於建立 tuple 物件的靜態方法。 |
| [TypeInfo](./typeinfo/) | 表示特定類型並提供相關資訊。 |
| [Uri](./uri/) | 統一資源標識符。此類別的物件只能透過 [System::MakeObject()](./makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，否則會導致執行時錯誤或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](./smartptr/) 指標，並以該指標作為參數傳遞給函式。 |
| [UriBuilder](./uribuilder/) | 提供建構與修改通用資源標識符 (URI) 的方法。此類別的物件只能透過 [System::MakeObject()](./makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，否則會導致執行時錯誤或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](./smartptr/) 指標，並以該指標作為參數傳遞給函式。 |
| [UriParser](./uriparser/) | 用於解析新 URI 協議的類別。此類別的物件只能透過 [System::MakeObject()](./makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，否則會導致執行時錯誤或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](./smartptr/) 指標，並以該指標作為參數傳遞給函式。 |
| [UriShim](./urishim/) | 服務類別。 |
| [ValueTuple](./valuetuple/) | 表示 [ValueTuple](./valuetuple/) 資料結構的類別。 |
| [ValueType](./valuetype/) | 因效能考量，作為具有 [Object](./object/) 繼承且被截斷的值類型的基類。此類型應在堆疊上分配，並以值或參考傳遞給函式。切勿使用 [System::SmartPtr](./smartptr/) 類別來管理此類型的物件。 |
| [Version](./version/) | 表示版本號。此類型應在堆疊上分配，並以值或參考傳遞給函式。切勿使用 [System::SmartPtr](./smartptr/) 類別來管理此類型的物件。 |
| [Void](./void/) |  |
| [WeakPtr](./weakptr/) | [System::SmartPtr](./smartptr/) 的子類別，於建構時設定為弱模式。請注意，因為仍可存取 [set_Mode()](./smartptr/set_mode/)，此類別無法保證其實例始終保持在弱模式。此類型是用於管理其他物件刪除的指標。它應該在堆疊上分配，並以值或 const 參考傳遞給函式。 |
| [WeakReference< T >](./weakreference_tmpl_t__end_tmpl/) | 表示弱參考，會參考物件但仍允許該物件被刪除。 |
| [WeakReference<>](./weakreference_tmpl_end_tmpl/) | 表示弱參考，會參考物件但仍允許該物件被刪除。 |

## 結構

| 結構 | 說明 |
| --- | --- |
| [CastResult](./castresult/) | 用於推導轉型結果的模板技巧。 |
| [CollectionAssertHelper](./collectionasserthelper/) | 用於集合相關操作的輔助 API。 |
| [Convert](./convert/) | 包含執行不同類型值轉換方法的結構。此類型應在堆疊上分配，並以值或參考傳遞給函式。切勿使用 [System::SmartPtr](./smartptr/) 類別來管理此類型的物件。 |
| [Double](./double/) | 包含處理雙精度浮點數的方法。 |
| [Enum](./enum/) | 提供對列舉類型值執行某些操作的方法。這是一個沒有實例服務的靜態類型，切不可以任何方式建立其實例。 |
| [EnumGetNameHelper](./enumgetnamehelper/) | 提供取得列舉常數字串名稱功能的輔助類別。 |
| [EnumParseHelper](./enumparsehelper/) | 提供將列舉字串表示轉換為相應列舉值功能的輔助類別。 |
| [Environment](./environment/) | [Environment](./environment/) 服務。這是一個沒有實例服務的靜態類型，切不可以任何方式建立其實例。 |
| [HolderInitializer](./holderinitializer/) | 此類別用於取得物件實例的持久參考，無論是左值還是右值。要取得此類參考，使用 'HoldIfTemporary' 方法，該方法有三個重載。其中兩個接受右值作為參數，僅返回該右值的參考。第三個相反，接受左值作為參數，建立指標副本，然後返回該副本的參考。此外，類別具有 'Hold' 方法，可無條件持有傳入的值（用於複製本地堆疊變數或其子參考的值）。 |
| [HolderInitializer< T, false >](./holderinitializer_tmpl_t__false__end_tmpl/) | [HolderInitializer](./holderinitializer/) 在 T 為值類型時的特化。使用情境允許返回對暫時物件的參考，因為保證呼叫方會複製該實例。因此，此特化僅作為存根使用，什麼也不做。 |
| [IsBoxable](./isboxable/) | 檢查指定類型是否支援裝箱的模板謂詞。 |
| [IsExceptionWrapper](./isexceptionwrapper/) | 判斷指定類型是否為 Exception 類別或其衍生類別的模板謂詞。 |
| [IsNullable](./isnullable/) | 判斷其模板參數 T 是否屬於 [Nullable](./nullable/) 或其子類別的模板謂詞。 |
| [IsSmartPtr](./issmartptr/) | 用於檢查類型是否為 [SmartPtr](./smartptr/) 類別的特化的特徵類別。 |
| [IsStringByteSequence](./isstringbytesequence/) | 用於檢查類型是否為字串字符序列的模板技巧。 |
| [IsStringLiteral](./isstringliteral/) | 用於檢查類型是否為字串常量的模板技巧。 |
| [IsStringPointer](./isstringpointer/) | 用於檢查類型是否為字元字串指標的模板技巧。 |
| [IsWeakPtr](./isweakptr/) | 檢查特定類別是否為 [System::WeakPtr](./weakptr/) 的特化的特徵類別。不檢查實例是否實際處於弱模式。 |
| [MakeConstRef](./makeconstref/) | 如果類型是 [String](./string/) 或 SmartPtr<>，則將通用類型轉為「const 參考」的特徵。 |
| [Math](./math/) | 包含數學函式。這是一個沒有實例服務的靜態類型，切不可以任何方式建立其實例。 |
| [MathF](./mathf/) | 包含單精度浮點值的數學函式。這是一個沒有實例服務的靜態類型，切不可以任何方式建立其實例。 |
| [MethodArgumentTuple< R(*)(Args...)>](./methodargumenttuple_tmpl_r_lbrace__star_rbrace__lbrace_args_dots_rbrace__end_tmpl/) | 定義用於存放方法參數的 tuple。 |
| [MethodArgumentTuple< R(C::*)(Args...) const >](./methodargumenttuple_tmpl_r_lbrace_c__star_rbrace__lbrace_args_dots_rbrace__const__end_tmpl/) | 定義用於存放方法參數的 tuple。 |
| [MethodArgumentTuple< R(C::*)(Args...)>](./methodargumenttuple_tmpl_r_lbrace_c__star_rbrace__lbrace_args_dots_rbrace__end_tmpl/) | 定義用於存放方法參數的 tuple。 |
| [MulticastDelegateTypeInfo](./multicastdelegatetypeinfo/) | 表示指向包含 MulticastDelegate 類別資訊的 [TypeInfo](./typeinfo/) 物件的指標。 |
| [RemoveShared](./removeshared/) | 用於從參數類型移除 SharedPtr/WeakPtr 的特徵結構。 |
| [SByte](./sbyte/) | 包含處理 8 位元整數的方法。 |
| [ScopeGuard](./scopeguard/) | 在類別實例超出範圍時執行特定函式物件的服務類別。 |
| [Single](./single/) | 包含處理單精度浮點數的方法。 |
| [TestCompare](./testcompare/) | 提供比較集合介面的服務結構。 |
| [TestTools](./testtools/) | 提供一套檢查不同類型與函式之基本屬性的有用方法。 |
| [TestToolsExt](./testtoolsext/) | 供測試翻譯使用的共用函式。 |
| [TypeInfoPtr](./typeinfoptr/) | [TypeInfo](./typeinfo/) 類別實例指標的包裝器。此類型應在堆疊上分配，並以值或參考傳遞給函式。切勿使用 [System::SmartPtr](./smartptr/) 類別來管理此類型的物件。 |
| [UInt16](./uint16/) | 包含處理未簽名 16 位元整數的方法。 |
| [UInt32](./uint32/) | 包含處理未簽名 32 位元整數的方法。 |
| [UInt64](./uint64/) | 包含處理未簽名 64 位元整數的方法。 |
| [ValueTupleTypeInfo](./valuetupletypeinfo/) | 表示指向包含 [ValueTuple](./valuetuple/) 類別資訊的 [TypeInfo](./typeinfo/) 物件的指標。 |
| [WeakPtrFromTypeParameter](./weakptrfromtypeparameter/) | 將參數類型轉換為弱指標的特徵結構（如果它是指標類型）。 |

## 函式

| Function | Description |
| --- | --- |
| [ArrayPtr](./arrayptr/)\<T\> [MakeArray](./makearray/)(std::initializer_list\<T\>) | 建構新 [Array](./array/) 物件、以指定初始化清單的元素填充，並回傳指向 [Array](./array/) 物件的智慧指標的工廠函式。 |
| [ArrayPtr](./arrayptr/)\<T\> [MakeArray](./makearray/)(Args\&&...) | 建構新 [Array](./array/) 物件，將指定參數傳遞給其建構子的工廠函式。 |
| std::enable_if\<std::is_integral\<Integral\>::value, [ArrayPtr](./arrayptr/)\<T\>\>::type [MakeArray](./makearray/)(Integral, Args\&&...) | 一個工廠函式，根據指定的參數呼叫其建構函式以建立新的 [Array](./array/) 物件。 |
| **bool** [operator==](./operator_equal_equal/)([ArraySegment](./arraysegment/)\<T\>, [ArraySegment](./arraysegment/)\<T\>) |  |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, [DateTime](./datetime/)) |  |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) |  |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | 判斷指定的 [Nullable](./nullable/) 物件是否表示等於 null 的值。 |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | 判斷指定的值是否透過應用 [operator==()](./operator_equal_equal/)，等於由指定的 [Nullable](./nullable/) 物件所表示的值。 |
| **bool** [operator==](./operator_equal_equal/)(const [SmartPtr](./smartptr/)\<X\>\&, const [SmartPtr](./smartptr/)\<Y\>\&) | 比較兩個智能指標是否相等。 |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, [SmartPtr](./smartptr/)\<X\> const\&) | 檢查智能指標是否為 null。 |
| std::enable_if\<std::is_base_of\<[Object](./object/), Y\>::value\&&detail::has_no_operator_equal\<X, Y\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const [SmartPtr](./smartptr/)\<X\>\&, const Y *) | 將智能指標與一般 (C) 指標進行相等比較。 |
| std::enable_if\<std::is_base_of\<[Object](./object/), X\>::value\&&detail::has_no_operator_equal\<X, Y\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const X *, const [SmartPtr](./smartptr/)\<Y\>\&) | 將智能指標與一般 (C) 指標進行相等比較。 |
| std::enable_if<\!std::is_scalar\<T\>::value\&&\!std::is_pointer\<T\>::value\&&\!std::is_array\<T\>::value\&&detail::has_method_is_null\<T\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(T const\&, std::nullptr_t) | 檢查值類型物件（翻譯自 C# 結構等）是否為 null。 |
| std::enable_if<\!std::is_scalar\<T\>::value\&&\!std::is_pointer\<T\>::value\&&\!std::is_array\<T\>::value\&&detail::has_method_is_null\<T\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(std::nullptr_t, T const\&) | 檢查值類型物件（翻譯自 C# 結構等）是否為 null。 |
| **bool** [operator==](./operator_equal_equal/)(Chars\&, const [String](./string/)\&) | [String](./string/) 比較。 |
| **bool** [operator==](./operator_equal_equal/)(T\&, const [String](./string/)\&) | [String](./string/) 比較。 |
| **bool** [operator==](./operator_equal_equal/)(const [SharedPtr](./sharedptr/)\<[Object](./object/)\>\&, const [String](./string/)\&) | [Object](./object/) 以及字串比較。 |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, const [String](./string/)\&) | 檢查字串是否為 null。 |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, [TimeSpan](./timespan/)) |  |
| **bool** [operator==](./operator_equal_equal/)(const [SharedPtr](./sharedptr/)\<[Uri](./uri/)\>\&, const [SharedPtr](./sharedptr/)\<[Uri](./uri/)\>\&) | 判斷目前與指定物件所表示的 URI 是否相等。 |
| **bool** [operator!=](./operator_not_equal/)([ArraySegment](./arraysegment/)\<T\>, [ArraySegment](./arraysegment/)\<T\>) |  |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, [DateTime](./datetime/)) |  |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) |  |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | 判斷指定的 [Nullable](./nullable/) 物件是否表示不等於 null 的值。 |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | 判斷指定的值是否透過應用 [operator!=()](./operator_not_equal/)，不等於由指定的 [Nullable](./nullable/) 物件所表示的值。 |
| **bool** [operator!=](./operator_not_equal/)(const [SmartPtr](./smartptr/)\<X\>\&, const [SmartPtr](./smartptr/)\<Y\>\&) | 比較兩個智能指標是否不相等。 |
| **bool** [operator!=](./operator_not_equal/)([SmartPtr](./smartptr/)\<X\> const\&, std::nullptr_t) | 檢查智能指標是否不為 null。 |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, [SmartPtr](./smartptr/)\<X\> const\&) | 檢查智能指標是否不為 null。 |
| std::enable_if\<std::is_base_of\<[Object](./object/), Y\>::value\&&detail::has_no_operator_equal\<X, Y\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const [SmartPtr](./smartptr/)\<X\>\&, const Y *) | 將智能指標與一般 (C) 指標進行不等比較。 |
| std::enable_if\<std::is_base_of\<[Object](./object/), X\>::value\&&detail::has_no_operator_equal\<X, Y\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const X *, const [SmartPtr](./smartptr/)\<Y\>\&) | 將智能指標與一般 (C) 指標進行相等比較。 |
| **bool** [operator!=](./operator_not_equal/)(Chars\&, const [String](./string/)\&) | [String](./string/) 比較。 |
| **bool** [operator!=](./operator_not_equal/)(T\&, const [String](./string/)\&) | [String](./string/) 比較。 |
| **bool** [operator!=](./operator_not_equal/)(const [SharedPtr](./sharedptr/)\<[Object](./object/)\>\&, const [String](./string/)\&) | [Object](./object/) 以及字串比較。 |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, const [String](./string/)\&) | 檢查字串是否為 null。 |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, [TimeSpan](./timespan/)) |  |
| **bool** [operator!=](./operator_not_equal/)(const [SharedPtr](./sharedptr/)\<[Uri](./uri/)\>\&, const [SharedPtr](./sharedptr/)\<[Uri](./uri/)\>\&) | 判斷目前與指定物件所表示的 URI 是否不相等。 |
| static **bool** [IsEnumMetaInfoDefined](./isenummetainfodefined/)(T) |  |
| static **bool** [IsEnumMetaInfoDefined](./isenummetainfodefined/)(T) |  |
| static [System::String](./string/) [EnumGetName](./enumgetname/)(T) |  |
| static [System::String](./string/) [EnumGetName](./enumgetname/)(T) |  |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t, [DateTime](./datetime/)) |  |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) |  |
| **bool** [operator<](./operator_less/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | 永遠回傳 false。 |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator<](./operator_less/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | 判斷指定的值是否透過應用 [operator<()](./operator_less/)，小於由指定的 [Nullable](./nullable/) 物件所表示的值。 |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t, [TimeSpan](./timespan/)) |  |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t, [DateTime](./datetime/)) |  |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) |  |
| **bool** [operator<=](./operator_less_equal/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | 永遠回傳 false。 |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator<=](./operator_less_equal/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | 判斷指定的值是否透過應用 [operator<=()](./operator_less_equal/)，小於或等於由指定的 [Nullable](./nullable/) 物件所表示的值。 |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t, [TimeSpan](./timespan/)) |  |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t, [DateTime](./datetime/)) |  |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) |  |
| **bool** [operator>](./operator_greater/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | 永遠回傳 false。 |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator>](./operator_greater/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | 判斷指定的值是否透過應用 [operator>()](./operator_greater/)，大於由指定的 [Nullable](./nullable/) 物件所表示的值。 |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t, [TimeSpan](./timespan/)) |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t, [DateTime](./datetime/)) |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) |  |
| **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | 永遠回傳 false。 |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator>=](./operator_greater_equal/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | 判斷指定的值是否透過應用 [operator>=()](./operator_greater_equal/)，大於或等於由指定的 [Nullable](./nullable/) 物件所表示的值。 |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t, [TimeSpan](./timespan/)) |  |
| void [PrintTo](./printto/)([DateTime](./datetime/), std::ostream *) | 將值列印至 ostream。主要用於除錯。 |
| void [PrintTo](./printto/)([DateTimeOffset](./datetimeoffset/), std::ostream *) | 將值列印至 ostream。主要用於除錯。 |
| void [PrintTo](./printto/)(const [Decimal](./decimal/)\&, ::std::ostream *) | 將指定物件所代表的值寫入指定的輸出串流。 |
| void [PrintTo](./printto/)(const [Details_Exception](./details_exception/)\&, std::ostream *) | 將值列印至 ostream。主要用於除錯。 |
| void [PrintTo](./printto/)(const [ExceptionWrapper](./exceptionwrapper/)\<T\>\&, std::ostream *) | 將值列印至 ostream。主要用於除錯。 |
| void [PrintTo](./printto/)(const [Guid](./guid/)\&, std::ostream *) | 將值列印至 ostream。主要用於除錯。 |
| void [PrintTo](./printto/)(const [Nullable](./nullable/)\<T\>\&, std::ostream *) | 將值列印至 ostream。主要用於除錯。 |
| void [PrintTo](./printto/)(const [System::Object](./object/)\&, std::ostream *) | 將值列印至 ostream。主要用於除錯。 |
| std::enable_if_t\<detail::has_print_to_function\<T\>::value, void\> [PrintTo](./printto/)(const [SmartPtr](./smartptr/)\<T\>\&, std::ostream *) | 將值列印至 ostream。主要用於除錯。 |
| std::enable_if_t<\!detail::has_print_to_function\<T\>::value, void\> [PrintTo](./printto/)(const [SmartPtr](./smartptr/)\<T\>\&, std::ostream *) | 將值列印至 ostream。主要用於除錯。 |
| void [PrintTo](./printto/)(const [System::String](./string/)\&, std::ostream *) | 將字串列印至 ostream。主要用於除錯。 |
| void [PrintTo](./printto/)([TimeSpan](./timespan/), std::ostream *) | 將值列印至 ostream。主要用於除錯。 |
| void [PrintTo](./printto/)(const [WeakPtr](./weakptr/)\<T\>\&, std::ostream *) | 將值列印至 ostream。主要用於除錯。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, [DateTime](./datetime/)) | 使用 UTF-8 編碼將資料插入串流。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, [DateTime](./datetime/)) | 將資料插入串流。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, [DateTimeOffset](./datetimeoffset/)) | 使用 UTF-8 編碼將資料插入串流。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, [DateTimeOffset](./datetimeoffset/)) | 將資料插入串流。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Decimal](./decimal/)\&) | 使用 UTF-8 編碼將資料插入串流。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Decimal](./decimal/)\&) | 將資料插入串流。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Exception](./exception/)\&) | 使用 UTF-8 編碼將資料插入串流。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Exception](./exception/)\&) | 將資料插入串流。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Guid](./guid/)\&) | 使用 UTF-8 編碼將資料插入串流。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Guid](./guid/)\&) | 將資料插入串流。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Nullable](./nullable/)\<T\>\&) | 使用 UTF-8 編碼將資料插入串流。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Nullable](./nullable/)\<T\>\&) | 將資料插入串流。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [System::Object](./object/)\&) | 使用 UTF-8 編碼將資料插入串流。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [System::Object](./object/)\&) | 將資料插入串流。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [OperatingSystem](./operatingsystem/)\&) | 使用 UTF-8 編碼將資料插入串流。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [OperatingSystem](./operatingsystem/)\&) | 將資料插入串流。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [SharedPtr](./sharedptr/)\<T\>\&) | 使用 UTF-8 編碼將資料插入串流。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [SharedPtr](./sharedptr/)\<T\>\&) | 將資料插入串流。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [String](./string/)\&) | 使用 UTF-8 編碼將字串輸出至輸出串流。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [String](./string/)\&) | 將字串輸出至輸出串流。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, [TimeSpan](./timespan/)) | 使用 UTF-8 編碼將資料插入串流。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, [TimeSpan](./timespan/)) | 將資料插入串流。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [TypeInfo](./typeinfo/)\&) | 使用 UTF-8 編碼將資料插入串流。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [TypeInfo](./typeinfo/)\&) | 將資料插入串流。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Version](./version/)\&) | 使用 UTF-8 編碼將資料插入串流。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Version](./version/)\&) | 將資料插入串流。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [WeakPtr](./weakptr/)\<T\>\&) | 使用 UTF-8 編碼將資料插入串流。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [WeakPtr](./weakptr/)\<T\>\&) | 將資料插入串流。 |
| auto [operator-](./operator_minus/)([DayOfWeek](./dayofweek/), [DayOfWeek](./dayofweek/)) | 計算兩個星期天之間的天數。 |
| [Decimal](./decimal/) [operator-](./operator_minus/)(const T\&, const [Decimal](./decimal/)\&) | 傳回一個新的 [Decimal](./decimal/) 類別實例，該實例表示從指定值減去由指定的 [Decimal](./decimal/) 物件所表示的值後的結果。 |
| MulticastDelegate\<T\> [operator-](./operator_minus/)(MulticastDelegate\<T\>, MulticastDelegate\<T\>) | 從左側委派的回呼清單末端斷開右側委派的所有回呼。 |
| auto [operator-](./operator_minus/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | 減去非空值與可空值。 |
| [Decimal](./decimal/) [operator+](./operator_plus/)(const T\&, const [Decimal](./decimal/)\&) | 傳回一個新的 [Decimal](./decimal/) 類別實例，該實例表示指定值與指定 [Decimal](./decimal/) 物件所代表的值之總和。 |
| MulticastDelegate\<T\> [operator+](./operator_plus/)(MulticastDelegate\<T\>, MulticastDelegate\<T\>) | 將右側委派的所有回呼連接至左側委派回呼列表的末端。 |
| auto [operator+](./operator_plus/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | 加總非空值與可空值。 |
| std::enable_if\<[IsStringLiteral](./isstringliteral/)\<T, char_t\>::value, [String](./string/)\>::type [operator+](./operator_plus/)(T\&, const [String](./string/)\&) | [String](./string/) 串接。 |
| std::enable_if\<[IsStringPointer](./isstringpointer/)\<T, char_t\>::value, [String](./string/)\>::type [operator+](./operator_plus/)(T\&, const [String](./string/)\&) | [String](./string/) 串接。 |
| [String](./string/) [operator+](./operator_plus/)(const char_t, const [String](./string/)\&) | [String](./string/) 串接。 |
| [Decimal](./decimal/) [operator*](./operator_star/)(const T\&, const [Decimal](./decimal/)\&) | 傳回一個新的 [Decimal](./decimal/) 類別實例，該實例表示指定值與指定 [Decimal](./decimal/) 物件所代表的值之乘積。 |
| [Decimal](./decimal/) [operator/](./operator_div/)(const T\&, const [Decimal](./decimal/)\&) | 傳回一個新的 [Decimal](./decimal/) 類別實例，該實例表示指定值與指定 [Decimal](./decimal/) 物件所代表的值之除法結果。 |
| std::enable_if\<[IsExceptionWrapper](./isexceptionwrapper/)\<T\>::value, constT\&\>::type [Default](./default/)() | 傳回例外類型唯一預設建構的實例參考。 |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<T\>::value, constT\&\>::type [Default](./default/)() | 傳回非例外類型唯一預設建構的實例參考。 |
| T\& [Discard](./discard/)(T\&&) | 傳回指定型別的預設建構暫時實例，可用於取代拋棄 '_' 參數的位置。 |
| Details::ObjectBuilder\<T, [SharedPtr](./sharedptr/)\<T\>\> [BuildObject](./buildobject/)(Args\&&...) | 以共享所有權建構物件。 |
| Details::ObjectBuilder\<T, [SharedPtr](./sharedptr/)\<T\>\> [InitObject](./initobject/)(const [SharedPtr](./sharedptr/)\<T\>\&) | 開始以共享所有權初始化物件。 |
| Details::ObjectBuilder\<Details::ArrayStorage\<T\>\> [BuildArray](./buildarray/)() | 建構陣列。 |
| Details::ObjectBuilder\<T\> [Build](./build/)(Args\&&...) | 以直接所有權建構物件。 |
| **bool** [Is](./is/)(const ExpressionT\&, ResultT\&) | 實作「is」宣告模式的轉譯。 |
| std::enable_if_t<\!std::is_base_of\<Details::Pattern, ConstantT\>::value, **bool**\> [Is](./is/)(const ExpressionT\&, const ConstantT\&) | 實作「is」常量模式的轉譯。 |
| std::enable_if_t\<std::is_base_of\<Details::Pattern, A\>::value, **bool**\> [Is](./is/)(const E\&, const A\&) | 頂層匹配函式。將模式套用至值。 |
| static **bool** [IsNull](./isnull/)(const T\&) | 實作「is null」模式。 |
| **bool** [Less](./less/)(const ExpressionT\&, const ConstantT\&) | 實作「<」相對模式的轉譯。 |
| **bool** [Greater](./greater/)(const ExpressionT\&, const ConstantT\&) | 實作「>」相對模式的轉譯。 |
| **bool** [LEqual](./lequal/)(const ExpressionT\&, const ConstantT\&) |實作「<=」相對模式的轉譯。 |
| **bool** [GEqual](./gequal/)(const ExpressionT\&, const ConstantT\&) | 實作「>=」相對模式的轉譯。 |
| **bool** [Set](./set/)(ExpressionT\&, const ExpressionT\&) | 實作「var」模式的轉譯。 |
| **bool** [IsTuple](./istuple/)(const [SharedPtr](./sharedptr/)\<[Object](./object/)\>\&, **int32_t**) | 檢查物件是否為 tuple（實作 ITuple 介面）。用於位置模式的實作。 |
| auto [Get](./get/)(const [SharedPtr](./sharedptr/)\<[Object](./object/)\>\&) | 取得給定 tuple 第 N 個元素的函式。基礎物件的重載。 |
| auto [Get](./get/)(const T\&) | 取得給定 tuple 第 N 個元素的函式。對有 Deconstruct 方法之物件的重載。 |
| auto [Get](./get/)(const [SharedPtr](./sharedptr/)\<T\>\&) | 取得給定 tuple 第 N 個元素的函式。對共享指標的重載。 |
| auto\& [Get](./get/)(T\&, const [Index](./index/)\&) | collection[index] 表達式的實作。 |
| auto [Get](./get/)(T\&, const [Range](./range/)\&) | 傳回由提供之範圍定義的指定集合切片。 |
| auto [Get](./get/)(const [ValueTuple](./valuetuple/)\<Args...\>\&) | 取得值 tuple 的第 N 個元素。 |
| [SharedPtr](./sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<T\>\> [MakeYieldEnumerable](./makeyieldenumerable/)(const Details::YieldFunction\<T\>\&) | 從 yield 函式建立 IEnumerable。 |
| [SharedPtr](./sharedptr/)\<[Collections::Generic::IEnumerator](../system.collections.generic/ienumerator/)\<T\>\> [MakeYieldEnumerator](./makeyieldenumerator/)(const Details::YieldFunction\<T\>\&) | 從 yield 函式建立 IEnumerator。 |
| std::enable_if_t\<Details::is_lambda_void_void\<T\>::value\> [DoTryFinally](./dotryfinally/)(T\&&, F\&&) | 模擬 C# 的 try[-catch]-finally 陳述式行為的單一函式。在使用翻譯器選項 finally_statement_as_lambda 設為 true 時，C# 的 try[-catch]-finally 陳述式會被轉譯為呼叫此方法。 |
| std::enable_if_t\<Details::is_lambda_void_boolref\<T\>::value, **bool**\> [DoTryFinally](./dotryfinally/)(T\&&, F\&&) | 模擬 C# 的 try[-catch]-finally 陳述式行為的單一函式。在使用翻譯器選項 finally_statement_as_lambda 設為 true 時，C# 的 try[-catch]-finally 陳述式會被轉譯為呼叫此方法。此重載處理返回值為 bool 的情況。 |
| std::enable_if_t\<Details::is_lambda_nonovoid_boolref\<T\>::value, std::optional\<Details::ResultOf\<T, **bool**\&\>\>\> [DoTryFinally](./dotryfinally/)(T\&&, F\&&) | 模擬 C# 的 try[-catch]-finally 陳述式行為的單一函式。在使用翻譯器選項 finally_statement_as_lambda 設為 true 時，C# 的 try[-catch]-finally 陳述式會被轉譯為呼叫此方法。此重載處理返回值為 bool& 的情況。 |
| [DynamicWeakPtr](./dynamicweakptr/)\<T, trunkMode, weakLeafs...\>::Reference [Ref](./ref/)([DynamicWeakPtr](./dynamicweakptr/)\<T, trunkMode, weakLeafs...\>\&) | 建立對 [DynamicWeakPtr](./dynamicweakptr/) 物件的參考。翻譯器在以參考方式傳遞函式參數時使用。 |
| T\& [Ref](./ref/)(T\&) | 協助函式，用於取得物件的參考。用以確保 [System::DynamicWeakPtr](./dynamicweakptr/) 在賦值後更新被參考的物件。 |
| std::enable_if_t<\!Details::IsIterable\<Enumerable\>::value, Details::EnumeratorAdapter\<Enumerable, T\>\> [IterateOver](./iterateover/)([System::SmartPtr](./smartptr/)\<Enumerable\>) | 此函式屬性將可列舉（或可迭代）物件包裝，使其可用於基於範圍的 for 迴圈。此重載針對沒有 begin()、end() 方法的 Enumerable，並提供目標型別參數，以供 (auto& value : IterateOver<SomeType>(enumerable)) 使用。 |
| std::enable_if_t<\!Details::IsIterable\<Enumerable\>::value, Details::EnumeratorAdapter\<Enumerable\>\> [IterateOver](./iterateover/)([System::SmartPtr](./smartptr/)\<Enumerable\>) | 此函式屬性將可列舉（或可迭代）物件包裝，使其可用於基於範圍的 for 迴圈。此重載針對沒有 begin()、end() 方法的 Enumerable，使用預設目標型別參數，以供 (auto& value : IterateOver(enumerable)) 使用，類似以下 C# 程式碼 foreach (var value in enumerable)。 |
| std::enable_if_t\<Details::IsIterable\<Enumerable\>::value, [System::SmartPtr](./smartptr/)\<Enumerable\>\> [IterateOver](./iterateover/)([System::SmartPtr](./smartptr/)\<Enumerable\>) | 此函式屬性將可列舉（或可迭代）物件包裝，使其可用於基於範圍的 for 迴圈。此重載針對具有 begin()、end() 方法的 Enumerable，使用預設目標型別參數，以供 (auto& value : IterateOver(enumerable)) 使用。 |
| std::enable_if_t\<Details::IsIterable\<Enumerable\>::value\&&std::is_same\<typename Details::ReturnTypeTrait\<T\>::ReturnType, Details::IterableValueType\<Enumerable\>\>::value, [System::SmartPtr](./smartptr/)\<Enumerable\>\> [IterateOver](./iterateover/)([System::SmartPtr](./smartptr/)\<Enumerable\>) | 此函式屬性將可列舉（或可迭代）物件包裝，使其可用於基於範圍的 for 迴圈。此重載針對具有 begin()、end() 方法的 Enumerable，目標型別與迭代器的原始 value_type 相同。 |
| std::enable_if_t\<Details::IsIterable\<Enumerable\>::value\&&\!std::is_same\<typename Details::ReturnTypeTrait\<T\>::ReturnType, Details::IterableValueType\<Enumerable\>\>::value, Details::CppIteratorAdapter\<Enumerable, T\>\> [IterateOver](./iterateover/)([System::SmartPtr](./smartptr/)\<Enumerable\>) | 此函式屬性將可列舉（或可迭代）物件包裝，使其可用於基於範圍的 for 迴圈。此重載針對具有 begin()、end() 方法的 Enumerable，提供與原始 value_type 不同的目標型別。 |
| std::enable_if_t<\![IsSmartPtr](./issmartptr/)\<Enumerable\>::value, Details::EnumeratorAdapter\<Enumerable, Details::ValueTypeOfEnumerable\<Enumerable\>, Enumerable *\>\> [IterateOver](./iterateover/)(const Enumerable *) | 此函式屬性將可列舉（或可迭代）物件包裝，使其可用於基於範圍的 for 迴圈。此重載針對此 Enumerable，使用預設目標型別。 |
| std::enable_if_t<\![IsSmartPtr](./issmartptr/)\<Enumerable\>::value, Details::EnumeratorAdapter\<Enumerable, T, Enumerable *\>\> [IterateOver](./iterateover/)(const Enumerable *) | 此函式屬性將可列舉（或可迭代）物件包裝，使其可用於基於範圍的 for 迴圈。此重載針對沒有 begin()、end() 方法的 Enumerable，並提供目標型別參數，以供 (auto& value : IterateOver<SomeType>(enumerable)) 使用。 |
| std::enable_if\<std::is_scalar\<T\>::value, int\>::type [GetHashCode](./gethashcode/)(const T\&) | 傳回指定標量值的雜湊碼。 |
| std::enable_if<\!std::is_scalar\<T\>::value\&&[System::IsSmartPtr](./issmartptr/)\<T\>::value, int\>::type [GetHashCode](./gethashcode/)(const T\&) | 傳回指定物件的雜湊碼。 |
| std::enable_if\<[System::IsExceptionWrapper](./isexceptionwrapper/)\<T\>::value, int\>::type [GetHashCode](./gethashcode/)(const T\&) | 傳回指定例外物件的雜湊碼。 |
| std::enable_if<\!std::is_scalar\<T\>::value\&&\![System::IsSmartPtr](./issmartptr/)\<T\>::value\&&\![System::IsExceptionWrapper](./isexceptionwrapper/)\<T\>::value, int\>::type [GetHashCode](./gethashcode/)(const T\&) | 傳回指定非智慧指標且非例外的物件之雜湊碼。 |
| int [GetHashCode](./gethashcode/)(const std::thread::id\&) | 針對 std::thread::id 的特殊化；傳回指定執行緒物件的雜湊碼。 |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [Cast_noexcept](./cast_noexcept/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | 對 [SmartPtr](./smartptr/) 物件執行型別轉換。 |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [Cast](./cast/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | 對 [SmartPtr](./smartptr/) 物件執行型別轉換。 |
| std::enable_if\<[IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value\&&(std::is_convertible\<TTo, TFrom\>::value||std::is_base_of\<TTo, TFrom\>::value), TTo\>::type [DynamicCast_noexcept](./dynamiccast_noexcept/)(const TFrom\&) | 舊的已淘汰型別轉換。未來版本將移除。 |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [DynamicCast_noexcept](./dynamiccast_noexcept/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | 對 [SmartPtr](./smartptr/) 物件執行動態型別轉換。 |
| std::enable_if\<std::is_same\<[System::Object](./object/), TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, TTo\>::type [DynamicCast_noexcept](./dynamiccast_noexcept/)([SmartPtr](./smartptr/)\<TFrom\>) | 將 Objects 動態轉換為 Exception 物件。 |
| std::enable_if\<[IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value\&&(std::is_convertible\<TTo, TFrom\>::value||std::is_base_of\<TTo, TFrom\>::value), TTo\>::type [DynamicCast](./dynamiccast/)(const TFrom\&) | 對 Exception 物件執行動態型別轉換。 |
| std::enable_if<\!std::is_enum\<TTo\>::value\&&\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [DynamicCast](./dynamiccast/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | 對 [SmartPtr](./smartptr/) 物件執行動態型別轉換。 |
| std::enable_if\<std::is_enum\<TTo\>::value, TTo\>::type [DynamicCast](./dynamiccast/)([SmartPtr](./smartptr/)\<TFrom\>) | 透過型別轉換解箱已裝箱的 enum。 |
| [CastResult](./castresult/)\<TTo\>::type [DynamicCast](./dynamiccast/)(std::nullptr_t) | 對 null 物件執行動態型別轉換。 |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&\![IsSmartPtr](./issmartptr/)\<TFrom\>::value\&&std::is_convertible\<TTo, TFrom\>::value, TTo\>::type [DynamicCast](./dynamiccast/)(TFrom\&) | 對非指標物件執行動態型別轉換。 |
| std::enable_if\<std::is_same\<[System::Object](./object/), TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, TTo\>::type [DynamicCast](./dynamiccast/)([SmartPtr](./smartptr/)\<TFrom\>) | 對 Objects 執行動態轉型至 Exception 物件。 |
| std::enable_if\<std::is_pointer\<TTo\>::value\&&std::is_same\<IntPtr, TFrom\>::value, TTo\>::type [DynamicCast](./dynamiccast/)(TFrom) | 對 IntPtr 執行動態轉型為指標。 |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [StaticCast_noexcept](./staticcast_noexcept/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | 對 [SmartPtr](./smartptr/) 物件執行靜態轉型。 |
| [CastResult](./castresult/)\<TTo\>::type [StaticCast_noexcept](./staticcast_noexcept/)([WeakPtr](./weakptr/)\<TFrom\> const\&) | 對 [WeakPtr](./weakptr/) 物件執行靜態轉型。 |
| std::enable_if\<[IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value\&&(std::is_convertible\<TTo, TFrom\>::value||std::is_base_of\<TTo, TFrom\>::value), TTo\>::type [StaticCast_noexcept](./staticcast_noexcept/)(const TFrom\&) | 對 Exception 物件執行靜態轉型。 |
| std::enable_if\<std::is_same\<[System::Object](./object/), TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, TTo\>::type [StaticCast_noexcept](./staticcast_noexcept/)([SmartPtr](./smartptr/)\<TFrom\>) | 對 Objects 執行靜態轉型至 Exception 物件。 |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [StaticCast](./staticcast/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | 對 [SmartPtr](./smartptr/) 物件執行靜態轉型。 |
| [CastResult](./castresult/)\<TTo\>::type [StaticCast](./staticcast/)([WeakPtr](./weakptr/)\<TFrom\> const\&) | 對 [WeakPtr](./weakptr/) 物件執行靜態轉型。 |
| [CastResult](./castresult/)\<TTo\>::type [StaticCast](./staticcast/)(std::nullptr_t) | 對 null 物件執行靜態轉型。 |
| std::enable_if\<std::is_arithmetic\<TFrom\>::value, TTo\>::type [StaticCast](./staticcast/)(TFrom) | 算術型別的特化。 |
| std::enable_if\<std::is_same\<TTo, [System::String](./string/)\>::value, TTo\>::type [StaticCast](./staticcast/)(TTo) | 處理從 [String](./string/) 到 [String](./string/) 的轉型。 |
| std::enable_if\<std::is_arithmetic\<TFrom\>::value, TTo\>::type [StaticCast](./staticcast/)(const TFrom *) | 算術型別的特化。 |
| std::enable_if<\!std::is_same\<TFrom, [System::String](./string/)\>::value\&&\![IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&\![IsSmartPtr](./issmartptr/)\<TFrom\>::value\&&\!std::is_arithmetic\<TFrom\>::value, TTo\>::type [StaticCast](./staticcast/)(const TFrom\&) | 對非指標物件執行靜態轉型。 |
| std::enable_if\<[IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value\&&(std::is_convertible\<TTo, TFrom\>::value||std::is_base_of\<TTo, TFrom\>::value), TTo\>::type [StaticCast](./staticcast/)(const TFrom\&) | 對 Exception 物件執行靜態轉型。 |
| std::enable_if\<std::is_same\<[System::Object](./object/), TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, TTo\>::type [StaticCast](./staticcast/)([SmartPtr](./smartptr/)\<TFrom\>) | 對 Objects 執行靜態轉型至 Exception 物件。 |
| [CastResult](./castresult/)\<TTo\>::type [ConstCast](./constcast/)(const [SmartPtr](./smartptr/)\<TFrom\>\&) | 已棄用的轉型結束。 |
| [CastResult](./castresult/)\<TTo\>::type [ForceStaticCast](./forcestaticcast/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | 對 [SmartPtr](./smartptr/) 物件執行真正的靜態轉型。 |
| [SmartPtr](./smartptr/)\<[Object](./object/)\> [MemberwiseClone](./memberwiseclone/)(T *) | 使用拷貝建構函式執行逐成員克隆。 |
| [SharedPtr](./sharedptr/)\<T\> [With](./with/)(const [SharedPtr](./sharedptr/)\<T\>\&, const A\&) | 複製參考記錄並對其套用初始化函式物件。 |
| T [With](./with/)(const T\&, const A\&) | 複製結構記錄並對其套用初始化函式物件。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::None, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | 使用顯式轉型將來源型別轉為結果型別。當來源型別與結果型別相同時使用。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Static, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | 使用顯式轉型將來源型別轉為結果型別。需要簡單建構函式式轉型時使用。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>[::Exception](./exception/), Result\> [ExplicitCast](./explicitcast/)(const Source\&) | 使用顯式轉型將來源型別轉為結果型別。用於例外封裝。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::ObjectToException, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | 使用顯式轉型將來源型別轉為結果型別。用於將物件轉型為例外。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Pointer, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | 使用顯式轉型將來源型別轉為結果型別。當來源與結果都是智慧指標且結果型別未明確使用 SmartPtr<...> 時使用。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::RawPointer, typename [CastResult](./castresult/)\<std::remove_pointer_t\<Result\>\>::type\> [ExplicitCast](./explicitcast/)(Source) | 使用顯式轉型將來源型別轉為結果型別。用於將原始指標轉型為智慧指標。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::PointerToPointer, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | 使用顯式轉型將來源型別轉為結果型別。當來源與結果皆為智慧指標且結果型別明確使用 SmartPtr<...> 時使用。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::UnboxingToNullable, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | 使用顯式轉型將來源型別轉為結果型別。用於將物件解箱為可為 null 的類型。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::NullableBoxing, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | 使用顯式轉型將來源型別轉為結果型別。用於將可為 null 的類型裝箱。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::NullableUnboxing, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | 使用顯式轉型將來源型別轉為結果型別。用於解箱可為 null 的物件。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::EnumBoxing, [SmartPtr](./smartptr/)\<[BoxedValueBase](./boxedvaluebase/)\>\> [ExplicitCast](./explicitcast/)(const Source\&) | 使用顯式轉型將來源型別轉為結果型別。用於列舉裝箱。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::HeapifyBoxing, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | 使用顯式轉型將來源型別轉為結果型別。用於在需要將值型別作為智慧指標參考時，將值型別複製到堆上（用於以介面類型作為泛型限制，卻以實作該介面的結構體為具體類型的情況）。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::InterfaceBoxing, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | 使用顯式轉型將來源型別轉為結果型別。用於從值型別取得介面。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Boxing, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | 使用顯式轉型將來源型別轉為結果型別。用於一般裝箱。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::StringBoxing, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | 使用顯式轉型將來源型別轉為結果型別。用於 [System::String](./string/) 裝箱。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::InterfaceUnboxing, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | 使用顯式轉型將來源型別轉為結果型別。用於解箱介面。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Unboxing, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | 使用顯式轉型將來源型別轉為結果型別。用於一般解箱。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Null, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | 使用顯式轉型將來源型別轉為結果型別。用於 nullptr 轉型。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>**::Array**, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | 使用顯式轉型將來源型別轉為結果型別。用於陣列之間的轉型。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Static, Result\> [AsCast](./ascast/)(const Source\&) | 使用 'as' 運算子轉型將來源型別轉為結果型別。需要簡單建構函式式轉型時使用。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::None, Result\> [AsCast](./ascast/)(const Source\&) | 使用 'as' 運算子轉型將來源型別轉為結果型別。當來源與結果型別相同時使用。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>[::Exception](./exception/), Result\> [AsCast](./ascast/)(const Source\&) | 使用 'as' 運算子轉型將來源型別轉為結果型別。用於例外封裝。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::ObjectToException, Result\> [AsCast](./ascast/)(const Source\&) | 使用 'as' 運算子轉型將來源型別轉為結果型別。用於將物件轉型為例外。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Pointer, typename [CastResult](./castresult/)\<Result\>::type\> [AsCast](./ascast/)(const Source\&) | 使用 'as' 運算子轉型將來源型別轉為結果型別。當來源與結果都是智慧指標時使用。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::PointerToPointer, Result\> [AsCast](./ascast/)(const Source\&) | 使用 'as' 運算子轉型將來源型別轉為結果型別。當來源與結果皆為智慧指標且結果型別明確使用 SmartPtr<...> 時使用。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::UnboxingToNullable, Result\> [AsCast](./ascast/)(const Source\&) | 使用 'as' 運算子轉型將來源型別轉為結果型別。用於將物件解箱為可為 null 的類型。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::InterfaceUnboxingToNullable, Result\> [AsCast](./ascast/)(const Source\&) | 使用 'as' 運算子轉型將來源型別轉為結果型別。無效的解箱至非物件型別。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::InvalidUnboxing, Result\> [AsCast](./ascast/)(const Source\&) | 無效的解箱至非物件型別。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::NullableBoxing, Result\> [AsCast](./ascast/)(const Source\&) | 使用 'as' 運算子轉型將來源型別轉為結果型別。用於將可為 null 的物件裝箱。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::InterfaceBoxing, typename [CastResult](./castresult/)\<Result\>::type\> [AsCast](./ascast/)(const Source\&) | 使用 'as' 運算子轉型將來源型別轉為結果型別。用於裝箱一般物件。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Boxing, typename [CastResult](./castresult/)\<Result\>::type\> [AsCast](./ascast/)(const Source\&) | 使用 'as' 運算子轉型將來源型別轉為結果型別。用於裝箱一般物件。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::UnboxingToString, Result\> [AsCast](./ascast/)(const Source\&) | 使用 'as' 運算子轉型將來源型別轉為結果型別。用於字串解箱。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Null, typename [CastResult](./castresult/)\<Result\>::type\> [AsCast](./ascast/)(const Source\&) | 使用 'as' 運算子轉型將來源型別轉為結果型別。用於 nullptr 轉型。 |
| std::enable_if_t\<Details::CastType\<Source, Result\>**::Array**, typename [CastResult](./castresult/)\<Result\>::type\> [AsCast](./ascast/)(const Source\&) | 使用 'as' 運算子轉型將來源型別轉為結果型別。用於陣列之間的轉型。 |
| static auto [SafeInvoke](./safeinvoke/)(T0\&&, T1\&&) | 實作 '?.' 運算子翻譯。 |
| const [System::TypeInfo](./typeinfo/)\& [ObjectType::GetType< System::String >](./objecttype_dcolon_gettype_less_system_dcolon_string__greater/)() | 實作 typeof() 翻譯。[String](./string/) 的重載。 |
| const [System::TypeInfo](./typeinfo/)\& [ObjectType::GetType< System::DateTime >](./objecttype_dcolon_gettype_less_system_dcolon_datetime__greater/)() | 實作 typeof() 翻譯。[DateTime](./datetime/) 的重載。 |
| **bool** [Equals](./equals/)(const TA\&, const TB\&) | 判斷兩個值在套用 [operator==()](./operator_equal_equal/) 後的相等性。 |
| **bool** [Equals< float, float >](./equals_less_float,_float__greater/)(const **float**\&, const **float**\&) | 單精度浮點值的特化。根據 IEC 60559:1989，兩個浮點 NaN 被定義為永遠不相等，但 [System.Object.Equals](./object/equals/) 的合約要求覆寫必須符合等價運算子的要求。因此，System.Double.Equals 與 System.Single.Equals 在比較兩個 NaN 時會回傳 True，而相等運算子在此情況下會回傳 False，符合標準規定。 |
| **bool** [Equals< double, double >](./equals_less_double,_double__greater/)(const **double**\&, const **double**\&) | 雙精度浮點值的特化。 |
| std::enable_if_t<\!std::is_floating_point\<TA\>::value\&&\!std::is_floating_point\<TB\>::value, int\> [Compare](./compare/)(const TA\&, const TB\&) | 比較兩個值。 |
| std::enable_if_t\<std::is_floating_point\<TA\>::value\&&std::is_floating_point\<TB\>::value, int\> [Compare](./compare/)(const TA\&, const TB\&) | 比較兩個浮點數值。 |
| **bool** [IsNaN](./isnan/)(const T\&) | 判斷指定的值是否為非數 (NaN) 值。 |
| **bool** [IsInfinity](./isinfinity/)(const T\&) | 判斷指定的值是否表示無限大。 |
| **bool** [IsPositiveInfinity](./ispositiveinfinity/)(const T\&) | 判斷指定的值是否表示正無限大。 |
| **bool** [IsNegativeInfinity](./isnegativeinfinity/)(const T\&) | 判斷指定的值是否表示負無限大。 |
| TTo [CheckedCast](./checkedcast/)(TFrom) | 判斷指定的值是否落在 **TTo** 類型的值範圍內，若是則將其轉型為 **TTo** 類型。 |
| [ScopeGuard](./scopeguard/)\<F\> [MakeScopeGuard](./makescopeguard/)(F) | 建立 ScopedGuard 類別實例的工廠函式。 |
| T [setter_wrap](./setter_wrap/)(void(*)(T2), T) | 針對具有型別轉換的靜態設定函式的重載。 |
| std::enable_if\<std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_wrap](./setter_wrap/)(Host *const, void(HostSet::*)(T2), T) | 針對具有型別轉換的實例設定函式的重載。 |
| T [setter_increment_wrap](./setter_increment_wrap/)(T(*)(), void(*)(T)) | 翻譯器將 C# 的遞增運算式（目標為具有 setter 與 getter 的類別屬性）轉換為呼叫此函式。 |
| std::enable_if\<std::is_base_of\<HostGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_increment_wrap](./setter_increment_wrap/)(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) | 翻譯器將 C# 的遞增運算式（目標為具有 setter 與 getter 的類別屬性）轉換為呼叫此函式。 |
| T [setter_post_increment_wrap](./setter_post_increment_wrap/)(T(*)(), void(*)(T)) | 翻譯器將 C# 的後置遞增運算式（目標為具有 setter 與 getter 的類別屬性）轉換為呼叫此函式。 |
| std::enable_if\<std::is_base_of\<HostGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_post_increment_wrap](./setter_post_increment_wrap/)(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) | 翻譯器將 C# 的後置遞增運算式（目標為具有 setter 與 getter 的實例屬性）轉換為呼叫此函式（非 const getter 的重載）。 |
| std::enable_if\<std::is_base_of\<HostConstGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_post_increment_wrap](./setter_post_increment_wrap/)(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) | 翻譯器將 C# 的後置遞增運算式（目標為具有 setter 與 getter 的實例屬性）轉換為呼叫此函式（const getter 的重載）。 |
| T [setter_decrement_wrap](./setter_decrement_wrap/)(T(*)(), void(*)(T)) | 翻譯器將 C# 的前置遞減運算式（目標為具有 setter 與 getter 的類別屬性）轉換為呼叫此函式。 |
| std::enable_if\<std::is_base_of\<HostGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_decrement_wrap](./setter_decrement_wrap/)(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) | 翻譯器將 C# 的前置遞減運算式（目標為具有 setter 與 getter 的實例屬性）轉換為呼叫此函式（非 const getter 的重載）。 |
| std::enable_if\<std::is_base_of\<HostConstGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_decrement_wrap](./setter_decrement_wrap/)(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) | 翻譯器將 C# 的前置遞減運算式（目標為具有 setter 與 getter 的實例屬性）轉換為呼叫此函式（const getter 的重載）。 |
| T [setter_post_decrement_wrap](./setter_post_decrement_wrap/)(T(*)(), void(*)(T)) | 翻譯器將 C# 的後置遞減運算式（目標為具有 setter 與 getter 的類別屬性）轉換為呼叫此函式。 |
| std::enable_if\<std::is_base_of\<HostGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_post_decrement_wrap](./setter_post_decrement_wrap/)(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) | 翻譯器將 C# 的後置遞減運算式（目標為具有 setter 與 getter 的實例屬性）轉換為呼叫此函式（非 const getter 的重載）。 |
| std::enable_if\<std::is_base_of\<HostConstGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_post_decrement_wrap](./setter_post_decrement_wrap/)(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) | 翻譯器將 C# 的後置遞減運算式（目標為具有 setter 與 getter 的實例屬性）轉換為呼叫此函式（const getter 的重載）。 |
| std::enable_if<\![IsSmartPtr](./issmartptr/)\<T\>::value, [SmartPtr](./smartptr/)\<T\>\>::type [MakeObject](./makeobject/)(Args\&&...) | 在堆上建立物件，並返回指向它的共享指標。 |
| std::enable_if\<[IsSmartPtr](./issmartptr/)\<T\>::value, T\>::type [MakeObject](./makeobject/)(Args\&&...) | 在堆上建立物件，並返回指向它的共享指標。 |
| [SmartPtr](./smartptr/)\<X\> [MakeSharedPtr](./makesharedptr/)(X *) | 將原始指標轉換為智慧指標。 |
| [SmartPtr](./smartptr/)\<X\> [MakeSharedPtr](./makesharedptr/)(const X *) | 將原始指標轉換為智慧指標。針對 const 指標的重載。當在翻譯為 const 的 C# 方法中使用 'this' 變數時此 overload 很有用。 |
| [SmartPtr](./smartptr/)\<Y\> [static_pointer_cast](./static_pointer_cast/)([SmartPtr](./smartptr/)\<X\> const\&) | 使用 static_cast 轉型智慧指標。 |
| [SmartPtr](./smartptr/)\<Y\> [dynamic_pointer_cast](./dynamic_pointer_cast/)([SmartPtr](./smartptr/)\<X\> const\&) | 使用 dynamic_cast 轉型智慧指標。 |
| [SmartPtr](./smartptr/)\<Y\> [const_pointer_cast](./const_pointer_cast/)([SmartPtr](./smartptr/)\<X\> const\&) | 使用 const_cast 轉型智慧指標。 |
| T * [get_pointer](./get_pointer/)([System::SmartPtr](./smartptr/)\<T\> const\&) | 取得智慧指標所參考的物件。 |
| std::enable_if<\!System::detail::has_method_get_Count\<From\>::value, [Collections::Generic::ListPtr](../system.collections.generic/listptr/)\<To\>\>::type [CastEnumerableTo](./castenumerableto/)(const From\&) | 將指定可列舉物件的元素顯式轉型為不同的類型。 |
| std::enable_if\<System::detail::has_method_get_Count\<From\>::value, [Collections::Generic::ListPtr](../system.collections.generic/listptr/)\<To\>\>::type [CastEnumerableTo](./castenumerableto/)(const From\&) | 將指定可列舉物件的元素顯式轉型為不同的類型。 |
| std::enable_if_t\<[System::IsSmartPtr](./issmartptr/)\<From\>::value, [System::SharedPtr](./sharedptr/)\<[System::Array](./array/)\<To\>\>\> [StaticCastArray](./staticcastarray/)(const [System::SharedPtr](./sharedptr/)\<[System::Array](./array/)\<From\>\>\&) | 將指定陣列的元素轉型為不同的類型。此為從 [SmartPtr](./smartptr/) 物件的情況的覆寫。 |
| std::enable_if_t<\![System::IsSmartPtr](./issmartptr/)\<From\>::value\&&[System::IsBoxable](./isboxable/)\<From\>::value\&&std::is_same\<To, [System::SharedPtr](./sharedptr/)\<[Object](./object/)\>\>::value, [System::SharedPtr](./sharedptr/)\<[System::Array](./array/)\<To\>\>\> [StaticCastArray](./staticcastarray/)(const [System::SharedPtr](./sharedptr/)\<[System::Array](./array/)\<From\>\>\&) | 將指定陣列的元素轉型為不同的類型。此為當 From 為 Boxable 且 To 為 [Object](./object/)[] 時的覆寫。 |
| [SharedPtr](./sharedptr/)\<[Array](./array/)\<To\>\> [DynamicCastArray](./dynamiccastarray/)(const [SharedPtr](./sharedptr/)\<[Array](./array/)\<From\>\>\&) | 將指定陣列的元素轉型為不同的類型。 |
| std::istream\& [operator>>](./operator_greater_greater/)(std::istream\&, [String](./string/)\&) | 從使用 UTF-8 編碼的輸入串流中取得字串。 |
| std::wistream\& [operator>>](./operator_greater_greater/)(std::wistream\&, [String](./string/)\&) | 從輸入寬字元串流中取得字串。 |
| [TaskPtr](./taskptr/) [MakeAsync](./makeasync/)(const Details::AsyncFunction\&) |  |
| [RTaskPtr](./rtaskptr/)\<T\> [MakeAsync](./makeasync/)(const Details::ResultAsyncFunction\<T\>\&) |  |
| [Threading::Tasks::ResultValueTask](../system.threading.tasks/resultvaluetask/)\<T\> [MakeValueAsync](./makevalueasync/)(const Details::ResultAsyncFunction\<T\>\&) |  |
| [Threading::Tasks::ValueTask](../system.threading.tasks/valuetask/) [MakeValueAsync](./makevalueasync/)(const Details::AsyncFunction\&) |  |
| [ValueTuple](./valuetuple/)\<Args...\> [MakeTuple](./maketuple/)(Args...) | 在堆疊上建立 tuple。 |
| [ValueTuple](./valuetuple/)\<Args...\> [TieTuple](./tietuple/)(Args\&&...) | 建立與某些值綁定的 tuple。 |
| **bool** [is_vp_test](./is_vp_test/)(const ::testing::TestInfo *) |  |
| **bool** [is_parametrized_test](./is_parametrized_test/)(const ::testing::TestInfo *) |  |
| std::string [ForEachMemberGVName](./foreachmembergvname/)() |  |

## 列舉

| 列舉 | 說明 |
| --- | --- |
| [Base64FormattingOptions](./base64formattingoptions/) | 包含代表不同 Base-64 編碼資料格式之值的列舉。 |
| [DateTimeKind](./datetimekind/) | 列舉值代表日期與時間的種類。 |
| [DayOfWeek](./dayofweek/) | 代表一週中某天的列舉。 |
| [EnvironmentVariableTarget](./environmentvariabletarget/) | 指定環境變數的位置。 |
| [MidpointRounding](./midpointrounding/) | 指定捨入函式的行為。 |
| [PlatformID](./platformid/) | 代表作業系統平台。 |
| [SmartPtrMode](./smartptrmode/) | [SmartPtr](./smartptr/) 指標類型：弱指標或共享指標。定義在決定是否刪除物件時，指標是否被計數。 |
| [StringSplitOptions](./stringsplitoptions/) | 決定字串分割行為。 |
| [StringComparison](./stringcomparison/) | 定義字串比較樣式。 |
| [TypeCode](./typecode/) | 代表物件的類型。 |
| [UriKind](./urikind/) | 代表 URI 的種類。 |
| [UriComponents](./uricomponents/) | 代表 URI 的組件。 |
| [UriFormat](./uriformat/) | 指定 URI 的跳脫方式。 |
| [UriHostNameType](./urihostnametype/) | 代表主機名稱的類型。 |
| [UriPartial](./uripartial/) | 代表 [Uri.GetLeftPart](./uri/getleftpart/) 方法之 URI 的部份。 |

## 型別別名

| 型別別名 | 說明 |
| --- | --- |
| [IFormatProviderPtr](./iformatproviderptr/) | 指向 [System::IFormatProvider](./iformatprovider/) 類別實例的智慧指標別名。 |
| [DecoderFallbackPtr](./decoderfallbackptr/) | 指向 [System::Text::DecoderFallback](../system.text/decoderfallback/) 類別實例的智慧指標別名。 |
| [DecoderFallbackBufferPtr](./decoderfallbackbufferptr/) | 指向 [System::Text::DecoderFallbackBuffer](../system.text/decoderfallbackbuffer/) 類別實例的智慧指標別名。 |
| [DecoderReplacementFallbackPtr](./decoderreplacementfallbackptr/) | 指向 [System::Text::DecoderReplacementFallback](../system.text/decoderreplacementfallback/) 類別實例的智慧指標別名。 |
| [EncoderFallbackPtr](./encoderfallbackptr/) | 指向 [System::Text::EncoderFallback](../system.text/encoderfallback/) 類別實例的智慧指標別名。 |
| [EncoderFallbackBufferPtr](./encoderfallbackbufferptr/) | 指向 [System::Text::EncoderFallbackBuffer](../system.text/encoderfallbackbuffer/) 類別實例的智慧指標別名。 |
| [EncoderPtr](./encoderptr/) | 指向 [System::Text::Encoder](../system.text/encoder/) 類別實例的智慧指標別名。 |
| [DecoderPtr](./decoderptr/) | 指向 [System::Text::Decoder](../system.text/decoder/) 類別實例的智慧指標別名。 |
| [EncoderReplacementFallbackBufferPtr](./encoderreplacementfallbackbufferptr/) | 指向 [System::Text::EncoderReplacementFallbackBuffer](../system.text/encoderreplacementfallbackbuffer/) 類別實例的智慧指標別名。 |
| [EncoderReplacementFallbackPtr](./encoderreplacementfallbackptr/) | 指向 [System::Text::EncoderReplacementFallback](../system.text/encoderreplacementfallback/) 類別實例的智慧指標別名。 |
| [EncodingPtr](./encodingptr/) | 指向 [System::Text::Encoding](../system.text/encoding/) 類別實例的智慧指標別名。 |
| [EncodingInfoPtr](./encodinginfoptr/) | 指向 [System::Text::EncodingInfo](../system.text/encodinginfo/) 類別實例的智慧指標別名。 |
| [StreamPtr](./streamptr/) | 指向 [System::IO::Stream](../system.io/stream/) 類別實例的智慧指標別名。 |
| [FileStreamPtr](./filestreamptr/) | 指向 [System::IO::FileStream](../system.io/filestream/) 類別實例的智慧指標別名。 |
| [MemoryStreamPtr](./memorystreamptr/) | 指向 [System::IO::MemoryStream](../system.io/memorystream/) 類別實例的智慧指標別名。 |
| [StreamReaderPtr](./streamreaderptr/) | 指向 [System::IO::StreamReader](../system.io/streamreader/) 類別實例的智慧指標別名。 |
| [StreamWriterPtr](./streamwriterptr/) | 指向 [System::IO::StreamWriter](../system.io/streamwriter/) 類別實例的智慧指標別名。 |
| [FileInfoPtr](./fileinfoptr/) | 指向 [System::IO::FileInfo](../system.io/fileinfo/) 類別實例的智慧指標別名。 |
| [FileSystemInfoPtr](./filesysteminfoptr/) | 指向 [System::IO::FileSystemInfo](../system.io/filesysteminfo/) 類別實例的智慧指標別名。 |
| [DirectoryInfoPtr](./directoryinfoptr/) | 指向 [System::IO::DirectoryInfo](../system.io/directoryinfo/) 類別實例的智慧指標別名。 |
| [TaskPtr](./taskptr/) | 指向 [System::Threading::Tasks::Task](../system.threading.tasks/task/) 類別實例的智慧指標別名。 |
| [RTaskPtr](./rtaskptr/) | 指向 [System::Threading::Tasks::ResultTask](../system.threading.tasks/resulttask/) 類別實例的智慧指標別名。 |
| [FunctionPtr](./functionptr/) | 具有預設呼叫慣例的函式類型別名。 |
| [Action](./action/) | 代表沒有返回值之方法的委派類型。 |
| [AggregateException](./aggregateexception/) |  |
| [ByteArrayPtr](./bytearrayptr/) | 指向 unsigned 8 位元整數陣列的智慧指標物件別名。 |
| [AsyncCallback](./asynccallback/) | 代表在非同步操作完成時被呼叫的方法的委派類型。 |
| [BadImageFormatException](./badimageformatexception/) | 當 DLL 或可執行檔的檔案映像無效時拋出的例外。永遠不要將 BadImageFormatException 類別實例包裝成 [System::SmartPtr](./smartptr/)。 |
| [Converter](./converter/) | 代表接受單一 **TInput** 類型參數並返回 **TOutput** 類型值的可呼叫實體之指標。 |
| [Event](./event/) | 代表事件——一種透過委派呼叫通知訂閱者感興趣的發生情形的機制。 |
| [EventArgsPtr](./eventargsptr/) | 指向 [EventArgs](./eventargs/) 類別實例的共享指標。 |
| [EventHandler](./eventhandler/) | 代表回應與處理事件的方法。此類型應在堆疊上配置，並以值或參考傳遞給函式。永遠不要使用 [System::SmartPtr](./smartptr/) 類別來管理此類型的物件。 |
| [ExceptionPtr](./exceptionptr/) | 例外包裝器使用的型別別名。 |
| [Exception](./exception/) | 用於取代 Details::Exception 的別名。 |
| [SystemException](./systemexception/) |  |
| [ApplicationException](./applicationexception/) |  |
| [InvalidOperationException](./invalidoperationexception/) |  |
| [InvalidProgramException](./invalidprogramexception/) |  |
| [InvalidTimeZoneException](./invalidtimezoneexception/) |  |
| [TimeZoneNotFoundException](./timezonenotfoundexception/) |  |
| [ObjectDisposedException](./objectdisposedexception/) |  |
| [NotImplementedException](./notimplementedexception/) |  |
| [NotSupportedException](./notsupportedexception/) |  |
| [PlatformNotSupportedException](./platformnotsupportedexception/) |  |
| [ArgumentException](./argumentexception/) |  |
| [ArgumentNullException](./argumentnullexception/) |  |
| [ArgumentOutOfRangeException](./argumentoutofrangeexception/) |  |
| [FormatException](./formatexception/) |  |
| [UriFormatException](./uriformatexception/) |  |
| [ArithmeticException](./arithmeticexception/) |  |
| [OverflowException](./overflowexception/) |  |
| [DivideByZeroException](./dividebyzeroexception/) |  |
| [OutOfMemoryException](./outofmemoryexception/) |  |
| [IndexOutOfRangeException](./indexoutofrangeexception/) |  |
| [RankException](./rankexception/) |  |
| [InvalidCastException](./invalidcastexception/) |  |
| [NullReferenceException](./nullreferenceexception/) |  |
| [UnauthorizedAccessException](./unauthorizedaccessexception/) |  |
| [MemberAccessException](./memberaccessexception/) |  |
| [MethodAccessException](./methodaccessexception/) |  |
| [OperationCanceledException](./operationcanceledexception/) |  |
| [StackOverflowException](./stackoverflowexception/) |  |
| [TimeoutException](./timeoutexception/) |  |
| [ExecutionEngineException](./executionengineexception/) |  |
| [TypeInitializationException](./typeinitializationexception/) |  |
| [DataMisalignedException](./datamisalignedexception/) |  |
| [IAsyncResultPtr](./iasyncresultptr/) | 指向 [IAsyncResult](./iasyncresult/) 的共享指標。 |
| [MakeConstRef_t](./makeconstref_t/) | 用於 [MakeConstRef](./makeconstref/) 修飾器的輔助類型。 |
| [Predicate](./predicate/) | 代表指向 predicate 的指標 - 一個可接受單一參數並返回 bool 值的可呼叫實體。 |
| [ArrayPtr](./arrayptr/) | ‘pointer to array’ 類型的別名。 |
| [SharedPtr](./sharedptr/) | 在函式庫中廣泛使用的智慧指標的別名。 |
| [StringComparerPtr](./stringcomparerptr/) | 指向 [StringComparer](./stringcomparer/) 類別之實例的共享指標的別名。 |
| [TimeZonePtr](./timezoneptr/) | 指向 [TimeZone](./timezone/) 類別之實例的共享指標。 |
| [TimeZoneInfoPtr](./timezoneinfoptr/) | 指向 [TimeZoneInfo](./timezoneinfo/) 類別之實例的共享指標的別名。 |