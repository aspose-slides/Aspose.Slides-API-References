---
title: Rotation3D
second_title: Aspose.Slides for C++ – Odniesienie API
description: Reprezentuje trójwymiarowy obrót wykresu.
type: docs
weight: 1327
url: /pl/aspose.slides.charts/rotation3d/
---
## Rotation3D klasa

Represents 3D rotation of a chart.

```cpp
class Rotation3D : public Aspose::Slides::Charts::IRotation3D,
                   public Aspose::Slides::IDOMObject
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| **uint16_t** [get_DepthPercents](./get_depthpercents/)() override | Zwraca głębokość wykresu 3D jako procent szerokości wykresu (między 20 a 2000 procent). Odczyt **uint16_t**. |
| **uint16_t** [get_HeightPercents](./get_heightpercents/)() override | Określa wysokość wykresu 3-D jako procent szerokości wykresu (między 5 a 500 procent). Odczyt **uint16_t**. |
| **uint8_t** [get_Perspective](./get_perspective/)() override | Zwraca wartość perspektywy (kąt pola widzenia) dla wykresów 3D (między 0 a 240). Ignorowane, jeśli wartość właściwości RightAngleAxes jest prawdziwa. Odczyt **uint8_t**. |
| **bool** [get_RightAngleAxes](./get_rightangleaxes/)() override | Określa, czy osie wykresu są pod kątem prostym, a nie rysowane w perspektywie. Inaczej mówiąc, określa, czy kąty osi wykresu są niezależne od obrotu lub elewacji wykresu. Odczyt **bool**. |
| **int8_t** [get_RotationX](./get_rotationx/)() override | Zwraca stopień obrotu wokół osi X, czyli w kierunku Y dla wykresów 3D (między -90 a 90 stopni). Właściwość odpowiada elementowi 21.2.2.157 rotX (X Rotation) w ECMA-376 oraz opcji „Y Rotation” w PowerPoint 2007+. Odczyt **int8_t**. |
| **uint16_t** [get_RotationY](./get_rotationy/)() override | Zwraca stopień obrotu wokół osi Y, czyli w kierunku X dla wykresów 3D (między 0 a 360 stopni). Właściwość odpowiada elementowi 21.2.2.158 rotY (Y Rotation) w ECMA-376 oraz opcji „X Rotation” w PowerPoint 2007+. Odczyt **uint16_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia tworzenie skrótów niestandardowych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie niestandardowych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty według referencji. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty według referencji. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza liczbę współdzielonych referencji o podaną wartość. |
| void [set_DepthPercents](./set_depthpercents/)(**uint16_t**) override | Ustawia głębokość wykresu 3D jako procent szerokości wykresu (między 20 a 2000 procent). Zapis **uint16_t**. |
| void [set_HeightPercents](./set_heightpercents/)(**uint16_t**) override | Określa wysokość wykresu 3-D jako procent szerokości wykresu (między 5 a 500 procent). Zapis **uint16_t**. |
| void [set_Perspective](./set_perspective/)(**uint8_t**) override | Ustawia wartość perspektywy (kąt pola widzenia) dla wykresów 3D (między 0 a 240). Ignorowane, jeśli wartość właściwości RightAngleAxes jest prawdziwa. Zapis **uint8_t**. |
| void [set_RightAngleAxes](./set_rightangleaxes/)(**bool**) override | Określa, czy osie wykresu są pod kątem prostym, a nie rysowane w perspektywie. Inaczej mówiąc, określa, czy kąty osi wykresu są niezależne od obrotu lub elewacji wykresu. Zapis **bool**. |
| void [set_RotationX](./set_rotationx/)(**int8_t**) override | Ustawia stopień obrotu wokół osi X, czyli w kierunku Y dla wykresów 3D (między -90 a 90 stopni). Właściwość odpowiada elementowi 21.2.2.157 rotX (X Rotation) w ECMA-376 oraz opcji „Y Rotation” w PowerPoint 2007+. Zapis **int8_t**. |
| void [set_RotationY](./set_rotationy/)(**uint16_t**) override | Ustawia stopień obrotu wokół osi Y, czyli w kierunku X dla wykresów 3D (między 0 a 360 stopni). Właściwość odpowiada elementowi 21.2.2.158 rotY (Y Rotation) w ECMA-376 oraz opcji „X Rotation” w PowerPoint 2007+. Zapis **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączyć wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję niestandardowych obiektów na ciąg znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Usuwa obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [IRotation3D](../irotation3d/)
* Klasa [IDOMObject](../../aspose.slides/idomobject/)
* Przestrzeń nazw [Aspose::Slides::Charts](../)
* Biblioteka [Aspose.Slides](../../)