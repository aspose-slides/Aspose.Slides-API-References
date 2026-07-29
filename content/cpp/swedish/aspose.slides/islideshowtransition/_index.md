---
title: ISlideShowTransition
second_title: Aspose.Slides för C++ API-referens
description: Representerar bildspelsövergång.
type: docs
weight: 3810
url: /sv/aspose.slides/islideshowtransition/
---
## ISlideShowTransition klass


Representerar bildspelets övergång.

```cpp
class ISlideShowTransition : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför objekt av referenstyp i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför objekt av värdetyp i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN-värden betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN-värden betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual **bool** [get_AdvanceAfter](./get_advanceafter/)() | Detta attribut anger om bildspelet ska gå till nästa bild efter en viss tid. Läs **bool**. |
| virtual **uint32_t** [get_AdvanceAfterTime](./get_advanceaftertime/)() | Anger tiden i millisekunder efter vilken övergången ska starta. Denna inställning kan användas tillsammans med advClick-attributet. Om detta attribut inte anges antas att ingen automatisk vidaregång sker. Läs **uint32_t**. |
| virtual **bool** [get_AdvanceOnClick](./get_advanceonclick/)() | Anger om ett musklick ska gå vidare till nästa bild eller inte. Om detta attribut inte anges antas värdet true. Läs **bool**. |
| virtual **int32_t** [get_Duration](./get_duration/)() | Hämtar varaktigheten för bildövergångseffekten i millisekunder. Läs **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Sound](./get_sound/)() | Returnerar den inbäddade ljuddatat. Läs [IAudio](../iaudio/). |
| virtual **bool** [get_SoundIsBuiltIn](./get_soundisbuiltin/)() | Anger om detta ljud är ett inbyggt ljud. Om detta attribut är true får den genererande applikationen kontrollera namn-attributet för detta ljud i dess lista över inbyggda ljud och kan då visa ett anpassat namn eller UI vid behov. Läs **bool**. |
| virtual **bool** [get_SoundLoop](./get_soundloop/)() | Detta attribut anger om ljudet ska loopas tills nästa ljudevent inträffar i bildspelet. Läs **bool**. |
| virtual [SlideShow::TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/) [get_SoundMode](./get_soundmode/)() | Ställer in eller returnerar ljudläge för bildövergång. Läs [TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/). |
| virtual [System::String](../../system/string/) [get_SoundName](./get_soundname/)() | Anger ett människoläsbart namn för övergångens ljud. [ISlideShowTransition::set_Sound](./set_sound/) måste tilldelas för att få eller sätta ljudnamnet. Läs [System::String](../../system/string/). |
| virtual [SlideShow::TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/) [get_Speed](./get_speed/)() | Anger övergångshastigheten som ska användas när man går från aktuell bild till nästa. Läs [TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/). |
| virtual [SlideShow::TransitionType](../../aspose.slides.slideshow/transitiontype/) [get_Type](./get_type/)() | Typ av övergång. Läs [TransitionType](../../aspose.slides.slideshow/transitiontype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[SlideShow::ITransitionValueBase](../../aspose.slides.slideshow/itransitionvaluebase/)\> [get_Value](./get_value/)() | [Slide](../slide/) visningsövergångsvärde. Skrivskyddad [SlideShow::ITransitionValueBase](../../aspose.slides.slideshow/itransitionvaluebase/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknar-datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar faktiska typen för objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anropet. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet är en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-uttalandets låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vakterobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [set_AdvanceAfter](./set_advanceafter/)(**bool**) | Detta attribut anger om bildspelet ska gå till nästa bild efter en viss tid. Skriv **bool**. |
| virtual void [set_AdvanceAfterTime](./set_advanceaftertime/)(**uint32_t**) | Anger tiden i millisekunder efter vilken övergången ska starta. Denna inställning kan användas tillsammans med advClick-attributet. Om detta attribut inte anges antas att ingen automatisk vidaregång sker. Skriv **uint32_t**. |
| virtual void [set_AdvanceOnClick](./set_advanceonclick/)(**bool**) | Anger om ett musklick ska gå vidare till nästa bild eller inte. Om detta attribut inte anges antas värdet true. Skriv **bool**. |
| virtual void [set_Duration](./set_duration/)(**int32_t**) | Ställer in varaktigheten för bildövergångseffekten i millisekunder. Skriv **int32_t**. |
| virtual void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) | Ställer in den inbäddade ljuddatat. Skriv [IAudio](../iaudio/). |
| virtual void [set_SoundIsBuiltIn](./set_soundisbuiltin/)(**bool**) | Anger om detta ljud är ett inbyggt ljud. Om detta attribut är true får den genererande applikationen kontrollera namn-attributet för detta ljud i dess lista över inbyggda ljud och kan då visa ett anpassat namn eller UI vid behov. Skriv **bool**. |
| virtual void [set_SoundLoop](./set_soundloop/)(**bool**) | Detta attribut anger om ljudet ska loopas tills nästa ljudevent inträffar i bildspelet. Skriv **bool**. |
| virtual void [set_SoundMode](./set_soundmode/)([SlideShow::TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/)) | Ställer in eller returnerar ljudläge för bildövergång. Skriv [TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/). |
| virtual void [set_SoundName](./set_soundname/)([System::String](../../system/string/)) | Anger ett människoläsbart namn för övergångens ljud. [ISlideShowTransition::set_Sound](./set_sound/) måste tilldelas för att få eller sätta ljudnamnet. Skriv [System::String](../../system/string/). |
| virtual void [set_Speed](./set_speed/)([SlideShow::TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/)) | Anger övergångshastigheten som ska användas när man går från aktuell bild till nästa. Skriv [TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/). |
| virtual void [set_Type](./set_type/)([SlideShow::TransitionType](../../aspose.slides.slideshow/transitiontype/)) | Typ av övergång. Skriv [TransitionType](../../aspose.slides.slideshow/transitiontype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ställer in n:te mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-uttalandets upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vakterobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Se även

* Klass [Object](../../system/object/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)