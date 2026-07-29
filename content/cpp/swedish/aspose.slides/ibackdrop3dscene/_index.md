---
title: IBackdrop3DScene
second_title: Aspose.Slides för C++ API-referens
description: Definierar ett plan där effekter, såsom glöd och skugga, tillämpas i förhållande till den form de appliceras på.
type: docs
weight: 1392
url: /sv/aspose.slides/ibackdrop3dscene/
---
## IBackdrop3DScene klass

Definierar ett plan där effekter, såsom glöd och skugga, tillämpas i förhållande till den form de appliceras på.

```cpp
class IBackdrop3DScene : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_AnchorPoint](./get_anchorpoint/)() | Returnerar en punkt i 3D-rum. Denna punkt är den punkt i rummet som förankrar bakgrundsplanytan. 3D-punkt representeras av en array med 3 **float**-värden som definierar X-, Y- och Z-koordinater. Läs **float**[]. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_NormalVector](./get_normalvector/)() | Returnerar en normalvektor. Mer exakt definierar detta attribut en vektor som är normal mot bakgrundsplanytans yta. Vektorn representeras av en array med 3 **float**-värden som definierar X-, Y- och Z-koordinater. Läs **float**[]. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_UpVector](./get_upvector/)() | Returnerar en vektor som representerar uppåtriktning. Mer exakt definierar detta attribut en vektor som representerar uppåt i förhållande till bakgrundsplanytans yta. Vektorn representeras av en array med 3 **float**-värden som definierar X-, Y- och Z-koordinater. Läs **float**[]. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsen för låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-bevakningsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [set_AnchorPoint](./set_anchorpoint/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) | Sätter en punkt i 3D-rum. Denna punkt är den punkt i rummet som förankrar bakgrundsplanytan. 3D-punkt representeras av en array med 3 **float**-värden som definierar X-, Y- och Z-koordinater. Skriv **float**[]. |
| virtual void [set_NormalVector](./set_normalvector/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) | Sätter en normalvektor. Mer exakt definierar detta attribut en vektor som är normal mot bakgrundsplanytans yta. Vektorn representeras av en array med 3 **float**-värden som definierar X-, Y- och Z-koordinater. Skriv **float**[]. |
| virtual void [set_UpVector](./set_upvector/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) | Sätter en vektor som representerar uppåtriktning. Mer exakt definierar detta attribut en vektor som representerar uppåt i förhållande till bakgrundsplanytans yta. Vektorn representeras av en array med 3 **float**-värden som definierar X-, Y- och Z-koordinater. Skriv **float**[]. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätt n'te templatemargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktionen. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsen för upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-bevakningsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Se också

* Klass [Object](../../system/object/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)