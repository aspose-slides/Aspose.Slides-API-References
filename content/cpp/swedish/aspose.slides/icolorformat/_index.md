---
title: IColorFormat
second_title: Aspose.Slides för C++ API-referens
description: Representerar en färg som används i en presentation.
type: docs
weight: 1691
url: /sv/aspose.slides/icolorformat/
---
## IColorFormat klass

Representerar en färg som används i en presentation.

```cpp
class IColorFormat : public Aspose::Slides::IFillParamSource
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](./)\>) | Kopierar färgformat från \"color\". |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual **uint8_t** [get_B](./get_b/)() | Returnerar den blå komponenten av en färg. Alla färgtransformeringar ignoreras. Läs **uint8_t**. |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() | Returnerar resulterande färg (med alla färgtransformeringar tillämpade). Sätter RGB-färger och rensar alla färgtransformeringar. Läs [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) | Returnerar färgtransformationsoperation som tillämpas på färgen vid det angivna indexet. Läs/skriv [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() | Returnerar samlingen av färgtransformeringar som tillämpas på en färg. Endast läs [IColorOperationCollection](../icoloroperationcollection/). |
| virtual [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() | Returnerar färgdefinitionsmetoden. Läs [Slides::ColorType](../colortype/). |
| virtual **float** [get_FloatB](./get_floatb/)() | Returnerar den blå komponenten av en färg. Alla färgtransformeringar ignoreras. Läs **float**. |
| virtual **float** [get_FloatG](./get_floatg/)() | Returnerar den gröna komponenten av en färg. Alla färgtransformeringar ignoreras. Läs **float**. |
| virtual **float** [get_FloatR](./get_floatr/)() | Returnerar den röda komponenten av en färg. Alla färgtransformeringar ignoreras. Läs **float**. |
| virtual **uint8_t** [get_G](./get_g/)() | Returnerar den gröna komponenten av en färg. Alla färgtransformeringar ignoreras. Läs **uint8_t**. |
| virtual **float** [get_Hue](./get_hue/)() | Returnerar nyanskomponenten av en färg i HSL-representation. Alla färgtransformeringar ignoreras. Läs **float**. |
| virtual **float** [get_Luminance](./get_luminance/)() | Returnerar luminanskomponenten av en färg i HSL-representation. Alla färgtransformeringar ignoreras. Läs **float**. |
| virtual [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() | Returnerar färgförinställningen. Läs [Slides::PresetColor](../presetcolor/). |
| virtual **uint8_t** [get_R](./get_r/)() | Returnerar den röda komponenten av en färg. Alla färgtransformeringar ignoreras. Läs **uint8_t**. |
| virtual **float** [get_Saturation](./get_saturation/)() | Returnerar mättnadskomponenten av en färg i HSL-representation. Alla färgtransformeringar ignoreras. Läs **float**. |
| virtual [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() | Returnerar färgen som identifieras av ett färgschema. Läs [Slides::SchemeColor](../schemecolor/). |
| virtual [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() | Returnerar färgen som identifieras av systemets färgtabell. Läs [Slides::SystemColor](../systemcolor/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [set_B](./set_b/)(**uint8_t**) | Sätter den blå komponenten av en färg. Alla färgtransformeringar ignoreras. Skriv **uint8_t**. |
| virtual void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) | Returnerar resulterande färg (med alla färgtransformeringar tillämpade). Sätter RGB-färger och rensar alla färgtransformeringar. Skriv [System::Drawing::Color](../../system.drawing/color/). |
| virtual void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) | Sätt färgtransformationsoperation som tillämpas på färgen vid det angivna indexet. Läs/skriv [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) | Sätter färgdefinitionsmetoden. Skriv [Slides::ColorType](../colortype/). |
| virtual void [set_FloatB](./set_floatb/)(**float**) | Sätter den blå komponenten av en färg. Alla färgtransformeringar ignoreras. Skriv **float**. |
| virtual void [set_FloatG](./set_floatg/)(**float**) | Sätter den gröna komponenten av en färg. Alla färgtransformeringar ignoreras. Skriv **float**. |
| virtual void [set_FloatR](./set_floatr/)(**float**) | Sätter den röda komponenten av en färg. Alla färgtransformeringar ignoreras. Skriv **float**. |
| virtual void [set_G](./set_g/)(**uint8_t**) | Sätter den gröna komponenten av en färg. Alla färgtransformeringar ignoreras. Skriv **uint8_t**. |
| virtual void [set_Hue](./set_hue/)(**float**) | Sätter nyanskomponenten av en färg i HSL-representation. Alla färgtransformeringar ignoreras. Skriv **float**. |
| virtual void [set_Luminance](./set_luminance/)(**float**) | Sätter luminanskomponenten av en färg i HSL-representation. Alla färgtransformeringar ignoreras. Skriv **float**. |
| virtual void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) | Sätter färgförinställningen. Skriv [Slides::PresetColor](../presetcolor/). |
| virtual void [set_R](./set_r/)(**uint8_t**) | Sätter den röda komponenten av en färg. Alla färgtransformeringar ignoreras. Skriv **uint8_t**. |
| virtual void [set_Saturation](./set_saturation/)(**float**) | Sätter mättnadskomponenten av en färg i HSL-representation. Alla färgtransformeringar ignoreras. Skriv **float**. |
| virtual void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) | Sätter färgen identifierad av ett färgschema. Skriv [Slides::SchemeColor](../schemecolor/). |
| virtual void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) | Sätter färgen identifierad av systemets färgtabell. Skriv [Slides::SystemColor](../systemcolor/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätt n'te mallargument till en weak-pekare (istället för shared). Tillåter att byta pekare i behållare till weak-läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) | Returnerar en [System::String](../../system/string/) som representerar det aktuella färgformatet. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar weak-referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar weak-referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Se även

* Klass [IFillParamSource](../ifillparamsource/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)