---
title: ColorMatrix
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt een 5x5 matrix voor die de coördinaten voor de RGBAW kleur ruimte bevat. Objecten van deze klasse mogen alleen worden toegewezen met de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime fouten en/of assertiefouten oplevert. Omhul deze klasse altijd in een System::SmartPtr pointer en gebruik deze pointer om hem als argument aan functies door te geven."
type: docs
weight: 27
url: /nl/system.drawing.imaging/colormatrix/
---
## ColorMatrix klasse

Stelt een 5x5-matrix voor die de coördinaten voor de RGBAW-kleurruimte bevat. Objecten van deze klasse mogen alleen worden toegewezen met behulp van de [System::MakeObject()](../../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten oplevert. Omhul deze klasse altijd in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik deze pointer om hem als argument aan functies door te geven.

```cpp
class ColorMatrix : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [ColorMatrix](./colormatrix/)() | Construeert een nieuwe instantie van de [ColorMatrix](./) klasse en initialiseert deze met de waarden van de identiteitsmatrix. |
| [ColorMatrix](./colormatrix/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::ArrayPtr](../../system/arrayptr/)\<**float**\>\>\&) | Construeert een nieuwe instantie van de [ColorMatrix](./) klasse en initialiseert deze met de opgegeven waarden. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van referentietype in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van waardetype in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevend-komma-vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, zelfs al is NaN volgens IEC 60559:1989 niet gelijk aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevend-komma-vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, zelfs al is NaN volgens IEC 60559:1989 niet gelijk aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| **float** [get_Matrix00](./get_matrix00/)() const | Retourneert een waarde in de 0-de rij en 0-de kolom. |
| **float** [get_Matrix01](./get_matrix01/)() const | Retourneert een waarde in de 0-de rij en 1-de kolom. |
| **float** [get_Matrix02](./get_matrix02/)() const | Retourneert een waarde in de 0-de rij en 2-de kolom. |
| **float** [get_Matrix03](./get_matrix03/)() const | Retourneert een waarde in de 0-de rij en 3-de kolom. |
| **float** [get_Matrix04](./get_matrix04/)() const | Retourneert een waarde in de 0-de rij en 4-de kolom. |
| **float** [get_Matrix10](./get_matrix10/)() const | Retourneert een waarde in de 1-de rij en 0-de kolom. |
| **float** [get_Matrix11](./get_matrix11/)() const | Retourneert een waarde in de 1-de rij en 1-de kolom. |
| **float** [get_Matrix12](./get_matrix12/)() const | Retourneert een waarde in de 1-de rij en 2-de kolom. |
| **float** [get_Matrix13](./get_matrix13/)() const | Retourneert een waarde in de 1-de rij en 3-de kolom. |
| **float** [get_Matrix14](./get_matrix14/)() const | Retourneert een waarde in de 1-de rij en 4-de kolom. |
| **float** [get_Matrix20](./get_matrix20/)() const | Retourneert een waarde in de 2-de rij en 0-de kolom. |
| **float** [get_Matrix21](./get_matrix21/)() const | Retourneert een waarde in de 2-de rij en 1-de kolom. |
| **float** [get_Matrix22](./get_matrix22/)() const | Retourneert een waarde in de 2-de rij en 2-de kolom. |
| **float** [get_Matrix23](./get_matrix23/)() const | Retourneert een waarde in de 2-de rij en 3-de kolom. |
| **float** [get_Matrix24](./get_matrix24/)() const | Retourneert een waarde in de 2-de rij en 4-de kolom. |
| **float** [get_Matrix30](./get_matrix30/)() const | Retourneert een waarde in de 3-de rij en 0-de kolom. |
| **float** [get_Matrix31](./get_matrix31/)() const | Retourneert een waarde in de 3-de rij en 1-de kolom. |
| **float** [get_Matrix32](./get_matrix32/)() const | Retourneert een waarde in de 3-de rij en 2-de kolom. |
| **float** [get_Matrix33](./get_matrix33/)() const | Retourneert een waarde in de 3-de rij en 3-de kolom. |
| **float** [get_Matrix34](./get_matrix34/)() const | Retourneert een waarde in de 3-de rij en 4-de kolom. |
| **float** [get_Matrix40](./get_matrix40/)() const | Retourneert een waarde in de 4-de rij en 0-de kolom. |
| **float** [get_Matrix41](./get_matrix41/)() const | Retourneert een waarde in de 4-de rij en 1-de kolom. |
| **float** [get_Matrix42](./get_matrix42/)() const | Retourneert een waarde in de 4-de rij en 2-de kolom. |
| **float** [get_Matrix43](./get_matrix43/)() const | Retourneert een waarde in de 4-de rij en 3-de kolom. |
| **float** [get_Matrix44](./get_matrix44/)() const | Retourneert een waarde in de 4-de rij en 4-de kolom. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het actuele type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| **float** [idx_get](./idx_get/)(int, int) | Retourneert een waarde op de opgegeven rij en kolom. |
| **float** [idx_set](./idx_set/)(int, int, **float**) | Stelt de opgegeven waarde in op de opgegeven locatie in de matrix. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type dat door targetType wordt beschreven. Analoge van C#-operator ‘is’. |
| void [Lock](../../system/object/lock/)() | Implementeert C#-lock()-statement-vergrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-waarschuwingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
| [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-constructor. Kopieert niets, initialiseert slechts een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzings-operator. Kopieert niets, initialiseert slechts een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object met nullptr op referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [set_Matrix00](./set_matrix00/)(**float**) | Stelt een waarde in op de 0-de rij en 0-de kolom. |
| void [set_Matrix01](./set_matrix01/)(**float**) | Stelt een waarde in op de 0-de rij en 1-de kolom. |
| void [set_Matrix02](./set_matrix02/)(**float**) | Stelt een waarde in op de 0-de rij en 2-de kolom. |
| void [set_Matrix03](./set_matrix03/)(**float**) | Stelt een waarde in op de 0-de rij en 3-de kolom. |
| void [set_Matrix04](./set_matrix04/)(**float**) | Stelt een waarde in op de 0-de rij en 4-de kolom. |
| void [set_Matrix10](./set_matrix10/)(**float**) | Stelt een waarde in op de 1-de rij en 0-de kolom. |
| void [set_Matrix11](./set_matrix11/)(**float**) | Stelt een waarde in op de 1-de rij en 1-de kolom. |
| void [set_Matrix12](./set_matrix12/)(**float**) | Stelt een waarde in op de 1-de rij en 2-de kolom. |
| void [set_Matrix13](./set_matrix13/)(**float**) | Stelt een waarde in op de 1-de rij en 3-de kolom. |
| void [set_Matrix14](./set_matrix14/)(**float**) | Stelt een waarde in op de 1-de rij en 4-de kolom. |
| void [set_Matrix20](./set_matrix20/)(**float**) | Stelt een waarde in op de 2-de rij en 0-de kolom. |
| void [set_Matrix21](./set_matrix21/)(**float**) | Stelt een waarde in op de 2-de rij en 1-de kolom. |
| void [set_Matrix22](./set_matrix22/)(**float**) | Stelt een waarde in op de 2-de rij en 2-de kolom. |
| void [set_Matrix23](./set_matrix23/)(**float**) | Stelt een waarde in op de 2-de rij en 3-de kolom. |
| void [set_Matrix24](./set_matrix24/)(**float**) | Stelt een waarde in op de 2-de rij en 4-de kolom. |
| void [set_Matrix30](./set_matrix30/)(**float**) | Stelt een waarde in op de 3-de rij en 0-de kolom. |
| void [set_Matrix31](./set_matrix31/)(**float**) | Stelt een waarde in op de 3-de rij en 1-de kolom. |
| void [set_Matrix32](./set_matrix32/)(**float**) | Stelt een waarde in op de 3-de rij en 2-de kolom. |
| void [set_Matrix33](./set_matrix33/)(**float**) | Stelt een waarde in op de 3-de rij en 3-de kolom. |
| void [set_Matrix34](./set_matrix34/)(**float**) | Stelt een waarde in op de 3-de rij en 4-de kolom. |
| void [set_Matrix40](./set_matrix40/)(**float**) | Stelt een waarde in op de 4-de rij en 0-de kolom. |
| void [set_Matrix41](./set_matrix41/)(**float**) | Stelt een waarde in op de 4-de rij en 1-de kolom. |
| void [set_Matrix42](./set_matrix42/)(**float**) | Stelt een waarde in op de 4-de rij en 2-de kolom. |
| void [set_Matrix43](./set_matrix43/)(**float**) | Stelt een waarde in op de 4-de rij en 3-de kolom. |
| void [set_Matrix44](./set_matrix44/)(**float**) | Stelt een waarde in op de 4-de rij en 4-de kolom. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n-de templates-argument in op een zwakke pointer (in plaats van gedeelde). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het mogelijk om aangepaste objecten naar string te converteren. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C#-lock()-statement-ontgrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-waarschuwingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [Object](../../system/object/)
* Naamruimte [System::Drawing::Imaging](../)
* Bibliotheek [Aspose.Slides](../../)