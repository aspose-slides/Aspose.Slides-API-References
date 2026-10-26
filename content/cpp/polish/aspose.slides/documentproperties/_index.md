---
title: DocumentProperties
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Reprezentuje właściwości prezentacji.
type: docs
weight: 794
url: /pl/aspose.slides/documentproperties/
---
## DocumentProperties klasa

Represents properties of a presentation.

```cpp
class DocumentProperties : public Aspose::Slides::IDocumentProperties,
                           public Aspose::Slides::IGenericCloneable<System::SharedPtr<Aspose::Slides::IDocumentProperties>>
```

## Metody

| Metoda | Opis |
| --- | --- |
| void [ClearBuiltInProperties](./clearbuiltinproperties/)() override | Czyszczy i ustawia domyślne wartości dla wszystkich wbudowanych własności. |
| void [ClearCustomProperties](./clearcustomproperties/)() override | Usuwa wszystkie własności niestandardowe. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](./clone/)() override | Klonuje bieżący obiekt |
| [System::SharedPtr](../../system/sharedptr/)\<[IDocumentProperties](../idocumentproperties/)\> [CloneT](./clonet/)() override | Klonuje bieżący obiekt |
| **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) override | Sprawdza obecność własności niestandardowej o podanej nazwie. |
| [DocumentProperties](./documentproperties/)() | Inicjalizuje nową instancję klasy [DocumentProperties](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() override | Zwraca szablon aplikacji. Odczytaj [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() override | Zwraca wersję aplikacji. Tylko do odczytu [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Author](./get_author/)() override | Zwraca autora prezentacji. Odczytaj [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Category](./get_category/)() override | Zwraca kategorię prezentacji. Odczytaj [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Comments](./get_comments/)() override | Zwraca komentarze prezentacji. Odczytaj [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Company](./get_company/)() override | Zwraca własność firmy. Odczytaj [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() override | Zwraca status treści prezentacji. Odczytaj [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() override | Zwraca typ treści prezentacji. Odczytaj [System::String](../../system/string/). |
| **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() override | Zwraca liczbę własności niestandardowych faktycznie zawartych w kolekcji. Tylko do odczytu **int32_t**. |
| [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() override | Zwraca datę utworzenia prezentacji. Wartości podane w UTC. Odczytaj [System::DateTime](../../system/datetime/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() override | Wskazuje grupowanie części dokumentu i liczbę części w każdej grupie. Tylko do odczytu [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/). |
| **int32_t** [get_HiddenSlides](./get_hiddenslides/)() override | Zwraca liczbę ukrytych slajdów w dokumencie prezentacji. Tylko do odczytu **int32_t**. |
| [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() override | Zwraca własność dokumentu HyperlinkBase. Odczytaj [System::String](../../system/string/). |
| **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() override | Określa, że jeden lub więcej hiperłączy w tej części zostały zaktualizowane wyłącznie w tej części przez twórcę. Następny twórca otwierający dokument powinien zaktualizować relacje hiperłączy nowymi hiperłączami określonymi w tej części. Odczytaj **bool**. |
| [System::String](../../system/string/) [get_Keywords](./get_keywords/)() override | Zwraca słowa kluczowe prezentacji. Odczytaj [System::String](../../system/string/). |
| [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() override | Zwraca datę ostatniego drukowania prezentacji. Odczytaj [System::DateTime](../../system/datetime/). |
| [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() override | Zwraca nazwę ostatniej osoby, która zmodyfikowała prezentację. Odczytaj [System::String](../../system/string/). |
| [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() override | Zwraca datę ostatniej modyfikacji prezentacji. Wartości podane w UTC. Tylko do odczytu w przypadku [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) (ponieważ zostanie zaktualizowane wewnętrznie podczas procesu zapisywania obiektu [IPresentation](../ipresentation/)). Może być zmieniona poprzez instancję [DocumentProperties](./) zwracaną przez metodę [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). Proszę zobaczyć przykład w podsumowaniu metody [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| **bool** [get_LinksUpToDate](./get_linksuptodate/)() override | Wskazuje, czy hiperłącza w dokumencie są aktualne. Ustaw ten element na **true**, aby zaznaczyć, że hiperłącza są zaktualizowane. Ustaw ten element na **false**, aby zaznaczyć, że hiperłącza są nieaktualne. Odczytaj **bool**. |
| [System::String](../../system/string/) [get_Manager](./get_manager/)() override | Zwraca własność manager. Odczytaj [System::String](../../system/string/). |
| **int32_t** [get_MultimediaClips](./get_multimediaclips/)() override | Zwraca całkowitą liczbę klipów dźwiękowych lub wideo obecnych w dokumencie. Tylko do odczytu **int32_t**. |
| [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() override | Zwraca nazwę aplikacji. Odczytaj [System::String](../../system/string/). |
| **int32_t** [get_Notes](./get_notes/)() override | Zwraca liczbę slajdów w prezentacji zawierających notatki. Tylko do odczytu **int32_t**. |
| **int32_t** [get_Paragraphs](./get_paragraphs/)() override | Zwraca całkowitą liczbę akapitów znalezionych w dokumencie, jeśli dotyczy. Tylko do odczytu **int32_t**. |
| [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() override | Zwraca zamierzony format prezentacji. Odczytaj [System::String](../../system/string/). |
| **int32_t** [get_RevisionNumber](./get_revisionnumber/)() override | Zwraca numer rewizji prezentacji. Odczytaj **int32_t**. |
| **bool** [get_ScaleCrop](./get_scalecrop/)() override | Wskazuje tryb wyświetlania miniatury dokumentu. Ustaw ten element na **true**, aby włączyć skalowanie miniatury dokumentu do wyświetlacza. Ustaw ten element na **false**, aby włączyć przycinanie miniatury dokumentu, aby wyświetlać tylko sekcje pasujące do wyświetlacza. Odczytaj **bool**. |
| **bool** [get_SharedDoc](./get_shareddoc/)() override | Określa, czy prezentacja jest współdzielona pomiędzy wieloma osobami. Odczytaj **bool**. |
| **int32_t** [get_Slides](./get_slides/)() override | Zwraca całkowitą liczbę slajdów w dokumencie prezentacji. Tylko do odczytu **int32_t**. |
| [System::String](../../system/string/) [get_Subject](./get_subject/)() override | Zwraca temat prezentacji. Odczytaj [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Title](./get_title/)() override | Zwraca tytuł prezentacji. Odczytaj [System::String](../../system/string/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() override | Określa tytuł każdej części dokumentu. Te części nie są częściami dokumentu, lecz koncepcyjnymi reprezentacjami sekcji dokumentu. Tylko do odczytu [System::ArrayPtr<System::String>](../../system/arrayptr/). |
| [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() override | Całkowity czas edycji prezentacji. Odczytaj [System::TimeSpan](../../system/timespan/). |
| **int32_t** [get_Words](./get_words/)() override | Zwraca całkowitą liczbę słów zawartych w dokumencie. Tylko do odczytu **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązanego z obiektem. |
| [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) override | Zwraca nazwę własności niestandardowej pod określonym indeksem. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) override | Pobiera nazwany wartość logiczną z własności niestandardowych. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) override | Pobiera nazwany wartość całkowitą z własności niestandardowych. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) override | Pobiera nazwany wartość DateTime z własności niestandardowych. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) override | Pobiera nazwany wartość string z własności niestandardowych. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) override | Pobiera nazwany wartość float z własności niestandardowych. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) override | Pobiera nazwany wartość double z własności niestandardowych. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() override | Pobiera tablicę etykiet wrażliwości z własności niestandardowych dokumentu (Microsoft Information Protection SDK Metadata). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) override | Zwraca własność niestandardową powiązaną z określoną nazwą. Odczytaj [System::Object](../../system/object/). |
| void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Ustawia własność niestandardową powiązaną z określoną nazwą. Zapisz [System::Object](../../system/object/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażniczego [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
| [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku stringów. |
| **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) override | Usuwa własność niestandardową powiązaną z określoną nazwą. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o określoną wartość. |
| void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) override | Ustawia szablon aplikacji. Zapisz [System::String](../../system/string/). |
| void [set_Author](./set_author/)([System::String](../../system/string/)) override | Ustawia autora prezentacji. Zapisz [System::String](../../system/string/). |
| void [set_Category](./set_category/)([System::String](../../system/string/)) override | Ustawia kategorię prezentacji. Zapisz [System::String](../../system/string/). |
| void [set_Comments](./set_comments/)([System::String](../../system/string/)) override | Ustawia komentarze prezentacji. Zapisz [System::String](../../system/string/). |
| void [set_Company](./set_company/)([System::String](../../system/string/)) override | Ustawia własność firmy. Zapisz [System::String](../../system/string/). |
| void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) override | Ustawia status treści prezentacji. Zapisz [System::String](../../system/string/). |
| void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) override | Ustawia typ treści prezentacji. Zapisz [System::String](../../system/string/). |
| void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) override | Zwraca datę utworzenia prezentacji. Wartości podane w UTC. Zapisz [System::DateTime](../../system/datetime/). |
| void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) override | Ustawia własność dokumentu HyperlinkBase. Zapisz [System::String](../../system/string/). |
| void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) override | Określa, że jeden lub więcej hiperłączy w tej części zostały zaktualizowane wyłącznie w tej części przez twórcę. Następny twórca otwierający dokument powinien zaktualizować relacje hiperłączy nowymi hiperłączami określonymi w tej części. Zapisz **bool**. |
| void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) override | Ustawia słowa kluczowe prezentacji. Zapisz [System::String](../../system/string/). |
| void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) override | Zwraca datę ostatniego drukowania prezentacji. Zapisz [System::DateTime](../../system/datetime/). |
| void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) override | Ustawia nazwę ostatniej osoby, która zmodyfikowała prezentację. Zapisz [System::String](../../system/string/). |
| void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) override | Zwraca datę ostatniej modyfikacji prezentacji. Wartości podane w UTC. Tylko do odczytu w przypadku [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) (ponieważ zostanie zaktualizowane wewnętrznie podczas procesu zapisywania obiektu [IPresentation](../ipresentation/)). Może być zmieniona poprzez instancję [DocumentProperties](./) zwracaną przez metodę [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). Proszę zobaczyć przykład w podsumowaniu metody [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) override | Wskazuje, czy hiperłącza w dokumencie są aktualne. Ustaw ten element na **true**, aby zaznaczyć, że hiperłącza są zaktualizowane. Ustaw ten element na **false**, aby zaznaczyć, że hiperłącza są nieaktualne. Zapisz **bool**. |
| void [set_Manager](./set_manager/)([System::String](../../system/string/)) override | Ustawia własność manager. Zapisz [System::String](../../system/string/). |
| void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) override | Ustawia nazwę aplikacji. Zapisz [System::String](../../system/string/). |
| void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) override | Ustawia zamierzony format prezentacji. Zapisz [System::String](../../system/string/). |
| void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) override | Ustawia numer rewizji prezentacji. Zapisz **int32_t**. |
| void [set_ScaleCrop](./set_scalecrop/)(**bool**) override | Wskazuje tryb wyświetlania miniatury dokumentu. Ustaw ten element na **true**, aby włączyć skalowanie miniatury dokumentu do wyświetlacza. Ustaw ten element na **false**, aby włączyć przycinanie miniatury dokumentu, aby wyświetlać tylko sekcje pasujące do wyświetlacza. Zapisz **bool**. |
| void [set_SharedDoc](./set_shareddoc/)(**bool**) override | Określa, czy prezentacja jest współdzielona pomiędzy wieloma osobami. Zapisz **bool**. |
| void [set_Subject](./set_subject/)([System::String](../../system/string/)) override | Ustawia temat prezentacji. Zapisz [System::String](../../system/string/). |
| void [set_Title](./set_title/)([System::String](../../system/string/)) override | Ustawia tytuł prezentacji. Zapisz [System::String](../../system/string/). |
| void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) override | Całkowity czas edycji prezentacji. Zapisz [System::TimeSpan](../../system/timespan/). |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) override | Ustawia nazwany własność logiczną. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) override | Ustawia nazwany własność całkowitą. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) override | Ustawia nazwany własność DateTime. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) override | Ustawia nazwany własność string. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) override | Ustawia nazwany własność float. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) override | Ustawia nazwany własność double. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustaw n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów do string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażniczego [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Uwagi

Poniższy przykład pokazuje, jak uzyskać dostęp do wbudowanych właściwości PowerPoint [Presentation](../presentation/).  
```cpp
// Utwórz instancję klasy Presentation, która reprezentuje prezentację
auto pres = System::MakeObject<Presentation>(dataDir + u"AccessBuiltin Properties.pptx");

// Utwórz referencję do obiektu IDocumentProperties powiązanego z prezentacją
System::SharedPtr<IDocumentProperties> documentProperties = pres->get_DocumentProperties();
// Wyświetl wbudowane właściwości
System::Console::WriteLine(System::String(u"Category : ") + documentProperties->get_Category());
System::Console::WriteLine(System::String(u"Current Status : ") + documentProperties->get_ContentStatus());
System::Console::WriteLine(System::String(u"Creation Date : ") + documentProperties->get_CreatedTime());
System::Console::WriteLine(System::String(u"Author : ") + documentProperties->get_Author());
System::Console::WriteLine(System::String(u"Description : ") + documentProperties->get_Comments());
```
Poniższy przykład pokazuje, jak zmodyfikować wbudowane właściwości PowerPoint [Presentation](../presentation/).  
```cpp
// Utwórz instancję klasy Presentation, która reprezentuje prezentację
auto presentation = System::MakeObject<Presentation>(dataDir + u"ModifyBuiltinProperties.pptx");

// Utwórz referencję do obiektu IDocumentProperties powiązanego z prezentacją
System::SharedPtr<IDocumentProperties> documentProperties = presentation->get_DocumentProperties();
// Ustaw wbudowane właściwości
documentProperties->set_Author(u"Aspose.Slides for .NET");
documentProperties->set_Title(u"Modifying Presentation Properties");
documentProperties->set_Subject(u"Aspose Subject");
// Zapisz swoją prezentację do pliku
presentation->Save(u"DocumentProperties_out.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Klasa [IDocumentProperties](../idocumentproperties/)
* Klasa [IGenericCloneable](../igenericcloneable/)
* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)