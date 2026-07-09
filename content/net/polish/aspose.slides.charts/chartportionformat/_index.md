---
title: ChartPortionFormat
second_title: Aspose.Sildes dla .NET - dokumentacja API
description: Ta klasa zawiera właściwości formatowania fragmentu wykresu używane w wykresach. W przeciwieństwie do IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata wszystkie właściwości tej klasy są zapisywalne.
type: docs
weight: 1430
url: /pl/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat klasa

Ta klasa zawiera właściwości formatowania fragmentu wykresu używane w wykresach. W przeciwieństwie do [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata), wszystkie właściwości tej klasy są zapisywalne.

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## Właściwości

| Name | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Zwraca lub ustawia Id alternatywnego języka. Odczyt/zapis String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Umożliwia uzyskanie podstawowego interfejsu IPresentationComponent. Tylko do odczytu [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Zwraca lub ustawia informacje o czcionce skryptu złożonego. Null oznacza, że czcionka jest niezdefiniowana i powinna być dziedziczona z Mastera. Odczyt/zapis [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Zwraca lub ustawia informacje o czcionce wschodnioazjatyckiej. Null oznacza, że czcionka jest niezdefiniowana i powinna być dziedziczona z Mastera. Odczyt/zapis [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Zwraca właściwości EffectFormat tekstu. Nie stosuje się dziedziczenia. Tylko do odczytu [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Zwraca lub ustawia tekst w indeksie górnym lub dolnym. Wartość od -100 % (dolny indeks) do 100 % (górny indeks). **float.NaN** oznacza, że wartość jest niezdefiniowana i powinna być dziedziczona z Mastera. Odczyt/zapis Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Zwraca właściwości FillFormat tekstu. Nie stosuje się dziedziczenia. Tylko do odczytu [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Określa, czy czcionka jest pogrubiona. Nie stosuje się dziedziczenia. Odczyt/zapis [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Zwraca lub ustawia wysokość czcionki fragmentu. **float.NaN** oznacza, że wysokość jest niezdefiniowana i powinna być dziedziczona z Mastera. Odczyt/zapis Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Określa, czy czcionka jest kursywą. Nie stosuje się dziedziczenia. Odczyt/zapis [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Zwraca lub ustawia typ podkreślenia tekstu. Nie stosuje się dziedziczenia. Odczyt/zapis [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Zwraca kolor używany do podświetlenia tekstu. Nie stosuje się dziedziczenia. Tylko do odczytu [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Określa, czy styl podkreślenia ma własne właściwości FillFormat lub dziedziczy je z właściwości FillFormat tekstu. Odczyt/zapis [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Określa, czy styl podkreślenia ma własne właściwości LineFormat lub dziedziczy je z właściwości LineFormat tekstu. Odczyt/zapis [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Zwraca lub ustawia minimalny rozmiar czcionki, przy którym ma zostać włączone kerningowanie. **float.NaN** oznacza, że wartość jest niezdefiniowana i powinna być dziedziczona z Mastera. Odczyt/zapis Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Określa, czy liczby powinny ignorować specyficzny układ pionowy tekstu w językach wschodnioazjatyckich. Nie stosuje się dziedziczenia. Odczyt/zapis [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Zwraca lub ustawia Id języka korekty. Używane do sprawdzania pisowni i gramatyki. Odczyt/zapis String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Zwraca lub ustawia informacje o czcionce łacińskiej. Null oznacza, że czcionka jest niezdefiniowana i powinna być dziedziczona z Mastera. Odczyt/zapis [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Zwraca właściwości LineFormat dla obrysu tekstu. Nie stosuje się dziedziczenia. Tylko do odczytu [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Określa, czy wysokość tekstu powinna być znormalizowana. Nie stosuje się dziedziczenia. Odczyt/zapis [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Określa, czy tekst nie powinien być korektowany. Nie stosuje się dziedziczenia. Odczyt/zapis [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Zwraca lub ustawia przyrost odstępu między znakami. **float.NaN** oznacza, że wartość jest niezdefiniowana i powinna być dziedziczona z Mastera. Odczyt/zapis Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Określa, czy korekta pisowni jest włączona dla fragmentu tekstu. Gdy właściwość ma wartość false, sprawdzanie pisowni dla elementów tekstowych jest pomijane. Gdy ma wartość true, korekta pisowni jest dozwolona. Wartość domyślna to `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Zwraca lub ustawia typ przekreślenia tekstu. Nie stosuje się dziedziczenia. Odczyt/zapis [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Zwraca lub ustawia informacje o czcionce symbolicznej. Null oznacza, że czcionka jest niezdefiniowana i powinna być dziedziczona z Mastera. Odczyt/zapis [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Zwraca lub ustawia typ kapitalizacji tekstu. Nie stosuje się dziedziczenia. Odczyt/zapis [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Zwraca właściwości FillFormat linii podkreślenia. Nie stosuje się dziedziczenia. Tylko do odczytu [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Zwraca właściwości LineFormat używane do obrysu linii podkreślenia. Nie stosuje się dziedziczenia. Tylko do odczytu [`ILineFormat`](../../aspose.slides/ilineformat). |

## Metody

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Porównuje z określonym obiektem. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Zwraca kod skrótu. |

### Uwagi

Ta klasa służy do zwracania i modyfikowania właściwości formatowania fragmentu tekstu zdefiniowanych dla konkretnego fragmentu. Oznacza to, że przy pobieraniu wartości nie stosuje się dziedziczenia, więc w większości przypadków otrzymasz wartości oznaczające „niezdefiniowane”.

Aby uzyskać skuteczne wartości parametrów formatowania, w łącznie z dziedziczonymi, należy użyć metody [`GetEffective`](../../aspose.slides/portionformat/geteffective), która zwraca instancję [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata).

### Zobacz także

* klasa [BasePortionFormat](../../aspose.slides/baseportionformat)
* interfejs [IChartPortionFormat](../ichartportionformat)
* przestrzeń nazw [Aspose.Slides.Charts](../../aspose.slides.charts)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->