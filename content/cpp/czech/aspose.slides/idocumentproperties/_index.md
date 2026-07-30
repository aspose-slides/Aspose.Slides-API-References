---
title: IDocumentProperties
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Reprezentuje vlastnosti prezentace.
type: docs
weight: 1977
url: /cs/aspose.slides/idocumentproperties/
---
## IDocumentProperties třída

Reprezentuje vlastnosti prezentace.

```cpp
class IDocumentProperties : public virtual System::Object
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual void [ClearBuiltInProperties](./clearbuiltinproperties/)() | Vymaže a nastaví výchozí hodnoty pro všechny vestavěné vlastnosti. |
| virtual void [ClearCustomProperties](./clearcustomproperties/)() | Odstraní všechny vlastní vlastnosti. |
| virtual **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) | Zkontroluje přítomnost vlastní vlastnosti se zadaným názvem. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí C# [Object.Equals](../../system/object/equals/) semantiky. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu value ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání vodíkových čísel ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání vodíkových čísel ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro vnitřní účely. |
| virtual [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() | Vrací šablonu aplikace. Přečtěte [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() | Vrací verzi aplikace. Pouze pro čtení [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Author](./get_author/)() | Vrací autora prezentace. Přečtěte [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Category](./get_category/)() | Vrací kategorii prezentace. Přečtěte [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Comments](./get_comments/)() | Vrací komentáře prezentace. Přečtěte [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Company](./get_company/)() | Vrací vlastnost společnosti. Přečtěte [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() | Vrací stav obsahu prezentace. Přečtěte [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() | Vrací typ obsahu prezentace. Přečtěte [System::String](../../system/string/). |
| virtual **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() | Vrací počet vlastních vlastností skutečně obsažených ve sbírce. Pouze pro čtení **int32_t**. |
| virtual [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() | Vrací datum vytvoření prezentace. Hodnoty jsou v UTC. Přečtěte [System::DateTime](../../system/datetime/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() | Udává seskupení částí dokumentu a počet částí v každé skupině. Pouze pro čtení [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/). |
| virtual **int32_t** [get_HiddenSlides](./get_hiddenslides/)() | Udává počet skrytých snímků v dokumentu prezentace. Pouze pro čtení **int32_t**. |
| virtual [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() | Vrací vlastnost dokumentu HyperlinkBase. Přečtěte [System::String](../../system/string/). |
| virtual **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() | Určuje, že jeden nebo více hypertextových odkazů v této části byly aktualizovány výhradně v této části výrobcem. Další výrobce, který otevře tento dokument, aktualizuje vztahy hypertextových odkazů s novými odkazy specifikovanými v této části. Přečtěte **bool**. |
| virtual [System::String](../../system/string/) [get_Keywords](./get_keywords/)() | Vrací klíčová slova prezentace. Přečtěte [System::String](../../system/string/). |
| virtual [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() | Vrací datum posledního tisku prezentace. Přečtěte [System::DateTime](../../system/datetime/). |
| virtual [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() | Vrací jméno poslední osoby, která upravila prezentaci. Přečtěte [System::String](../../system/string/). |
| virtual [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() | Vrací datum poslední úpravy prezentace. Hodnoty jsou v UTC. Pouze pro čtení v případě Presentation.DocumentProperties (protože bude aktualizováno interně během procesu ukládání objektu [IPresentation](../ipresentation/)). Lze změnit pomocí instance [DocumentProperties](../documentproperties/) vrácené metodou [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). Viz příklad v souhrnu metody [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| virtual **bool** [get_LinksUpToDate](./get_linksuptodate/)() | Určuje, zda jsou hypertextové odkazy v dokumentu aktuální. Nastavte tento prvek na **true**, aby bylo indikováno, že odkazy jsou aktualizovány. Nastavte tento prvek na **false**, aby bylo indikováno, že odkazy jsou zastaralé. Přečtěte **bool**. |
| virtual [System::String](../../system/string/) [get_Manager](./get_manager/)() | Vrací vlastnost manažera. Přečtěte [System::String](../../system/string/). |
| virtual **int32_t** [get_MultimediaClips](./get_multimediaclips/)() | Udává celkový počet zvukových nebo video klipů, které jsou v dokumentu. Pouze pro čtení **int32_t**. |
| virtual [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() | Vrací název aplikace. Přečtěte [System::String](../../system/string/). |
| virtual **int32_t** [get_Notes](./get_notes/)() | Udává počet snímků v prezentaci obsahujících poznámky. Pouze pro čtení **int32_t**. |
| virtual **int32_t** [get_Paragraphs](./get_paragraphs/)() | Udává celkový počet odstavců nalezených v dokumentu, pokud je to relevantní. Pouze pro čtení **int32_t**. |
| virtual [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() | Vrací zamýšlený formát prezentace. Přečtěte [System::String](../../system/string/). |
| virtual **int32_t** [get_RevisionNumber](./get_revisionnumber/)() | Vrací číslo revize prezentace. Přečtěte **int32_t**. |
| virtual **bool** [get_ScaleCrop](./get_scalecrop/)() | Určuje režim zobrazení miniatury dokumentu. Nastavte tento prvek na **true**, aby se povolilo škálování miniatury dokumentu na displej. Nastavte tento prvek na **false**, aby se povolilo oříznutí miniatury dokumentu tak, aby zobrazovala pouze části, které se vejdou na displej. Přečtěte **bool**. |
| virtual **bool** [get_SharedDoc](./get_shareddoc/)() | Určuje, zda je prezentace sdílena mezi více lidmi. Přečtěte **bool**. |
| virtual **int32_t** [get_Slides](./get_slides/)() | Udává celkový počet snímků v dokumentu prezentace. Pouze pro čtení **int32_t**. |
| virtual [System::String](../../system/string/) [get_Subject](./get_subject/)() | Vrací předmět prezentace. Přečtěte [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Title](./get_title/)() | Vrací název prezentace. Přečtěte [System::String](../../system/string/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() | Udává název každé části dokumentu. Tyto části nejsou částmi dokumentu, ale konceptuálními reprezentacemi sekcí dokumentu. Pouze pro čtení [System::ArrayPtr<System::String>](../../system/arrayptr/). |
| virtual [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() | Celkový čas úprav prezentace. Přečtěte [System::TimeSpan](../../system/timespan/). |
| virtual **int32_t** [get_Words](./get_words/)() | Udává celkový počet slov obsažených v dokumentu. Pouze pro čtení **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu čítače odkazů přidruženou k objektu. |
| virtual [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) | Vrátí název vlastní vlastnosti na zadaném indexu. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) | Získá pojmenovanou boolean hodnotu ze vlastních vlastností. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) | Získá pojmenovanou celočíselnou hodnotu ze vlastních vlastností. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) | Získá pojmenovanou hodnotu DateTime ze vlastních vlastností. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) | Získá pojmenovanou řetězcovou hodnotu ze vlastních vlastností. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) | Získá pojmenovanou float hodnotu ze vlastních vlastností. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) | Získá pojmenovanou double hodnotu ze vlastních vlastností. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() | Získá pole štítků citlivosti z vlastních vlastností dokumentu (Microsoft Information Protection SDK Metadata). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) | Vrací vlastní vlastnost spojenou se zadaným názvem. Přečtěte [System::Object](../../system/object/). |
| virtual void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Nastaví vlastní vlastnost spojenou se zadaným názvem. Zapište [System::Object](../../system/object/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referenčně objekt typu value s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| virtual **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) | Odstraní vlastní vlastnost spojenou se zadaným názvem. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač odkazů o zadanou hodnotu. |
| virtual void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) | Nastaví šablonu aplikace. Zapište [System::String](../../system/string/). |
| virtual void [set_Author](./set_author/)([System::String](../../system/string/)) | Nastaví autora prezentace. Zapište [System::String](../../system/string/). |
| virtual void [set_Category](./set_category/)([System::String](../../system/string/)) | Nastaví kategorii prezentace. Zapište [System::String](../../system/string/). |
| virtual void [set_Comments](./set_comments/)([System::String](../../system/string/)) | Nastaví komentáře prezentace. Zapište [System::String](../../system/string/). |
| virtual void [set_Company](./set_company/)([System::String](../../system/string/)) | Nastaví vlastnost společnosti. Zapište [System::String](../../system/string/). |
| virtual void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) | Nastaví stav obsahu prezentace. Zapište [System::String](../../system/string/). |
| virtual void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) | Nastaví typ obsahu prezentace. Zapište [System::String](../../system/string/). |
| virtual void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) | Vrací datum vytvoření prezentace. Hodnoty jsou v UTC. Zapište [System::DateTime](../../system/datetime/). |
| virtual void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) | Nastaví vlastnost dokumentu HyperlinkBase. Zapište [System::String](../../system/string/). |
| virtual void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) | Určuje, že jeden nebo více hypertextových odkazů v této části byly aktualizovány výhradně v této části výrobcem. Další výrobce, který otevře tento dokument, aktualizuje vztahy hypertextových odkazů s novými odkazy specifikovanými v této části. Zapište **bool**. |
| virtual void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) | Nastaví klíčová slova prezentace. Zapište [System::String](../../system/string/). |
| virtual void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) | Vrací datum posledního tisku prezentace. Zapište [System::DateTime](../../system/datetime/). |
| virtual void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) | Nastaví jméno poslední osoby, která upravila prezentaci. Zapište [System::String](../../system/string/). |
| virtual void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) | Vrací datum poslední úpravy prezentace. Hodnoty jsou v UTC. Pouze pro čtení v případě Presentation.DocumentProperties (protože bude aktualizováno interně během procesu ukládání objektu [IPresentation](../ipresentation/)). Lze změnit pomocí instance [DocumentProperties](../documentproperties/) vrácené metodou [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). Viz příklad v souhrnu metody [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| virtual void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) | Určuje, zda jsou hypertextové odkazy v dokumentu aktuální. Nastavte tento prvek na **true**, aby bylo indikováno, že odkazy jsou aktualizovány. Nastavte tento prvek na **false**, aby bylo indikováno, že odkazy jsou zastaralé. Zapište **bool**. |
| virtual void [set_Manager](./set_manager/)([System::String](../../system/string/)) | Nastaví vlastnost manažera. Zapište [System::String](../../system/string/). |
| virtual void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) | Nastaví název aplikace. Zapište [System::String](../../system/string/). |
| virtual void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) | Nastaví zamýšlený formát prezentace. Zapište [System::String](../../system/string/). |
| virtual void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) | Nastaví číslo revize prezentace. Zapište **int32_t**. |
| virtual void [set_ScaleCrop](./set_scalecrop/)(**bool**) | Nastaví režim zobrazení miniatury dokumentu. Nastavte tento prvek na **true**, aby se povolilo škálování miniatury dokumentu na displej. Nastavte tento prvek na **false**, aby se povolilo oříznutí miniatury dokumentu tak, aby zobrazovala pouze části, které se vejdou na displej. Zapište **bool**. |
| virtual void [set_SharedDoc](./set_shareddoc/)(**bool**) | Určuje, zda je prezentace sdílena mezi více lidmi. Zapište **bool**. |
| virtual void [set_Subject](./set_subject/)([System::String](../../system/string/)) | Nastaví předmět prezentace. Zapište [System::String](../../system/string/). |
| virtual void [set_Title](./set_title/)([System::String](../../system/string/)) | Nastaví název prezentace. Zapište [System::String](../../system/string/). |
| virtual void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) | Celkový čas úprav prezentace. Zapište [System::TimeSpan](../../system/timespan/). |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) | Nastaví pojmenovanou boolean vlastní vlastnost. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) | Nastaví pojmenovanou celočíselnou vlastní vlastnost. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) | Nastaví pojmenovanou DateTime vlastní vlastnost. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) | Nastaví pojmenovanou řetězcovou vlastní vlastnost. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) | Nastaví pojmenovanou float vlastní vlastnost. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) | Nastaví pojmenovanou double vlastní vlastnost. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony jako weak ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do weak režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače odkazů. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač odkazů. Nemělo by být voláno přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač odkazů. Nemělo by být voláno přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje weak čítač odkazů. Nemělo by být voláno přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje weak čítač odkazů. Nemělo by být voláno přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Viz také

* Třída [Object](../../system/object/)
* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)