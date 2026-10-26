---
title: IRotation3D
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de 3D-rotatie van een diagram voor.
type: docs
weight: 1171
url: /nl/aspose.slides.charts/irotation3d/
---
## IRotation3D klasse


Stelt de 3D-rotatie van een diagram voor.

```cpp
class IRotation3D : public virtual System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-achtige zwevendekomma-vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-achtige zwevendekomma-vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor interne doeleinden. |
| virtual **uint16_t** [get_DepthPercents](./get_depthpercents/)() | Retourneert de diepte van een 3D-diagram als een percentage van de diagrambreedte (tussen 20 en 2000 procent). Lezen **uint16_t**. |
| virtual **uint16_t** [get_HeightPercents](./get_heightpercents/)() | Specificeert de hoogte van een 3-D-diagram als een percentage van de diagrambreedte (tussen 5 en 500 procent). Lezen **uint16_t**. |
| virtual **uint8_t** [get_Perspective](./get_perspective/)() | Retourneert de perspectiefwaarde (zichtveldhoek) voor 3D-diagrammen (tussen 0 en 100). Genegeerd als RightAngleAxes-eigenschapswaarde true is. Lezen **uint8_t**. |
| virtual **bool** [get_RightAngleAxes](./get_rightangleaxes/)() | Bepaalt of de diagramassen onder rechte hoeken staan, in plaats van in perspectief getekend. Met andere woorden, het bepaalt of de hoeken van de assen onafhankelijk zijn van diagramrotatie of -elevatie. Lezen **bool**. |
| virtual **int8_t** [get_RotationX](./get_rotationx/)() | Retourneert het rotatie-graadcijfer rond de X-as, d.w.z. in de Y-richting voor 3D-diagrammen (tussen -90 en 90 graden). De eigenschap komt overeen met het item 21.2.2.157 rotX (X Rotatie) in ECMA-376 en met de optie "Y Rotation" in PowerPoint 2007+. Lezen **int8_t**. |
| virtual **uint16_t** [get_RotationY](./get_rotationy/)() | Retourneert het rotatie-graadcijfer rond de Y-as, d.w.z. in de X-richting voor 3D-diagrammen (tussen 0 en 360 graden). De eigenschap komt overeen met het item 21.2.158 rotY (Y Rotatie) in ECMA-376 en met de optie "X Rotation" in PowerPoint 2007+. Lezen **uint16_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt hash-generatie van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analog van C# [System.Object.GetType()](../../system/object/gettype/) aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analog van de C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert de C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt het klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt een object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert feitelijk niets, initialiseert slechts een nieuw object en maakt het kopiëren van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert feitelijk niets, initialiseert slechts een nieuw object en maakt het kopiëren van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentieel een waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_DepthPercents](./set_depthpercents/)(**uint16_t**) | Stelt de diepte van een 3D-diagram in als een percentage van de diagrambreedte (tussen 20 en 2000 procent). Schrijven **uint16_t**. |
| virtual void [set_HeightPercents](./set_heightpercents/)(**uint16_t**) | Specificeert de hoogte van een 3-D-diagram als een percentage van de diagrambreedte (tussen 5 en 500 procent). Schrijven **uint16_t**. |
| virtual void [set_Perspective](./set_perspective/)(**uint8_t**) | Stelt de perspectiefwaarde (zichtveldhoek) voor 3D-diagrammen in (tussen 0 en 100). Genegeerd als RightAngleAxes-eigenschapswaarde true is. Schrijven **uint8_t**. |
| virtual void [set_RightAngleAxes](./set_rightangleaxes/)(**bool**) | Bepaalt of de diagramassen onder rechte hoeken staan, in plaats van in perspectief getekend. Met andere woorden, dit bepaalt of de hoeken van de assen onafhankelijk zijn van diagramrotatie of -elevatie. Schrijven **bool**. |
| virtual void [set_RotationX](./set_rotationx/)(**int8_t**) | Stelt het rotatie-graadcijfer rond de X-as in, d.w.z. in de Y-richting voor 3D-diagrammen (tussen -90 en 90 graden). De eigenschap komt overeen met het item 21.2.2.157 rotX (X Rotatie) in ECMA-376 en met de optie "Y Rotation" in PowerPoint 2007+. Schrijven **int8_t**. |
| virtual void [set_RotationY](./set_rotationy/)(**uint16_t**) | Stelt het rotatie-graadcijfer rond de Y-as in, d.w.z. in de X-richting voor 3D-diagrammen (tussen 0 en 360 graden). De eigenschap komt overeen met het item 21.2.2.158 rotY (Y Rotatie) in ECMA-376 en met de optie "X Rotation" in PowerPoint 2007+. Schrijven **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Hiermee kunnen pointers in containers naar zwakke modus worden geschoven. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert de C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert de C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [Object](../../system/object/)
* Naamruimte [Aspose::Slides::Charts](../)
* Bibliotheek [Aspose.Slides](../../)