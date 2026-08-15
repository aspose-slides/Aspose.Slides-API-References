---
title: FileInfo
second_title: Aspose.Slides C++ API 參考
description: "表示一個檔案的路徑以及該路徑所指向的檔案，並提供操作該檔案的方法。此類別的物件只能透過 System::MakeObject() 函式來配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，否則會導致執行時錯誤或斷言失敗。請始終將此類別包裝為 System::SmartPtr 指標，並使用該指標作為參數傳遞給函式。"
type: docs
weight: 274
url: /zh-hant/system.io/fileinfo/
---
## FileInfo 類別


Represents a path to a file and a file referred to by this path and provides methods for manipulating it. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class FileInfo : public System::IO::FileSystemInfo
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)() | 以 UTF-8 編碼寫入文字，於「Append」模式且無共享，開啟目前物件所表示的檔案。 |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&) | 將目前物件所代表的檔案複製到指定位置。若目標檔案已存在，複製失敗。 |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&, **bool**) | 將目前物件所代表的檔案複製到指定位置。參數指定是否應覆寫已存在的目標檔案。 |
| [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)() | 在目前物件所表示之路徑指向的位置建立檔案，並以截斷模式、無共享開啟，以供讀寫。 |
| [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)() | 在目前物件所表示之路徑指向的位置建立檔案，並以 UTF-8 編碼寫入文字，無共享。 |
| void [Decrypt](./decrypt/)() | 未實作。 |
| void [Delete](./delete/)() override | 刪除目前物件所代表的檔案。 |
| void [Encrypt](./encrypt/)() | 未實作。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989 NaN 不等於任何值（包括 NaN）。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989 NaN 不等於任何值（包括 NaN）。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [FileInfo](./fileinfo/)(const [String](../../system/string/)\&) | 建構代表指定檔案的 [FileInfo](./) 類別新實例。 |
| virtual void [Finalize](../filesysteminfo/finalize/)() | 不執行任何操作。 |
| [FileAttributes](../fileattributes/) [get_Attributes](../filesysteminfo/get_attributes/)() | 返回目前物件所代表實體的屬性。 |
| [DateTime](../../system/datetime/) [get_CreationTime](../filesysteminfo/get_creationtime/)() | 以本地時間返回目前物件所代表實體的建立時間。 |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](../filesysteminfo/get_creationtimeutc/)() | 以 UTC 時間返回目前物件所代表實體的建立時間。 |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Directory](./get_directory/)() | 返回一個 [DirectoryInfo](../directoryinfo/) 物件，表示目前物件所代表檔案所在的目錄。 |
| [String](../../system/string/) [get_DirectoryName](./get_directoryname/)() | 返回目前物件所代表檔案所在目錄的完整名稱。 |
| **bool** [get_Exists](./get_exists/)() override | 返回表示檔案是否存在的值。 |
| [String](../../system/string/) [get_Extension](../filesysteminfo/get_extension/)() | 返回目前物件所代表檔案的副檔名。 |
| virtual [String](../../system/string/) [get_FullName](../filesysteminfo/get_fullname/)() | 返回目前物件所代表實體的完整名稱（包括路徑）。 |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | 返回指示 ReadOnly 屬性是否已設定的值。 |
| [DateTime](../../system/datetime/) [get_LastAccessTime](../filesysteminfo/get_lastaccesstime/)() | 以本地時間返回目前物件所代表實體的最後存取時間。 |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](../filesysteminfo/get_lastaccesstimeutc/)() | 以 UTC 時間返回目前物件所代表實體的最後存取時間。 |
| [DateTime](../../system/datetime/) [get_LastWriteTime](../filesysteminfo/get_lastwritetime/)() | 以本地時間返回目前物件所代表實體的最後寫入時間。 |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](../filesysteminfo/get_lastwritetimeutc/)() | 以 UTC 時間返回目前物件所代表實體的最後寫入時間。 |
| **int64_t** [get_Length](./get_length/)() | 返回檔案的大小（位元組）。 |
| [String](../../system/string/) [get_Name](./get_name/)() override | 返回檔案的名稱。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。提供自訂物件的雜湊功能。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。可直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。提供自訂類型的克隆功能。 |
| void [MoveTo](./moveto/)(const [String](../../system/string/)\&) | 將目前物件所代表的檔案移動到指定位置。 |
| [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/)) | 以指定模式開啟目前物件所代表的檔案供讀寫，且無共享。 |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/)) | 以指定模式、指定存取類型開啟目前物件所代表的檔案，且無共享。 |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | 以指定模式、指定存取類型與共享選項開啟目前物件所代表的檔案。 |
| [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)() | 以「Open」模式、共享讀取，僅開啟目前物件所代表的檔案供讀取。 |
| [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)() | 以 UTF-8 編碼讀取文字且無共享，開啟目前物件所表示路徑指向的既有檔案。 |
| [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)() | 以「OpenOrCreate」模式且無共享，僅開啟目前物件所代表的檔案供寫入。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式將值型別物件與 nullptr 進行比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串的情況。 |
| void [Refresh](../filesysteminfo/refresh/)() | 重新整理目前物件的狀態。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定值。 |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 以目前 [FileInfo](./) 物件所代表的檔案內容取代指定目標檔案的內容，並為被取代的檔案建立備份。 |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | 以目前 [FileInfo](./) 物件所代表的檔案內容取代指定目標檔案的內容，並為被取代的檔案建立備份。 |
| void [set_Attributes](../filesysteminfo/set_attributes/)([FileAttributes](../fileattributes/)) | 設定目前物件所代表實體的指定屬性。 |
| void [set_CreationTime](../filesysteminfo/set_creationtime/)([DateTime](../../system/datetime/)) | 以本地時間設定目前物件所代表實體的建立時間。 |
| void [set_CreationTimeUtc](../filesysteminfo/set_creationtimeutc/)([DateTime](../../system/datetime/)) | 以 UTC 時間設定目前物件所代表實體的建立時間。 |
| void [set_IsReadOnly](./set_isreadonly/)(**bool**) | 設定或取消檔案的 ReadOnly 屬性。 |
| void [set_LastAccessTime](../filesysteminfo/set_lastaccesstime/)([DateTime](../../system/datetime/)) | 以本地時間設定目前物件所代表實體的最後存取時間。 |
| void [set_LastAccessTimeUtc](../filesysteminfo/set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | 以 UTC 時間設定目前物件所代表實體的最後存取時間。 |
| void [set_LastWriteTime](../filesysteminfo/set_lastwritetime/)([DateTime](../../system/datetime/)) | 以本地時間設定目前物件所代表實體的最後寫入時間。 |
| void [set_LastWriteTimeUtc](../filesysteminfo/set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | 以 UTC 時間設定目前物件所代表實體的最後寫入時間。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享指標）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並返回共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| [String](../../system/string/) [ToString](./tostring/)() const override | 返回目前物件所代表的路徑。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。可直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 參見

* 類別 [FileSystemInfo](../filesysteminfo/)
* 命名空間 [System::IO](../)
* 程式庫 [Aspose.Slides](../../)