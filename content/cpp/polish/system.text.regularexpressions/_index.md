---
title: "System::Text::RegularExpressions"
second_title: Aspose.Slides dla C++ – referencja API
description: 
type: docs
weight: 989
url: /pl/system.text.regularexpressions/
---
## Klasy

| Klasa | Opis |
| --- | --- |
| [Capture](./capture/) | Wynik dopasowania pojedynczego podwyrażenia. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie działania i/lub awarie asercji. Zawsze opakowuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej funkcjom jako argument. |
| [CaptureCollection](./capturecollection/) | Lista przechwyceń wykonanych przez pojedynczą grupę przechwytującą. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie działania i/lub awarie asercji. Zawsze opakowuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej funkcjom jako argument. |
| [Group](./group/) | Wynik dopasowania wykonanego przez pojedynczą grupę przechwytującą. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie działania i/lub awarie asercji. Zawsze opakowuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej funkcjom jako argument. |
| [GroupCollection](./groupcollection/) | Lista grup przechwytujących w pojedynczym dopasowaniu. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie działania i/lub awarie asercji. Zawsze opakowuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej funkcjom jako argument. |
| [GroupCollectionPtr](./groupcollectionptr/) | [Group](./group/) wskaźnik kolekcji. Ten typ jest wskaźnikiem do zarządzania usuwaniem obiektów innych. Powinien być alokowany na stosie i przekazywany do funkcji przez wartość lub przez stałą referencję. |
| [Match](./match/) | [Single](../system/single/) dopasowanie wyrażenia regularnego do łańcucha. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie działania i/lub awarie asercji. Zawsze opakowuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej funkcjom jako argument. |
| [MatchCollection](./matchcollection/) | Kolekcja dopasowań wykonanych przez wielokrotne stosowanie wyrażenia regularnego do łańcucha. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie działania i/lub awarie asercji. Zawsze opakowuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej funkcjom jako argument. |
| [Regex](./regex/) | Wyrażenie regularne, które używa składni podobnej do C#. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie działania i/lub awarie asercji. Zawsze opakowuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej funkcjom jako argument. |
## Funkcje

| Funkcja | Opis |
| --- | --- |
|  [ASPOSECPP_3RD_PARTY_UNCOPYBALE_TYPE_HOLDER](./asposecpp_3rd_party_uncopybale_type_holder/)(Detail::MatchHolder, MatchHolder, sizeof(Detail::DummyMatchHolder), Detail::DummyMatchHolder, MatchHolderAlias) | Opakowanie służące do przechowywania klasy MatchHolder bez jej dołączania oraz PCRE2. |
## Wyliczenia

| Wyliczenie | Opis |
| --- | --- |
| [RegexOptions](./regexoptions/) | [Regex](./regex/) opcje. |
## Typedefy

| Typedef | Opis |
| --- | --- |
| [UStringPtr](./ustringptr/) | Współdzielony UnicodeString w celu uniknięcia kopiowania. |
| [CapturePtr](./captureptr/) | Wskaźnik do pojedynczego obiektu przechwycenia. |
| [CaptureCollectionPtr](./capturecollectionptr/) | Wskaźnik do kolekcji przechwytów. |
| [GroupPtr](./groupptr/) | Wskaźnik do grupy. |
| [RegexPtr](./regexptr/) | [Regex](./regex/) wskaźnik. |
| [MatchPtr](./matchptr/) | [Match](./match/) wskaźnik. |
| [MatchCollectionPtr](./matchcollectionptr/) | [Match](./match/) wskaźnik kolekcji. |
| [MatchEvaluator](./matchevaluator/) | Typ delegata do oceny dopasowania. |