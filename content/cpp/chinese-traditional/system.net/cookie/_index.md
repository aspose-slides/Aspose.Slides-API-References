---
title: Cookie
second_title: Aspose.Slides for C++ API 參考
description: "代表一個 HTTP Cookie。此類別的物件應僅使用 System::MakeObject() 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 System::SmartPtr 指標，並使用該指標作為參數傳遞給函式。"
type: docs
weight: 1
url: /zh-hant/system.net/cookie/
---
## Cookie 類別


代表一個 HTTP Cookie。此類別的物件應僅使用 [System::MakeObject()](../../system/makeobject/) 函式來配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為這會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 [System::SmartPtr](../../system/smartptr/) 指標，並使用該指標作為參數傳遞至函式。

```cpp
class Cookie : public System::Object
```

## 方法

| 方法 | 說明 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Cookie](./)\> [Clone](./clone/)() | 建立當前實例的副本。 |
|  [Cookie](./cookie/)() | 建立新的實例。 |
|  [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/)) | 建立新的實例。 |
|  [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | 建立新的實例。 |
|  [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | 建立新的實例。 |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [String](../../system/string/) [get_Comment](./get_comment/)() const | 取得「Comment」屬性的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_CommentUri](./get_commenturi/)() const | 取得「CommentURL」屬性的值。 |
| **bool** [get_Discard](./get_discard/)() const | 取得「Discard」屬性的值。 |
| [String](../../system/string/) [get_Domain](./get_domain/)() const | 取得「Domain」屬性的值。 |
| **bool** [get_DomainImplicit](./get_domainimplicit/)() | 取得指示網域是否隱含的值。 |
| [String](../../system/string/) [get_DomainKey](./get_domainkey/)() const | 傳回網域鍵值。 |
| **bool** [get_Expired](./get_expired/)() | 取得指示 Cookie 是否已過期的值。 |
| [DateTime](../../system/datetime/) [get_Expires](./get_expires/)() | 取得「Expires」屬性的值。 |
| **bool** [get_HttpOnly](./get_httponly/)() const | 取得「HttpOnly」屬性的值。 |
| [String](../../system/string/) [get_Name](./get_name/)() const | 取得 Cookie 的名稱。 |
| [String](../../system/string/) [get_Path](./get_path/)() const | 取得「Path」屬性的值。 |
| **bool** [get_Plain](./get_plain/)() const | 傳回指示 Cookie 規範是否為「Plain」的值。 |
| [String](../../system/string/) [get_Port](./get_port/)() const | 取得「Port」屬性的值。 |
| [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\> [get_PortList](./get_portlist/)() const | 傳回「Port」屬性值的集合。 |
| **bool** [get_Secure](./get_secure/)() const | 取得「Secure」屬性的值。 |
| [DateTime](../../system/datetime/) [get_TimeStamp](./get_timestamp/)() const | 傳回 Cookie 建立的時間。 |
| [String](../../system/string/) [get_Value](./get_value/)() const | 取得 Cookie 的值。 |
| [CookieVariant](../cookievariant/) [get_Variant](./get_variant/)() const | 取得 Cookie 的規範。 |
| **int32_t** [get_Version](./get_version/)() const | 取得「[Version](../../system/version/)」屬性的值。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數資料結構。 |
| **int32_t** [GetHashCode](./gethashcode/)() const override | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的類似實作。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| **bool** [InternalSetName](./internalsetname/)([String](../../system/string/)) | 此方法由其他方法呼叫以設定方法名稱。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述型別的實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的類似實作。啟用自訂型別的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷貝建構子。實際上並未拷貝任何內容，只是初始化新物件並允許子類別的拷貝建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上並未拷貝任何內容，只是初始化新物件並允許子類別的拷貝建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式將值型別物件與 nullptr 比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串與 nullptr 情況下的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串情況下的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 依指定值減少共享參考計數。 |
| void [set_Comment](./set_comment/)([String](../../system/string/)) | 設定「Comment」屬性的值。 |
| void [set_CommentUri](./set_commenturi/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | 設定「CommentURL」屬性的值。 |
| void [set_Discard](./set_discard/)(**bool**) | 設定「Discard」屬性的值。 |
| void [set_Domain](./set_domain/)([String](../../system/string/)) | 設定「Domain」屬性的值。 |
| void [set_DomainImplicit](./set_domainimplicit/)(**bool**) | 設定指示網域是否隱含的值。 |
| void [set_Expired](./set_expired/)(**bool**) | 設定指示 Cookie 是否已過期的值。 |
| void [set_Expires](./set_expires/)([DateTime](../../system/datetime/)) | 設定「Expires」屬性的值。 |
| void [set_HttpOnly](./set_httponly/)(**bool**) | 設定「HttpOnly」屬性的值。 |
| void [set_Name](./set_name/)([String](../../system/string/)) | 設定 Cookie 的名稱。 |
| void [set_Path](./set_path/)([String](../../system/string/)) | 設定「Path」屬性的值。 |
| void [set_Port](./set_port/)([String](../../system/string/)) | 設定「Port」屬性的值。 |
| void [set_Secure](./set_secure/)(**bool**) | 設定「Secure」屬性的值。 |
| void [set_Value](./set_value/)([String](../../system/string/)) | 設定 Cookie 的值。 |
| void [set_Variant](./set_variant/)([CookieVariant](../cookievariant/)) | 設定 Cookie 的規範。 |
| void [set_Version](./set_version/)(**int32_t**) | 設定「[Version](../../system/version/)」屬性的值。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數目前的值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| [String](../../system/string/) [ToServerString](./toserverstring/)() | 將當前實例序列化為字串表示。 |
| [String](../../system/string/) [ToString](./tostring/)() const override | C# [Object.ToString()](../../system/object/tostring/) 方法的類似實作。啟用自訂物件轉為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| **bool** [VerifySetDefaults](./verifysetdefaults/)([CookieVariant](../cookievariant/), [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, **bool**, [String](../../system/string/), **bool**, **bool**) | 驗證並設定預設屬性的值。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 欄位

| 欄位 | 說明 |
| --- | --- |
| static [CommentAttributeName](./commentattributename/) | 「Comment」屬性的名稱。 |
| static [CommentUrlAttributeName](./commenturlattributename/) | 「CommentURL」屬性的名稱。 |
| static [DiscardAttributeName](./discardattributename/) | 「Discard」屬性的名稱。 |
| static [DomainAttributeName](./domainattributename/) | 「Domain」屬性的名稱。 |
| static [EqualsLiteral](./equalsliteral/) | 用於分隔屬性名稱與值的分隔符號。 |
| static [ExpiresAttributeName](./expiresattributename/) | 「Expires」屬性的名稱。 |
| static [HttpOnlyAttributeName](./httponlyattributename/) | 「HttpOnly」屬性的名稱。 |
| static [MaxAgeAttributeName](./maxageattributename/) | 「Max-Age」屬性的名稱。 |
| static [MaxSupportedVersion](./maxsupportedversion/) | 支援的最大版本。 |
| static [MaxSupportedVersionString](./maxsupportedversionstring/) | 支援的最大版本的字串表示。 |
| static [PathAttributeName](./pathattributename/) | 「Path」屬性的名稱。 |
| static [PortAttributeName](./portattributename/) | 「Port」屬性的名稱。 |
| static [PortSplitDelimiters](./portsplitdelimiters/) | 包含「Port」屬性值分隔符的陣列。 |
| static [QuotesLiteral](./quotesliteral/) | 用於包裹屬性部分的符號。 |
| static [ReservedToName](./reservedtoname/) | 保留給 Cookie 名稱的值。 |
| static [ReservedToValue](./reservedtovalue/) | 保留給 Cookie 值的值。 |
| static [SecureAttributeName](./secureattributename/) | 「Secure」屬性的名稱。 |
| static [SeparatorLiteral](./separatorliteral/) | 屬性分隔符號。 |
| static [SpecialAttributeLiteral](./specialattributeliteral/) | 特殊屬性名稱的前綴。 |
| static [VersionAttributeName](./versionattributename/) | 「[Version](../../system/version/)」屬性的名稱。 |

## 另請參閱

* 類別 [Object](../../system/object/)
* 命名空間 [System::Net](../)
* 程式庫 [Aspose.Slides](../../)