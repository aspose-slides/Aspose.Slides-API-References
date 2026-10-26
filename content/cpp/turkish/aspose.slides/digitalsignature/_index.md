---
title: DigitalSignature
second_title: Aspose.Slides için C++ API Referansı
description: İmzalı dosyada dijital imza.
type: docs
weight: 768
url: /tr/aspose.slides/digitalsignature/
---
## DigitalSignature sınıfı

İmzalı dosyada dijital imza.

```cpp
class DigitalSignature : public Aspose::Slides::IDigitalSignature
```

## Yöntemler

| Method | Description |
| --- | --- |
|  [DigitalSignature](./digitalsignature/)([System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate2](../../system.security.cryptography.x509certificates/x509certificate2/)\>) | Belirtilen sertifikayla yeni bir [DigitalSignature](./) nesnesi oluşturur. |
|  [DigitalSignature](./digitalsignature/)([System::String](../../system/string/), [System::String](../../system/string/)) | Belirtilen sertifika dosyası yolu ve parola ile yeni bir [DigitalSignature](./) nesnesi oluşturur. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) mantığıyla karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 standardına göre NaN herhangi bir değere (NaN dahil) eşit olmamasına rağmen, iki NaN’in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 standardına göre NaN herhangi bir değere (NaN dahil) eşit olmamasına rağmen, iki NaN’in eşit kabul edildiği C# tarzı çift kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate2](../../system.security.cryptography.x509certificates/x509certificate2/)\> [get_Certificate](./get_certificate/)() override | Belgeyi imzalamak için kullanılan sertifika nesnesi. Yalnızca okuma [X509Certificate2](../../system.security.cryptography.x509certificates/x509certificate2/). |
| [System::String](../../system/string/) [get_Comments](./get_comments/)() override | İmzanın amacı. Okuma [System::String](../../system/string/). |
| **bool** [get_IsValid](./get_isvalid/)() override | Bu dijital imza geçerli ve belge değiştirilmemişse, bu değer doğru olur. Yalnızca okuma **bool**. |
| [System::DateTime](../../system/datetime/) [get_SignTime](./get_signtime/)() override | Belgenin imzalandığı zaman. Yalnızca okuma [System::DateTime](../../system/datetime/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hash edilmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın ya da [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in dize ve nullptr durumu için özelleştirilmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in dizeler durumu için özelleştirilmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşımlı referans sayacını azaltır. |
| void [set_Comments](./set_comments/)([System::String](../../system/string/)) override | İmzanın amacı. Yaz [System::String](../../system/string/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 'n'inci şablon argümanını paylaşımlı yerine zayıf işaretçi olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçirmeye izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşımlı referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşımlı referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşımlı referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın ya da [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Açıklamalar

Aşağıdaki örnek, PowerPoint [Presentation](../presentation/) içinde bir PFX sertifikasından dijital imza eklemeyi gösterir. 
```cpp
// Presentation örneğini başlat
auto pres = System::MakeObject<Presentation>();

// PFX dosyası ve PFX parolası ile DigitalSignature nesnesi oluştur
System::SharedPtr<DigitalSignature> signature = System::MakeObject<DigitalSignature>(u"testsignature1.pfx", u"testpass1");
// Yeni dijital imzaya yorum ekle
signature->set_Comments(u"Aspose.Slides digital signing test.");
// Dijital imzayı sunuma ekle
pres->get_DigitalSignatures()->Add(signature);
// Sunumu kaydet
pres->Save(u"SomePresentationSigned.pptx", SaveFormat::Pptx);
```
Aşağıdaki örnek kod, PowerPoint [Presentation](../presentation/) içinde dijital imzanın doğrulanmasını gösterir. 
```cpp
// Presentation örneğini başlat
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");

if (pres->get_DigitalSignatures()->get_Count() > 0)
{
    bool allSignaturesAreValid = true;
    System::Console::WriteLine(u"Signatures used to sign the presentation: ");
    // Tüm dijital imzaların geçerli olup olmadığını kontrol et
    for (auto&& signature : System::IterateOver(pres->get_DigitalSignatures()))
    {
        System::Console::WriteLine(signature->get_Certificate()->get_SubjectName()->get_Name() + u", " +
                                   signature->get_SignTime().ToString(u"yyyy-MM-dd HH:mm") + u" -- " +
                                   (signature->get_IsValid() ? System::String(u"VALID") : System::String(u"INVALID")));
        allSignaturesAreValid &= signature->get_IsValid();
    }

    if (allSignaturesAreValid)
    {
        System::Console::WriteLine(u"Presentation is genuine, all signatures are valid.");
    }
    else
    {
        System::Console::WriteLine(u"Presentation has been modified since signing.");
    }
}
```

## Ayrıca Bakınız

* Sınıf [IDigitalSignature](../idigitalsignature/)
* İsimAlanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)