---
title: Thread
second_title: Dokumentacja API Aspose.Slides dla C++
description: "Implementacja wątku. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonania i/lub błędy asercji. Zawsze opakowuj tę klasę w wskaźnik System::SmartPtr i używaj tego wskaźnika do przekazywania go do funkcji jako argument."
type: docs
weight: 209
url: /pl/system.threading/thread/
---
## Klasa Thread

[Thread](./) implementacja. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonania i/lub błędy asercji. Zawsze opakowuj tę klasę w wskaźnik [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argument.

```cpp
class Thread : public System::Object
```

## Metody

| Metoda | Opis |
| --- | --- |
| void [Abort](./abort/)() | Zatrzymuje wątek. Nie zaimplementowano. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\> [get_CurrentCulture](./get_currentculture/)() | Pobiera kulturę wątku. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Thread](./)\> [get_CurrentThread](./get_currentthread/)() | Pobiera obiekt opisujący bieżący wątek. |
| [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\> [get_CurrentUICulture](./get_currentuiculture/)() | Pobiera kulturę interfejsu użytkownika używaną przez wątek. |
| **bool** [get_IsAlive](./get_isalive/)() | Sprawdza, czy wątek jest żywy. |
| **bool** [get_IsBackground](./get_isbackground/)() | Sprawdza, czy wątek działa w tle. |
| **bool** [get_IsThreadPoolThread](./get_isthreadpoolthread/)() | Sprawdza, czy wątek jest własnością puli wątków. |
| int [get_ManagedThreadId](./get_managedthreadid/)() const | Pobiera identyfikator wątku. Można go uzyskać z systemu operacyjnego, ale jeśli identyfikator wątku OS przekracza zakres int, identyfikatory wątków mogą się pokrywać. |
| [System::String](../../system/string/) [get_Name](./get_name/)() | Pobiera nazwę wątku. |
| [ThreadState](../threadstate/) [get_ThreadState](./get_threadstate/)() | Pobiera stan wątku. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| static int [GetCurrentThreadId](./getcurrentthreadid/)() | Pobiera identyfikator bieżącego wątku. |
| int [GetHashCode](./gethashcode/)() const override |  |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| void [Interrupt](./interrupt/)() | Przerywa wątek. Nie zaimplementowano. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt reprezentuje instancję typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Join](./join/)() | Dołącza do zarządzanego wątku. Wykonuje nieograniczone oczekiwanie, jeśli wymaga tego sytuacja. |
| **bool** [Join](./join/)(int) | Dołącza do zarządzanego wątku. Wykonuje ograniczone oczekiwanie. |
| **bool** [Join](./join/)([TimeSpan](../../system/timespan/)) | Dołącza do zarządzanego wątku. Wykonuje ograniczone oczekiwanie. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie typów niestandardowych. |
| static void [MemoryBarrier](./memorybarrier/)() | Synchronizuje dostęp do pamięci. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nie kopiuje nic, tylko inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Thread](./)\& [operator=](./operator_equal/)(const [Thread](./)\&) | Kopiuje dane TLS z innego wątku. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nie kopiuje nic, tylko inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku stringów. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| void [set_CurrentCulture](./set_currentculture/)(const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Ustawia kulturę wątku. |
| void [set_CurrentUICulture](./set_currentuiculture/)(const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Ustawia kulturę interfejsu użytkownika używaną przez wątek. |
| void [set_IsBackground](./set_isbackground/)(**bool**) | Ustawia, czy wątek ma działać w tle, czy na pierwszym planie. |
| void [set_Name](./set_name/)(const [System::String](../../system/string/)\&) | Ustawia nazwę wątku. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego używaj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego używaj inteligentnych wskaźników lub ThisProtector. |
| static void [Sleep](./sleep/)(int) | Zatrzymuje bieżący wątek na określony limit czasu. |
| static void [Sleep](./sleep/)([TimeSpan](../../system/timespan/)) | Zatrzymuje bieżący wątek na określony limit czasu. |
| static void [SpinWait](./spinwait/)(int) | Czeka na określoną liczbę iteracji pętli. |
| void [Start](./start/)() | Uruchamia wątek przy użyciu obiektu argumentu null. |
| void [Start](./start/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Uruchamia wątek. |
|  [Thread](./thread/)() | Konstruktor. |
|  [Thread](./thread/)([ThreadStart](../threadstart/)) | Konstruktor. |
|  [Thread](./thread/)([ParameterizedThreadStart](../parameterizedthreadstart/)) | Konstruktor. |
|  [Thread](./thread/)([Thread](./)\&) | Konstruktor kopiujący. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwertowanie niestandardowych obiektów na ciąg znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego używaj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego używaj inteligentnych wskaźników lub ThisProtector. |
| static **bool** [Yield](./yield/)() | Zawiesza wątek. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |
| virtual  [~Thread](./~thread/)() | Destruktor. |

## Uwagi

```cpp
#include "system/threading/thread.h"
#include "system/smart_ptr.h"

int main()
{
  auto thread = System::MakeObject<System::Threading::Thread>([]()
  {
    std::cout << "Child thread ID: " << System::Threading::Thread::GetCurrentThreadId() << std::endl;
    System::Threading::Thread::Sleep(200);
  });

  std::cout << "Main thread ID: " << System::Threading::Thread::GetCurrentThreadId() << std::endl;

  thread->Start();
  thread->Join();

  return 0;
}
/*
Ten przykład kodu generuje następujący wynik:
Identyfikator wątku głównego: 2
Identyfikator wątku potomnego: 1
*/
```

## Zobacz także

* Klasa [Object](../../system/object/)
* Przestrzeń nazw [System::Threading](../)
* Biblioteka [Aspose.Slides](../../)