---
title: ISlideShowTransition
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de overgang van een diavoorstelling voor.
type: docs
weight: 3810
url: /nl/aspose.slides/islideshowtransition/
---
## ISlideShowTransition klasse


Stelt de overgang van een diavoorstelling voor.

```cpp
class ISlideShowTransition : public virtual System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C# stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C# stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevendekomma-vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevendekomma-vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual **bool** [get_AdvanceAfter](./get_advanceafter/)() | Dit attribuut specificeert of de diavoorstelling naar de volgende dia gaat na een bepaalde tijd. Lezen **bool**. |
| virtual **uint32_t** [get_AdvanceAfterTime](./get_advanceaftertime/)() | Specificeert de tijd, in milliseconden, waarna de overgang moet starten. Deze instelling kan samen met het advClick-attribuut worden gebruikt. Als dit attribuut niet wordt gespecificeerd, wordt aangenomen dat er geen automatische voortgang zal plaatsvinden. Leest **uint32_t**. |
| virtual **bool** [get_AdvanceOnClick](./get_advanceonclick/)() | Specificeert of een muisklik de dia zal voortzetten of niet. Als dit attribuut niet wordt gespecificeerd, wordt een waarde van true aangenomen. Leest **bool**. |
| virtual **int32_t** [get_Duration](./get_duration/)() | Verkrijgt de duur van het dia-overgangseffect in milliseconden. Lezen **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Sound](./get_sound/)() | Retourneert de ingesloten audiodata. Leest [IAudio](../iaudio/). |
| virtual **bool** [get_SoundIsBuiltIn](./get_soundisbuiltin/)() | Specificeert of dit geluid al dan niet een ingebouwd geluid is. Als dit attribuut op true wordt gezet, wordt de gegenereerde toepassing gewaarschuwd om het name-attribuut van dit geluid in de lijst met ingebouwde geluiden te controleren en kan vervolgens een aangepaste naam of UI tonen indien nodig. Leest **bool**. |
| virtual **bool** [get_SoundLoop](./get_soundloop/)() | Dit attribuut specificeert of het geluid zal herhalen tot het volgende geluids-event zich voordoet in de diavoorstelling. Leest **bool**. |
| virtual [SlideShow::TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/) [get_SoundMode](./get_soundmode/)() | Stelt in of retourneert de geluidsmodus voor de dia-overgang. Leest [TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/). |
| virtual [System::String](../../system/string/) [get_SoundName](./get_soundname/)() | Specificeert een menselijk leesbare naam voor het geluid van de overgang. De [ISlideShowTransition::set_Sound](./set_sound/) moet worden toegewezen om de geluidsnaam te verkrijgen of in te stellen. Leest [System::String](../../system/string/). |
| virtual [SlideShow::TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/) [get_Speed](./get_speed/)() | Specificeert de overgangssnelheid die moet worden gebruikt bij het overgaan van de huidige dia naar de volgende. Leest [TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/). |
| virtual [SlideShow::TransitionType](../../aspose.slides.slideshow/transitiontype/) [get_Type](./get_type/)() | Type van overgang. Leest [TransitionType](../../aspose.slides.slideshow/transitiontype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[SlideShow::ITransitionValueBase](../../aspose.slides.slideshow/itransitionvaluebase/)\> [get_Value](./get_value/)() | [Slide](../slide/) toon overgangswaarde. Alleen-lezen [SlideShow::ITransitionValueBase](../../aspose.slides.slideshow/itransitionvaluebase/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Verkrijgt de referentieteller-datastructuur geassocieerd met het object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Zorgt voor hashing van aangepaste objecten. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Verkrijgt het daadwerkelijke type van het object. Analoge van C# [System.Object.GetType()](../../system/object/gettype/) oproep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type vertegenwoordigt dat wordt beschreven door targetType. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt kopiëren van aangepaste typen mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets werkelijk, initialiseert enkel een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets werkelijk, initialiseert enkel een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_AdvanceAfter](./set_advanceafter/)(**bool**) | Dit attribuut specificeert of de diavoorstelling naar de volgende dia gaat na een bepaalde tijd. Schrijven **bool**. |
| virtual void [set_AdvanceAfterTime](./set_advanceaftertime/)(**uint32_t**) | Specificeert de tijd, in milliseconden, waarna de overgang moet starten. Deze instelling kan samen met het advClick-attribuut worden gebruikt. Als dit attribuut niet wordt gespecificeerd, wordt aangenomen dat er geen automatische voortgang zal plaatsvinden. Schrijft **uint32_t**. |
| virtual void [set_AdvanceOnClick](./set_advanceonclick/)(**bool**) | Specificeert of een muisklik de dia zal voortzetten of niet. Als dit attribuut niet wordt gespecificeerd, wordt een waarde van true aangenomen. Schrijft **bool**. |
| virtual void [set_Duration](./set_duration/)(**int32_t**) | Stelt de duur van het dia-overgangseffect in milliseconden in. Schrijf **int32_t**. |
| virtual void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) | Stelt de ingesloten audiodata in. Schrijft [IAudio](../iaudio/). |
| virtual void [set_SoundIsBuiltIn](./set_soundisbuiltin/)(**bool**) | Specificeert of dit geluid al dan niet een ingebouwd geluid is. Als dit attribuut op true wordt gezet, wordt de gegenereerde toepassing gewaarschuwd om het name-attribuut van dit geluid in de lijst met ingebouwde geluiden te controleren en kan vervolgens een aangepaste naam of UI tonen indien nodig. Schrijft **bool**. |
| virtual void [set_SoundLoop](./set_soundloop/)(**bool**) | Dit attribuut specificeert of het geluid zal herhalen tot het volgende geluids-event zich voordoet in de diavoorstelling. Schrijft **bool**. |
| virtual void [set_SoundMode](./set_soundmode/)([SlideShow::TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/)) | Stelt in of retourneert de geluidsmodus voor de dia-overgang. Schrijft [TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/). |
| virtual void [set_SoundName](./set_soundname/)([System::String](../../system/string/)) | Specificeert een menselijk leesbare naam voor het geluid van de overgang. De [ISlideShowTransition::set_Sound](./set_sound/) moet worden toegewezen om de geluidsnaam te verkrijgen of in te stellen. Schrijft [System::String](../../system/string/). |
| virtual void [set_Speed](./set_speed/)([SlideShow::TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/)) | Specificeert de overgangssnelheid die moet worden gebruikt bij het overgaan van de huidige dia naar de volgende. Schrijft [TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/). |
| virtual void [set_Type](./set_type/)([SlideShow::TransitionType](../../aspose.slides.slideshow/transitiontype/)) | Type van overgang. Schrijft [TransitionType](../../aspose.slides.slideshow/transitiontype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in als zwakke pointer (in plaats van gedeelde). Staat het wisselen van pointers in containers naar zwakke modus toe. |
| int [SharedCount](../../system/object/sharedcount/)() const | Verkrijgt de huidige waarde van de gedeelde referentieteller. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het mogelijk aangepaste objecten naar string te converteren. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt zwakke referentieteller. Moet niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt zwakke referentieteller. Moet niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [Object](../../system/object/)
* Namespace [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)