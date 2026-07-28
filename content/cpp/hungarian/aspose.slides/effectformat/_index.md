---
title: EffectFormat
second_title: Aspose.Slides C++ API referenciája
description: A forma effektus tulajdonságait képviseli.
type: docs
weight: 846
url: /hu/aspose.slides/effectformat/
---
## EffectFormat osztály

A forma effektus tulajdonságait képviseli.

```cpp
class EffectFormat : public Aspose::Slides::PVIObject,
                     public Aspose::Slides::IEffectFormat
```

## Módszerek

| Metódus | Leírás |
| --- | --- |
| void [DisableBlurEffect](./disableblureffect/)() override | Letiltja az elmosási effektust. |
| void [DisableFillOverlayEffect](./disablefilloverlayeffect/)() override | Letiltja a kitöltés átfedés effektust. |
| void [DisableGlowEffect](./disablegloweffect/)() override | Letiltja a ragyogás effektust. |
| void [DisableInnerShadowEffect](./disableinnershadoweffect/)() override | Letiltja a belső árnyék effektust. |
| void [DisableOuterShadowEffect](./disableoutershadoweffect/)() override | Letiltja a külső árnyék effektust. |
| void [DisablePresetShadowEffect](./disablepresetshadoweffect/)() override | Letiltja az előre beállított árnyék effektust. |
| void [DisableReflectionEffect](./disablereflectioneffect/)() override | Letiltja a tükrözési effektust. |
| void [DisableSoftEdgeEffect](./disablesoftedgeeffect/)() override | Letiltja a lágy szegély effektust. |
| void [EnableFillOverlayEffect](./enablefilloverlayeffect/)() override | Engedélyezi a kitöltés átfedés effektust. |
| void [EnableGlowEffect](./enablegloweffect/)() override | Engedélyezi a ragyogás effektust. |
| void [EnableInnerShadowEffect](./enableinnershadoweffect/)() override | Engedélyezi a belső árnyék effektust. |
| void [EnableOuterShadowEffect](./enableoutershadoweffect/)() override | Engedélyezi a külső árnyék effektust. |
| void [EnablePresetShadowEffect](./enablepresetshadoweffect/)() override | Engedélyezi az előre beállított árnyékok effektusát. |
| void [EnableReflectionEffect](./enablereflectioneffect/)() override | Engedélyezi a tükrözési effektust. |
| void [EnableSoftEdgeEffect](./enablesoftedgeeffect/)() override | Engedélyezi a lágy szegély effektust. |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Összehasonlít a megadott objektummal. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantikával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referencia típusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol a két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol a két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlur](../../aspose.slides.effects/iblur/)\> [get_BlurEffect](./get_blureffect/)() override | Elmosási effektus. Olvassa [Effects::IBlur](../../aspose.slides.effects/iblur/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)\> [get_FillOverlayEffect](./get_filloverlayeffect/)() override | Kitöltés átfedés effektus. Olvassa [Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlow](../../aspose.slides.effects/iglow/)\> [get_GlowEffect](./get_gloweffect/)() override | Ragyogás effektus. Olvassa [Effects::IGlow](../../aspose.slides.effects/iglow/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)\> [get_InnerShadowEffect](./get_innershadoweffect/)() override | Belső árnyék. Olvassa [Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/). |
| **bool** [get_IsNoEffects](./get_isnoeffects/)() override | Igaz értéket ad vissza, ha minden effektus le van tiltva (úgy, mint egy frissen létrehozott, alapértelmezett [EffectFormat](./) objektum). Csak olvasható **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)\> [get_OuterShadowEffect](./get_outershadoweffect/)() override | Külső árnyék. Olvassa [Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Visszaadja a Parent_Immediate objektumot. Csak olvasható [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Visszaadja a szülő [IPresentationComponent](../ipresentationcomponent/) objektumot. Csak olvasható [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)\> [get_PresetShadowEffect](./get_presetshadoweffect/)() override | Előre beállított árnyék. Olvassa [Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflection](../../aspose.slides.effects/ireflection/)\> [get_ReflectionEffect](./get_reflectioneffect/)() override | Tükrözés. Olvassa [Effects::IReflection](../../aspose.slides.effects/ireflection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)\> [get_SoftEdgeEffect](./get_softedgeeffect/)() override | Lágy szegély. Olvassa [Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referenciaszámláló adatstruktúrát. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormatEffectiveData](../ieffectformateffectivedata/)\> [GetEffective](./geteffective/)() override | Lekéri a hatékony effektusformázási adatokat az öröklődés alkalmazásával. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Visszaadja a hash kódot. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() állítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi az egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit sem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában semmit sem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával összehasonlítja az értéktípusú objektumot a nullptr-vel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_BlurEffect](./set_blureffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlur](../../aspose.slides.effects/iblur/)\>) override | Elmosási effektus. Írja [Effects::IBlur](../../aspose.slides.effects/iblur/). |
| void [set_FillOverlayEffect](./set_filloverlayeffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)\>) override | Kitöltés átfedés effektus. Írja [Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/). |
| void [set_GlowEffect](./set_gloweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlow](../../aspose.slides.effects/iglow/)\>) override | Ragyogás effektus. Írja [Effects::IGlow](../../aspose.slides.effects/iglow/). |
| void [set_InnerShadowEffect](./set_innershadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)\>) override | Belső árnyék. Írja [Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/). |
| void [set_OuterShadowEffect](./set_outershadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)\>) override | Külső árnyék. Írja [Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/). |
| void [set_PresetShadowEffect](./set_presetshadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)\>) override | Előre beállított árnyék. Írja [Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/). |
| void [set_ReflectionEffect](./set_reflectioneffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflection](../../aspose.slides.effects/ireflection/)\>) override | Tükrözés. Írja [Effects::IReflection](../../aspose.slides.effects/ireflection/). |
| void [set_SoftEdgeEffect](./set_softedgeeffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)\>) override | Lágy szegély. Írja [Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/). |
| void [SetBlurEffect](./setblureffect/)(**double**, **bool**) override | Beállítja az elmosási effektust. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge mutatóvá állítja (megosztott helyett). Lehetővé teszi a mutatók átkapcsolását a konténerekben gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti, majd visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi az egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() állítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [PVIObject](../pviobject/)
* Osztály [IEffectFormat](../ieffectformat/)
* Névtér [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)