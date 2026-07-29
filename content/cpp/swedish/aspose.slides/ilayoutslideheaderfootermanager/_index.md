---
title: ILayoutSlideHeaderFooterManager
second_title: Aspose.Slides för C++ API-referens
description: Representerar en hanterare som styr beteendet för layout-slide-sidfot, datum-tid- och sidnummer-platshållare samt alla underordnade platshållare. Underordnade platshållare betyder att platshållare finns på beroende slides. Beroende slides använder och är beroende av layout-slide.
type: docs
weight: 2666
url: /sv/aspose.slides/ilayoutslideheaderfootermanager/
---
## ILayoutSlideHeaderFooterManager klass

Representerar hanterare som innehar beteendet för layout-slides sidfot, datum-tid, sidnummer-platshållare och alla underordnade platshållare. Underordnade platshållare betyder att platshållare finns på beroende slides. Beroende slides använder och är beroende av layout-slide.

```cpp
class ILayoutSlideHeaderFooterManager : public virtual Aspose::Slides::IBaseSlideHeaderFooterManager
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Efterliknar C#-stil likställdhet för flyttal där två NaN-värden betraktas som lika även om IEC 60559:1989 anger att NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Efterliknar C#-stil likställdhet för flyttal där två NaN-värden betraktas som lika även om IEC 60559:1989 anger att NaN inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för internt bruk. |
| virtual **bool** [get_IsDateTimeVisible](../ibaseslideheaderfootermanager/get_isdatetimevisible/)() | Hämtar värde som indikerar att en datum-tid-platshållare finns. Läs**bool**. |
| virtual **bool** [get_IsFooterVisible](../ibaseslideheaderfootermanager/get_isfootervisible/)() | Hämtar värde som indikerar att en sidfot-platshållare finns. Läs **bool**. |
| virtual **bool** [get_IsSlideNumberVisible](../ibaseslideheaderfootermanager/get_isslidenumbervisible/)() | Hämtar värde som indikerar att en sidnummer-platshållare finns. Läs**bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referenstillräknings-datstruktur associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metod. Aktiverar hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar faktiskt typ av objekt. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet är en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C#-lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vakt-objekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Aktiverar kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referenstillräkning med angivet värde. |
| virtual void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) | Ställer in text för layout-slide datum-tid-platshållare och alla underordnade datum-tid-platshållare. Underordnade platshållare betyder att platshållare finns på beroende slides. Beroende slides använder och är beroende av layout-slide. |
| virtual void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) | Ändrar synlighet för layout-slide datum-tid-platshållare och alla underordnade datum-tid-platshållare. Underordnade platshållare betyder att platshållare finns på beroende slides. Beroende slides använder och är beroende av layout-slide. |
| virtual void [SetDateTimeText](../ibaseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) | Ställer in text för slide datum-tid-platshållare. |
| virtual void [SetDateTimeVisibility](../ibaseslideheaderfootermanager/setdatetimevisibility/)(**bool**) | Ändrar synlighet för slide datum-tid-platshållare. |
| virtual void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) | Ställer in text för layout-slide sidfot-platshållare och alla underordnade sidfot-platshållare. Underordnade platshållare betyder att platshållare finns på beroende slides. Beroende slides använder och är beroende av layout-slide. |
| virtual void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) | Ändrar synlighet för layout-slide sidfot-platshållare och alla underordnade sidfot-platshållare. Underordnade platshållare betyder att platshållare finns på beroende slides. Beroende slides använder och är beroende av master-slide. |
| virtual void [SetFooterText](../ibaseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) | Ställer in text för slide sidfot-platshållare. |
| virtual void [SetFooterVisibility](../ibaseslideheaderfootermanager/setfootervisibility/)(**bool**) | Ändrar synlighet för slide sidfot-platshållare. |
| virtual void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) | Ändrar synlighet för layout-slide sidnummer-platshållare och alla underordnade sidnummer-platshållare. Underordnade platshållare betyder att platshållare finns på beroende slides. Beroende slides använder och är beroende av layout-slide. |
| virtual void [SetSlideNumberVisibility](../ibaseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) | Ändrar synlighet för slide sidnummer-platshållare. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter det n-te mall-argumentet till en svag pekare (istället för delad). Tillåter byte av pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referenstillräkning. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referenstillräkning. Ska inte anropas direkt; använd smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referenstillräkning. Ska inte anropas direkt; använd smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metod. Aktiverar konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vakt-objekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referenstillräkning. Ska inte anropas direkt; använd smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referenstillräkning. Ska inte anropas direkt; använd smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigir alla interna datastrukturer. |

## Se även

* Klass [IBaseSlideHeaderFooterManager](../ibaseslideheaderfootermanager/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)