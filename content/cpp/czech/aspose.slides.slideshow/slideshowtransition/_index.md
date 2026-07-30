---
title: SlideShowTransition
second_title: Aspose.Slides pro C++ – reference API
description: Representuje přechod prezentace.
type: docs
weight: 404
url: /cs/aspose.slides.slideshow/slideshowtransition/
---
## SlideShowTransition třída

Reprezentuje přechod prezentace.

```cpp
class SlideShowTransition : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::BaseSlide>>,
                            public Aspose::Slides::ISlideShowTransition
```

## Metody

| Metoda | Popis |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Určuje, zda jsou dvě instance [SlideShowTransition](./) rovny. Čtení/zápis **bool**. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| **bool** [get_AdvanceAfter](./get_advanceafter/)() override | Tento atribut určuje, zda se prezentace přesune na další snímek po určité době. Čtení **bool**. |
| **uint32_t** [get_AdvanceAfterTime](./get_advanceaftertime/)() override | Určuje čas v milisekundách, po kterém by měl přechod začít. Toto nastavení může být použito spolu s atributem advClick. Pokud není tento atribut zadán, předpokládá se, že nedojde k automatickému postupu. Čtení **uint32_t**. |
| **bool** [get_AdvanceOnClick](./get_advanceonclick/)() override | Určuje, zda kliknutí myší posune snímek nebo ne. Pokud není tento atribut zadán, předpokládá se hodnota true. Čtení **bool**. |
| **int32_t** [get_Duration](./get_duration/)() override | Získává dobu trvání efektu přechodu snímku v milisekundách. Čtení **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\> [get_Sound](./get_sound/)() override | Vrací vložená audio data. Čtení [IAudio](../../aspose.slides/iaudio/). |
| **bool** [get_SoundIsBuiltIn](./get_soundisbuiltin/)() override | Určuje, zda je tento zvuk vestavěný zvuk nebo ne. Pokud je tento atribut nastaven na true, generující aplikace je upozorněna, aby zkontrolovala atribut name uvedený pro tento zvuk v její seznamu vestavěných zvuků a může pak zobrazit vlastní název nebo UI podle potřeby. Čte **bool**. |
| **bool** [get_SoundLoop](./get_soundloop/)() override | Tento atribut určuje, zda se zvuk bude opakovat, dokud nedojde k dalšímu zvukovému události v prezentaci. Čtení **bool**. |
| [TransitionSoundMode](../transitionsoundmode/) [get_SoundMode](./get_soundmode/)() override | Nastavuje nebo vrací režim zvuku pro přechod snímku. Čtení [TransitionSoundMode](../transitionsoundmode/). |
| [System::String](../../system/string/) [get_SoundName](./get_soundname/)() override | Určuje čitelný název zvuku přechodu. [ISlideShowTransition::set_Sound](../../aspose.slides/islideshowtransition/set_sound/) musí být přiřazen pro získání nebo nastavení názvu zvuku. Čte [System::String](../../system/string/). |
| [TransitionSpeed](../transitionspeed/) [get_Speed](./get_speed/)() override | Určuje rychlost přechodu, která se použije při přechodu z aktuálního snímku na další. Čtení [TransitionSpeed](../transitionspeed/). |
| [TransitionType](../transitiontype/) [get_Type](./get_type/)() override | Typ přechodu. Čtení [TransitionType](../transitiontype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITransitionValueBase](../itransitionvaluebase/)\> [get_Value](./get_value/)() override | [Slide](../../aspose.slides/slide/) ukazuje hodnotu přechodu. Pouze pro čtení [ITransitionValueBase](../itransitionvaluebase/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získává datovou strukturu počítadla referencí spojenou s objektem. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Slouží jako hash funkce pro konkrétní typ, vhodná pro použití v hashovacích algoritmech a datových strukturách jako hash tabulka. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získává skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock(). Volat přímo nebo použít objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytváří objekt. Inicializuje všechny interní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený čítač referencí o zadanou hodnotu. |
| void [set_AdvanceAfter](./set_advanceafter/)(**bool**) override | Tento atribut určuje, zda se prezentace přesune na další snímek po určité době. Zápis **bool**. |
| void [set_AdvanceAfterTime](./set_advanceaftertime/)(**uint32_t**) override | Určuje čas v milisekundách, po kterém by měl přechod začít. Toto nastavení může být použito spolu s atributem advClick. Pokud není tento atribut zadán, předpokládá se, že nedojde k automatickému postupu. Zápis **uint32_t**. |
| void [set_AdvanceOnClick](./set_advanceonclick/)(**bool**) override | Určuje, zda kliknutí myší posune snímek nebo ne. Pokud není tento atribut zadán, předpokládá se hodnota true. Zápis **bool**. |
| void [set_Duration](./set_duration/)(**int32_t**) override | Nastavuje dobu trvání efektu přechodu snímku v milisekundách. Zápis **int32_t**. |
| void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\>) override | Nastavuje vložená audio data. Zápis [IAudio](../../aspose.slides/iaudio/). |
| void [set_SoundIsBuiltIn](./set_soundisbuiltin/)(**bool**) override | Určuje, zda je tento zvuk vestavěný zvuk nebo ne. Pokud je tento atribut nastaven na true, generující aplikace je upozorněna, aby zkontrolovala atribut name uvedený pro tento zvuk v její seznamu vestavěných zvuků a může pak zobrazit vlastní název nebo UI podle potřeby. Zápis **bool**. |
| void [set_SoundLoop](./set_soundloop/)(**bool**) override | Tento atribut určuje, zda se zvuk bude opakovat, dokud nedojde k dalšímu zvukovému události v prezentaci. Zápis **bool**. |
| void [set_SoundMode](./set_soundmode/)([TransitionSoundMode](../transitionsoundmode/)) override | Nastavuje nebo vrací režim zvuku pro přechod snímku. Zápis [TransitionSoundMode](../transitionsoundmode/). |
| void [set_SoundName](./set_soundname/)([System::String](../../system/string/)) override | Určuje čitelný název zvuku přechodu. [ISlideShowTransition::set_Sound](../../aspose.slides/islideshowtransition/set_sound/) musí být přiřazen pro získání nebo nastavení názvu zvuku. Zápis [System::String](../../system/string/). |
| void [set_Speed](./set_speed/)([TransitionSpeed](../transitionspeed/)) override | Určuje rychlost přechodu, která se použije při přechodu z aktuálního snímku na další. Zápis [TransitionSpeed](../transitionspeed/). |
| void [set_Type](./set_type/)([TransitionType](../transitiontype/)) override | Typ přechodu. Zápis [TransitionType](../transitiontype/). |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Nastaví n-tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepínat ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získává aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení pomocí C# lock(). Volat přímo nebo použít objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niči objekt. Uvolňuje všechny interní datové struktury. |

## Viz také

* Třída [DomObject](../../aspose.slides/domobject/)
* Třída [ISlideShowTransition](../../aspose.slides/islideshowtransition/)
* Jmenný prostor [Aspose::Slides::SlideShow](../)
* Knihovna [Aspose.Slides](../../)