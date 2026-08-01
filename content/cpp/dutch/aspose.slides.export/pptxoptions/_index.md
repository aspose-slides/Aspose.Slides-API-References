---
title: PptxOptions
second_title: Aspose.Slides voor C++ API-referentie
description: Geeft de opties weer voor het opslaan van OpenXml-presentaties (PPTX, PPSX, POTX, PPTM, PPSM, POTM).
type: docs
weight: 599
url: /nl/aspose.slides.export/pptxoptions/
---
## PptxOptions klasse

Representeert opties voor het opslaan van OpenXml-presentaties (PPTX, PPSX, POTX, PPTM, PPSM, POTM).

```cpp
class PptxOptions : public Aspose::Slides::Export::SaveOptions,
                    public Aspose::Slides::Export::IPptxOptions
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-achtige floating-point-vergelijking waarbij twee NaN's als gelijk worden beschouwd, ook al is NaN volgens IEC 60559:1989 niet gelijk aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-achtige floating-point-vergelijking waarbij twee NaN's als gelijk worden beschouwd, ook al is NaN volgens IEC 60559:1989 niet gelijk aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [Aspose::Slides::Export::CompressionLevel](../compressionlevel/) [get_CompressionLevel](./get_compressionlevel/)() override | Specificeert het compressieniveau dat wordt gebruikt bij het opslaan van het presentatiedocument. De standaardwaarde is [CompressionLevel::Level6](../compressionlevel/). |
| [Aspose::Slides::Export::Conformance](../conformance/) [get_Conformance](./get_conformance/)() override | Specificeert de conformiteitsklasse waaraan het [Presentation](../../aspose.slides/presentation/)-document voldoet. Standaardwaarde is [Aspose::Slides::Export::Conformance::Ecma376_2006](../conformance/) |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Retourneert het lettertype dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden. Leest [System::String](../../system/string/). |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Retourneert de visuele stijl van de gradiënt. Leest [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Stelt een callback-object voor het opslaan van voortgangsupdates in procenten voor. Zie [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_RefreshThumbnail](./get_refreshthumbnail/)() override | Specificeert of de miniatuur van de presentatie wordt vernieuwd. Lees **bool**. Standaardwaarde is **true**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Specificeert of hyperlinks met JavaScript-aanroepen worden overgeslagen bij het opslaan van de presentatie. Lees **bool**. Standaardwaarde is **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Retourneert of stelt een object in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of geannuleerd. Lees [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| [Aspose::Slides::Export::Zip64Mode](../zip64mode/) [get_Zip64Mode](./get_zip64mode/)() override | Specificeert of het ZIP64-formaat wordt gebruikt voor het [Presentation](../../aspose.slides/presentation/)-document. Standaardwaarde is [Zip64Mode::IfNecessary](../zip64mode/) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog van C#-[Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analog van C#-[System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type vertegenwoordigt dat wordt beschreven door targetType. Analog van C#-'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C#-lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-sentinel-object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog van C#-[Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste typen mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
|  [PptxOptions](./pptxoptions/)() | Maakt een nieuwe instantie van [PptxOptions](./) aan |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object via referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_CompressionLevel](./set_compressionlevel/)([Aspose::Slides::Export::CompressionLevel](../compressionlevel/)) override | Specificeert het compressieniveau dat wordt gebruikt bij het opslaan van het presentatiedocument. De standaardwaarde is [CompressionLevel::Level6](../compressionlevel/). |
| void [set_Conformance](./set_conformance/)([Aspose::Slides::Export::Conformance](../conformance/)) override | Specificeert de conformiteitsklasse waaraan het [Presentation](../../aspose.slides/presentation/)-document voldoet. Standaardwaarde is [Aspose::Slides::Export::Conformance::Ecma376_2006](../conformance/) |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Stelt het lettertype in dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden. Schrijft [System::String](../../system/string/). |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Stelt de visuele stijl van de gradiënt in. Schrijft [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Stelt een callback-object voor het opslaan van voortgangsupdates in procenten voor. Zie [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_RefreshThumbnail](./set_refreshthumbnail/)(**bool**) override | Specificeert of de miniatuur van de presentatie wordt vernieuwd. Schrijf **bool**. Standaardwaarde is **true**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Specificeert of hyperlinks met JavaScript-aanroepen worden overgeslagen bij het opslaan van de presentatie. Schrijf **bool**. Standaardwaarde is **false**. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Retourneert of stelt een object in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of afgebroken. Schrijf [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| void [set_Zip64Mode](./set_zip64mode/)([Aspose::Slides::Export::Zip64Mode](../zip64mode/)) override | Specificeert of het ZIP64-formaat wordt gebruikt voor het [Presentation](../../aspose.slides/presentation/)-document. Standaardwaarde is [Zip64Mode::IfNecessary](../zip64mode/) |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n-de sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Staat toe om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog van C#-[Object.ToString()](../../system/object/tostring/)-methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C#-typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C#-lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-sentinel-object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [SaveOptions](../saveoptions/)
* Klasse [IPptxOptions](../ipptxoptions/)
* Namespace [Aspose::Slides::Export](../)
* Bibliotheek [Aspose.Slides](../../)