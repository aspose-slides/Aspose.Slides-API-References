---
title: Rotation3D
second_title: Aspose.Slides voor C++ API-referentie
description: Vertegenwoordigt 3D-rotatie van een diagram.
type: docs
weight: 1327
url: /nl/aspose.slides.charts/rotation3d/
---
## Rotation3D klasse

Vertegenwoordigt 3D-rotatie van een diagram.

```cpp
class Rotation3D : public Aspose::Slides::Charts::IRotation3D,
                   public Aspose::Slides::IDOMObject
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl drijvende-kommagetallen vergelijking waarbij twee NaN’s als gelijk worden beschouwd, ook al is NaN volgens IEC 60559:1989 niet gelijk aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl drijvende-kommagetallen vergelijking waarbij twee NaN’s als gelijk worden beschouwd, ook al is NaN volgens IEC 60559:1989 niet gelijk aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| **uint16_t** [get_DepthPercents](./get_depthpercents/)() override | Geeft de diepte van een 3D-diagram terug als een percentage van de diagrambreedte (tussen 20 en 2000 procent). Lees **uint16_t**. |
| **uint16_t** [get_HeightPercents](./get_heightpercents/)() override | Specificeert de hoogte van een 3-D-diagram als een percentage van de diagrambreedte (tussen 5 en 500 procent). Lees **uint16_t**. |
| **uint8_t** [get_Perspective](./get_perspective/)() override | Geeft de perspectiefwaarde (zichtveld-hoek) voor 3D-diagrammen terug (tussen 0 en 240). Genegeerd als RightAngleAxes-eigenschap waar is. Lees **uint8_t**. |
| **bool** [get_RightAngleAxes](./get_rightangleaxes/)() override | Bepaalt of de diagramassen onder rechte hoeken staan, in plaats van getekend in perspectief. Met andere woorden, het bepaalt of de hoeken van de assen onafhankelijk zijn van de diagramrotatie of -elevatie. Lees **bool**. |
| **int8_t** [get_RotationX](./get_rotationx/)() override | Geeft de rotatiegraad rond de X-as terug, d.w.z. in de Y-richting voor 3D-diagrammen (tussen -90 en 90 graden). De eigenschap komt overeen met het item 21.2.2.157 rotX (X-rotatie) in ECMA-376 en met de “Y Rotation”-optie in PowerPoint 2007+. Lees **int8_t**. |
| **uint16_t** [get_RotationY](./get_rotationy/)() override | Geeft de rotatiegraad rond de Y-as terug, d.w.z. in de X-richting voor 3D-diagrammen (tussen 0 en 360 graden). De eigenschap komt overeen met het item 21.2.2.158 rotY (Y-rotatie) in ECMA-376 en met de “X Rotation”-optie in PowerPoint 2007+. Lees **uint16_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Stelt hashing van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type vertegenwoordigt dat door targetType wordt beschreven. Analoge van de C#-operator ‘is’. |
| void [Lock](../../system/object/lock/)() | Implementeert C#-lock()-statement-vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Stelt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-constructor. Kopieert niets, initialiseert slechts een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, initialiseert slechts een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt waardetype-object met nullptr per referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [set_DepthPercents](./set_depthpercents/)(**uint16_t**) override | Stelt de diepte van een 3D-diagram in als een percentage van de diagrambreedte (tussen 20 en 2000 procent). Schrijf **uint16_t**. |
| void [set_HeightPercents](./set_heightpercents/)(**uint16_t**) override | Specificeert de hoogte van een 3-D-diagram als een percentage van de diagrambreedte (tussen 5 en 500 procent). Schrijf **uint16_t**. |
| void [set_Perspective](./set_perspective/)(**uint8_t**) override | Stelt de perspectiefwaarde (zichtveld-hoek) voor 3D-diagrammen in (tussen 0 en 240). Genegeerd als RightAngleAxes-eigenschap waar is. Schrijf **uint8_t**. |
| void [set_RightAngleAxes](./set_rightangleaxes/)(**bool**) override | Bepaalt of de diagramassen onder rechte hoeken staan, in plaats van getekend in perspectief. Met andere woorden, het bepaalt of de hoeken van de assen onafhankelijk zijn van de diagramrotatie of -elevatie. Schrijf **bool**. |
| void [set_RotationX](./set_rotationx/)(**int8_t**) override | Stelt de rotatiegraad rond de X-as in, d.w.z. in de Y-richting voor 3D-diagrammen (tussen -90 en 90 graden). De eigenschap komt overeen met het item 21.2.2.157 rotX (X-rotatie) in ECMA-376 en met de “Y Rotation”-optie in PowerPoint 2007+. Schrijf **int8_t**. |
| void [set_RotationY](./set_rotationy/)(**uint16_t**) override | Stelt de rotatiegraad rond de Y-as in, d.w.z. in de X-richting voor 3D-diagrammen (tussen 0 en 360 graden). De eigenschap komt overeen met het item 21.2.2.158 rotY (Y-rotatie) in ECMA-376 en met de “X Rotation”-optie in PowerPoint 2007+. Schrijf **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt nth-sjabloon-argument in als zwakke pointer (in plaats van gedeelde). Staat toe om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Stelt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement-ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [IRotation3D](../irotation3d/)
* Klasse [IDOMObject](../../aspose.slides/idomobject/)
* Naamruimte [Aspose::Slides::Charts](../)
* Bibliotheek [Aspose.Slides](../../)