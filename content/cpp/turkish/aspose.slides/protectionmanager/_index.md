---
title: ProtectionManager
second_title: Aspose.Slides için C++ API Referansı
description: Sunum şifre koruma yönetimi.
type: docs
weight: 4915
url: /tr/aspose.slides/protectionmanager/
---
## ProtectionManager sınıfı


[Presentation](../presentation/) şifre koruma yönetimi.

```cpp
class ProtectionManager : public Aspose::Slides::IProtectionManager
```

## Yöntemler

| Method | Description |
| --- | --- |
| **bool** [CheckWriteProtection](./checkwriteprotection/)([System::String](../../system/string/)) override | Bir sunumun değiştirilebilmesi için şifre korumalı olup olmadığını belirler. |
| void [Encrypt](./encrypt/)([System::String](../../system/string/)) override | [Presentation](../presentation/) öğesini belirtilen şifre ile şifreler. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objeleri C# [Object.Equals](../../system/object/equals/) anlamı kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# stilinde karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesneleri C# stilinde karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | İki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder; IEC 60559:1989 a göre NaN, NaN dahil hiçbir değere eşit değildir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | İki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder; IEC 60559:1989 a göre NaN, NaN dahil hiçbir değere eşit değildir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| **bool** [get_EncryptDocumentProperties](./get_encryptdocumentproperties/)() override | Bu özellik, sunum şifre korumalıysa anlamlıdır. Doğru ise belge özellikleri sunum dosyasında şifrelenir. Yanlış ise belge özellikleri halka açıktır, sunum şifrelenir. **bool** okunur. |
| [System::String](../../system/string/) [get_EncryptionPassword](./get_encryptionpassword/)() override | Sunum şifrelemesi için kullanılan şifreyi alır. Yalnızca-okunur [System::String](../../system/string/). |
| **bool** [get_IsEncrypted](./get_isencrypted/)() override | Bu örneğin şifrelenip şifrelenmediğini gösteren bir değer alır. Yalnızca-okunur **bool**. |
| **bool** [get_IsOnlyDocumentPropertiesLoaded](./get_isonlydocumentpropertiesloaded/)() override | Bu özellik, sunum dosyası şifre korumalı ve bu dosyanın belge özellikleri halka açıksa anlamlıdır. Doğru değeri, şifre kullanılmadan yalnızca belge özelliklerinin şifreli bir sunum dosyasından yüklendiğini gösterir. Yanlış değeri, doğru şifre kullanılarak tüm şifreli sunumun yüklendiğini, yalnızca belge özelliklerinin değil, tamamının yüklendiğini gösterir. Sunum şifrelenmemişse özellik değeri her zaman yanlıştır. Şifreli bir dosyanın belge özellikleri halka açık değilse özellik değeri her zaman yanlıştır. Presentation.EncryptDocumentProperties doğruysa IsOnlyDocumentPropertiesLoaded özelliği değeri her zaman yanlıştır. Yalnızca-okunur **bool**. |
| **bool** [get_IsWriteProtected](./get_iswriteprotected/)() override | Bu sunumun yazma korumalı olup olmadığını gösteren bir değer alır. Yalnızca-okunur **bool**. |
| **bool** [get_ReadOnlyRecommended](./get_readonlyrecommended/)() override | Yalnızca-okunur öneriyi alır. **bool** okunur. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analogu. Özel nesnelerin hash'lemesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analogu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) koruma nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analogu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapıları başlatılır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, yalnızca yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, yalnızca yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referansla değer tipi nesneyi nullptr ile karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumları için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [RemoveEncryption](./removeencryption/)() override | Şifrelemeyi kaldırır. |
| void [RemoveWriteProtection](./removewriteprotection/)() override | Bu sunumun yazma korumasını kaldırır. |
| void [set_EncryptDocumentProperties](./set_encryptdocumentproperties/)(**bool**) override | Bu özellik, sunum şifre korumalıysa anlamlıdır. Doğru ise belge özellikleri sunum dosyasında şifrelenir. Yanlış ise belge özellikleri halka açıkken sunum şifrelenir. **bool** yazılır. |
| void [set_ReadOnlyRecommended](./set_readonlyrecommended/)(**bool**) override | Yalnızca-okunur öneriyi ayarlar. **bool** yazılır. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşılan yerine) olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| void [SetWriteProtection](./setwriteprotection/)([System::String](../../system/string/)) override | Belirtilen şifreyle bu sunum için yazma korumasını ayarlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve geri döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analogu. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) ifadesini uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) koruma nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapıları serbest bırakılır. |

## Ayrıca Bakınız

* Sınıf [IProtectionManager](../iprotectionmanager/)
* İsim Uzayı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)