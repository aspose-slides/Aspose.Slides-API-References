---
title: Reflection
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een reflectie-effect voor.
type: docs
weight: 1067
url: /nl/aspose.slides.effects/reflection/
---
## Reflectieklasse


Stelt een [Reflection](./) effect voor.

```cpp
class Reflection : public Aspose::Slides::Effects::IReflection,
                   public Aspose::Slides::Effects::IVisualEffect,
                   public Aspose::Slides::IPVIObject
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Bepaalt of de opgegeven [Reflection](./) gelijk is aan de huidige [Reflection](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevend-kommagelijkende vergelijking waarbij twee NaN’s als gelijk worden beschouwd, ook al is NaN volgens IEC 60559:1989 niet gelijk aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevend-kommagelijkende vergelijking waarbij twee NaN’s als gelijk worden beschouwd, ook al is NaN volgens IEC 60559:1989 niet gelijk aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor interne doeleinden. |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) radius. Lezen **double**. |
| **float** [get_Direction](./get_direction/)() override | Richting van reflectie. Lezen **float**. |
| **double** [get_Distance](./get_distance/)() override | Afstand van reflectie. Lezen **double**. |
| **float** [get_EndPosAlpha](./get_endposalpha/)() override | Bepaalt de eindpositie (langs de alfa-gradienthelling) van de eind-alfa-waarde (percenten). Lezen **float**. |
| **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() override | Eind-reflectie-opperdoorzichtigheid (percenten). Lezen **float**. |
| **float** [get_FadeDirection](./get_fadedirection/)() override | Bepaalt de richting om de reflectie te verschuiven (hoek). Lezen **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Geeft bovenliggend [IPresentationComponent](../../aspose.slides/ipresentationcomponent/) terug. Alleen-lezen [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | Rechthoek-uitlijning. Lezen [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | Bepaalt of de reflectie moet meedraaien met de vorm wanneer de vorm wordt geroteerd. Lezen **bool**. |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | Bepaalt de horizontale schaalfactor; negatieve skalering veroorzaakt een omkering (percenten). Lezen **double**. |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | Bepaalt de verticale schaalfactor; negatieve skalering veroorzaakt een omkering (percenten). Lezen **double**. |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | Bepaalt de horizontale scheefhoek. Lezen **double**. |
| **double** [get_SkewVertical](./get_skewvertical/)() override | Bepaalt de verticale scheefhoek. Lezen **double**. |
| **float** [get_StartPosAlpha](./get_startposalpha/)() override | Bepaalt de startpositie (langs de alfa-gradienthelling) van de start-alfa-waarde (percenten). Lezen **float**. |
| **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() override | Start-reflectie-opperdoorzichtigheid (percenten). Lezen **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | Versie. Alleen-lezen **uint32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die bij het object hoort. |
| [System::SharedPtr](../../system/sharedptr/)\<[IReflectionEffectiveData](../ireflectioneffectivedata/)\> [GetEffective](./geteffective/)() override | Haalt effectieve [Reflection](./)-effectgegevens op met de toegebrachte overerving. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Dient als hash-functie voor een bepaald type. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analogie van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type vertegenwoordigt dat wordt beschreven door targetType. Analogie van de C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-waarschuwingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt een object aan. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-constructor. Kopieert niets echt, initialiseert gewoon een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert gewoon een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een referentietype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) radius. Schrijf **double**. |
| void [set_Direction](./set_direction/)(**float**) override | Richting van reflectie. Schrijf **float**. |
| void [set_Distance](./set_distance/)(**double**) override | Afstand van reflectie. Schrijf **double**. |
| void [set_EndPosAlpha](./set_endposalpha/)(**float**) override | Bepaalt de eindpositie (langs de alfa-gradienthelling) van de eind-alfa-waarde (percenten). Schrijf **float**. |
| void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) override | Eind-reflectie-opperdoorzichtigheid (percenten). Schrijf **float**. |
| void [set_FadeDirection](./set_fadedirection/)(**float**) override | Bepaalt de richting om de reflectie te verschuiven (hoek). Schrijf **float**. |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | Rechthoek-uitlijning. Schrijf [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | Bepaalt of de reflectie moet meedraaien met de vorm wanneer de vorm wordt geroteerd. Schrijf **bool**. |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | Bepaalt de horizontale schaalfactor; negatieve skalering veroorzaakt een omkering (percenten). Schrijf **double**. |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | Bepaalt de verticale schaalfactor; negatieve skalering veroorzaakt een omkering (percenten). Schrijf **double**. |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | Bepaalt de horizontale scheefhoek. Schrijf **double**. |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | Bepaalt de verticale scheefhoek. Schrijf **double**. |
| void [set_StartPosAlpha](./set_startposalpha/)(**float**) override | Bepaalt de startpositie (langs de alfa-gradienthelling) van de start-alfa-waarde (percenten). Schrijf **float**. |
| void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) override | Start-reflectie-opperdoorzichtigheid (percenten). Schrijf **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n-de sjabloonargument in als een zwakke pointer (in plaats van gedeelde). Maakt het wisselen van pointers in containers naar zwakke modus mogelijk. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-waarschuwingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijgeeft alle interne gegevensstructuren. |

## Zie ook

* Class [IReflection](../ireflection/)
* Class [IVisualEffect](../ivisualeffect/)
* Class [IPVIObject](../../aspose.slides/ipviobject/)
* Namespace [Aspose::Slides::Effects](../)
* Library [Aspose.Slides](../../)