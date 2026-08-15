---
title: X509Certificate
second_title: Aspose.Slides for C++ API 參考文件
description: "X.509 v.3 證書。不支援加密證書。僅支援 X509KeyStorageFlags::DefaultKeySet 標誌。此類別的物件應僅透過 System::MakeObject() 函式配置。切勿在堆疊上或使用 operator new 建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。始終將此類別包裝在 System::SmartPtr 指標中，並使用此指標作為參數傳遞給函式。"
type: docs
weight: 27
url: /zh-hant/system.security.cryptography.x509certificates/x509certificate/
---
## X509Certificate 類別


X.509 v.3 證書。不支援加密證書。僅支援 [X509KeyStorageFlags::DefaultKeySet](../x509keystorageflags/) 標誌。此類別的物件應僅透過 [System::MakeObject()](../../system/makeobject/) 函式配置。切勿在堆疊上或使用 operator new 建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。始終將此類別包裝在 [System::SmartPtr](../../system/smartptr/) 指標中，並使用此指標作為參數傳遞給函式。

```cpp
class X509Certificate : public virtual System::Object,
                        public System::IDisposable
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](./)\> [CreateFromCertFile](./createfromcertfile/)(const [String](../../system/string/)\&) | 從指定的 PKCS7 檔案建立證書。 |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](./)\> [CreateFromSignedFile](./createfromsignedfile/)(const [String](../../system/string/)\&) | 從指定的已簽署檔案建立證書。 |
| void [Dispose](./dispose/)() override | 什麼也不做。 |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 比較兩個證書。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別的物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，當兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，當兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN。 |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](./export/)([X509ContentType](../x509contenttype/)) const | 以指定的格式將目前物件匯出為位元組陣列。未實作。 |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](./export/)([X509ContentType](../x509contenttype/), const [SecureStringPtr](../../system.security/securestringptr/)\&) const | 以指定的格式將目前物件匯出為位元組陣列。未實作。 |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](./export/)([X509ContentType](../x509contenttype/), const [String](../../system/string/)\&) const | 以指定的格式將目前物件匯出為位元組陣列。未實作。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| IntPtr [get_Handle](./get_handle/)() const | 取得 Microsoft Cryptographic API 證書上下文的句柄。 |
| [String](../../system/string/) [get_Issuer](./get_issuer/)() const | 取得頒發 X.509v3 證書的憑證授權機構名稱。 |
| [String](../../system/string/) [get_Subject](./get_subject/)() const | 取得證書中的主體辨識名稱。 |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](./getcerthash/)() const | 以位元組陣列取得目前物件的雜湊值。 |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](./getcerthash/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | 以位元組陣列取得目前物件的雜湊值。 |
| virtual [String](../../system/string/) [GetCertHashString](./getcerthashstring/)() const | 取得 [SHA1](../../system.security.cryptography/sha1/) 雜湊值，並以十六進位字串表示。 |
| virtual [String](../../system/string/) [GetCertHashString](./getcerthashstring/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | 取得 [SHA1](../../system.security.cryptography/sha1/) 雜湊值，並以十六進位字串表示。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual [String](../../system/string/) [GetEffectiveDateString](./geteffectivedatestring/)() const | 取得目前證書的生效日期。 |
| virtual [String](../../system/string/) [GetExpirationDateString](./getexpirationdatestring/)() const | 取得目前證書的到期日期。 |
| virtual [String](../../system/string/) [GetFormat](./getformat/)() const | 取得證書格式的名稱。 |
| **int32_t** [GetHashCode](./gethashcode/)() const override | 取得證書雜湊碼。 |
| virtual [String](../../system/string/) [GetIssuerName](./getissuername/)() const | 取得頒發目前證書的認證機構名稱。 |
| virtual [String](../../system/string/) [GetKeyAlgorithm](./getkeyalgorithm/)() const | 以字串形式取得目前證書的金鑰資訊。 |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetKeyAlgorithmParameters](./getkeyalgorithmparameters/)() const | 以位元組陣列形式取得目前證書的金鑰資訊。 |
| virtual [String](../../system/string/) [GetKeyAlgorithmParametersString](./getkeyalgorithmparametersstring/)() const | 以十六進位字串形式取得目前證書的金鑰資訊。 |
| virtual [String](../../system/string/) [GetName](./getname/)() const | 取得目前證書所頒發的主體名稱。 |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetPublicKey](./getpublickey/)() const | 以位元組陣列形式取得證書的公鑰。 |
| virtual [String](../../system/string/) [GetPublicKeyString](./getpublickeystring/)() const | 以十六進位字串形式取得證書的公鑰。 |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetRawCertData](./getrawcertdata/)() const | 以位元組陣列形式取得證書的原始資料。 |
| virtual [String](../../system/string/) [GetRawCertDataString](./getrawcertdatastring/)() const | 以十六進位字串形式取得證書的原始資料。 |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetSerialNumber](./getserialnumber/)() const | 以位元組陣列形式取得證書的序號。 |
| virtual [String](../../system/string/) [GetSerialNumberString](./getserialnumberstring/)() const | 以十六進位字串形式取得證書的序號。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual void [Import](./import/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | 從指定的證書檔案匯入資訊。未實作。 |
| virtual void [Import](./import/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | 從指定的證書檔案匯入資訊。未實作。 |
| virtual void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | 從指定的證書檔案匯入資訊。未實作。 |
| virtual void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | 從指定的證書檔案匯入資訊。未實作。 |
| virtual void [Import](./import/)(const [String](../../system/string/)\&) | 從指定的證書檔案匯入資訊。未實作。 |
| virtual void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | 從指定的證書資料匯入資訊。未實作。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述型別的實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監護物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [X509Certificate](./)\& [operator=](./operator_equal/)(const [X509Certificate](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| virtual void [Reset](./reset/)() | 重設證書狀態。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享指標）。允許在容器中將指標切換至弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 將共享參考計數遞增。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 將共享參考計數遞減並回傳。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](./tostring/)(**bool**) const | 以文字格式回傳證書資訊。 |
| [String](../../system/string/) [ToString](./tostring/)() const override | 以文字格式回傳證書資訊。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監護物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 將弱參考計數遞增。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 將弱參考計數遞減。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
|  [X509Certificate](./x509certificate/)(const [X509Certificate](./)\&) |  |
|  [X509Certificate](./x509certificate/)() | 建構子。 |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | 建構子。 |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&) | 建構子。 |
|  [X509Certificate](./x509certificate/)(const [SharedPtr](../../system/sharedptr/)\<[X509Certificate](./)\>\&) | 建構子。 |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&) | 建構子。 |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | 建構子。 |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 建構子。 |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | 建構子。 |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | 建構子。 |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | 建構子。 |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | 建構子。 |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | 建構子。 |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | 建構子。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 類型別名

| 類型別名 | 描述 |
| --- | --- |
| [Ptr](./ptr/) | 指標類型。 |

## 參見

* 類別 [Object](../../system/object/)
* 類別 [IDisposable](../../system/idisposable/)
* 命名空間 [System::Security::Cryptography::X509Certificates](../)
* 函式庫 [Aspose.Slides](../../)