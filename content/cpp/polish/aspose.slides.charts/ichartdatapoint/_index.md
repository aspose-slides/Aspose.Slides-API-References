---
title: IChartDataPoint
second_title: Aspose.Slides dla C++ - odniesienie API
description: Reprezentuje punkt danych serii.
type: docs
weight: 677
url: /pl/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint klasa

Reprezentuje punkt danych serii.

```cpp
class IChartDataPoint : public Aspose::Slides::Charts::IActualLayout
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, gdzie dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, gdzie dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | Określa rzeczywistą wysokość elementu wykresu. Wywołaj metodę [IChart::ValidateChartLayout](../ichart/validatechartlayout/) przed uzyskaniem rzeczywistych wartości. Odczyt **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | Określa rzeczywistą szerokość elementu wykresu. Wywołaj metodę [IChart::ValidateChartLayout](../ichart/validatechartlayout/) przed uzyskaniem rzeczywistych wartości. Odczyt **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | Określa rzeczywistą pozycję x (lewo) elementu wykresu względem lewego górnego rogu wykresu. Wywołaj metodę [IChart::ValidateChartLayout](../ichart/validatechartlayout/) przed uzyskaniem rzeczywistych wartości. Odczyt **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | Określa rzeczywisty górny róg elementu wykresu względem lewego górnego rogu wykresu. Wywołaj metodę [IChart::ValidateChartLayout](../ichart/validatechartlayout/) przed uzyskaniem rzeczywistych wartości. Odczyt **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_BubbleSize](./get_bubblesize/)() | Zwraca rozmiar bąbelka punktu danych wykresu. Tylko do odczytu [IDoubleChartValue](../idoublechartvalue/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_ColorValue](./get_colorvalue/)() | Zwraca wartość koloru punktu danych wykresu. Używane z wykresami map. Tylko do odczytu [IDoubleChartValue](../idoublechartvalue/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointLevel](../ichartdatapointlevel/)\> [get_DataPointLevel](./get_datapointlevel/)(**int32_t**) | Zwraca poziom punktu danych pod podanym indeksem. Stosowane dla serii Treeamp i Sunburst. Indeksowanie poziomów punktów danych jest zerowe. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointLevelsManager](../ichartdatapointlevelsmanager/)\> [get_DataPointLevels](./get_datapointlevels/)() | Zwraca kontener poziomów punktów danych. Stosowane dla serii Treeamp i Sunburst. Indeksowanie poziomów punktów danych jest zerowe. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsCustomValues](../ierrorbarscustomvalues/)\> [get_ErrorBarsCustomValues](./get_errorbarscustomvalues/)() | Reprezentuje wartości słupków błędów serii w przypadku typu wartości Custom. Tylko do odczytu [IErrorBarsCustomValues](../ierrorbarscustomvalues/). |
| virtual **int32_t** [get_Explosion](./get_explosion/)() | Określa, o ile punkt danych ma być przesunięty od środka koła. Odczyt **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Reprezentuje właściwości formatowania. Odczyt [IFormat](../iformat/). |
| virtual **uint32_t** [get_Index](./get_index/)() | Określa, do której kolekcji dzieci rodzica ten punkt danych ma zastosowanie. Odczyt **uint32_t**. |
| virtual **bool** [get_InvertIfNegative](./get_invertifnegative/)() | Określa, że punkt danych odwróci swoje kolory, jeśli wartość jest ujemna. Odczyt **bool**. |
| virtual **bool** [get_IsBubble3D](./get_isbubble3d/)() | Określa, że bąbelki mają zastosowany efekt 3-D. Odczyt **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataLabel](../idatalabel/)\> [get_Label](./get_label/)() | Reprezentuje etykietę punktu danych wykresu. Tylko do odczytu [IDataLabel](../idatalabel/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMarker](../imarker/)\> [get_Marker](./get_marker/)() | Określa znacznik danych. Tylko do odczytu [IMarker](../imarker/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() | Właściwości odpowiadającego wpisu legendy w przypadku typów wykresów z tej listy: [ChartType::BarOfPie](../charttype/), [ChartType::ExplodedPie](../charttype/), [ChartType::ExplodedPie3D](../charttype/), [ChartType::Pie](../charttype/), [ChartType::Pie3D](../charttype/), [ChartType::PieOfPie](../charttype/). Tylko do odczytu [ILegendEntryProperties](../ilegendentryproperties/). |
| virtual **bool** [get_SetAsTotal](./get_setastotal/)() | Ustawia punkt danych jako całkowity. Stosowane wyłącznie dla typów serii Waterfall. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_SizeValue](./get_sizevalue/)() | Zwraca wartość rozmiaru punktu danych wykresu. Używane z wykresami Treemap i Sunburst. Tylko do odczytu [IDoubleChartValue](../idoublechartvalue/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_Value](./get_value/)() | Zwraca wartość punktu danych wykresu. Tylko do odczytu [IDoubleChartValue](../idoublechartvalue/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IStringOrDoubleChartValue](../istringordoublechartvalue/)\> [get_XValue](./get_xvalue/)() | Zwraca wartość x punktu danych wykresu. Tylko do odczytu [IStringOrDoubleChartValue](../istringordoublechartvalue/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_YValue](./get_yvalue/)() | Zwraca wartość y punktu danych wykresu. Tylko do odczytu [IDoubleChartValue](../idoublechartvalue/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [GetAutomaticDataPointColor](./getautomaticdatapointcolor/)() | Zwraca automatyczny kolor punktu danych na podstawie indeksu serii, indeksu punktu danych, własności ParentSeriesGroup.IsColorVaried oraz stylu wykresu. Ten kolor jest używany domyślnie, jeśli FillType równa się NotDefined. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogia metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie niestandardowych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analogia wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analogia operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogia metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie niestandardowych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| virtual void [Remove](./remove/)() | Usuwa DataPoint z serii wykresu. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| virtual void [set_Explosion](./set_explosion/)(**int32_t**) | Określa, o ile punkt danych ma być przesunięty od środka koła. Zapis **int32_t**. |
| virtual void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) | Reprezentuje właściwości formatowania. Zapis [IFormat](../iformat/). |
| virtual void [set_InvertIfNegative](./set_invertifnegative/)(**bool**) | Określa, że punkt danych odwróci swoje kolory, jeśli wartość jest ujemna. Zapis **bool**. |
| virtual void [set_IsBubble3D](./set_isbubble3d/)(**bool**) | Określa, że bąbelki mają zastosowany efekt 3-D. Zapis **bool**. |
| virtual void [set_SetAsTotal](./set_setastotal/)(**bool**) | Ustawia punkt danych jako całkowity. Stosowane wyłącznie dla serii Waterfall. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego używaj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego używaj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogia metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję niestandardowych obiektów do łańcucha znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego używaj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego używaj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [IActualLayout](../iactuallayout/)
* Przestrzeń nazw [Aspose::Slides::Charts](../)
* Biblioteka [Aspose.Slides](../../)