---
title: BulletFormat
second_title: Aspose.Slides för C++ API-referens
description: Representerar egenskaper för formatering av styckespunkter.
type: docs
weight: 248
url: /sv/aspose.slides/bulletformat/
---
## BulletFormat klass

Representerar egenskaper för styckespunktformatering.

```cpp
class BulletFormat : public Aspose::Slides::PVIObject,
                     public Aspose::Slides::IBulletFormat
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| void [ApplyDefaultParagraphIndentsShifts](./applydefaultparagraphindentsshifts/)() override | Ställer in standard icke-nollförskjutningar för effektiv stycke Indent och MarginLeft när bullets är aktiverade (som PowerPoint gör om man aktiverar styckepunkter/-numrering i det). Om bullets är inaktiverade återställs bara stycke Indent och MarginLeft (som PowerPoint gör om man inaktiverar styckepunkter/-numrering i det). Indent-förskjutningar tillämpas i förhållande till aktuellt bullet-sammanhang – IBulletFormat::get(set)_Type, .NumberedBulletStyle och FontHeight för den första delen. Icke-noll Indent-förskjutningar tillämpas på den effektiva Indent och MarginLeft för aktuellt stycke (gör resultatvärdena till lokala värden). |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Jämför med specificerat objekt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om IEC 60559:1989 anger att NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om IEC 60559:1989 anger att NaN inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för intern användning. |
| char16_t [get_Char](./get_char/)() override | Returnerar bullet-tecknet för ett stycke utan arv. Läs **wchar_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_Color](./get_color/)() override | Returnerar färgformatet för en bullet i ett stycke utan arv. Endast läsning [IColorFormat](../icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_Font](./get_font/)() override | Returnerar bullet-teckensnittet för ett stycke utan arv. Läs [IFontData](../ifontdata/). |
| **float** [get_Height](./get_height/)() override | Returnerar bullet-höjden för ett stycke utan arv. Värdet std::numeric_limits<float>::quiet_NaN() anger att bullet ärver höjden från den första delen i stycket. Läs **float**. |
| [NullableBool](../nullablebool/) [get_IsBulletHardColor](./get_isbullethardcolor/)() override | Bestämmer om bullet har egen färg eller ärver den från den första delen i stycket. **[NullableBool::True](../nullablebool/)** om bullet har egen färg och **[NullableBool::False](../nullablebool/)** om bullet ärver färg från den första delen i stycket. Läs [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsBulletHardFont](./get_isbullethardfont/)() override | Bestämmer om bullet har eget teckensnitt eller ärver det från den första delen i stycket. **[NullableBool::True](../nullablebool/)** om bullet har eget teckensnitt och **[NullableBool::False](../nullablebool/)** om bullet ärver teckensnitt från den första delen i stycket. Läs [NullableBool](../nullablebool/). |
| **int16_t** [get_NumberedBulletStartWith](./get_numberedbulletstartwith/)() override | Returnerar det första talet som används för en grupp numrerade bullets utan arv. Läs **int16_t**. |
| [Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/) [get_NumberedBulletStyle](./get_numberedbulletstyle/)() override | Returnerar stilen för en numrerad bullet utan arv. Läs [Slides::NumberedBulletStyle](../numberedbulletstyle/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Returnerar Parent_Immediate-objektet. Endast läsning [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Returnerar förälder [IPresentationComponent](../ipresentationcomponent/). Endast läsning [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | Returnerar bilden som används som bullet i ett stycke utan arv. Endast läsning [ISlidesPicture](../islidespicture/). |
| [BulletType](../bullettype/) [get_Type](./get_type/)() override | Returnerar bullet-typen för ett stycke utan arv. Läs [BulletType](../bullettype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [GetEffective](./geteffective/)() override | Hämtar effektiv bullet-formateringsdata med arv tillämpat. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Returnerar hash-kod. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen för objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-bevakningsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktör. Kopierar i själva verket ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar i själva verket ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypsobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_Char](./set_char/)(char16_t) override | Ställer in bullet-tecknet för ett stycke utan arv. Skriv **wchar_t**. |
| void [set_Font](./set_font/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Ställer in bullet-teckensnittet för ett stycke utan arv. Skriv [IFontData](../ifontdata/). |
| void [set_Height](./set_height/)(**float**) override | Ställer in bullet-höjden för ett stycke utan arv. Värdet std::numeric_limits<float>::quiet_NaN() anger att bullet ärver höjden från den första delen i stycket. Skriv **float**. |
| void [set_IsBulletHardColor](./set_isbullethardcolor/)([NullableBool](../nullablebool/)) override | Bestämmer om bullet har egen färg eller ärver den från den första delen i stycket. **[NullableBool::True](../nullablebool/)** om bullet har egen färg och **[NullableBool::False](../nullablebool/)** om bullet ärver färg från den första delen i stycket. Skriv [NullableBool](../nullablebool/). |
| void [set_IsBulletHardFont](./set_isbullethardfont/)([NullableBool](../nullablebool/)) override | Bestämmer om bullet har eget teckensnitt eller ärver det från den första delen i stycket. **[NullableBool::True](../nullablebool/)** om bullet har eget teckensnitt och **[NullableBool::False](../nullablebool/)** om bullet ärver teckensnitt från den första delen i stycket. Skriv [NullableBool](../nullablebool/). |
| void [set_NumberedBulletStartWith](./set_numberedbulletstartwith/)(**int16_t**) override | Ställer in det första talet som används för en grupp numrerade bullets utan arv. Skriv **int16_t**. |
| void [set_NumberedBulletStyle](./set_numberedbulletstyle/)([Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/)) override | Ställer in stilen för en numrerad bullet utan arv. Skriv [Slides::NumberedBulletStyle](../numberedbulletstyle/). |
| void [set_Type](./set_type/)([BulletType](../bullettype/)) override | Ställer in bullet-typen för ett stycke utan arv. Skriv [BulletType](../bullettype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ställer in n'te mallargument som en svag pekare (istället för delad). Tillåter byte av pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräkning. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräkning. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metod. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-bevakningsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräkning. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräkning. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigir alla interna datastrukturer. |

## Se även

* Klass [PVIObject](../pviobject/)
* Klass [IBulletFormat](../ibulletformat/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)