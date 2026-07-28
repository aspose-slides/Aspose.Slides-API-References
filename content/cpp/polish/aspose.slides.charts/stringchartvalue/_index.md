---
title: StringChartValue
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: "Reprezentuje wartość łańcuchową, którą można przechowywać w dokumencie prezentacji pptx na dwa sposoby: 1) w komórce/komórkach skoroszytu powiązanego z wykresem; 2) jako wartość dosłowną."
type: docs
weight: 1340
url: /pl/aspose.slides.charts/stringchartvalue/
---
## StringChartValue klasa

Reprezentuje wartość łańcuchową, którą można przechowywać w dokumencie prezentacji pptx na dwa sposoby: 1) w komórce/komórkach skoroszytu powiązanego z wykresem; 2) jako wartość dosłowną.

```cpp
class StringChartValue : public Aspose::Slides::Charts::BaseChartValue,
                         public Aspose::Slides::Charts::IStringChartValue
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartości w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_AsCell](./get_ascell/)(**int32_t**) override | Zwraca komórkę wykresu o podanym indeksie. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartCellCollection](../ichartcellcollection/)\> [get_AsCells](./get_ascells/)() override | Przypisywanie wartości null nie jest dozwolone. Zwracana wartość zawsze nie jest nullem. Odczytaj [IChartCellCollection](../ichartcellcollection/). |
| [System::String](../../system/string/) [get_AsLiteralString](./get_asliteralstring/)() override | Zwraca wartość jako dosłowny ciąg znaków. Odczytaj [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Data](./get_data/)() override | Zwraca obiekt Data. Odczytaj [System::Object](../../system/object/). |
| [Aspose::Slides::Charts::DataSourceType](../datasourcetype/) [get_DataSourceType](../basechartvalue/get_datasourcetype/)() override | Określa, czy właściwość AsCell, AsCells, AsLiteralString lub AsLiteralDouble jest aktualna w klasach potomnych. Innymi słowy określa typ wartości właściwości Data. Odczytaj [Charts::DataSourceType](../datasourcetype/). |
| [System::String](../../system/string/) [GetCellsAddressInWorkbook](./getcellsaddressinworkbook/)() override | Jeśli właściwość DataSourceType jest [DataSourceType::Worksheet](../datasourcetype/), metoda zwraca adres komórek w skoroszycie, które reprezentują dane tekstowe. W przeciwnym razie zwraca pusty ciąg. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę wyrażenia C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartości z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągu znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| void [set_AsCells](./set_ascells/)([System::SharedPtr](../../system/sharedptr/)\<[IChartCellCollection](../ichartcellcollection/)\>) override | Przypisywanie wartości null nie jest dozwolone. Zwracana wartość zawsze nie jest nullem. Zapisz [IChartCellCollection](../ichartcellcollection/). |
| void [set_AsLiteralString](./set_asliteralstring/)([System::String](../../system/string/)) override | Ustawia wartość jako dosłowny ciąg znaków. Zapisz [System::String](../../system/string/). |
| void [set_Data](./set_data/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Ustawia obiekt Data. Zapisz [System::Object](../../system/object/). |
| void [set_DataSourceType](../basechartvalue/set_datasourcetype/)([Aspose::Slides::Charts::DataSourceType](../datasourcetype/)) override | Określa, czy właściwość AsCell, AsCells, AsLiteralString lub AsLiteralDouble jest aktualna w klasach potomnych. Innymi słowy określa typ wartości właściwości Data. Zapisz [Charts::DataSourceType](../datasourcetype/). |
| void [SetFromOneCell](./setfromonecell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) override | Ustawia wartość z określonej komórki. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączenie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; użyj inteligentnych wskaźników lub ThisProtector. |
| [System::String](../../system/string/) [ToString](./tostring/)() const override | Zwraca dane wartości ciągu znaków. Zwraca null, jeśli DataSourceType jest false i nie przypisano żadnej wartości ciągu. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie wyrażenia C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [BaseChartValue](../basechartvalue/)
* Klasa [IStringChartValue](../istringchartvalue/)
* Przestrzeń nazw [Aspose::Slides::Charts](../)
* Biblioteka [Aspose.Slides](../../)