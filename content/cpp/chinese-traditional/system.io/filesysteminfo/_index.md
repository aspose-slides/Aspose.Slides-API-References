---
title: FileSystemInfo
second_title: Aspose.Slides for C++ API 參考文件
description: "FileInfo 和 DirectoryInfo 的基底類別。此類別的物件只能使用 System::MakeObject() 函式配置。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 System::SmartPtr 指標，並使用該指標將其作為參數傳遞給函式。"
type: docs
weight: 300
url: /zh-hant/system.io/filesysteminfo/
---
## FileSystemInfo 類別

此類別的基礎類別為 [FileInfo](../fileinfo/) 和 [DirectoryInfo](../directoryinfo/)。此類別的物件應僅使用 [System::MakeObject()](../../system/makeobject/) 函式配置。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 [System::SmartPtr](../../system/smartptr/) 指標，並使用該指標將其作為參數傳遞給函式。

```cpp
class FileSystemInfo : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual void [Delete](./delete/)() | 刪除由目前物件所代表的實體。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別的物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別的物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，其中兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，其中兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual void [Finalize](./finalize/)() | 不執行任何操作。 |
| [FileAttributes](../fileattributes/) [get_Attributes](./get_attributes/)() | 返回目前物件所代表的實體的屬性。 |
| [DateTime](../../system/datetime/) [get_CreationTime](./get_creationtime/)() | 以本機時間返回目前物件所代表的實體的建立時間。 |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](./get_creationtimeutc/)() | 以 UTC 時間返回目前物件所代表的實體的建立時間。 |
| virtual **bool** [get_Exists](./get_exists/)() | 判斷目前物件所代表的路徑所參照的實體是否存在。 |
| [String](../../system/string/) [get_Extension](./get_extension/)() | 返回目前物件所代表的檔案的副檔名。 |
| virtual [String](../../system/string/) [get_FullName](./get_fullname/)() | 返回目前物件所代表的實體的完整名稱（包括路徑）。 |
| [DateTime](../../system/datetime/) [get_LastAccessTime](./get_lastaccesstime/)() | 以本機時間返回目前物件所代表的實體的最後存取時間。 |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](./get_lastaccesstimeutc/)() | 以 UTC 時間返回目前物件所代表的實體的最後存取時間。 |
| [DateTime](../../system/datetime/) [get_LastWriteTime](./get_lastwritetime/)() | 以本機時間返回目前物件所代表的實體的最後寫入時間。 |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](./get_lastwritetimeutc/)() | 以 UTC 時間返回目前物件所代表的實體的最後寫入時間。 |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | 返回目前物件所代表的實體的名稱。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與此物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊功能。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 描述的類型實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定行為。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於 string 與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串的情況。 |
| void [Refresh](./refresh/)() | 重新整理目前物件的狀態。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| void [set_Attributes](./set_attributes/)([FileAttributes](../fileattributes/)) | 設定目前物件所代表的實體的指定屬性。 |
| void [set_CreationTime](./set_creationtime/)([DateTime](../../system/datetime/)) | 將目前物件所代表的實體的建立時間設定為本機時間。 |
| void [set_CreationTimeUtc](./set_creationtimeutc/)([DateTime](../../system/datetime/)) | 將目前物件所代表的實體的建立時間設定為 UTC 時間。 |
| void [set_LastAccessTime](./set_lastaccesstime/)([DateTime](../../system/datetime/)) | 將目前物件所代表的實體的最後存取時間設定為本機時間。 |
| void [set_LastAccessTimeUtc](./set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | 請將目前物件所代表的實體的最後存取時間設定為 UTC 時間。 |
| void [set_LastWriteTime](./set_lastwritetime/)([DateTime](../../system/datetime/)) | 將目前物件所代表的實體的最後寫入時間設定為本機時間。 |
| void [set_LastWriteTimeUtc](./set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | 將目前物件所代表的實體的最後寫入時間設定為 UTC 時間。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 減少並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解除鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 減少弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另見

* 類別 [Object](../../system/object/)
* 命名空間 [System::IO](../)
* 函式庫 [Aspose.Slides](../../)