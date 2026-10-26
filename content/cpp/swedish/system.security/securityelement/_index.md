---
title: SecurityElement
second_title: Aspose.Slides för C++ API-referens
description: "XML-objektmodell för kodning av säkerhetsobjekt. Ej implementerad. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av den här typen på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument."
type: docs
weight: 40
url: /sv/system.security/securityelement/
---
## SecurityElement klass


XML-objektmodell för kodning av säkerhetsobjekt. Ej implementerad. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av den här typen på stacken eller med operatorn new, eftersom det kommer att resultera i körfel och/eller assertion-fel. Omge alltid denna klass med en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class SecurityElement : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| void [AddAttribute](./addattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Lägger till attribut till tagg. |
| void [AddChild](./addchild/)([SecurityElement](./)) | Lägger till barn-tagg. |
| [String](../../system/string/) [Attribute](./attribute/)(const [String](../../system/string/)\&) | Hämtar attributvärde. |
| [SecurityElement](./) [Copy](./copy/)() | Klonar tagg. |
| **bool** [Equal](./equal/)([SecurityElement](./)) | Kontrollerar om parametrar är lika. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil jämförelse av flyttal där två NaN-värden anses lika även om IEC 60559:1989 säger att NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil jämförelse av flyttal där två NaN-värden anses lika även om IEC 60559:1989 säger att NaN inte är lika med något värde, inklusive NaN. |
| static [String](../../system/string/) [Escape](./escape/)(const [String](../../system/string/)\&) | Escapar tecken i XML-sträng. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för internt bruk. |
| static [SecurityElement](./) [FromString](./fromstring/)(const [String](../../system/string/)\&) | Skapar element från XML-kod. |
| [System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<[String](../../system/string/), [String](../../system/string/)\> [get_Attributes](./get_attributes/)() | Hämtar tagg-attribut. |
| [System::Collections::Generic::List](../../system.collections.generic/list/)\<[SecurityElement](./)\> [get_Children](./get_children/)() | Hämtar barn-objekt för tagg. |
| [String](../../system/string/) [get_Tag](./get_tag/)() | Hämtar taggnamn. |
| [String](../../system/string/) [get_Text](./get_text/)() | Hämtar taggens inre text. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknardatastrukturen som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anropet. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| static **bool** [IsValidAttributeName](./isvalidattributename/)(const [String](../../system/string/)\&) | Kontrollerar om attributnamn är giltigt. |
| static **bool** [IsValidAttributeValue](./isvalidattributevalue/)(const [String](../../system/string/)\&) | Kontrollerar om attributvärde är giltigt. |
| static **bool** [IsValidTag](./isvalidtag/)(const [String](../../system/string/)\&) | Kontrollerar om tagg är giltig. |
| static **bool** [IsValidText](./isvalidtext/)(const [String](../../system/string/)\&) | Kontrollerar om text är giltig. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-uttalandet för låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjektet. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referens på värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräkning med angivet värde. |
| [SecurityElement](./) [SearchForChildByTag](./searchforchildbytag/)(const [String](../../system/string/)\&) | Hämtar barn-tagg efter namn. |
| [String](../../system/string/) [SearchForTextOfTag](./searchfortextoftag/)(const [String](../../system/string/)\&) | Hämtar barn-taggens inre text efter taggnamn. |
|  [SecurityElement](./securityelement/)(const [String](../../system/string/)\&) | Konstruktor. |
|  [SecurityElement](./securityelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Konstruktor. |
| void [set_Attributes](./set_attributes/)([System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<[String](../../system/string/), [String](../../system/string/)\>) | Sätter tagg-attribut. |
| void [set_Children](./set_children/)([System::Collections::Generic::List](../../system.collections.generic/list/)\<[SecurityElement](./)\>) | Sätter barn-objekt för tagg. |
| void [set_Tag](./set_tag/)(const [String](../../system/string/)\&) | Sätter taggnamn. |
| void [set_Text](./set_text/)(const [String](../../system/string/)\&) | Sätter taggens inre text. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter det n:te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräkning. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräkning. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Konverterar tagg till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktionen. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-uttalandet för utlåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjektet. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräkning. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräkning. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |
## Se även

* Klass [Object](../../system/object/)
* Namnrymd [System::Security](../)
* Bibliotek [Aspose.Slides](../../)