---
title: SlideShowTransition
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een diavoorstellingovergang voor.
type: docs
weight: 404
url: /nl/aspose.slides.slideshow/slideshowtransition/
---
## SlideShowTransition klasse

Stelt een diavoorstellingovergang voor.

```cpp
class SlideShowTransition : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::BaseSlide>>,
                            public Aspose::Slides::ISlideShowTransition
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Bepaalt of de twee [SlideShowTransition](./) instanties gelijk zijn. Lezen/schrijven **bool**. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevend-kommapuntenvergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevend-kommapuntenvergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| **bool** [get_AdvanceAfter](./get_advanceafter/)() override | Dit attribuut geeft aan of de diavoorstelling naar de volgende dia gaat na een bepaalde tijd. Lezen **bool**. |
| **uint32_t** [get_AdvanceAfterTime](./get_advanceaftertime/)() override | Geeft de tijd in milliseconden op waarna de overgang moet starten. Deze instelling kan samen met het advClick-attribuut worden gebruikt. Als dit attribuut niet is gespecificeerd, wordt aangenomen dat er geen automatische voortgang plaatsvindt. Lezen **uint32_t**. |
| **bool** [get_AdvanceOnClick](./get_advanceonclick/)() override | Geeft aan of een muisklik de dia zal voortzetten of niet. Als dit attribuut niet is gespecificeerd, wordt een waarde van true aangenomen. Lezen **bool**. |
| **int32_t** [get_Duration](./get_duration/)() override | Haalt de duur van het dia-overgangseffect in milliseconden op. Lezen **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\> [get_Sound](./get_sound/)() override | Retourneert de ingesloten audiogegevens. Lezen [IAudio](../../aspose.slides/iaudio/). |
| **bool** [get_SoundIsBuiltIn](./get_soundisbuiltin/)() override | Geeft aan of dit geluid een ingebouwd geluid is. Als dit attribuut op true staat, wordt de genererende applicatie gewaarschuwd om het naam-attribuut van dit geluid in de lijst met ingebouwde geluiden te controleren en kan vervolgens een aangepaste naam of UI tonen indien nodig. Leest **bool**. |
| **bool** [get_SoundLoop](./get_soundloop/)() override | Dit attribuut geeft aan of het geluid zal blijven herhalen tot het volgende geluid-event in de diavoorstelling plaatsvindt. Lezen **bool**. |
| [TransitionSoundMode](../transitionsoundmode/) [get_SoundMode](./get_soundmode/)() override | Stel de geluidsmodus voor dia-overgang in of retourneer deze. Lezen [TransitionSoundMode](../transitionsoundmode/). |
| [System::String](../../system/string/) [get_SoundName](./get_soundname/)() override | Geeft een menselijk leesbare naam voor het geluid van de overgang op. De [ISlideShowTransition::set_Sound](../../aspose.slides/islideshowtransition/set_sound/) moet worden toegewezen om de geluidsnaam op te halen of in te stellen. Leest [System::String](../../system/string/). |
| [TransitionSpeed](../transitionspeed/) [get_Speed](./get_speed/)() override | Geeft de overgangssnelheid op die gebruikt wordt bij het overgaan van de huidige dia naar de volgende. Lezen [TransitionSpeed](../transitionspeed/). |
| [TransitionType](../transitiontype/) [get_Type](./get_type/)() override | Type van overgang. Lezen [TransitionType](../transitiontype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITransitionValueBase](../itransitionvaluebase/)\> [get_Value](./get_value/)() override | [Slide](../../aspose.slides/slide/) weergave overgangswaarde. Alleen-lezen [ITransitionValueBase](../itransitionvaluebase/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Dient als een hash-functie voor een bepaald type, geschikt voor gebruik in hashing-algoritmen en datastructuren zoals een hashtabel. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleer of het object een instantie van het type vertegenwoordigt dat wordt beschreven door targetType. Analoge van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock() statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert niets echt, initialiseert slechts een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert slechts een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waarde-type object via referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| void [set_AdvanceAfter](./set_advanceafter/)(**bool**) override | Dit attribuut geeft aan of de diavoorstelling naar de volgende dia gaat na een bepaalde tijd. Schrijf **bool**. |
| void [set_AdvanceAfterTime](./set_advanceaftertime/)(**uint32_t**) override | Geeft de tijd in milliseconden op waarna de overgang moet starten. Deze instelling kan samen met het advClick-attribuut worden gebruikt. Als dit attribuut niet is gespecificeerd, wordt aangenomen dat er geen automatische voortgang plaatsvindt. Schrijf **uint32_t**. |
| void [set_AdvanceOnClick](./set_advanceonclick/)(**bool**) override | Geeft aan of een muisklik de dia zal voortzetten of niet. Als dit attribuut niet is gespecificeerd, wordt een waarde van true aangenomen. Schrijf **bool**. |
| void [set_Duration](./set_duration/)(**int32_t**) override | Stelt de duur van het dia-overgangseffect in milliseconden in. Schrijf **int32_t**. |
| void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\>) override | Stelt de ingesloten audiogegevens in. Schrijf [IAudio](../../aspose.slides/iaudio/). |
| void [set_SoundIsBuiltIn](./set_soundisbuiltin/)(**bool**) override | Geeft aan of dit geluid een ingebouwd geluid is. Als dit attribuut op true staat, wordt de genererende applicatie gewaarschuwd om het naam-attribuut van dit geluid in de lijst met ingebouwde geluiden te controleren en kan vervolgens een aangepaste naam of UI tonen indien nodig. Schrijft **bool**. |
| void [set_SoundLoop](./set_soundloop/)(**bool**) override | Dit attribuut geeft aan of het geluid zal blijven herhalen tot het volgende geluid-event in de diavoorstelling plaatsvindt. Schrijf **bool**. |
| void [set_SoundMode](./set_soundmode/)([TransitionSoundMode](../transitionsoundmode/)) override | Stel de geluidsmodus voor dia-overgang in of retourneer deze. Schrijf [TransitionSoundMode](../transitionsoundmode/). |
| void [set_SoundName](./set_soundname/)([System::String](../../system/string/)) override | Geeft een menselijk leesbare naam voor het geluid van de overgang op. De [ISlideShowTransition::set_Sound](../../aspose.slides/islideshowtransition/set_sound/) moet worden toegewezen om de geluidsnaam op te halen of in te stellen. Schrijft [System::String](../../system/string/). |
| void [set_Speed](./set_speed/)([TransitionSpeed](../transitionspeed/)) override | Geeft de overgangssnelheid op die gebruikt moet worden bij het overgaan van de huidige dia naar de volgende. Schrijf [TransitionSpeed](../transitionspeed/). |
| void [set_Type](./set_type/)([TransitionType](../transitiontype/)) override | Type van overgang. Schrijf [TransitionType](../transitiontype/). |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Stel het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Staat toe om pointers in containers naar zwakke modus om te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het mogelijk om aangepaste objecten naar string te converteren. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock() statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [DomObject](../../aspose.slides/domobject/)
* Klasse [ISlideShowTransition](../../aspose.slides/islideshowtransition/)
* Naamruimte [Aspose::Slides::SlideShow](../)
* Bibliotheek [Aspose.Slides](../../)