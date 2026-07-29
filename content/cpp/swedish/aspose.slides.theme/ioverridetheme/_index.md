---
title: IOverrideTheme
second_title: Aspose.Slides för C++ API-referens
description: Representerar ett åsidosättande tema.
type: docs
weight: 391
url: /sv/aspose.slides.theme/ioverridetheme/
---
## IOverrideTheme klass


Representerar ett åsidosättande tema.

```cpp
class IOverrideTheme : public virtual Aspose::Slides::Theme::ITheme
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual void [Clear](./clear/)() | Sätt [ColorScheme](../colorscheme/), [FontScheme](../fontscheme/), [FormatScheme](../formatscheme/) till null för att inaktivera all åsidosättning med detta temaattribut. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för internt bruk. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ColorFormat](../itheme/get_colorformat/)([ColorSchemeIndex](../../aspose.slides/colorschemeindex/)) |  |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorScheme](../icolorscheme/)\> [get_ColorScheme](../itheme/get_colorscheme/)() | Returnerar färgschemat. Skrivskyddad [IColorScheme](../icolorscheme/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontScheme](../ifontscheme/)\> [get_FontScheme](../itheme/get_fontscheme/)() | Returnerar font-schemat. Skrivskyddad [IFontScheme](../ifontscheme/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormatScheme](../iformatscheme/)\> [get_FormatScheme](../itheme/get_formatscheme/)() | Returnerar shape-formatschemat. Skrivskyddad [IFormatScheme](../iformatscheme/). |
| virtual **bool** [get_IsEmpty](./get_isempty/)() | Sant värde betyder att [ColorScheme](../colorscheme/), [FontScheme](../fontscheme/), [FormatScheme](../formatscheme/) är null och all åsidosättning med detta temaattribut är inaktiverad. Skrivskyddad **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Returnerar presentationen. Skrivskyddad [IPresentation](../../aspose.slides/ipresentation/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknardatastruktur associerad med objektet. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../ithemeeffectivedata/)\> [GetEffective](../itheme/geteffective/)() | Hämtar effektiv temadata med arv tillämpat. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metod. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar faktisk typ av objekt. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual void [InitColorScheme](./initcolorscheme/)() | Initiera [ColorScheme](../colorscheme/) med nytt objekt för att åsidosätta [ColorScheme](../colorscheme/) av InheritedTheme. |
| virtual void [InitColorSchemeFrom](./initcolorschemefrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorScheme](../icolorscheme/)\>) | Initiera [ColorScheme](../colorscheme/) med nytt objekt för att åsidosätta [ColorScheme](../colorscheme/) av InheritedTheme. |
| virtual void [InitColorSchemeFromInherited](./initcolorschemefrominherited/)() | Initiera [ColorScheme](../colorscheme/) med nytt objekt för att åsidosätta [ColorScheme](../colorscheme/) av InheritedTheme. och initiera data för detta nya objekt med data från [ColorScheme](../colorscheme/) av InheritedTheme. |
| virtual void [InitFontScheme](./initfontscheme/)() | Initiera [FontScheme](../fontscheme/) med nytt objekt för att åsidosätta [FontScheme](../fontscheme/) av InheritedTheme. |
| virtual void [InitFontSchemeFrom](./initfontschemefrom/)([System::SharedPtr](../../system/sharedptr/)\<[IFontScheme](../ifontscheme/)\>) | Initiera [FontScheme](../fontscheme/) med nytt objekt för att åsidosätta [FontScheme](../fontscheme/) av InheritedTheme. |
| virtual void [InitFontSchemeFromInherited](./initfontschemefrominherited/)() | Initiera [FontScheme](../fontscheme/) med nytt objekt för att åsidosätta [FontScheme](../fontscheme/) av InheritedTheme. och initiera data för detta nya objekt med data från [FontScheme](../fontscheme/) av InheritedTheme. |
| virtual void [InitFormatScheme](./initformatscheme/)() | Initiera [FormatScheme](../formatscheme/) med nytt objekt för att åsidosätta [FormatScheme](../formatscheme/) av InheritedTheme. |
| virtual void [InitFormatSchemeFrom](./initformatschemefrom/)([System::SharedPtr](../../system/sharedptr/)\<[IFormatScheme](../iformatscheme/)\>) | Initiera [FormatScheme](../formatscheme/) med nytt objekt för att åsidosätta [FormatScheme](../formatscheme/) av InheritedTheme. |
| virtual void [InitFormatSchemeFromInherited](./initformatschemefrominherited/)() | Initiera [FormatScheme](../formatscheme/) med nytt objekt för att åsidosätta [FormatScheme](../formatscheme/) av InheritedTheme. och initiera data för detta nya objekt med data från [FormatScheme](../formatscheme/) av InheritedTheme. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollera om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-sentry-objekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräkning med angivet värde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätt n:te mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräkning. bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräkning. bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metod. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-sentry-objekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräkning. bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräkning. bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Se även

* Klass [ITheme](../itheme/)
* Namnrymd [Aspose::Slides::Theme](../)
* Bibliotek [Aspose.Slides](../../)