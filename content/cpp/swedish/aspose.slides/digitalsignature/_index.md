---
title: DigitalSignature
second_title: Aspose.Slides för C++ API-referens
description: Digital signatur i signerad fil.
type: docs
weight: 768
url: /sv/aspose.slides/digitalsignature/
---
## DigitalSignature klass


Digital signature in signed file.

```cpp
class DigitalSignature : public Aspose::Slides::IDigitalSignature
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  [DigitalSignature](./digitalsignature/)([System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate2](../../system.security.cryptography.x509certificates/x509certificate2/)\>) | Skapar ett nytt [DigitalSignature](./)-objekt med det angivna certifikatet. |
|  [DigitalSignature](./digitalsignature/)([System::String](../../system/string/), [System::String](../../system/string/)) | Skapar ett nytt [DigitalSignature](./)-objekt med den angivna sökvägen till certifikatfilen och lösenordet. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate2](../../system.security.cryptography.x509certificates/x509certificate2/)\> [get_Certificate](./get_certificate/)() override | Certifikatobjekt som användes för att signera dokumentet. Skrivskyddad [X509Certificate2](../../system.security.cryptography.x509certificates/x509certificate2/). |
| [System::String](../../system/string/) [get_Comments](./get_comments/)() override | Syftet med signaturen. Läs [System::String](../../system/string/). |
| **bool** [get_IsValid](./get_isvalid/)() override | Om denna digitala signatur är giltig och dokumentet inte har manipulerats, kommer detta värde att vara true. Skrivskyddad **bool**. |
| [System::DateTime](../../system/datetime/) [get_SignTime](./get_signtime/)() override | Tidpunkten då dokumentet signerades. Skrivskyddad [System::DateTime](../../system/datetime/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktör. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_Comments](./set_comments/)([System::String](../../system/string/)) override | Syftet med signaturen. Skriv [System::String](../../system/string/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter det n'te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |
## Anmärkningar


Följande exempel visar hur man lägger till en digital signatur från ett PFX-certifikat i PowerPoint [Presentation](../presentation/). 
```cpp
// Initiera Presentation-instans
auto pres = System::MakeObject<Presentation>();

// Skapa DigitalSignature-objekt med PFX-fil och PFX-lösenord
System::SharedPtr<DigitalSignature> signature = System::MakeObject<DigitalSignature>(u"testsignature1.pfx", u"testpass1");
// Kommentera ny digital signatur
signature->set_Comments(u"Aspose.Slides digital signing test.");
// Lägg till digital signatur till presentationen
pres->get_DigitalSignatures()->Add(signature);
// Spara presentationen
pres->Save(u"SomePresentationSigned.pptx", SaveFormat::Pptx);
```
 Följande exempel kod visar hur man validerar digital signatur i PowerPoint [Presentation](../presentation/). 
```cpp
// Initiera Presentation-instans
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");

if (pres->get_DigitalSignatures()->get_Count() > 0)
{
    bool allSignaturesAreValid = true;
    System::Console::WriteLine(u"Signatures used to sign the presentation: ");
    // Kontrollera om alla digitala signaturer är giltiga
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

## Se även

* Klass [IDigitalSignature](../idigitalsignature/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)