---
title: SlideShowTransition
second_title: Aspose.Slides för C++ API-referens
description: Representerar bildspelsövergång.
type: docs
weight: 404
url: /sv/aspose.slides.slideshow/slideshowtransition/
---
## SlideShowTransition klass

Representerar bildspelsövergång.

```cpp
class SlideShowTransition : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::BaseSlide>>,
                            public Aspose::Slides::ISlideShowTransition
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Bestämmer om de två [SlideShowTransition](./) instanserna är lika. Läs/skriv **bool**. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses vara lika även om enligt IEC 60559:1989 NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses vara lika även om enligt IEC 60559:1989 NaN inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för intern användning. |
| **bool** [get_AdvanceAfter](./get_advanceafter/)() override | Detta attribut anger om bildspelet ska gå till nästa bild efter en viss tid. Läs **bool**. |
| **uint32_t** [get_AdvanceAfterTime](./get_advanceaftertime/)() override | Anger tiden i millisekunder efter vilken övergången ska starta. Denna inställning kan användas tillsammans med advClick-attributet. Om detta attribut inte specificeras antas att ingen automatisk vidaregång sker. Läs **uint32_t**. |
| **bool** [get_AdvanceOnClick](./get_advanceonclick/)() override | Anger om ett musklick ska gå vidare till nästa bild eller inte. Om detta attribut inte specificeras antas värdet true. Läs **bool**. |
| **int32_t** [get_Duration](./get_duration/)() override | Hämtar varaktigheten för bildövergångseffekten i millisekunder. Läs **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\> [get_Sound](./get_sound/)() override | Returnerar den inbäddade ljuddata. Läs [IAudio](../../aspose.slides/iaudio/). |
| **bool** [get_SoundIsBuiltIn](./get_soundisbuiltin/)() override | Anger om detta ljud är ett inbyggt ljud eller inte. Om detta attribut är satt till true får den genererande applikationen en indikation att kontrollera namn-attributet som specificerats för detta ljud i dess lista över inbyggda ljud och kan då visa ett anpassat namn eller UI vid behov. Läser **bool**. |
| **bool** [get_SoundLoop](./get_soundloop/)() override | Detta attribut anger om ljudet ska loopa tills nästa ljudevent inträffar i bildspelet. Läs **bool**. |
| [TransitionSoundMode](../transitionsoundmode/) [get_SoundMode](./get_soundmode/)() override | Ställer in eller returnerar ljudläge för bildövergång. Läs [TransitionSoundMode](../transitionsoundmode/). |
| [System::String](../../system/string/) [get_SoundName](./get_soundname/)() override | Anger ett människoläsbart namn för övergångsljudet. [ISlideShowTransition::set_Sound](../../aspose.slides/islideshowtransition/set_sound/) måste tilldelas för att hämta eller sätta ljudnamnet. Läser [System::String](../../system/string/). |
| [TransitionSpeed](../transitionspeed/) [get_Speed](./get_speed/)() override | Anger övergångshastigheten som ska användas när man går från aktuell bild till nästa. Läs [TransitionSpeed](../transitionspeed/). |
| [TransitionType](../transitiontype/) [get_Type](./get_type/)() override | Typ av övergång. Läs [TransitionType](../transitiontype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITransitionValueBase](../itransitionvaluebase/)\> [get_Value](./get_value/)() override | [Slide](../../aspose.slides/slide/) visar övergångsvärde. Skrivskyddad [ITransitionValueBase](../itransitionvaluebase/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknar-datastruktur som är associerad med objektet. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Fungerar som hash-funktion för en specifik typ, lämplig för användning i hash-algoritmer och datastrukturer såsom en hash-tabell. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_AdvanceAfter](./set_advanceafter/)(**bool**) override | Detta attribut anger om bildspelet ska gå till nästa bild efter en viss tid. Skriv **bool**. |
| void [set_AdvanceAfterTime](./set_advanceaftertime/)(**uint32_t**) override | Anger tiden i millisekunder efter vilken övergången ska starta. Denna inställning kan användas tillsammans med advClick-attributet. Om detta attribut inte specificeras antas att ingen automatisk vidaregång sker. Skriv **uint32_t**. |
| void [set_AdvanceOnClick](./set_advanceonclick/)(**bool**) override | Anger om ett musklick ska gå vidare till nästa bild eller inte. Om detta attribut inte specificeras antas värdet true. Skriv **bool**. |
| void [set_Duration](./set_duration/)(**int32_t**) override | Sätter varaktigheten för bildövergångseffekten i millisekunder. Skriv **int32_t**. |
| void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\>) override | Sätter den inbäddade ljuddata. Skriv [IAudio](../../aspose.slides/iaudio/). |
| void [set_SoundIsBuiltIn](./set_soundisbuiltin/)(**bool**) override | Anger om detta ljud är ett inbyggt ljud eller inte. Om detta attribut är satt till true får den genererande applikationen en indikation att kontrollera namn-attributet som specificerats för detta ljud i dess lista över inbyggda ljud och kan då visa ett anpassat namn eller UI vid behov. Skriver **bool**. |
| void [set_SoundLoop](./set_soundloop/)(**bool**) override | Detta attribut anger om ljudet ska loopa tills nästa ljudevent inträffar i bildspelet. Skriv **bool**. |
| void [set_SoundMode](./set_soundmode/)([TransitionSoundMode](../transitionsoundmode/)) override | Ställer in eller returnerar ljudläge för bildövergång. Skriv [TransitionSoundMode](../transitionsoundmode/). |
| void [set_SoundName](./set_soundname/)([System::String](../../system/string/)) override | Anger ett människoläsbart namn för övergångsljudet. [ISlideShowTransition::set_Sound](../../aspose.slides/islideshowtransition/set_sound/) måste tilldelas för att hämta eller sätta ljudnamnet. Skriver [System::String](../../system/string/). |
| void [set_Speed](./set_speed/)([TransitionSpeed](../transitionspeed/)) override | Anger övergångshastigheten som ska användas när man går från aktuell bild till nästa. Skriv [TransitionSpeed](../transitionspeed/). |
| void [set_Type](./set_type/)([TransitionType](../transitiontype/)) override | Typ av övergång. Skriv [TransitionType](../transitiontype/). |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Sätt det n:te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i containrar till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräkning. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräkning. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metod. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräkning. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräkning. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Friger alla interna datastrukturer. |

## Se även

* Klass [DomObject](../../aspose.slides/domobject/)
* Klass [ISlideShowTransition](../../aspose.slides/islideshowtransition/)
* Namnrymd [Aspose::Slides::SlideShow](../)
* Bibliotek [Aspose.Slides](../../)