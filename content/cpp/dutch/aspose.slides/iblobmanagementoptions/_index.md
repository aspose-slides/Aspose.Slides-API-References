---
title: IBlobManagementOptions
second_title: Aspose.Slides voor C++ API-referentie
description: Een Binary Large Object (BLOB) is een binaire gegevens die als één entiteit wordt opgeslagen – d.w.z. een BLOB kan een audio, video of presentatie zelf zijn. Er worden verschillende technieken gebruikt om het geheugengebruik te optimaliseren bij het werken met BLOB's – die al in de presentatie is opgeslagen of later programmatisch wordt toegevoegd. Met IBlobManagementOptions kun je verschillende gedragseigenschappen met betrekking tot BLOB's verwerking aanpassen voor de levensduur van de IPresentation instantie.
type: docs
weight: 1535
url: /nl/aspose.slides/iblobmanagementoptions/
---
## IBlobManagementOptions klasse


Een Binary Large Object (BLOB) is een binaire gegevens die als één entiteit wordt opgeslagen – d.w.z. een BLOB kan een audio-, video- of presentatie-bestand zelf zijn. Er worden verschillende technieken gebruikt om het geheugengebruik te optimaliseren bij het werken met BLOB’s – die al in de presentatie zijn opgeslagen of later programmatisch worden toegevoegd. Met [IBlobManagementOptions](./) kun je verschillende gedragseigenschappen met betrekking tot BLOB-verwerking voor de [IPresentation](../ipresentation/)-instantielevensduur wijzigen.

```cpp
class IBlobManagementOptions : public virtual System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevende-kommagelijk vergelijken waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevende-kommagelijk vergelijken waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor interne doeleinden. |
| virtual **bool** [get_IsTemporaryFilesAllowed](./get_istemporaryfilesallowed/)() | Deze eigenschap bepaalt of tijdelijke bestanden kunnen worden aangemaakt tijdens het werken met BLOB’s, wat het geheugengebruik sterk vermindert maar wel rechten vereist om bestanden te creëren. |
| virtual **uint64_t** [get_MaxBlobsBytesInMemory](./get_maxblobsbytesinmemory/)() | Definieert de maximale totale grootte (in bytes) die alle BLOB’s in het geheugen mogen innemen. Standaard worden alle BLOB’s in het geheugen geladen; pas wanneer deze limiet is bereikt, worden alternatieve mechanismen (zoals tijdelijke bestanden) ingezet. BLOB’s in het geheugen houden maximaliseert de prestaties, maar kan leiden tot hoog geheugengebruik. Gebruik deze eigenschap om het gedrag aan te passen aan uw omgeving of vereisten. |
| virtual [Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/) [get_PresentationLockingBehavior](./get_presentationlockingbehavior/)() | Deze eigenschap bepaalt of een instantie van de [Presentation](../presentation/)-klasse eigenaar kan zijn van de bron – bestand of stream – gedurende de levensduur van de instantie. Is de instantie eigenaar, dan wordt de bron vergrendeld. Dit helpt het geheugengebruik en de prestaties te verbeteren tijdens het werken met BLOB’s, maar de bron (stream of bestand) kan niet worden gewijzigd gedurende [Presentation](../presentation/)'s instantielevensduur. Dit is een voorbeeld: |
| virtual [System::String](../../system/string/) [get_TempFilesRootPath](./get_tempfilesrootpath/)() | Het basispad waar tijdelijke bestanden worden aangemaakt. [System](../../system/) tijdelijke map wordt standaard gebruikt. Het host-proces moet rechten hebben om daar bestanden en mappen aan te maken. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datstructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashing van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type dat wordt beschreven door targetType. Analoge van C#-operator ‘is’. |
| void [Lock](../../system/object/lock/)() | Implementeert C#-lock()-statement voor vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-constructor. Kopieert niets echt, initialiseert gewoon een nieuw object en maakt het mogelijk subklassen te kopiëren. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert gewoon een nieuw object en maakt het mogelijk subklassen te kopiëren. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object met nullptr op referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_IsTemporaryFilesAllowed](./set_istemporaryfilesallowed/)(**bool**) | Deze eigenschap bepaalt of tijdelijke bestanden kunnen worden aangemaakt tijdens het werken met BLOB’s, wat het geheugengebruik sterk vermindert maar wel rechten vereist om bestanden te creëren. |
| virtual void [set_MaxBlobsBytesInMemory](./set_maxblobsbytesinmemory/)(**uint64_t**) | Definieert de maximale totale grootte (in bytes) die alle BLOB’s in het geheugen mogen innemen. Standaard worden alle BLOB’s in het geheugen geladen; pas wanneer deze limiet is bereikt, worden alternatieve mechanismen (zoals tijdelijke bestanden) ingezet. BLOB’s in het geheugen houden maximaliseert de prestaties, maar kan leiden tot hoog geheugengebruik. Gebruik deze eigenschap om het gedrag aan te passen aan uw omgeving of vereisten. |
| virtual void [set_PresentationLockingBehavior](./set_presentationlockingbehavior/)([Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/)) | Deze eigenschap bepaalt of een instantie van de [Presentation](../presentation/)-klasse eigenaar kan zijn van de bron – bestand of stream – gedurende de levensduur van de instantie. Is de instantie eigenaar, dan wordt de bron vergrendeld. Dit helpt het geheugengebruik en de prestaties te verbeteren tijdens het werken met BLOB’s, maar de bron (stream of bestand) kan niet worden gewijzigd gedurende [Presentation](../presentation/)'s instantielevensduur. Dit is een voorbeeld: |
| virtual void [set_TempFilesRootPath](./set_tempfilesrootpath/)([System::String](../../system/string/)) | Het basispad waar tijdelijke bestanden worden aangemaakt. [System](../../system/) tijdelijke map wordt standaard gebruikt. Het host-proces moet rechten hebben om daar bestanden en mappen aan te maken. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n-de sjabloon-argument in als een zwakke pointer (in plaats van een gedeelde). Maakt het mogelijk pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het mogelijk aangepaste objecten naar string te converteren. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement voor ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |
## Zie ook

* Klasse [Object](../../system/object/)
* Namespace [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)