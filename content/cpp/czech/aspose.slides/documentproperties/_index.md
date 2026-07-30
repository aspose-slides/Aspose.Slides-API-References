---
title: DocumentProperties
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Reprezentuje vlastnosti prezentace.
type: docs
weight: 794
url: /cs/aspose.slides/documentproperties/
---
## DocumentProperties třída

Reprezentuje vlastnosti prezentace.

```cpp
class DocumentProperties : public Aspose::Slides::IDocumentProperties,
                           public Aspose::Slides::IGenericCloneable<System::SharedPtr<Aspose::Slides::IDocumentProperties>>
```

## Metody

| Metoda | Popis |
| --- | --- |
| void [ClearBuiltInProperties](./clearbuiltinproperties/)() override | Vymaže a nastaví výchozí hodnoty pro všechny vestavěné vlastnosti. |
| void [ClearCustomProperties](./clearcustomproperties/)() override | Odstraní všechny vlastní vlastnosti. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](./clone/)() override | Klonuje aktuální objekt |
| [System::SharedPtr](../../system/sharedptr/)\<[IDocumentProperties](../idocumentproperties/)\> [CloneT](./clonet/)() override | Klonuje aktuální objekt |
| **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) override | Ověřuje přítomnost vlastní vlastnosti se zadaným názvem. |
|  [DocumentProperties](./documentproperties/)() | Inicializuje novou instanci třídy [DocumentProperties](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnota ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() override | Vrací šablonu aplikace. Číst [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() override | Vrací verzi aplikace. Pouze pro čtení [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Author](./get_author/)() override | Vrací autora prezentace. Číst [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Category](./get_category/)() override | Vrací kategorii prezentace. Číst [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Comments](./get_comments/)() override | Vrací komentáře k prezentaci. Číst [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Company](./get_company/)() override | Vrací vlastnost společnosti. Číst [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() override | Vrací stav obsahu prezentace. Číst [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() override | Vrací typ obsahu prezentace. Číst [System::String](../../system/string/). |
| **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() override | Vrací počet vlastních vlastností skutečně obsažených ve sbírce. Pouze pro čtení **int32_t**. |
| [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() override | Vrací datum vytvoření prezentace. Hodnoty jsou v UTC. Číst [System::DateTime](../../system/datetime/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() override | Indikuje seskupení částí dokumentu a počet částí v každé skupině. Pouze pro čtení [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/). |
| **int32_t** [get_HiddenSlides](./get_hiddenslides/)() override | Vrací počet skrytých snímků v dokumentu prezentace. Pouze pro čtení **int32_t**. |
| [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() override | Vrací vlastnost dokumentu HyperlinkBase. Číst [System::String](../../system/string/). |
| **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() override | Určuje, že jeden nebo více hypertextových odkazů v této části byly aktualizovány výhradně v této části producentem. Další producent otevřouci tento dokument by měl aktualizovat vztahy hypertextových odkazů s novými odkazy specifikovanými v této části. Číst **bool**. |
| [System::String](../../system/string/) [get_Keywords](./get_keywords/)() override | Vrací klíčová slova prezentace. Číst [System::String](../../system/string/). |
| [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() override | Vrací datum posledního vytištění prezentace. Číst [System::DateTime](../../system/datetime/). |
| [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() override | Vrací jméno poslední osoby, která upravila prezentaci. Číst [System::String](../../system/string/). |
| [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() override | Vrací datum poslední úpravy prezentace. Hodnoty jsou v UTC. Pouze pro čtení v případě [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) (protože bude aktualizováno interně během procesu ukládání objektu [IPresentation](../ipresentation/)). Lze změnit pomocí instance [DocumentProperties](./) vrácené metodou [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). Viz příklad v souhrnu metody [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| **bool** [get_LinksUpToDate](./get_linksuptodate/)() override | Indikuje, zda jsou hypertextové odkazy v dokumentu aktuální. Nastavte tento prvek na **true**, aby bylo indikováno, že odkazy jsou aktualizovány. Nastavte na **false**, aby bylo indikováno, že odkazy jsou zastaralé. Číst **bool**. |
| [System::String](../../system/string/) [get_Manager](./get_manager/)() override | Vrací vlastnost správce. Číst [System::String](../../system/string/). |
| **int32_t** [get_MultimediaClips](./get_multimediaclips/)() override | Vrací celkový počet zvukových nebo video klipů, které jsou v dokumentu. Pouze pro čtení **int32_t**. |
| [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() override | Vrací název aplikace. Číst [System::String](../../system/string/). |
| **int32_t** [get_Notes](./get_notes/)() override | Vrací počet snímků v prezentaci obsahujících poznámky. Pouze pro čtení **int32_t**. |
| **int32_t** [get_Paragraphs](./get_paragraphs/)() override | Vrací celkový počet odstavců nalezených v dokumentu, pokud je to použitelné. Pouze pro čtení **int32_t**. |
| [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() override | Vrací zamýšlený formát prezentace. Číst [System::String](../../system/string/). |
| **int32_t** [get_RevisionNumber](./get_revisionnumber/)() override | Vrací číslo revize prezentace. Číst **int32_t**. |
| **bool** [get_ScaleCrop](./get_scalecrop/)() override | Indikuje režim zobrazení náhledu dokumentu. Nastavte tento prvek na **true**, aby se povolilo škálování náhledu dokumentu na displej. Nastavte na **false**, aby se povolilo oříznutí náhledu dokumentu tak, aby zobrazoval pouze části, které se vejdou do displeje. Číst **bool**. |
| **bool** [get_SharedDoc](./get_shareddoc/)() override | Určuje, zda je prezentace sdílena mezi více lidmi. Číst **bool**. |
| **int32_t** [get_Slides](./get_slides/)() override | Vrací celkový počet snímků v dokumentu prezentace. Pouze pro čtení **int32_t**. |
| [System::String](../../system/string/) [get_Subject](./get_subject/)() override | Vrací předmět prezentace. Číst [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Title](./get_title/)() override | Vrací název prezentace. Číst [System::String](../../system/string/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() override | Určuje název každé části dokumentu. Tyto části nejsou částmi dokumentu, ale konceptuálními reprezentacemi sekcí dokumentu. Pouze pro čtení [System::ArrayPtr<System::String>](../../system/arrayptr/). |
| [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() override | Celkový čas editace prezentace. Číst [System::TimeSpan](../../system/timespan/). |
| **int32_t** [get_Words](./get_words/)() override | Vrací celkový počet slov obsažených v dokumentu. Pouze pro čtení **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získává datovou strukturu počítadla referencí spojenou s objektem. |
| [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) override | Vrací název vlastní vlastnosti na zadaném indexu. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) override | Získává pojmenovanou boolean hodnotu z vlastních vlastností. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) override | Získává pojmenovanou celočíselnou hodnotu z vlastních vlastností. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) override | Získává pojmenovanou DateTime hodnotu z vlastních vlastností. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) override | Získává pojmenovanou řetězcovou hodnotu z vlastních vlastností. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) override | Získává pojmenovanou float hodnotu z vlastních vlastností. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) override | Získává pojmenovanou double hodnotu z vlastních vlastností. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() override | Získává pole štítků citlivosti z vlastních vlastností dokumentu (Metadata Microsoft Information Protection SDK). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získává aktuální typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) override | Vrací vlastní vlastnost spojenou se zadaným názvem. Číst [System::Object](../../system/object/). |
| void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Nastavuje vlastní vlastnost spojenou se zadaným názvem. Zapsat [System::Object](../../system/object/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ověřuje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytváří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referenci typu hodnota s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) override | Odstraňuje vlastní vlastnost spojenou se zadaným názvem. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený počítadlo referencí o zadanou hodnotu. |
| void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) override | Nastavuje šablonu aplikace. Zapsat [System::String](../../system/string/). |
| void [set_Author](./set_author/)([System::String](../../system/string/)) override | Nastavuje autora prezentace. Zapsat [System::String](../../system/string/). |
| void [set_Category](./set_category/)([System::String](../../system/string/)) override | Nastavuje kategorii prezentace. Zapsat [System::String](../../system/string/). |
| void [set_Comments](./set_comments/)([System::String](../../system/string/)) override | Nastavuje komentáře prezentace. Zapsat [System::String](../../system/string/). |
| void [set_Company](./set_company/)([System::String](../../system/string/)) override | Nastavuje vlastnost společnosti. Zapsat [System::String](../../system/string/). |
| void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) override | Nastavuje stav obsahu prezentace. Zapsat [System::String](../../system/string/). |
| void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) override | Nastavuje typ obsahu prezentace. Zapsat [System::String](../../system/string/). |
| void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) override | Vrací datum vytvoření prezentace. Hodnoty jsou v UTC. Zapsat [System::DateTime](../../system/datetime/). |
| void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) override | Nastavuje vlastnost dokumentu HyperlinkBase. Zapsat [System::String](../../system/string/). |
| void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) override | Určuje, že jeden nebo více hypertextových odkazů v této části byly aktualizovány výhradně v této části producentem. Další producent otevřouci tento dokument by měl aktualizovat vztahy hypertextových odkazů s novými odkazy specifikovanými v této části. Zapsat **bool**. |
| void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) override | Nastavuje klíčová slova prezentace. Zapsat [System::String](../../system/string/). |
| void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) override | Vrací datum posledního vytištění prezentace. Zapsat [System::DateTime](../../system/datetime/). |
| void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) override | Nastavuje jméno poslední osoby, která upravila prezentaci. Zapsat [System::String](../../system/string/). |
| void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) override | Vrací datum poslední úpravy prezentace. Hodnoty jsou v UTC. Pouze pro čtení v případě [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) (protože bude aktualizováno interně během procesu ukládání objektu [IPresentation](../ipresentation/)). Lze změnit pomocí instance [DocumentProperties](./) vrácené metodou [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). Viz příklad v souhrnu metody [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) override | Indikuje, zda jsou hypertextové odkazy v dokumentu aktuální. Nastavte tento prvek na **true**, aby bylo indikováno, že odkazy jsou aktualizovány. Nastavte na **false**, aby bylo indikováno, že odkazy jsou zastaralé. Zapsat **bool**. |
| void [set_Manager](./set_manager/)([System::String](../../system/string/)) override | Nastavuje vlastnost správce. Zapsat [System::String](../../system/string/). |
| void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) override | Nastavuje název aplikace. Zapsat [System::String](../../system/string/). |
| void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) override | Nastavuje zamýšlený formát prezentace. Zapsat [System::String](../../system/string/). |
| void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) override | Nastavuje číslo revize prezentace. Zapsat **int32_t**. |
| void [set_ScaleCrop](./set_scalecrop/)(**bool**) override | Indikuje režim zobrazení náhledu dokumentu. Nastavte tento prvek na **true**, aby se povolilo škálování náhledu dokumentu na displej. Nastavte na **false**, aby se povolilo oříznutí náhledu dokumentu tak, aby zobrazoval pouze části, které se vejdou do displeje. Zapsat **bool**. |
| void [set_SharedDoc](./set_shareddoc/)(**bool**) override | Určuje, zda je prezentace sdílena mezi více lidmi. Zapsat **bool**. |
| void [set_Subject](./set_subject/)([System::String](../../system/string/)) override | Nastavuje předmět prezentace. Zapsat [System::String](../../system/string/). |
| void [set_Title](./set_title/)([System::String](../../system/string/)) override | Nastavuje název prezentace. Zapsat [System::String](../../system/string/). |
| void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) override | Celkový čas editace prezentace. Zapsat [System::TimeSpan](../../system/timespan/). |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) override | Nastavuje pojmenovanou boolean vlastní vlastnost. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) override | Nastavuje pojmenovanou celočíselnou vlastní vlastnost. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) override | Nastavuje pojmenovanou DateTime vlastní vlastnost. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) override | Nastavuje pojmenovanou řetězcovou vlastní vlastnost. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) override | Nastavuje pojmenovanou float vlastní vlastnost. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) override | Nastavuje pojmenovanou double vlastní vlastnost. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony na slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získává aktuální hodnotu sdíleného počítadla referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený počítadlo referencí. Nemělo by být voláno přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený počítadlo referencí. Nemělo by být voláno přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení pomocí C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje počítadlo slabých referencí. Nemělo by být voláno přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje počítadlo slabých referencí. Nemělo by být voláno přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Poznámky

