---
title: AutoShapeLock
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Określa, które operacje są wyłączone w nadrzędnym obiekcie AutoshapeEx.
type: docs
weight: 79
url: /pl/aspose.slides/autoshapelock/
---
## AutoShapeLock klasa


Determines which operations are disabled on the parent AutoshapeEx.

```cpp
class AutoShapeLock : public Aspose::Slides::BaseShapeLock,
                      public Aspose::Slides::IAutoShapeLock
```

## Metody

| Method | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartości w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() override | Określa, czy zmiana wartości dopasowania jest zabroniona. Odczyt **bool**. |
| **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() override | Określa, czy zmiana grotów jest zabroniona. Odczyt **bool**. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | Określa, czy kształt musi zachować proporcje przy zmianie rozmiaru. Odczyt **bool**. |
| **bool** [get_EditPointsLocked](./get_editpointslocked/)() override | Określa, czy bezpośrednia zmiana konturu tego kształtu jest zabroniona. Odczyt **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | Określa, czy dodanie tego kształtu do grupy jest zabronione. Odczyt **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | Zwraca true, jeśli wszystkie flagi blokady są wyłączone. **bool** tylko do odczytu. |
| **bool** [get_PositionLocked](./get_positionlocked/)() override | Określa, czy przenoszenie tego kształtu jest zabronione. Odczyt **bool**. |
| **bool** [get_RotateLocked](./get_rotatelocked/)() override | Określa, czy zmiana kąta obrotu tego kształtu jest zabroniona. Odczyt **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | Określa, czy wybór tego kształtu jest zabroniony. Odczyt **bool**. |
| **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() override | Określa, czy zmiana typu kształtu jest zabroniona. Odczyt **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | Określa, czy zmiana rozmiaru tego kształtu jest zabroniona. Odczyt **bool**. |
| **bool** [get_TextLocked](./get_textlocked/)() override | Określa, czy edycja tekstu jest zabroniona. Odczyt **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nic nie kopiuje, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nic nie kopiuje, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartości z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku stringów. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) override | Określa, czy zmiana wartości dopasowania jest zabroniona. Zapis **bool**. |
| void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) override | Określa, czy zmiana grotów jest zabroniona. Zapis **bool**. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | Określa, czy kształt musi zachować proporcje przy zmianie rozmiaru. Zapis **bool**. |
| void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) override | Określa, czy bezpośrednia zmiana konturu tego kształtu jest zabroniona. Zapis **bool**. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | Określa, czy dodanie tego kształtu do grupy jest zabronione. Zapis **bool**. |
| void [set_PositionLocked](./set_positionlocked/)(**bool**) override | Określa, czy przenoszenie tego kształtu jest zabronione. Zapis **bool**. |
| void [set_RotateLocked](./set_rotatelocked/)(**bool**) override | Określa, czy zmiana kąta obrotu tego kształtu jest zabroniona. Zapis **bool**. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | Określa, czy wybór tego kształtu jest zabroniony. Zapis **bool**. |
| void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) override | Określa, czy zmiana typu kształtu jest zabroniona. Zapis **bool**. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | Określa, czy zmiana rozmiaru tego kształtu jest zabroniona. Zapis **bool**. |
| void [set_TextLocked](./set_textlocked/)(**bool**) override | Określa, czy edycja tekstu jest zabroniona. Zapis **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera aktualną wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowywanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Usuwa obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [BaseShapeLock](../baseshapelock/)
* Klasa [IAutoShapeLock](../iautoshapelock/)
* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)