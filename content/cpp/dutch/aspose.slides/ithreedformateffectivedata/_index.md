---
title: IThreeDFormatEffectiveData
second_title: Aspose.Slides voor C++ API-referentie
description: Onveranderlijk object dat effectieve 3-D-opmaak-eigenschappen vertegenwoordigt.
type: docs
weight: 4174
url: /nl/aspose.slides/ithreedformateffectivedata/
---
## IThreeDFormatEffectiveData klasse


Onveranderlijk object dat effectieve 3-D-opmaak-eigenschappen vertegenwoordigt.

```cpp
class IThreeDFormatEffectiveData : public Aspose::Slides::IThreeDParamSource
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met gebruik van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevende-kommageregel waarbij twee NaN’s als gelijk worden beschouwd, ook al is volgens IEC 60559:1989 NaN niet gelijk aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevende-kommageregel waarbij twee NaN’s als gelijk worden beschouwd, ook al is volgens IEC 60559:1989 NaN niet gelijk aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeBevelEffectiveData](../ishapebeveleffectivedata/)\> [get_BevelBottom](./get_bevelbottom/)() | Retourneert het type van een onderste 3D-schuine rand. Alleen-lezen [IShapeBevelEffectiveData](../ishapebeveleffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeBevelEffectiveData](../ishapebeveleffectivedata/)\> [get_BevelTop](./get_beveltop/)() | Retourneert het type van een bovenste 3D-schuine rand. Alleen-lezen [IShapeBevelEffectiveData](../ishapebeveleffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICameraEffectiveData](../icameraeffectivedata/)\> [get_Camera](./get_camera/)() | Retourneert de instellingen van een camera. Alleen-lezen [ICameraEffectiveData](../icameraeffectivedata/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_ContourColor](./get_contourcolor/)() | Retourneert de kleur van een contour. Alleen-lezen [System::Drawing::Color](../../system.drawing/color/). |
| virtual **double** [get_ContourWidth](./get_contourwidth/)() | Retourneert de breedte van een 3D-contour. Alleen-lezen **double**. |
| virtual **double** [get_Depth](./get_depth/)() | Retourneert de diepte van een 3D-vorm. Alleen-lezen **double**. |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_ExtrusionColor](./get_extrusioncolor/)() | Retourneert de kleur van een extrusie. Alleen-lezen [System::Drawing::Color](../../system.drawing/color/). |
| virtual **double** [get_ExtrusionHeight](./get_extrusionheight/)() | Retourneert de hoogte van een extrusie-effect. Alleen-lezen **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILightRigEffectiveData](../ilightrigeffectivedata/)\> [get_LightRig](./get_lightrig/)() | Retourneert het type van een licht. Alleen-lezen [ILightRigEffectiveData](../ilightrigeffectivedata/). |
| virtual [MaterialPresetType](../materialpresettype/) [get_Material](./get_material/)() | Retourneert het type van een materiaal. Alleen-lezen [MaterialPresetType](../materialpresettype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt het hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het door targetType beschreven type vertegenwoordigt. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert het lock()-statement van C# voor vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-constructor. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object met nullptr op referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Sta toe om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Zou niet direct aangeroepen moeten worden; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Zou niet direct aangeroepen moeten worden; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert het lock()-statement van C# voor ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Zou niet direct aangeroepen moeten worden; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Zou niet direct aangeroepen moeten worden; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Opmerkingen

Deze interface wordt samen met de [IThreeDFormat](../ithreedformat/) interface gebruikt om effectieve opmaakwaarden te retourneren met overerving toegepast. 

## Zie ook

* Klasse [IThreeDParamSource](../ithreedparamsource/)
* Naamruimte [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)