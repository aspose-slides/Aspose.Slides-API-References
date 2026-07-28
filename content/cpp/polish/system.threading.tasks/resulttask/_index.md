---
title: ResultTask
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Specjalizacja klasy Task, która zwraca wartość wyniku po zakończeniu.
type: docs
weight: 40
url: /pl/system.threading.tasks/resulttask/
---
## ResultTask klasa

Specjalizacja [Task](../task/) zwracająca wartość wyniku po zakończeniu.

```cpp
template<typename T>class ResultTask : public System::Threading::Tasks::Task
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ wartości wyniku zwracanej przez zadanie |

## Metody

| Metoda | Opis |
| --- | --- |
| void [Activate](../task/activate/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Aktywuje zadanie do wykonania w harmonogramie. |
| void [AddCompletionAction](../task/addcompletionaction/)(const [Action](../../system/action/)<>\&) | Dodaje akcję kontynuacji, która ma zostać wykonana po zakończeniu. |
| void [Cancel](../task/cancel/)() | Oznacza zadanie jako anulowane i kończy je. |
| void [Complete](./complete/)(const T\&) | Ustawia wartość wyniku dla zadania i kończy je. |
| void [Complete](../task/complete/)() | Oznacza zadanie jako zakończone i kończy je. |
| [Runtime::CompilerServices::ConfiguredResultTaskAwaitable](../../system.runtime.compilerservices/configuredresulttaskawaitable/)\<T\> [ConfigureAwait](./configureawait/)(**bool**) const | Konfiguruje zachowanie oczekiwań na to zadanie wynikowe w odniesieniu do przechwytywania kontekstu. |
| [TaskPtr](../../system/taskptr/) [ContinueWith](./continuewith/)(const [Action](../../system/action/)\<[RTaskPtr](../../system/rtaskptr/)\<T\>\>\&) | Tworzy kontynuację, która jest wykonywana po zakończeniu zadania wynikowego. |
| [RTaskPtr](../../system/rtaskptr/)\<TNewResult\> [ContinueWith](./continuewith/)(const [Func](../../system/func/)\<[RTaskPtr](../../system/rtaskptr/)\<T\>, TNewResult\>\&) | Tworzy kontynuację, która jest wykonywana po zakończeniu zadania wynikowego. |
| [TaskPtr](../../system/taskptr/) [ContinueWith](./continuewith/)(const [Action](../../system/action/)\<[TaskPtr](../../system/taskptr/)\>\&) | Tworzy kontynuację, która jest wykonywana po zakończeniu zadania. |
| [RTaskPtr](../../system/rtaskptr/)\<TResult\> [ContinueWith](./continuewith/)(const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/), TResult\>\&) | Tworzy kontynuację, która jest wykonywana po zakończeniu zadania. |
| void [Deactivate](../task/deactivate/)() | Dezaktywuje zadanie dla wykonania w jego bieżącym harmonogramie, jeśli istnieje. |
| void [Dispose](../task/dispose/)() override | Zwalnia zasoby powiązane z zadaniem. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| void [Execute](../task/execute/)() | Wykonuje funkcję zadania. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& [get_AsyncState](../task/get_asyncstate/)() const | Pobiera obiekt stanu zdefiniowany przez użytkownika powiązany z zadaniem. |
| static const [TaskPtr](../../system/taskptr/)\& [get_CompletedTask](../task/get_completedtask/)() | Pobiera zakończone zadanie (singleton). |
| static [Nullable](../../system/nullable/)\<**int32_t**\> [get_CurrentId](../task/get_currentid/)() |  |
| [AggregateException](../../system/aggregateexception/) [get_Exception](../task/get_exception/)() const | Pobiera identyfikator zadania. |
| **int32_t** [get_Id](../task/get_id/)() const |  |
| **bool** [get_IsCanceled](../task/get_iscanceled/)() const | Pobiera informację, czy zadanie zakończyło się z powodu anulowania. |
| **bool** [get_IsCompleted](../task/get_iscompleted/)() const | Pobiera informację, czy zadanie zostało zakończone. |
| **bool** [get_IsFaulted](../task/get_isfaulted/)() const | Pobiera informację, czy zadanie zakończyło się z powodu nieobsłużonego wyjątku. |
| T [get_Result](./get_result/)() | Pobiera wynik operacji asynchronicznej. |
| const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\& [get_Scheduler](../task/get_scheduler/)() const | Pobiera harmonogram powiązany z tym zadaniem. |
| [TaskStatus](../taskstatus/) [get_Status](../task/get_status/)() const | Pobiera bieżący status zadania. |
| [Runtime::CompilerServices::ResultTaskAwaiter](../../system.runtime.compilerservices/resulttaskawaiter/)\<T\> [GetAwaiter](./getawaiter/)() const | Pobiera oczekującego dla tego zadania wynikowego do użycia z Await. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku stringów. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
|  [ResultTask](./resulttask/)(const [Func](../../system/func/)\<T\>\&) | Tworzy [ResultTask](./) z funkcją zwracającą wartość. |
|  [ResultTask](./resulttask/)() | Wewnętrzna implementacja. Nie przeznaczona dla kodu użytkownika. |
|  [ResultTask](./resulttask/)(const T\&) | Wewnętrzny konstruktor tworzący zadania wynikowe z określonym wynikiem. |
| void [RunSynchronously](../task/runsynchronously/)() | Uruchamia zadanie synchronicznie w bieżącym wątku. |
| void [RunSynchronously](../task/runsynchronously/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Uruchamia zadanie synchronicznie przy użyciu określonego harmonogramu. |
| void [set_Function](../task/set_function/)(const [FunctionT](../task/functiont/)\&) | Ustawia wewnętrzną funkcję do wykonania. |
| void [set_Result](./set_result/)(const T\&) | Ustawia wartość wyniku dla zadania. |
| void [set_Scheduler](../task/set_scheduler/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Ustawia harmonogram powiązany z tym zadaniem. |
| void [set_Status](../task/set_status/)([TaskStatus](../taskstatus/)) | Ustawia status zadania. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [Start](../task/start/)() | Rozpoczyna wykonanie zadania przy użyciu domyślnego harmonogramu. |
| void [Start](../task/start/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Rozpoczyna wykonanie zadania przy użyciu określonego harmonogramu. |
|  [Task](../task/task/)(const [Action](../../system/action/)<>\&) | Tworzy [Task](../task/) z akcją do wykonania. |
|  [Task](../task/task/)(const [Action](../../system/action/)<>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Tworzy [Task](../task/) z akcją i tokenem anulowania. |
|  [Task](../task/task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Tworzy [Task](../task/) z akcją stanową i obiektem stanu. |
|  [Task](../task/task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Tworzy [Task](../task/) z akcją stanową, stanem i tokenem anulowania. |
|  [Task](../task/task/)() | Wewnętrzny konstruktor tworzący niezainicjowane zadania. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na ciąg znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| void [Wait](../task/wait/)(const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Czeka na zakończenie zadania z obsługą anulowania. |
| void [Wait](../task/wait/)() | Czeka na zakończenie zadania. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Usuwa obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |
|  [~Task](../task/~task/)() | Destruktor. |

## Uwagi

Reprezentuje operację asynchroniczną, która zwraca wynik, podobną do System.Threading.Tasks.Task<TResult> w .NET 

## Zobacz także

* Klasa [Task](../task/)
* Przestrzeń nazw [System::Threading::Tasks](../)
* Biblioteka [Aspose.Slides](../../)