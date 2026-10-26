---
title: X509CertificateCollectionPtr
second_title: Odwołanie API Aspose.Slides dla C++
description: Wskaźnik do kolekcji certyfikatów X509. Ten typ jest wskaźnikiem służącym do zarządzania usuwaniem innych obiektów. Powinien być alokowany na stosie i przekazywany do funkcji jako wartość lub przez referencję const.
type: docs
weight: 92
url: /pl/system.security.cryptography.x509certificates/x509certificatecollectionptr/
---
## X509CertificateCollectionPtr klasa

Wskaźnik do kolekcji certyfikatów X509. Ten typ jest wskaźnikiem służącym do zarządzania usuwaniem innych obiektów. Powinien być alokowany na stosie i przekazywany do funkcji jako wartość lub przez referencję const.

```cpp
class X509CertificateCollectionPtr : public System::SmartPtr<X509CertificateCollection>
```

## Metody

| Metoda | Opis |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Akcesor dla metody [begin()](../../system/smartptr/begin/) w bazowej kolekcji. Kompiluje się tylko, gdy SmartPtr_ jest typem specjalizacji z metodą [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | Akcesor dla metody [begin()](../../system/smartptr/begin/) w bazowej kolekcji. Kompiluje się tylko, gdy SmartPtr_ jest typem specjalizacji z metodą [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Rzutuje wskaźnik na jego własny typ. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Rzutuje wskaźnik na typ bazowy przy użyciu static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Rzutuje wskaźnik na typ pochodny przy użyciu dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Rzutuje wskaźnik na typ pochodny przy użyciu dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Akcesor dla metody [cbegin()](../../system/smartptr/cbegin/) w bazowej kolekcji. Kompiluje się tylko, gdy SmartPtr_ jest typem specjalizacji z metodą [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | Akcesor dla metody [cend()](../../system/smartptr/cend/) w bazowej kolekcji. Kompiluje się tylko, gdy SmartPtr_ jest typem specjalizacji z metodą [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Rzutuje wskaźnik na inny typ przy użyciu const_cast na wskazywanym obiekcie. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Rzutuje wskaźnik na inny typ przy użyciu dynamic_cast na wskazywanym obiekcie. |
| auto [end](../../system/smartptr/end/)() | Akcesor dla metody [end()](../../system/smartptr/end/) w bazowej kolekcji. Kompiluje się tylko, gdy SmartPtr_ jest typem specjalizacji z metodą [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | Akcesor dla metody [end()](../../system/smartptr/end/) w bazowej kolekcji. Kompiluje się tylko, gdy SmartPtr_ jest typem specjalizacji z metodą [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Pobiera wskazywany obiekt. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Pobiera tryb wskaźnika. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Pobiera wskazywany obiekt, ale wymusza, że wskaźnik jest w trybie współdzielonym. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Zwraca liczbę istniejących współdzielonych wskaźników do referowanego obiektu, włączając bieżący. Wymusza, że bieżący wskaźnik jest w trybie współdzielonym. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Wywołuje [GetHashCode()](../../system/smartptr/gethashcode/) na wskazywanym obiekcie. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Pobiera aktualnie referowany obiekt (jeśli istnieje) lub zgłasza wyjątek. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Pobiera wskazywany obiekt (jeśli istnieje) lub nullptr. To samo co [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Pobiera referowany obiekt. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Pobiera wskazywany obiekt (jeśli istnieje) lub nullptr. To samo co [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy wskazywany obiekt jest określonego typu lub jego typu potomnego. Zgodne z semantyką C# 'is'. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Sprawdza, czy wskaźnik wskazuje na inny obiekt niż własny (utworzony konstruktorem aliasującym). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Sprawdza, czy wskaźnik jest w trybie współdzielonym. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Sprawdza, czy wskaźnik jest w trybie słabym. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Sprawdza, czy wskaźnik nie jest null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Sprawdza, czy wskaźnik jest null. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Pobiera referencję do wskazywanego obiektu. Wymusza, że wskaźnik nie jest null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Umożliwia dostęp do członków referowanego obiektu. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Udostępnia semantykę porównania mniejszości dla klasy [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Udostępnia semantykę porównania mniejszości dla klasy [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Przypisuje przenosząco obiekt [SmartPtr](../../system/smartptr/). x staje się nieużyteczny. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Kopiująco przypisuje obiekt [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Kopiująco przypisuje obiekt [SmartPtr](../../system/smartptr/). Wykonuje wymagane konwersje typów. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Przypisuje surowy wskaźnik do obiektu [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Ustawia wartość wskaźnika na nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Sprawdza, czy wskaźnik wskazuje na nullptr. |
| [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\>\& [operator[]](./operator[]/)(int) const | Akcesor. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Usuwa aliasowanie (utworzone konstruktorem aliasującym) ze wskaźnika, zapewniając, że zarządza (jeśli współdzielony) lub śledzi (jeśli słaby) tym samym obiektem, na który wskazuje. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Ustawia wskazywany obiekt. |
| void [reset](../../system/smartptr/reset/)() | Ustawia wskaźnik na nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Ustawia tryb wskaźnika. Może zmienić liczniki referencji referowanego obiektu. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Wywołuje metodę SetTemplateWeakPtr() na wskazywanym obiekcie (jeśli istnieje). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Tworzy obiekt [SmartPtr](../../system/smartptr/) w wymaganym trybie. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Tworzy null-pointer obiekt [SmartPtr](../../system/smartptr/) w wymaganym trybie. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Tworzy [SmartPtr](../../system/smartptr/) wskazujący na określony obiekt lub konwertuje surowy wskaźnik na [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Konstruktor kopiujący tworzy obiekt [SmartPtr](../../system/smartptr/). Po konstrukcji oba wskaźniki wskazują na ten sam obiekt. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Konstruktor kopiujący tworzy obiekt [SmartPtr](../../system/smartptr/). Po konstrukcji oba wskaźniki wskazują na ten sam obiekt. Wykonuje konwersję typów, jeśli jest dozwolona. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Konstruktor przenoszący tworzy obiekt [SmartPtr](../../system/smartptr/). W praktyce zamienia dwa wskaźniki, jeśli oba są tego samego trybu. x może być nieużyteczny po wywołaniu. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Konwertuje typ referowanej tablicy, tworząc nową tablicę innego typu. Przydatne, gdy w C# istnieje rzutowanie typu tablicy, które nie jest obsługiwane w C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Inicjalizuje pustą tablicę. Używane do tłumaczenia niektórych konstrukcji kodu C#. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Konstruktor tworzy [SmartPtr](../../system/smartptr/), który współdzieli informacje o własności z początkową wartością ptr, ale przechowuje niepowiązany i niezarządzany wskaźnik p. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Rzutuje wskaźnik na inny typ przy użyciu static_cast na wskazywanym obiekcie. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Konwertuje dowolny typ wskaźnika na wskaźnik do [Object](../../system/object/). Nie wymaga, aby typ Pointee_ był kompletny. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Skrót aby uzyskać obiekt [System::TypeInfo](../../system/typeinfo/) dla typu Pointee_. |
|  [X509CertificateCollectionPtr](./x509certificatecollectionptr/)() | Konstruktor wskaźnika null. |
|  [X509CertificateCollectionPtr](./x509certificatecollectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[X509CertificateCollection](../x509certificatecollection/)\>\&) | Konstruktor. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Niszczy obiekt [SmartPtr](../../system/smartptr/). W razie potrzeby zmniejsza licznik referencji wskazywanego obiektu i usuwa obiekt. |

## Zobacz także

* Klasa [SmartPtr](../../system/smartptr/)
* Przestrzeń nazw [System::Security::Cryptography::X509Certificates](../)
* Biblioteka [Aspose.Slides](../../)