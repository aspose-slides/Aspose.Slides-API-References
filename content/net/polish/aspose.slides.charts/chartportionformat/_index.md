---
title: ChartPortionFormat
second_title: Aspose.Sildes dla .NET – odniesienie API
description: Ta klasa zawiera właściwości formatowania części wykresu używane w wykresach. W przeciwieństwie do IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata wszystkie właściwości tej klasy są zapisywalne.
type: docs
weight: 1410
url: /pl/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat klasa

Ta klasa zawiera właściwości formatowania części wykresu używane w wykresach. W przeciwieństwie do [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata), wszystkie właściwości tej klasy są zapisywalne.

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Zwraca lub ustawia Id alternatywnego języka. Odczyt/zapis String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Umożliwia pobranie podstawowego interfejsu IPresentationComponent. Tylko do odczytu [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Zwraca lub ustawia informacje o czcionce skryptu złożonego. null oznacza, że czcionka jest niezdefiniowana i powinna być dziedziczona z Master. Odczyt/zapis [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Zwraca lub ustawia informacje o czcionce wschodnioazjatyckiej. null oznacza, że czcionka jest niezdefiniowana i powinna być dziedziczona z Master. Odczyt/zapis [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Zwraca właściwości EffectFormat tekstu. Nie zastosowano dziedziczenia. Tylko do odczytu [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Zwraca lub ustawia tekst w indeksie górnym lub dolnym. Wartość od -100% (indeks dolny) do 100% (indeks górny). **float.NaN** oznacza, że wartość jest niezdefiniowana i powinna być dziedziczona z Master. Odczyt/zapis Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Zwraca właściwości FillFormat tekstu. Nie zastosowano dziedziczenia. Tylko do odczytu [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Określa, czy czcionka jest pogrubiona. Nie zastosowano dziedziczenia. Odczyt/zapis [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Zwraca lub ustawia wysokość czcionki części. **float.NaN** oznacza, że wysokość jest niezdefiniowana i powinna być dziedziczona z Master. Odczyt/zapis Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Określa, czy czcionka jest pochyła. Nie zastosowano dziedziczenia. Odczyt/zapis [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Zwraca lub ustawia typ podkreślenia tekstu. Nie zastosowano dziedziczenia. Odczyt/zapis [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Zwraca kolor używany do podświetlania tekstu. Nie zastosowano dziedziczenia. Tylko do odczytu [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Określa, czy styl podkreślenia ma własne właściwości FillFormat lub dziedziczy je z FillFormat tekstu. Odczyt/zapis [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Określa, czy styl podkreślenia ma własne właściwości LineFormat lub dziedziczy je z LineFormat tekstu. Odczyt/zapis [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Zwraca lub ustawia minimalny rozmiar czcionki, przy którym włącza się kerning. **float.NaN** oznacza, że wartość jest niezdefiniowana i powinna być dziedziczona z Master. Odczyt/zapis Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Określa, czy liczby powinny ignorować specyficzny układ pionowy tekstu w języku wschodnim. Nie zastosowano dziedziczenia. Odczyt/zapis [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Zwraca lub ustawia Id języka korekty. Używany do sprawdzania pisowni i gramatyki. Odczyt/zapis String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Zwraca lub ustawia informacje o czcionce łacińskiej. null oznacza, że czcionka jest niezdefiniowana i powinna być dziedziczona z Master. Odczyt/zapis [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Zwraca właściwości LineFormat dla obramowania tekstu. Nie zastosowano dziedziczenia. Tylko do odczytu [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Określa, czy wysokość tekstu powinna być znormalizowana. Nie zastosowano dziedziczenia. Odczyt/zapis [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Określa, czy tekst nie powinien być poddawany korekcie. Nie zastosowano dziedziczenia. Odczyt/zapis [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Zwraca lub ustawia przyrost odstępu między znakami. **float.NaN** oznacza, że wartość jest niezdefiniowana i powinna być dziedziczona z Master. Odczyt/zapis Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Pobiera lub ustawia wartość określającą, czy sprawdzanie pisowni jest włączone dla tej części tekstu. Gdy właściwość ma wartość false, sprawdzanie pisowni dla elementów tekstowych jest wyłączone. Gdy ma wartość true, sprawdzanie jest dozwolone. Domyślna wartość to `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Zwraca lub ustawia typ przekreślenia tekstu. Nie zastosowano dziedziczenia. Odczyt/zapis [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Zwraca lub ustawia informacje o czcionce symbolicznej. null oznacza, że czcionka jest niezdefiniowana i powinna być dziedziczona z Master. Odczyt/zapis [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Zwraca lub ustawia typ kapitalizacji tekstu. Nie zastosowano dziedziczenia. Odczyt/zapis [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Zwraca właściwości FillFormat linii podkreślenia. Nie zastosowano dziedziczenia. Tylko do odczytu [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Zwraca właściwości LineFormat używane do obramowania linii podkreślenia. Nie zastosowano dziedziczenia. Tylko do odczytu [`ILineFormat`](../../aspose.slides/ilineformat). |

## Metody

| Nazwa | Opis |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Porównuje z podanym obiektem. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Zwraca kod skrótu. |

### Uwagi

Ta klasa jest używana do zwracania i manipulacji właściwościami formatowania części tekstu zdefiniowanymi dla konkretnej części. Oznacza to, że przy pobieraniu wartości nie stosuje się dziedziczenia, więc w większości przypadków otrzymasz wartości oznaczające „niezdefiniowane”.

Aby uzyskać skuteczne wartości parametrów formatowania, w tym dziedziczone, należy użyć metody [`GetEffective`](../../aspose.slides/portionformat/geteffective), która zwraca instancję [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata).

### Zobacz także

* klasa [BasePortionFormat](../../aspose.slides/baseportionformat)
* interfejs [IChartPortionFormat](../ichartportionformat)
* przestrzeń nazw [Aspose.Slides.Charts](../../aspose.slides.charts)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->