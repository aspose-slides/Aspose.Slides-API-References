---
title: TextInfo
second_title: Aspose.Slides for C++ API 參考
description: "定義區域特定的文字屬性。Setter 操作僅在非唯讀物件上啟用。此類別的物件應僅使用 System::MakeObject() 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝在 System::SmartPtr 指標中，並使用該指標作為參數傳遞給函式。"
type: docs
weight: 365
url: /zh-hant/system.globalization/textinfo/
---
## TextInfo 類


定義區域特定的文字屬性。Setter 操作僅在非唯讀物件上啟用。此類的物件應僅使用 [System::MakeObject()](../../system/makeobject/) 函式來配置。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類包裝成 [System::SmartPtr](../../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。

```cpp
class TextInfo : public System::ICloneable
```

## 方法

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | 建立目前物件的副本並回傳指向它的 shared pointer。 |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override |  |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點數比較，兩個 NaN 被視為相等，即使 IEC 60559:1989 規定 NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點數比較，兩個 NaN 被視為相等，即使 IEC 60559:1989 規定 NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual int [get_ANSICodePage](./get_ansicodepage/)() const | 取得 ANSI 代碼頁。 |
| [String](../../system/string/) [get_CultureName](./get_culturename/)() const | 取得文化名稱。 |
| virtual int [get_EBCDICCodePage](./get_ebcdiccodepage/)() const | 取得 EBCDIC 代碼頁。 |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | 檢查格式是否為唯讀。 |
| **bool** [get_IsRightToLeft](./get_isrighttoleft/)() const | 檢查文字是否由左至右書寫。 |
| int [get_LCID](./get_lcid/)() const | 取得區域 ID。 |
| virtual [String](../../system/string/) [get_ListSeparator](./get_listseparator/)() const | 取得清單分隔符號。 |
| virtual int [get_MacCodePage](./get_maccodepage/)() const | 取得 Macintosh 代碼頁。 |
| virtual int [get_OEMCodePage](./get_oemcodepage/)() const | 取得 OEM 代碼頁。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數器資料結構。 |
| int [GetHashCode](./gethashcode/)() const override | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的類比。啟用自訂物件的雜湊運算。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。C# [System.Object.GetType()](../../system/object/gettype/) 呼叫的類比。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為目標類型的實例。C# `is` 運算子的類比。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監護物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的類比。啟用自訂類型的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [TextInfo](./)\& [operator=](./operator_equal/)(const [TextInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static [TextInfoPtr](../textinfoptr/) [ReadOnly](./readonly/)(const [TextInfoPtr](../textinfoptr/)\&) | 取得文化的唯讀版本。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串與 nullptr 情況的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串情況的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 依指定值減少 shared 參考計數。 |
| virtual void [set_ListSeparator](./set_listseparator/)([String](../../system/string/)) | 設定清單分隔符號。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非 shared），允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得目前的 shared 參考計數值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加 shared 參考計數。不要直接呼叫，請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 減少並回傳 shared 參考計數。不要直接呼叫，請改用智慧指標或 ThisProtector。 |
|  [TextInfo](./textinfo/)(const [TextInfo](./)\&) | RTTI 資訊。 |
| virtual char_t [ToLower](./tolower/)(char_t) const | 將字元轉換為小寫。 |
| virtual [String](../../system/string/) [ToLower](./tolower/)([String](../../system/string/)) const | 將字串轉換為小寫。 |
| [String](../../system/string/) [ToString](./tostring/)() const override | C# [Object.ToString()](../../system/object/tostring/) 方法的類比。啟用自訂物件轉為字串。 |
| [String](../../system/string/) [ToTitleCase](./totitlecase/)([String](../../system/string/)) const | 將字串轉換為首字大寫形式（已是全大寫的縮寫除外）。 |
| virtual char_t [ToUpper](./toupper/)(char_t) const | 將字元轉換為大寫。 |
| virtual [String](../../system/string/) [ToUpper](./toupper/)([String](../../system/string/)) const | 將字串轉換為大寫。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監護物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱參考計數。不要直接呼叫，請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 減少弱參考計數。不要直接呼叫，請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另見

* 類 [ICloneable](../../system/icloneable/)
* 命名空間 [System::Globalization](../)
* 函式庫 [Aspose.Slides](../../)