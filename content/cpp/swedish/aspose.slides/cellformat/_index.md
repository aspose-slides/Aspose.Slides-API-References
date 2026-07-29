---
title: CellFormat
second_title: Aspose.Slides för C++ API-referens
description: Representerar formatet för en tabellcell.
type: docs
weight: 326
url: /sv/aspose.slides/cellformat/
---
## CellFormat klass

Representerar formatet för en tabellcell.

```cpp
class CellFormat : public Aspose::Slides::PVIObject,
                   public Aspose::Slides::ICellFormat
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Jämför med specificerat objekt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med hjälp av C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar jämförelse av flyttal i C#-stil där två NaN-värden anses vara lika även om enligt IEC 60559:1989 NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar jämförelse av flyttal i C#-stil där två NaN-värden anses vara lika även om enligt IEC 60559:1989 NaN inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_BorderBottom](./get_borderbottom/)() override | Returnerar ett objekt för egenskaper för en nedre kantlinje. Skrivskyddad [ILineFormat](../ilineformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_BorderDiagonalDown](./get_borderdiagonaldown/)() override | Returnerar ett objekt för egenskaper för en diagonal linje från övre vänster till nedre höger. Skrivskyddad [ILineFormat](../ilineformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_BorderDiagonalUp](./get_borderdiagonalup/)() override | Returnerar ett objekt för egenskaper för en diagonal linje från nedre vänster till övre höger. Skrivskyddad [ILineFormat](../ilineformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_BorderLeft](./get_borderleft/)() override | Returnerar ett objekt för egenskaper för en vänsterkantlinje. Skrivskyddad [ILineFormat](../ilineformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_BorderRight](./get_borderright/)() override | Returnerar ett objekt för egenskaper för en högerkantlinje. Skrivskyddad [ILineFormat](../ilineformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_BorderTop](./get_bordertop/)() override | Returnerar ett objekt för egenskaper för en överkantlinje. Skrivskyddad [ILineFormat](../ilineformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() override | Returnerar ett objekt för egenskaper för cellfyllning. Skrivskyddad [IFillFormat](../ifillformat/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Returnerar ett Parent_Immediate-objekt. Skrivskyddad [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Returnerar förälder [IPresentationComponent](../ipresentationcomponent/). Skrivskyddad [IPresentationComponent](../ipresentationcomponent/). |
| **float** [get_Transparency](./get_transparency/)() override | Hämtar fyllningsfärgens genomskinlighet. Läs **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICellFormatEffectiveData](../icellformateffectivedata/)\> [GetEffective](./geteffective/)() override | Hämtar effektiva formatteringsegenskaper för tabellcellen med arv och tabellstilar tillämpade. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Returnerar hash-kod. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
| [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_Transparency](./set_transparency/)(**float**) override | Sätter fyllningsfärgens genomskinlighet. Skriv **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'te mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Se även

* Klass [PVIObject](../pviobject/)
* Klass [ICellFormat](../icellformat/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)