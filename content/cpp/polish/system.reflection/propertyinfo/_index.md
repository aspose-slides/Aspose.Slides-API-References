---
title: PropertyInfo
second_title: Aspose.Slides dla C++ referencji API
description: Reprezentuje informacje o właściwości.
type: docs
weight: 144
url: /pl/system.reflection/propertyinfo/
---
## PropertyInfo klasa

Reprezentuje informacje o właściwościach.

```cpp
class PropertyInfo : public System::Reflection::MemberInfo
```

## Metody

| Metoda | Opis |
| --- | --- |
| void [AddAttribute](../memberinfo/addattribute/)(const [ObjectPtr](../memberinfo/objectptr/)\&) | Dodaje atrybut do kolekcji. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [TypeInfo](../../system/typeinfo/) [get_DeclaringType](../memberinfo/get_declaringtype/)() const | Zwraca typ deklarujący. |
| const [String](../../system/string/)\& [get_FullName](../memberinfo/get_fullname/)() const | Zwraca pełną nazwę członka. Może się różnić w ręcznie implementowanych częściach. |
| [MemberTypes](../membertypes/) [get_MemberType](./get_membertype/)() const override | Zwraca wartość MemberTypes wskazującą, że ten członek jest właściwością. |
| const [String](../../system/string/)\& [get_Name](../memberinfo/get_name/)() const | Zwraca nazwę członka. |
| [TypeInfo](../../system/typeinfo/) [get_PropertyType](./get_propertytype/)() | Zwraca typ właściwości. |
| [TypeInfo](../../system/typeinfo/) [get_ReflectedType](../memberinfo/get_reflectedtype/)() const | Zwraca typ odzwierciedlonego typu. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Zwraca strukturę danych licznika referencji powiązaną z obiektem. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\> [GetCustomAttributes](../memberinfo/getcustomattributes/)(const [TypeInfo](../../system/typeinfo/)\&, **bool**) const | Zwraca tablicę zawierającą obiekty reprezentujące wszystkie niestandardowe atrybuty zastosowane do typu reprezentowanego przez bieżący obiekt. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\> [GetCustomAttributes](../memberinfo/getcustomattributes/)(**bool**) const | Zwraca tablicę zawierającą obiekty reprezentujące wszystkie niestandardowe atrybuty zastosowane do typu reprezentowanego przez bieżący obiekt. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie niestandardowych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Zwraca rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [GetValue](./getvalue/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Zwraca wartość właściwości z określonego obiektu. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [GetValue](./getvalue/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>, [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>) | Zwraca wartość właściwości z określonego obiektu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie niestandardowych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Właściwie nic nie kopiuje, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Właściwie nic nie kopiuje, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const) | Konstruktor. Właściwość z jedynie stałym getterem. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<PropertyType\>(ClassType::*)()) | Konstruktor. Właściwość z jedynie nie-stałym getterem. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)([System::SharedPtr](../../system/sharedptr/)\<PropertyType\>), [System::SharedPtr](../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const) | Konstruktor. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)([System::Nullable](../../system/nullable/)\<NullableType\>), [System::Nullable](../../system/nullable/)\<NullableType\>(ClassType::*)()) | Konstruktor. Właściwość [Nullable](../../system/nullable/) z setterem i getterem. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)([System::Nullable](../../system/nullable/)\<NullableType\>), [System::Nullable](../../system/nullable/)\<NullableType\>(ClassType::*)() const) | Konstruktor. Właściwość [Nullable](../../system/nullable/) z jedynie stałym getterem. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)([System::SharedPtr](../../system/sharedptr/)\<PropertyType\>), [System::SharedPtr](../../system/sharedptr/)\<PropertyType\>(ClassType::*)()) | Konstruktor. Właściwość [Object](../../system/object/) z jedynie getterem. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)([System::String](../../system/string/)), [System::String](../../system/string/)(ClassType::*)()) | Tworzy informację o właściwości typu string. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)([System::String](../../system/string/)), [System::String](../../system/string/)(ClassType::*)() const) | Tworzy informację o właściwości typu string z klasy posiadającej stały getter. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)([System::Decimal](../../system/decimal/)), [System::Decimal](../../system/decimal/)(ClassType::*)()) | Tworzy informację o właściwości [Decimal](../../system/decimal/). |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)([System::Decimal](../../system/decimal/)), [System::Decimal](../../system/decimal/)(ClassType::*)() const) | Tworzy informację o właściwości [Decimal](../../system/decimal/) z klasy posiadającej stały getter. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)(**bool**), **bool**(ClassType::*)()) | Tworzy informację o właściwości typu bool. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)(**bool**), **bool**(ClassType::*)() const) | Tworzy informację o właściwości typu bool z klasy posiadającej stały getter. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)(**int64_t**), **int64_t**(ClassType::*)()) | Tworzy informację o właściwości typu **int64_t**. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)(**int64_t**), **int64_t**(ClassType::*)() const) | Tworzy informację o właściwości typu **int64_t** z klasy posiadającej stały getter. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku stringów. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| void [set_PropertyType](./set_propertytype/)(const [TypeInfo](../../system/typeinfo/)\&) | Ustawia typ tej właściwości. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala na przełączanie wskaźników w kontenerach na tryb słaby. |
| void [SetValue](./setvalue/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>, [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Ustawia wartość właściwości dla określonego obiektu. |
| void [SetValue](./setvalue/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>, [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>, [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>) | Ustawia wartość właściwości dla określonego obiektu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Zwraca bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję niestandardowych obiektów na string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Class [MemberInfo](../memberinfo/)
* Namespace [System::Reflection](../)
* Library [Aspose.Slides](../../)