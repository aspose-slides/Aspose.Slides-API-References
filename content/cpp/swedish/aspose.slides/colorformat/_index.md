---
title: ColorFormat
second_title: Aspose.Slides för C++ API-referens
description: Representerar en färg som används i en presentation.
type: docs
weight: 339
url: /sv/aspose.slides/colorformat/
---
## ColorFormat klass

Representerar en färg som används i en presentation.

```cpp
class ColorFormat : public Aspose::Slides::PVIObject,
                    public Aspose::Slides::IColorFormat
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\>) override | Kopierar färgformat från "color". |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Kontrollerar jämförelse med specificerat objekt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses lika även om IEC 60559:1989 säger att NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses lika även om IEC 60559:1989 säger att NaN inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| **uint8_t** [get_B](./get_b/)() override | Returnerar den blå komponenten i en färg. Alla färgtransformeringar ignoreras. Läs **uint8_t**. |
| [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() override | Returnerar resulterande färg (med alla färgtransformeringar tillämpade). Sätter RGB-färger och rensar alla färgtransformeringar. Läs [System::Drawing::Color](../../system.drawing/color/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) override | Returnerar färgtransformationsoperation som tillämpats på färgen vid angivet index. Läs/skriv [Aspose::Slides::IColorOperation](../icoloroperation/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() override | Returnerar samlingen av färgtransformeringar som tillämpats på en färg. Endast läsning [IColorOperationCollection](../icoloroperationcollection/). |
| [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() override | Returnerar metod för färgdefinition. Läs [Slides::ColorType](../colortype/). |
| **float** [get_FloatB](./get_floatb/)() override | Returnerar den blå komponenten i en färg. Alla färgtransformeringar ignoreras. Läs **float**. |
| **float** [get_FloatG](./get_floatg/)() override | Returnerar den gröna komponenten i en färg. Alla färgtransformeringar ignoreras. Läs **float**. |
| **float** [get_FloatR](./get_floatr/)() override | Returnerar den röda komponenten i en färg. Alla färgtransformeringar ignoreras. Läs **float**. |
| **uint8_t** [get_G](./get_g/)() override | Returnerar den gröna komponenten i en färg. Alla färgtransformeringar ignoreras. |
| **float** [get_Hue](./get_hue/)() override | Returnerar nyanskomponenten i en färg i HSL-representation. Alla färgtransformeringar ignoreras. Läs **float**. |
| **float** [get_Luminance](./get_luminance/)() override | Returnerar luminanskomponenten i en färg i HSL-representation. Alla färgtransformeringar ignoreras. Läs **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Returnerar Parent_Immediate-objekt. Skrivskyddad [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Returnerar förälder [IPresentationComponent](../ipresentationcomponent/). Skrivskyddad [IPresentationComponent](../ipresentationcomponent/). |
| [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() override | Returnerar färgförinställningen. Läs [Slides::PresetColor](../presetcolor/). |
| **uint8_t** [get_R](./get_r/)() override | Returnerar den röda komponenten i en färg. Alla färgtransformeringar ignoreras. Läs **uint8_t**. |
| **float** [get_Saturation](./get_saturation/)() override | Returnerar saturationskomponenten i en färg i HSL-representation. Alla färgtransformeringar ignoreras. Läs **float**. |
| [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() override | Returnerar färgen identifierad av ett färgschema. Läs [Slides::SchemeColor](../schemecolor/). |
| [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() override | Returnerar färgen identifierad av systemets färgtabell. Läs [Slides::SystemColor](../systemcolor/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräkningsdatastruktur associerad med objektet. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Returnerar hash-värde. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar faktisk typ av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar faktiskt ingenting, bara initierar nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar faktiskt ingenting, bara initierar nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_B](./set_b/)(**uint8_t**) override | Ställer in den blå komponenten i en färg. Alla färgtransformeringar ignoreras. Skriv **uint8_t**. |
| void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) override | Returnerar resulterande färg (med alla färgtransformeringar tillämpade). Sätter RGB-färger och rensar alla färgtransformeringar. Skriv [System::Drawing::Color](../../system.drawing/color/). |
| void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) override | Ställer in färgtransformationsoperation som tillämpats på färgen vid angivet index. Läs/skriv [Aspose::Slides::IColorOperation](../icoloroperation/) |
| void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) override | Ställer in metod för färgdefinition. Skriv [Slides::ColorType](../colortype/). |
| void [set_FloatB](./set_floatb/)(**float**) override | Ställer in den blå komponenten i en färg. Alla färgtransformeringar ignoreras. Skriv **float**. |
| void [set_FloatG](./set_floatg/)(**float**) override | Ställer in den gröna komponenten i en färg. Alla färgtransformeringar ignoreras. Skriv **float**. |
| void [set_FloatR](./set_floatr/)(**float**) override | Ställer in den röda komponenten i en färg. Alla färgtransformeringar ignoreras. Skriv **float**. |
| void [set_G](./set_g/)(**uint8_t**) override | Ställer in den gröna komponenten i en färg. Alla färgtransformeringar ignoreras. |
| void [set_Hue](./set_hue/)(**float**) override | Ställer in nyanskomponenten i en färg i HSL-representation. Alla färgtransformeringar ignoreras. Skriv **float**. |
| void [set_Luminance](./set_luminance/)(**float**) override | Ställer in luminanskomponenten i en färg i HSL-representation. Alla färgtransformeringar ignoreras. Skriv **float**. |
| void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) override | Ställer in färgförinställningen. Skriv [Slides::PresetColor](../presetcolor/). |
| void [set_R](./set_r/)(**uint8_t**) override | Ställer in den röda komponenten i en färg. Alla färgtransformeringar ignoreras. Skriv **uint8_t**. |
| void [set_Saturation](./set_saturation/)(**float**) override | Ställer in saturationskomponenten i en färg i HSL-representation. Alla färgtransformeringar ignoreras. Skriv **float**. |
| void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) override | Ställer in färgen identifierad av ett färgschema. Skriv [Slides::SchemeColor](../schemecolor/). |
| void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) override | Ställer in färgen identifierad av systemets färgtabell. Skriv [Slides::SystemColor](../systemcolor/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ställer in n'th mallargument till en svag pekare (istället för delad). Tillåter byte av pekare i containrar till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) override | Returnerar en [System::String](../../system/string/) som representerar det aktuella färgformatet. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |
## Se också

* Klass [PVIObject](../pviobject/)
* Klass [IColorFormat](../icolorformat/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)