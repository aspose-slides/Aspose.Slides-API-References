---
title: StringBuilder
second_title: Aspose.Slides för C++ API-referens
description: "Buffer för att samla strängdelar steg för steg. Denna typ kan allokeras antingen på stacken som värdetyp eller på heapen med hjälp av System::MakeObject()-funktionen. När objektet är allokerat får man aldrig blanda dessa två användningsfall: att ha SmartPtr-pekare till stackallokerade objekt är strikt förbjudet."
type: docs
weight: 326
url: /sv/system.text/stringbuilder/
---
## StringBuilder klass

[Buffer](../../system/buffer/) för att samla sträng delar efter varandra. Denna typ kan allokeras antingen på stacken som värdetyp eller på heapen med hjälp av [System::MakeObject()](../../system/makeobject/)-funktionen. När objektet är allokerat får man aldrig blanda dessa två användningsfall: att ha [SmartPtr](../../system/smartptr/)-pekare på stackallokerade objekt är strikt förbjudet.

```cpp
class StringBuilder : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [StringBuilder](./) * [Append](./append/)(char_t) | Lägger till ett tecken i byggaren. |
| [StringBuilder](./) * [Append](./append/)(char_t, int) | Lägger till tecken i byggaren. |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Lägger till en teckenarray i byggaren. |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | Lägger till ett utdrag av teckenarray i byggaren. |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&) | Lägger till en sträng i byggaren. |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&, int, int) | Lägger till ett utdrag av en sträng i byggaren. |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<T\>\&) | Lägger till objektets strängrepresentation i byggaren. |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<[StringBuilder](./)\>\&) | Lägger till byggarens innehåll i byggaren. |
| [StringBuilder](./) * [Append](./append/)(**float**) | Lägger till ett flyttal i byggaren. |
| [StringBuilder](./) * [Append](./append/)(**double**) | Lägger till ett dubbelprecisionsflyttal i byggaren. |
| [StringBuilder](./) * [Append](./append/)(int) | Lägger till ett heltal i byggaren. |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Append](./append/)(T) | Lägger till ett aritmetiskt värde i byggaren. |
| std::enable_if\<std::is_enum\<E\>::value, [StringBuilder](./) *\>::type [Append](./append/)(E) | Lägger till en uppräkningvärdes strängrepresentation i byggaren. |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [String](../../system/string/)\&, const TArgs\&...) | Lägger till en formaterad sträng i byggaren. |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\>\&, const [String](../../system/string/)\&, const TArgs\&...) | Lägger till en formaterad sträng i byggaren. |
| [StringBuilder](./) * [AppendLine](./appendline/)() | Lägger till tecken för ny rad i byggaren. |
| [StringBuilder](./) * [AppendLine](./appendline/)(const [String](../../system/string/)\&) | Lägger till en sträng följd av tecken för ny rad i byggaren. |
| [StringBuilder](./) * [Clear](./clear/)() | Tar bort alla tecken från byggaren. |
| void [CopyTo](./copyto/)(int, [System::ArrayPtr](../../system/arrayptr/)\<char_t\> const\&, int, int) | Kopierar byggarens data till befintliga arraypositioner. |
| **int32_t** [EnsureCapacity](./ensurecapacity/)(**int32_t**) | Säkerställer att kapaciteten för denna instans av [System.Text.StringBuilder](./) är minst det angivna värdet. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypsobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil jämförelse av flyttal där två NaN betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil jämförelse av dubbelprecisionflyttal där två NaN betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för intern användning. |
| int [get_Capacity](./get_capacity/)() const | Hämtar aktuell kapacitet för strängbyggaren. |
| int [get_Length](./get_length/)() const | Hämtar längden på strängen som för närvarande finns i byggaren. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är kopplad till objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog med C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog med C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| char_t [idx_get](./idx_get/)(int) const | Hämtar tecken på angiven position. |
| void [idx_set](./idx_set/)(int, char_t) | Sätter tecken på angiven position. |
| [StringBuilder](./) * [Insert](./insert/)(int, const [String](../../system/string/)\&) | Infogar sträng på byggarens fasta position. |
| [StringBuilder](./) * [Insert](./insert/)(**int32_t**, const [String](../../system/string/)\&, **int32_t**) | Infogar upprepad sträng på byggarens fasta position. |
| [StringBuilder](./) * [Insert](./insert/)(int, char_t) | Infogar tecken på byggarens fasta position. |
| [StringBuilder](./) * [Insert](./insert/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | Infogar tecken på byggarens fasta position. |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Insert](./insert/)(int, T) | Infogar värde på byggarens fasta position. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog med C# 'is'-operatorn. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjektet. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog med C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
| [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar nytt objekt och möjliggör kopieringskonstruktion av subklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar nytt objekt och möjliggör kopieringskonstruktion av subklasser. |
| char_t [operator[]](./operator[]/)(int) const | Hämtar tecken på angiven position. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referens för värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| [StringBuilder](./) * [Remove](./remove/)(int, int) | Tar bort fragment från byggaren. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Ersätter delsträng i byggaren. |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) | Ersätter delsträng inom byggarens område. |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t) | Ersätter tecken i byggaren. |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t, int, int) | Ersätter tecken i byggarens område. |
| void [set_Capacity](./set_capacity/)(int) | Sätter aktuell kapacitet för strängbyggaren. |
| void [set_Length](./set_length/)(int) | Avkortar eller utökar strängbyggaren till angiven längd. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n:te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| [StringBuilder](./stringbuilder/)() | Konstruktor. |
| [StringBuilder](./stringbuilder/)(int) | Konstruktor. |
| [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&) | Konstruktor. |
| [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int) | Konstruktor. |
| [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int, int, int) | Konstruktor. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Hämtar strängen som för närvarande finns i byggaren. |
| [String](../../system/string/) [ToString](./tostring/)(int, int) const | Hämtar delsträng som för närvarande finns i byggaren. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropas direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |
| [~StringBuilder](./~stringbuilder/)() | Destruktor. |

## Se även

* Klass [Object](../../system/object/)
* Namnrymd [System::Text](../)
* Bibliotek [Aspose.Slides](../../)