---
title: ModernComment
second_title: Aspose.Slides dla C++ - odniesienie API
description: Reprezentuje komentarz na slajdzie.
type: docs
weight: 4512
url: /pl/aspose.slides/moderncomment/
---
## ModernComment klasa


Reprezentuje komentarz na slajdzie.

```cpp
class ModernComment : public Aspose::Slides::Comment,
                      public Aspose::Slides::IModernComment
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\> [get_Author](../comment/get_author/)() override | Zwraca autora komentarza. Tylko do odczytu [ICommentAuthor](../icommentauthor/). |
| [System::DateTime](../../system/datetime/) [get_CreatedTime](../comment/get_createdtime/)() override | Zwraca czas utworzenia komentarza. Ustawienie tej właściwości na [DateTime::MinValue](../../system/datetime/minvalue/) oznacza, że nie ustawiono czasu komentarza. Tylko odczyt [System::DateTime](../../system/datetime/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\> [get_ParentComment](../comment/get_parentcomment/)() override | Pobiera komentarz nadrzędny. Tylko odczyt [IComment](../icomment/). |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_Position](../comment/get_position/)() override | Zwraca pozycję komentarza na slajdzie. Tylko odczyt [System::Drawing::PointF](../../system.drawing/pointf/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](./get_shape/)() override | Zwraca kształt powiązany z komentarzem. Tylko do odczytu [IShape](../ishape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_Slide](../comment/get_slide/)() override | Zwraca slajd nadrzędny komentarza. Tylko do odczytu [ISlide](../islide/). |
| [ModernCommentStatus](../moderncommentstatus/) [get_Status](./get_status/)() override | Pobiera status komentarza. Tylko odczyt [ModernCommentStatus](../moderncommentstatus/). |
| [System::String](../../system/string/) [get_Text](../comment/get_text/)() override | Zwraca zwykły tekst komentarza slajdu. Tylko odczyt [System::String](../../system/string/). |
| **int32_t** [get_TextSelectionLength](./get_textselectionlength/)() override | Pobiera długość zaznaczenia tekstu w ramce tekstowej, jeśli komentarz jest powiązany z [AutoShape](../autoshape/). Tylko odczyt **int32_t**. |
| **int32_t** [get_TextSelectionStart](./get_textselectionstart/)() override | Pobiera początkową pozycję zaznaczenia tekstu w ramce tekstowej, jeśli komentarz jest powiązany z [AutoShape](../autoshape/). Tylko odczyt **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu straży [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku łańcucha znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku łańcuchów znaków. |
| void [Remove](../comment/remove/)() override | Usuwa komentarz i wszystkie jego odpowiedzi z kolekcji nadrzędnej. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| void [set_CreatedTime](../comment/set_createdtime/)([System::DateTime](../../system/datetime/)) override | Ustawia czas utworzenia komentarza. Ustawienie tej właściwości na [DateTime::MinValue](../../system/datetime/minvalue/) oznacza, że nie ustawiono czasu komentarza. Zapis [System::DateTime](../../system/datetime/). |
| void [set_ParentComment](../comment/set_parentcomment/)([System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\>) override | Ustawia komentarz nadrzędny. Zapis [IComment](../icomment/). |
| void [set_Position](../comment/set_position/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | Ustawia pozycję komentarza na slajdzie. Zapis [System::Drawing::PointF](../../system.drawing/pointf/). |
| void [set_Status](./set_status/)([ModernCommentStatus](../moderncommentstatus/)) override | Ustawia status komentarza. Zapis [ModernCommentStatus](../moderncommentstatus/). |
| void [set_Text](../comment/set_text/)([System::String](../../system/string/)) override | Ustawia zwykły tekst komentarza slajdu. Zapis [System::String](../../system/string/). |
| void [set_TextSelectionLength](./set_textselectionlength/)(**int32_t**) override | Ustawia długość zaznaczenia tekstu w ramce tekstowej, jeśli komentarz jest powiązany z [AutoShape](../autoshape/). Zapis **int32_t**. |
| void [set_TextSelectionStart](./set_textselectionstart/)(**int32_t**) override | Ustawia początkową pozycję zaznaczenia tekstu w ramce tekstowej, jeśli komentarz jest powiązany z [AutoShape](../autoshape/). Zapis **int32_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala zmienić wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów do stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu straży [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Usuwa obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Uwagi



```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto newAuthor = pres->get_CommentAuthors()->AddAuthor(u"Some Author", u"SA");
auto modernComment = newAuthor->get_Comments()->AddModernComment(u"This is modern comment", slide, nullptr, PointF(100.0f, 100.0f), DateTime::get_Now());

pres->Save(u"output.pptx", SaveFormat::Pptx);
```




## Zobacz także

* Klasa [Comment](../comment/)
* Klasa [IModernComment](../imoderncomment/)
* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)