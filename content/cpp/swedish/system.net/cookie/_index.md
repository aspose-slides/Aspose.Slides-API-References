---
title: Cookie
second_title: Aspose.Slides för C++ API-referens
description: "Representerar en HTTP-cookie. Objekt av denna klass bör endast allokeras med funktionen System::MakeObject() . Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller assert-fel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument."
type: docs
weight: 1
url: /sv/system.net/cookie/
---
## Cookie-klass

Representerar en HTTP-cookie. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller assert-fel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class Cookie : public System::Object
```

## Metoder

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Cookie](./)\> [Clone](./clone/)() | Skapar en kopia av den aktuella instansen. |
| [Cookie](./cookie/)() | Skapar en ny instans. |
| [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/)) | Skapar en ny instans. |
| [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Skapar en ny instans. |
| [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Skapar en ny instans. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypsobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil floating-point-jämförelse där två NaN-värden anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil floating-point-jämförelse där två NaN-värden anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| [String](../../system/string/) [get_Comment](./get_comment/)() const | Hämtar 'Comment'-attributets värde. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_CommentUri](./get_commenturi/)() const | Hämtar 'CommentURL'-attributets värde. |
| **bool** [get_Discard](./get_discard/)() const | Hämtar 'Discard'-attributets värde. |
| [String](../../system/string/) [get_Domain](./get_domain/)() const | Hämtar 'Domain'-attributets värde. |
| **bool** [get_DomainImplicit](./get_domainimplicit/)() | Hämtar ett värde som indikerar om domänen är implicit. |
| [String](../../system/string/) [get_DomainKey](./get_domainkey/)() const | Returnerar domännyckeln. |
| **bool** [get_Expired](./get_expired/)() | Hämtar ett värde som indikerar om cookien har gått ut. |
| [DateTime](../../system/datetime/) [get_Expires](./get_expires/)() | Hämtar 'Expires'-attributets värde. |
| **bool** [get_HttpOnly](./get_httponly/)() const | Hämtar 'HttpOnly'-attributets värde. |
| [String](../../system/string/) [get_Name](./get_name/)() const | Hämtar cookiens namn. |
| [String](../../system/string/) [get_Path](./get_path/)() const | Hämtar 'Path'-attributets värde. |
| **bool** [get_Plain](./get_plain/)() const | Returnerar ett värde som indikerar om cookie-specifikationen är 'Plain'. |
| [String](../../system/string/) [get_Port](./get_port/)() const | Hämtar 'Port'-attributets värde. |
| [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\> [get_PortList](./get_portlist/)() const | Returnerar samlingen av 'Port'-attributets värden. |
| **bool** [get_Secure](./get_secure/)() const | Hämtar 'Secure'-attributets värde. |
| [DateTime](../../system/datetime/) [get_TimeStamp](./get_timestamp/)() const | Returnerar den tid då cookien skapades. |
| [String](../../system/string/) [get_Value](./get_value/)() const | Hämtar cookiens värde. |
| [CookieVariant](../cookievariant/) [get_Variant](./get_variant/)() const | Hämtar cookiens specifikation. |
| **int32_t** [get_Version](./get_version/)() const | Hämtar '[Version](../../system/version/)'-attributets värde. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Aktiverar hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| **bool** [InternalSetName](./internalsetname/)([String](../../system/string/)) | Denna metod anropas av andra metoder för att sätta ett metodnamn. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C# 'is'-operatorn. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Aktiverar kloning av anpassade typer. |
| [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referenräknare med specificerat värde. |
| void [set_Comment](./set_comment/)([String](../../system/string/)) | Sätter 'Comment'-attributets värde. |
| void [set_CommentUri](./set_commenturi/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Sätter 'CommentURL'-attributets värde. |
| void [set_Discard](./set_discard/)(**bool**) | Sätter 'Discard'-attributets värde. |
| void [set_Domain](./set_domain/)([String](../../system/string/)) | Sätter 'Domain'-attributets värde. |
| void [set_DomainImplicit](./set_domainimplicit/)(**bool**) | Sätter ett värde som indikerar om domänen är implicit. |
| void [set_Expired](./set_expired/)(**bool**) | Sätter ett värde som indikerar om cookien har gått ut. |
| void [set_Expires](./set_expires/)([DateTime](../../system/datetime/)) | Sätter 'Expires'-attributets värde. |
| void [set_HttpOnly](./set_httponly/)(**bool**) | Sätter 'HttpOnly'-attributets värde. |
| void [set_Name](./set_name/)([String](../../system/string/)) | Sätter cookiens namn. |
| void [set_Path](./set_path/)([String](../../system/string/)) | Sätter 'Path'-attributets värde. |
| void [set_Port](./set_port/)([String](../../system/string/)) | Sätter 'Port'-attributets värde. |
| void [set_Secure](./set_secure/)(**bool**) | Sätter 'Secure'-attributets värde. |
| void [set_Value](./set_value/)([String](../../system/string/)) | Sätter cookiens värde. |
| void [set_Variant](./set_variant/)([CookieVariant](../cookievariant/)) | Sätter cookiens specifikation. |
| void [set_Version](./set_version/)(**int32_t**) | Sätter '[Version](../../system/version/)'-attributets värde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'th mallargument till en svag pekare (istället för delad). Tillåter byte av pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde på delad referenräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referenräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referenräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| [String](../../system/string/) [ToServerString](./toserverstring/)() | Serialiserar den aktuella instansen till strängrepresentationen. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Aktiverar konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktionen. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| **bool** [VerifySetDefaults](./verifysetdefaults/)([CookieVariant](../cookievariant/), [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, **bool**, [String](../../system/string/), **bool**, **bool**) | Verifierar och sätter standardattributens värden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referenräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referenräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Fält

| Field | Description |
| --- | --- |
| static [CommentAttributeName](./commentattributename/) | Namnet på 'Comment'-attributet. |
| static [CommentUrlAttributeName](./commenturlattributename/) | Namnet på 'CommentURL'-attributet. |
| static [DiscardAttributeName](./discardattributename/) | Namnet på 'Discard'-attributet. |
| static [DomainAttributeName](./domainattributename/) | Namnet på 'Domain'-attributet. |
| static [EqualsLiteral](./equalsliteral/) | Separatorn som används för att separera namn och värde på ett attribut. |
| static [ExpiresAttributeName](./expiresattributename/) | Namnet på 'Expires'-attributet. |
| static [HttpOnlyAttributeName](./httponlyattributename/) | Namnet på 'HttpOnly'-attributet. |
| static [MaxAgeAttributeName](./maxageattributename/) | Namnet på 'Max-Age'-attributet. |
| static [MaxSupportedVersion](./maxsupportedversion/) | Den maximalt stödjade versionen. |
| static [MaxSupportedVersionString](./maxsupportedversionstring/) | Strängrepresentationen av den maximalt stödjade versionen. |
| static [PathAttributeName](./pathattributename/) | Namnet på 'Path'-attributet. |
| static [PortAttributeName](./portattributename/) | Namnet på 'Port'-attributet. |
| static [PortSplitDelimiters](./portsplitdelimiters/) | Arrayen som innehåller avgränsare för 'Port'-attributets värden. |
| static [QuotesLiteral](./quotesliteral/) | Symbolen som används för att omge attributets delar. |
| static [ReservedToName](./reservedtoname/) | Ett värde som är reserverat för cookiens namn. |
| static [ReservedToValue](./reservedtovalue/) | Ett värde som är reserverat för cookiens värde. |
| static [SecureAttributeName](./secureattributename/) | Namnet på 'Secure'-attributet. |
| static [SeparatorLiteral](./separatorliteral/) | Attributseparatorn. |
| static [SpecialAttributeLiteral](./specialattributeliteral/) | Prefixet för de speciella attributens namn. |
| static [VersionAttributeName](./versionattributename/) | Namnet på '[Version](../../system/version/)'-attributet. |

## Se även

* Klass [Object](../../system/object/)
* Namnrymd [System::Net](../)
* Bibliotek [Aspose.Slides](../../)