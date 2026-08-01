---
title: IXpsOptions
second_title: Aspose.Slides voor C++ API-referentie
description: Biedt opties die regelen hoe een presentatie wordt opgeslagen in XPS-indeling.
type: docs
weight: 534
url: /nl/aspose.slides.export/ixpsoptions/
---
## IXpsOptions klasse

Biedt opties die regelen hoe een presentatie wordt opgeslagen in XPS-indeling.

```cpp
class IXpsOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met de C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevendekommagelijken waar twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevendekommagelijken waar twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | Retourneert het lettertype dat wordt gebruikt als het bronlettertype niet wordt gevonden. Leest [System::String](../../system/string/). |
| virtual **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() | Waar om een zwarte rand rond elke dia te tekenen. Lees **bool**. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | Retourneert de visuele stijl van de verloop. Lees [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | Representeert een callback-object voor het opslaan van voortgangsupdates in procenten. Zie [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() | Waar om alle metafiles die in een presentatie worden gebruikt om te zetten naar PNG-afbeeldingen. Lees **bool**. |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. Standaard is **false**. |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | Specificeert of hyperlinks met JavaScript-aanroepen moeten worden overgeslagen bij het opslaan van de presentatie. Lees **bool**. De standaardwaarde is **false**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | Retourneert een object dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of afgebroken. Lees [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentie-teller datastructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van de C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Schakelt hashing van aangepaste objecten in. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van de C# [System.Object.GetType()](../../system/object/gettype/) aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleer of het object een instantie van het type dat door targetType wordt beschreven vertegenwoordigt. Analoge van de C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert de C# lock() statement vergrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-waarnemingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van de C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Schakelt klonen van aangepaste types in. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert niets echt, initialiseert alleen een nieuw object en schakelt het kopiëren van subklassen in. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen een nieuw object en schakelt het kopiëren van subklassen in. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object op referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | Stelt het lettertype in dat wordt gebruikt als het bronlettertype niet wordt gevonden. Schrijft [System::String](../../system/string/). |
| virtual void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) | Waar om een zwarte rand rond elke dia te tekenen. Schrijf **bool**. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | Stelt de visuele stijl van de verloop in. Schrijf [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | Representeert een callback-object voor het opslaan van voortgangsupdates in procenten. Zie [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) | Waar om alle metafiles die in een presentatie worden gebruikt om te zetten naar PNG-afbeeldingen. Schrijf **bool**. |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. Standaard is **false**. |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | Specificeert of hyperlinks met JavaScript-aanroepen moeten worden overgeslagen bij het opslaan van de presentatie. Schrijf **bool**. De standaardwaarde is **false**. |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | Stelt een object in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of afgebroken. Schrijf [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stel het n'te sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Hiermee kunnen pointers in containers naar zwakke modus worden geschakeld. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van de C# [Object.ToString()](../../system/object/tostring/) methode. Schakelt conversie van aangepaste objecten naar string in. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert de C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert het ontgrendelen van de C# lock() statement. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-waarnemingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [ISaveOptions](../isaveoptions/)
* Naamruimte [Aspose::Slides::Export](../)
* Bibliotheek [Aspose.Slides](../../)