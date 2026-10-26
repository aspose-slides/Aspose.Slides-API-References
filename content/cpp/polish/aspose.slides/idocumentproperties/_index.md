---
title: IDocumentProperties
second_title: Aspose.Slides dla C++ Referencja API
description: Reprezentuje właściwości prezentacji.
type: docs
weight: 1977
url: /pl/aspose.slides/idocumentproperties/
---
## IDocumentProperties klasa

Reprezentuje właściwości prezentacji.

```cpp
class IDocumentProperties : public virtual System::Object
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual void [ClearBuiltInProperties](./clearbuiltinproperties/)() | Czyści i ustawia wartości domyślne dla wszystkich własności builtIn. |
| virtual void [ClearCustomProperties](./clearcustomproperties/)() | Usuwa wszystkie własności niestandardowe. |
| virtual **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) | Sprawdza obecność własności niestandardowej o określonej nazwie. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartości w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() | Zwraca szablon aplikacji. Zobacz [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() | Zwraca wersję aplikacji. Tylko do odczytu [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Author](./get_author/)() | Zwraca autora prezentacji. Zobacz [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Category](./get_category/)() | Zwraca kategorię prezentacji. Zobacz [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Comments](./get_comments/)() | Zwraca komentarze prezentacji. Zobacz [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Company](./get_company/)() | Zwraca własność firmy. Zobacz [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() | Zwraca status treści prezentacji. Zobacz [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() | Zwraca typ treści prezentacji. Zobacz [System::String](../../system/string/). |
| virtual **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() | Zwraca liczbę własności niestandardowych rzeczywiście zawartych w kolekcji. Tylko do odczytu **int32_t**. |
| virtual [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() | Zwraca datę utworzenia prezentacji. Wartości w UTC. Zobacz [System::DateTime](../../system/datetime/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() | Wskazuje grupowanie części dokumentu oraz liczbę części w każdej grupie. Tylko do odczytu [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/). |
| virtual **int32_t** [get_HiddenSlides](./get_hiddenslides/)() | Określa liczbę ukrytych slajdów w dokumencie prezentacji. Tylko do odczytu **int32_t**. |
| virtual [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() | Zwraca własność dokumentu HyperlinkBase. Zobacz [System::String](../../system/string/). |
| virtual **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() | Określa, że jeden lub więcej hiperłączy w tej części zostało zaktualizowanych wyłącznie w tej części przez producenta. Następny producent otwierający dokument powinien zaktualizować relacje hiperłączy nowymi hiperłączami określonymi w tej części. Zobacz **bool**. |
| virtual [System::String](../../system/string/) [get_Keywords](./get_keywords/)() | Zwraca słowa kluczowe prezentacji. Zobacz [System::String](../../system/string/). |
| virtual [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() | Zwraca datę ostatniego wydrukowania prezentacji. Zobacz [System::DateTime](../../system/datetime/). |
| virtual [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() | Zwraca nazwę ostatniej osoby, która modyfikowała prezentację. Zobacz [System::String](../../system/string/). |
| virtual [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() | Zwraca datę ostatniej modyfikacji prezentacji. Wartości w UTC. Tylko do odczytu w przypadku Presentation.DocumentProperties (ponieważ zostanie zaktualizowane wewnętrznie podczas procesu zapisywania obiektu [IPresentation](../ipresentation/)). Może być zmieniona poprzez instancję [DocumentProperties](../documentproperties/) zwracaną metodą [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). Proszę zobaczyć przykład w podsumowaniu metody [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| virtual **bool** [get_LinksUpToDate](./get_linksuptodate/)() | Wskazuje, czy hiperłącza w dokumencie są aktualne. Ustaw ten element na **true**, aby oznaczyć, że hiperłącza są zaktualizowane. Ustaw na **false**, aby oznaczyć, że są nieaktualne. Zobacz **bool**. |
| virtual [System::String](../../system/string/) [get_Manager](./get_manager/)() | Zwraca własność managera. Zobacz [System::String](../../system/string/). |
| virtual **int32_t** [get_MultimediaClips](./get_multimediaclips/)() | Określa łączną liczbę klipów dźwiękowych lub wideo obecnych w dokumencie. Tylko do odczytu **int32_t**. |
| virtual [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() | Zwraca nazwę aplikacji. Zobacz [System::String](../../system/string/). |
| virtual **int32_t** [get_Notes](./get_notes/)() | Określa liczbę slajdów w prezentacji zawierających notatki. Tylko do odczytu **int32_t**. |
| virtual **int32_t** [get_Paragraphs](./get_paragraphs/)() | Określa łączną liczbę akapitów znalezionych w dokumencie, jeśli ma zastosowanie. Tylko do odczytu **int32_t**. |
| virtual [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() | Zwraca zamierzony format prezentacji. Zobacz [System::String](../../system/string/). |
| virtual **int32_t** [get_RevisionNumber](./get_revisionnumber/)() | Zwraca numer wersji prezentacji. Zobacz **int32_t**. |
| virtual **bool** [get_ScaleCrop](./get_scalecrop/)() | Wskazuje tryb wyświetlania miniatury dokumentu. Ustaw element na **true**, aby włączyć skalowanie miniatury do wyświetlacza. Ustaw na **false**, aby przyciąć miniaturę, by wyświetlić jedynie sekcje pasujące do ekranu. Zobacz **bool**. |
| virtual **bool** [get_SharedDoc](./get_shareddoc/)() | Określa, czy prezentacja jest udostępniana wielu osobom. Zobacz **bool**. |
| virtual **int32_t** [get_Slides](./get_slides/)() | Określa łączną liczbę slajdów w dokumencie prezentacji. Tylko do odczytu **int32_t**. |
| virtual [System::String](../../system/string/) [get_Subject](./get_subject/)() | Zwraca temat prezentacji. Zobacz [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Title](./get_title/)() | Zwraca tytuł prezentacji. Zobacz [System::String](../../system/string/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() | Określa tytuł każdej części dokumentu. Te części nie są rzeczywistymi częściami dokumentu, lecz konceptualnymi reprezentacjami sekcji dokumentu. Tylko do odczytu [System::ArrayPtr<System::String>](../../system/arrayptr/). |
| virtual [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() | Łączny czas edycji prezentacji. Zobacz [System::TimeSpan](../../system/timespan/). |
| virtual **int32_t** [get_Words](./get_words/)() | Określa łączną liczbę słów w dokumencie. Tylko do odczytu **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) | Zwraca nazwę własności niestandardowej pod podanym indeksem. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) | Pobiera nazwany wartość boolowską z własności niestandardowych. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) | Pobiera nazwany wartość całkowitą z własności niestandardowych. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) | Pobiera nazwany wartość DateTime z własności niestandardowych. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) | Pobiera nazwany wartość typu string z własności niestandardowych. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) | Pobiera nazwany wartość float z własności niestandardowych. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) | Pobiera nazwany wartość double z własności niestandardowych. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie obiektów niestandardowych. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() | Pobiera tablicę etykiet wrażliwości z własności niestandardowych dokumentu (Microsoft Information Protection SDK Metadata). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) | Zwraca własność niestandardową powiązaną z określoną nazwą. Zobacz [System::Object](../../system/object/). |
| virtual void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Ustawia własność niestandardową powiązaną z określoną nazwą. Zapisz [System::Object](../../system/object/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt reprezentuje instancję typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu ochronnego [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie typów niestandardowych. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartości z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| virtual **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) | Usuwa własność niestandardową powiązaną z określoną nazwą. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| virtual void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) | Ustawia szablon aplikacji. Zapisz [System::String](../../system/string/). |
| virtual void [set_Author](./set_author/)([System::String](../../system/string/)) | Ustawia autora prezentacji. Zapisz [System::String](../../system/string/). |
| virtual void [set_Category](./set_category/)([System::String](../../system/string/)) | Ustawia kategorię prezentacji. Zapisz [System::String](../../system/string/). |
| virtual void [set_Comments](./set_comments/)([System::String](../../system/string/)) | Ustawia komentarze prezentacji. Zapisz [System::String](../../system/string/). |
| virtual void [set_Company](./set_company/)([System::String](../../system/string/)) | Ustawia własność firmy. Zapisz [System::String](../../system/string/). |
| virtual void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) | Ustawia status treści prezentacji. Zapisz [System::String](../../system/string/). |
| virtual void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) | Ustawia typ treści prezentacji. Zapisz [System::String](../../system/string/). |
| virtual void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) | Zwraca datę utworzenia prezentacji. Wartości w UTC. Zapisz [System::DateTime](../../system/datetime/). |
| virtual void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) | Ustawia własność dokumentu HyperlinkBase. Zapisz [System::String](../../system/string/). |
| virtual void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) | Określa, że jeden lub więcej hiperłączy w tej części zostało zaktualizowanych wyłącznie w tej części przez producenta. Następny producent otwierający dokument powinien zaktualizować relacje hiperłączy nowymi hiperłączami określonymi w tej części. Zapisz **bool**. |
| virtual void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) | Ustawia słowa kluczowe prezentacji. Zapisz [System::String](../../system/string/). |
| virtual void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) | Zwraca datę ostatniego wydrukowania prezentacji. Zapisz [System::DateTime](../../system/datetime/). |
| virtual void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) | Ustawia nazwę ostatniej osoby, która modyfikowała prezentację. Zapisz [System::String](../../system/string/). |
| virtual void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) | Zwraca datę ostatniej modyfikacji prezentacji. Wartości w UTC. Tylko do odczytu w przypadku Presentation.DocumentProperties (ponieważ będzie aktualizowane wewnętrznie podczas procesu zapisywania obiektu [IPresentation](../ipresentation/)). Może być zmieniona poprzez instancję [DocumentProperties](../documentproperties/) zwracaną metodą [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). Proszę zobaczyć przykład w podsumowaniu metody [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| virtual void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) | Wskazuje, czy hiperłącza w dokumencie są aktualne. Ustaw element na **true**, aby oznaczyć, że hiperłącza są zaktualizowane. Ustaw na **false**, aby oznaczyć, że są nieaktualne. Zapisz **bool**. |
| virtual void [set_Manager](./set_manager/)([System::String](../../system/string/)) | Ustawia własność managera. Zapisz [System::String](../../system/string/). |
| virtual void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) | Ustawia nazwę aplikacji. Zapisz [System::String](../../system/string/). |
| virtual void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) | Ustawia zamierzony format prezentacji. Zapisz [System::String](../../system/string/). |
| virtual void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) | Ustawia numer wersji prezentacji. Zapisz **int32_t**. |
| virtual void [set_ScaleCrop](./set_scalecrop/)(**bool**) | Wskazuje tryb wyświetlania miniatury dokumentu. Ustaw element na **true**, aby włączyć skalowanie miniatury do wyświetlacza. Ustaw na **false**, aby przyciąć miniaturę, by wyświetlić jedynie sekcje pasujące do ekranu. Zapisz **bool**. |
| virtual void [set_SharedDoc](./set_shareddoc/)(**bool**) | Określa, czy prezentacja jest udostępniana wielu osobom. Zapisz **bool**. |
| virtual void [set_Subject](./set_subject/)([System::String](../../system/string/)) | Ustawia temat prezentacji. Zapisz [System::String](../../system/string/). |
| virtual void [set_Title](./set_title/)([System::String](../../system/string/)) | Ustawia tytuł prezentacji. Zapisz [System::String](../../system/string/). |
| virtual void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) | Łączny czas edycji prezentacji. Zapisz [System::TimeSpan](../../system/timespan/). |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) | Ustawia nazwany własność boolowską. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) | Ustawia nazwany własność całkowitą. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) | Ustawia nazwany własność DateTime. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) | Ustawia nazwany własność typu string. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) | Ustawia nazwany własność float. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) | Ustawia nazwany własność double. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako wskaźnik słaby (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję obiektów niestandardowych na string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu ochronnego [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [Object](../../system/object/)
* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)