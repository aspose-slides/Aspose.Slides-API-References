---
title: Pen
second_title: Aspose.Slides voor C++ API-referentie
description: "Vertegenwoordigt eigenschappen zoals kleur, breedte enz. van de lijnen en curven die getekend worden. Objecten van deze klasse mogen alleen worden gealloceerd met de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten veroorzaakt. Wikkel deze klasse altijd in een System::SmartPtr pointer en gebruik deze pointer om deze als argument aan functies door te geven."
type: docs
weight: 183
url: /nl/system.drawing/pen/
---
## Pen klasse


Vertegenwoordigt eigenschappen zoals kleur, breedte enz. van de lijnen en curven die getekend worden. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten veroorzaakt. Wikkel deze klasse altijd in een [System::SmartPtr](../../system/smartptr/) pointer en gebruik deze pointer om deze als argument aan functies door te geven.

```cpp
class Pen : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Pen](./)\> [Clone](./clone/)() | Geeft een kopie van het huidige object terug. |
| void [Dispose](./dispose/)() | Vrijgeeft alle operationele bronnen die door het huidige object zijn verkregen. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevend-kommapunten vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevend-kommapunten vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [Drawing2D::PenAlignment](../../system.drawing.drawing2d/penalignment/) [get_Alignment](./get_alignment/)() const | Geeft een waarde terug die de uitlijning van het huidige [Pen](./) object aangeeft. |
| [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\> [get_Brush](./get_brush/)() | Geeft het [Brush](../brush/) object van deze pen terug. |
| [Color](../color/) [get_Color](./get_color/)() const | Geeft de kleur van deze pen terug. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_CompoundArray](./get_compoundarray/)() const | Geeft een reeks waarden terug die een samengestelde pen specificeert. |
| [Drawing2D::DashCap](../../system.drawing.drawing2d/dashcap/) [get_DashCap](./get_dashcap/)() const | Geeft een waarde terug die de cap aangeeft die aan beide uiteinden van een gestippelde lijn wordt gebruikt. |
| **float** [get_DashOffset](./get_dashoffset/)() const | Geeft de afstand terug van het begin van een lijn tot het begin van een stippellijnpatroon. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_DashPattern](./get_dashpattern/)() const | Geeft een reeks terug die een aangepast stippellijnpatroon in een gestippelde lijn aangeeft. |
| [Drawing2D::DashStyle](../../system.drawing.drawing2d/dashstyle/) [get_DashStyle](./get_dashstyle/)() const | Geeft een waarde terug die de stippellijnstijl van het huidige [Pen](./) object aangeeft. |
| [Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/) [get_EndCap](./get_endcap/)() const | Geeft een waarde terug die de eindcap van de huidige [Pen](./) lijn aangeeft. |
| [Drawing2D::LineJoin](../../system.drawing.drawing2d/linejoin/) [get_LineJoin](./get_linejoin/)() const | Geeft een waarde terug die aangeeft hoe de lijnen die door dit [Pen](./) object worden getekend, worden samengevoegd. |
| **float** [get_MiterLimit](./get_miterlimit/)() const | Geeft de limiet van de dikte van de verbinding op een afgeschoten hoek terug. |
| [Drawing2D::PenType](../../system.drawing.drawing2d/pentype/) [get_PenType](./get_pentype/)() const | NIET GEREALISEERD. |
| [Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/) [get_StartCap](./get_startcap/)() const | Geeft een waarde terug die de startcap van de huidige [Pen](./) lijn aangeeft. |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\> [get_Transform](./get_transform/)() | Geeft een kopie van een Matrix-object terug dat de geometrische transformaties voor de pen die door het huidige object wordt gerepresenteerd, specificeert. |
| **float** [get_Width](./get_width/)() const | Geeft de breedte van het huidige [Pen](./) object terug. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van de C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge van de C# [System.Object.GetType()](../../system/object/gettype/) aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type beschrijft dat door targetType wordt gegeven. Analoge van de C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert het lock()-statement van C# voor vergrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/) waakhond-object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van de C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt klonen van aangepaste types mogelijk. |
| void [MultiplyTransform](./multiplytransform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | Vermenigvuldigt de transformatie-matrix van het huidige object met de opgegeven matrix. |
|  [Object](../../system/object/object/)() | Maak object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieconstructor. Kopieert niets, initialiseert alleen een nieuw object en maakt kopiëren van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, initialiseert alleen een nieuw object en maakt kopiëren van subklassen mogelijk. |
|  [Pen](./pen/)(const [Color](../color/)\&) | Construeert een nieuw [Pen](./) object dat de opgegeven kleur representeert. |
|  [Pen](./pen/)(const [Color](../color/)\&, **float**) | Construeert een nieuw [Pen](./) object dat de opgegeven kleur en breedte representeert. |
|  [Pen](./pen/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&) | Construeert een nieuw [Pen](./) object en initialiseert het met het opgegeven [Brush](../brush/) object. |
|  [Pen](./pen/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, **float**) | Construeert een nieuw [Pen](./) object en initialiseert het met het opgegeven [Brush](../brush/) object. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object referentieel met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [ResetTransform](./resettransform/)() | Reset de transformatie-matrix van het huidige object zodat deze een identiteitsmatrix wordt. |
| void [RotateTransform](./rotatetransform/)(**float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | Roteert de lokale geometrische transformatie met de opgegeven hoek in de opgegeven volgorde. |
| void [ScaleTransform](./scaletransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | Schaalt de lokale geometrische transformatie met de opgegeven factoren in de opgegeven volgorde. |
| void [set_Alignment](./set_alignment/)([Drawing2D::PenAlignment](../../system.drawing.drawing2d/penalignment/)) | Stelt de uitlijning van het huidige [Pen](./) object in. |
| void [set_Brush](./set_brush/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&) | Stelt het [Brush](../brush/) object van deze pen in. |
| void [set_Color](./set_color/)(const [Color](../color/)\&) | Stelt de kleur van deze pen in. |
| void [set_CompoundArray](./set_compoundarray/)(const [System::ArrayPtr](../../system/arrayptr/)\<**float**\>\&) | Stelt een reeks waarden in die een samengestelde pen specificeert. |
| void [set_CustomEndCap](./set_customendcap/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::CustomLineCap](../../system.drawing.drawing2d/customlinecap/)\>\&) | Stelt de aangepaste eindcap van de lijn in. |
| void [set_CustomStartCap](./set_customstartcap/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::CustomLineCap](../../system.drawing.drawing2d/customlinecap/)\>\&) | Stelt de aangepaste startcap van de lijn in. |
| void [set_DashCap](./set_dashcap/)([Drawing2D::DashCap](../../system.drawing.drawing2d/dashcap/)) | Stelt een waarde in die de cap specificeert die aan beide uiteinden van een gestippelde lijn wordt gebruikt. |
| void [set_DashOffset](./set_dashoffset/)(**float**) | Stelt de afstand in van het begin van een lijn tot het begin van een stippellijnpatroon. |
| void [set_DashPattern](./set_dashpattern/)(const [System::ArrayPtr](../../system/arrayptr/)\<**float**\>\&) | Stelt een reeks in die een aangepast stippellijnpatroon in een gestippelde lijn specificeert. De reeks bestaat uit getallen die de lengtes van afwisselende streepjes en ruimtes aangeven. |
| void [set_DashStyle](./set_dashstyle/)([Drawing2D::DashStyle](../../system.drawing.drawing2d/dashstyle/)) | Stelt een waarde in die de stippellijnstijl van het huidige [Pen](./) object specificeert. |
| void [set_EndCap](./set_endcap/)([Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/)) | Stelt de eindcap van de huidige [Pen](./) lijn in. |
| void [set_LineJoin](./set_linejoin/)([Drawing2D::LineJoin](../../system.drawing.drawing2d/linejoin/)) | Stelt een waarde in die aangeeft hoe de lijnen die door dit [Pen](./) object worden getekend, worden samengevoegd. |
| void [set_MiterLimit](./set_miterlimit/)(**float**) | Stelt de limiet in van de dikte van de verbinding op een afgeschoten hoek. |
| void [set_StartCap](./set_startcap/)([Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/)) | Stelt de startcap van het huidige [Pen](./) object in. |
| void [set_Transform](./set_transform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) | Stelt een Matrix-object in dat de geometrische transformaties voor de pen die door het huidige object wordt gerepresenteerd, specificeert. |
| void [set_Width](./set_width/)(**float**) | Stelt de breedte van het huidige [Pen](./) object in. |
| void [SetLineCap](./setlinecap/)([Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/), [Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/), [Drawing2D::DashCap](../../system.drawing.drawing2d/dashcap/)) | NIET GEREALISEERD. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in op een zwakke pointer (in plaats van gedeelde). Maakt het mogelijk om pointers in containers te wijzigen naar zwakke modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van de C# [Object.ToString()](../../system/object/tostring/) methode. Maakt het omzetten van aangepaste objecten naar string mogelijk. |
| void [TranslateTransform](./translatetransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | Vertaalt de lokale geometrische transformatie met de opgegeven afmetingen in de opgegeven volgorde. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert de C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert het ontgrendelen van de C# lock() statement. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/) waakhond-object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Verwijdert het object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [Object](../../system/object/)
* Naamruimte [System::Drawing](../)
* Bibliotheek [Aspose.Slides](../../)