Následující příklad ukazuje, jak přistupovat k vestavěným vlastnostem PowerPoint [Presentation](../presentation/).
```cpp
// Vytvořte instanci třídy Presentation, která představuje prezentaci
auto pres = System::MakeObject<Presentation>(dataDir + u"AccessBuiltin Properties.pptx");

// Vytvořte referenci na objekt IDocumentProperties spojený s objektem Presentation
System::SharedPtr<IDocumentProperties> documentProperties = pres->get_DocumentProperties();
// Zobrazte vestavěné vlastnosti
System::Console::WriteLine(System::String(u"Category : ") + documentProperties->get_Category());
System::Console::WriteLine(System::String(u"Current Status : ") + documentProperties->get_ContentStatus());
System::Console::WriteLine(System::String(u"Creation Date : ") + documentProperties->get_CreatedTime());
System::Console::WriteLine(System::String(u"Author : ") + documentProperties->get_Author());
System::Console::WriteLine(System::String(u"Description : ") + documentProperties->get_Comments());
```
Následující příklad ukazuje, jak upravit vestavěné vlastnosti PowerPoint [Presentation](../presentation/).
```cpp
// Vytvořte instanci třídy Presentation, která představuje prezentaci
auto presentation = System::MakeObject<Presentation>(dataDir + u"ModifyBuiltinProperties.pptx");

// Vytvořte referenci na objekt IDocumentProperties spojený s objektem Presentation
System::SharedPtr<IDocumentProperties> documentProperties = presentation->get_DocumentProperties();
// Nastavte vestavěné vlastnosti
documentProperties->set_Author(u"Aspose.Slides for .NET");
documentProperties->set_Title(u"Modifying Presentation Properties");
documentProperties->set_Subject(u"Aspose Subject");
// Uložte prezentaci do souboru
presentation->Save(u"DocumentProperties_out.pptx", SaveFormat::Pptx);
```

## Viz také

* Třída [IDocumentProperties](../idocumentproperties/)
* Třída [IGenericCloneable](../igenericcloneable/)
* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)