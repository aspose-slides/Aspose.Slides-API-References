---
title: ProtectionManager
second_title: Aspose.Slides C++ API 參考
description: 簡報密碼保護管理。
type: docs
weight: 4915
url: /zh-hant/aspose.slides/protectionmanager/
---
## ProtectionManager 類別


[Presentation](../presentation/) 密碼保護管理。

```cpp
class ProtectionManager : public Aspose::Slides::IProtectionManager
```

## 方法

| 方法 | 說明 |
| --- | --- |
| **bool** [CheckWriteProtection](./checkwriteprotection/)([System::String](../../system/string/)) override | 判斷簡報是否受密碼保護以進行修改。 |
| void [Encrypt](./encrypt/)([System::String](../../system/string/)) override | 使用指定的密碼加密 [Presentation](../presentation/)。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考類型物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值類型物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| **bool** [get_EncryptDocumentProperties](./get_encryptdocumentproperties/)() override | 如果簡報受密碼保護，此屬性才有意義。若為 true，則文件屬性在簡報檔案中被加密。若為 false，則文件屬性為公開，同時簡報被加密。讀取 **bool**。 |
| [System::String](../../system/string/) [get_EncryptionPassword](./get_encryptionpassword/)() override | 取得用於簡報加密的密碼。唯讀 [System::String](../../system/string/)。 |
| **bool** [get_IsEncrypted](./get_isencrypted/)() override | 取得指示此實例是否已加密的值。唯讀 **bool**。 |
| **bool** [get_IsOnlyDocumentPropertiesLoaded](./get_isonlydocumentpropertiesloaded/)() override | 如果簡報檔案受密碼保護且其文件屬性為公開，此屬性才有意義。true 表示僅從已加密的簡報檔案中載入文件屬性，而不使用密碼。false 表示使用正確的密碼載入整個已加密的簡報，而不僅載入文件屬性。如果簡報未加密，則屬性值恆為 false。如果已加密檔案的文件屬性不是公開的，則屬性值恆為 false。如果 Presentation.EncryptDocumentProperties 為 true，則 IsOnlyDocumentPropertiesLoaded 屬性值恆為 false。唯讀 **bool**。 |
| **bool** [get_IsWriteProtected](./get_iswriteprotected/)() override | 取得指示此簡報是否受寫入保護的值。唯讀 **bool**。 |
| **bool** [get_ReadOnlyRecommended](./get_readonlyrecommended/)() override | 取得唯讀建議。讀取 **bool**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守衛物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指定運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值類型物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 依指定值減少共享參考計數。 |
| void [RemoveEncryption](./removeencryption/)() override | 移除加密。 |
| void [RemoveWriteProtection](./removewriteprotection/)() override | 移除此簡報的寫入保護。 |
| void [set_EncryptDocumentProperties](./set_encryptdocumentproperties/)(**bool**) override | 如果簡報受密碼保護，此屬性才有意義。若為 true，則文件屬性在簡報檔案中被加密。若為 false，則文件屬性為公開，同時簡報被加密。寫入 **bool**。 |
| void [set_ReadOnlyRecommended](./set_readonlyrecommended/)(**bool**) override | 設定唯讀建議。寫入 **bool**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| void [SetWriteProtection](./setwriteprotection/)([System::String](../../system/string/)) override | 使用指定的密碼設定此簡報的寫入保護。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並返回共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守衛物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另見

* 類別 [IProtectionManager](../iprotectionmanager/)
* 命名空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)