---
title: IReflection
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een reflectie-effect voor.
type: docs
weight: 937
url: /nl/aspose.slides.effects/ireflection/
---
## IReflection klasse


Representeert een reflectie-effect.

```cpp
class IReflection : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                    public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IReflectionEffectiveData>>
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C# stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waarde-type-objecten in C# stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevend-kommagelijk vergelijking waarbij twee NaN's als gelijk worden beschouwd, zelfs hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevend-kommagelijk vergelijking waarbij twee NaN's als gelijk worden beschouwd, zelfs hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) radius. Lezen **double**. |
| virtual **float** [get_Direction](./get_direction/)() | Richting van reflectie. Lezen **float**. |
| virtual **double** [get_Distance](./get_distance/)() | Afstand van reflectie. Lezen **double**. |
| virtual **float** [get_EndPosAlpha](./get_endposalpha/)() | Specificeert de eindpositie (langs de alfaclauwheidhelling) van de eindalpha-waarde (procenten). Lezen **float**. |
| virtual **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() | Eindreflectie-opaciteit. (procenten). Lezen **float**. |
| virtual **float** [get_FadeDirection](./get_fadedirection/)() | Specificeert de richting om de reflectie te verplaatsen. (hoek). Lezen **float**. |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | Rechthoekuitlijning. Lezen [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | Specificeert of de reflectie moet roteren met de vorm als de vorm wordt geroteerd. Lezen **bool**. |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | Specificeert de horizontale schaalfactor, negatieve schaal veroorzaakt een omkering. (procenten) Lezen **double**. |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | Specificeert de verticale schaalfactor, negatieve schaal veroorzaakt een omkering. (procenten) Lezen **double**. |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | Specificeert de horizontale scheefhoek. Lezen **double**. |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | Specificeert de verticale scheefhoek. Lezen **double**. |
| virtual **float** [get_StartPosAlpha](./get_startposalpha/)() | Specificeert de startpositie (langs de alfaclauwheidhelling) van de startalpha-waarde (procenten). Lezen **float**. |
| virtual **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() | Beginnende reflectie-opaciteit. (procenten). Lezen **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt referentieteller gegevensstructuur op die bij het object hoort. |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | Haalt effectieve gegevens op met de toegepaste overerving. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analog van C# [System.Object.GetType()](../../system/object/gettype/) aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleer of het object een instantie van het door targetType beschreven type vertegenwoordigt. Analog van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock() statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copyconstructor. Kopieert niets, echt, initialiseert alleen een nieuw object en maakt kopiëren van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, echt, initialiseert alleen een nieuw object en maakt kopiëren van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentie-waarde type object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) radius. Schrijf **double**. |
| virtual void [set_Direction](./set_direction/)(**float**) | Richting van reflectie. Schrijf **float**. |
| virtual void [set_Distance](./set_distance/)(**double**) | Afstand van reflectie. Schrijf **double**. |
| virtual void [set_EndPosAlpha](./set_endposalpha/)(**float**) | Specificeert de eindpositie (langs de alfaclauwheidhelling) van de eindalpha-waarde (procenten). Schrijf **float**. |
| virtual void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) | Eindreflectie-opaciteit. (procenten). Schrijf **float**. |
| virtual void [set_FadeDirection](./set_fadedirection/)(**float**) | Specificeert de richting om de reflectie te verplaatsen. (hoek). Schrijf **float**. |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | Rechthoekuitlijning. Schrijf [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | Specificeert of de reflectie moet roteren met de vorm als de vorm wordt geroteerd. Schrijf **bool**. |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | Specificeert de horizontale schaalfactor, negatieve schaal veroorzaakt een omkering. (procenten) Schrijf **double**. |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | Specificeert de verticale schaalfactor, negatieve schaal veroorzaakt een omkering. (procenten) Schrijf **double**. |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | Specificeert de horizontale scheefhoek. Schrijf **double**. |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | Specificeert de verticale scheefhoek. Schrijf **double**. |
| virtual void [set_StartPosAlpha](./set_startposalpha/)(**float**) | Specificeert de startpositie (langs de alfaclauwheidhelling) van de startalpha-waarde (procenten). Schrijf **float**. |
| virtual void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) | Beginnende reflectie-opaciteit. (procenten). Schrijf **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stel het n'te sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Staat het wisselen van pointers in containers naar zwakke modus toe. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock() statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne gegevensstructuren. |

## Zie ook

* Klasse [IImageTransformOperation](../iimagetransformoperation/)
* Klasse [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* Naamruimte [Aspose::Slides::Effects](../)
* Bibliotheek [Aspose.Slides](../../)